# Risques éthiques + classification AI Act — Mini-cours

> Brief associé : M8-B1
> Durée de lecture : ~25 min
> Pré-requis : RGPD/AI Act vus en M7-B1

## Pourquoi cette techno ?

Identifier les risques **dès le cadrage** (pas en audit a posteriori) évite de
concevoir un projet non conforme. Selon le secteur tiré (juridique, RH, industrie),
les risques diffèrent : secret professionnel, surveillance employés, sécurité
critique. Savoir **classer le système selon l'AI Act** (risque élevé / limité /
minimal) détermine les obligations — et c'est un marqueur du palier final C2 N3.

## Concepts clés

- **Classification AI Act** : *inacceptable* (interdit) / *haut risque* (Annexe III :
  santé, justice, emploi…) / *risque limité* (transparence) / *minimal*. La plupart
  des cas internes récupérables = **risque limité**.
- **Haut risque ⇒ obligations** : transparence, traçabilité, supervision humaine,
  gestion des risques. Lourd — donc bien classer.
- **Risques par secteur** : juridique → secret professionnel + hallucination ;
  RH → surveillance employés + PII ; industrie → sécurité critique + responsabilité.
- **RGPD** : base légale, minimisation, art. 22 (décision automatisée), art. 9
  (données sensibles : santé, mutuelle).
- **Sévérité** : classer chaque risque 🔴/🟠/🟡 + l'obligation associée (article).
- **Dès le cadrage** : un risque identifié tôt se traite dans l'architecture (ex.
  pseudonymisation, revue humaine), pas après coup.

## Exemple minimal qui tourne

```markdown
| Risque | Sévérité | Obligation |
|---|---|---|
| PII dans les tickets (santé mutuelle) | 🔴 | RGPD art. 9 → pseudonymisation |
| Surveillance employés possible | 🟠 | cloisonnement d'usage |
| Biais de catégorisation historique | 🟡 | audit léger |
```

## Exercice guidé

Pour ton cas :
1. Classe le système selon l'AI Act (élevé / limité / minimal) + justifie.
2. Liste 5-7 risques avec sévérité 🔴/🟠/🟡 et l'obligation associée.
3. Pour chaque 🔴, propose un traitement **dans l'architecture**.

## Pièges fréquents

| Piège | Conséquence |
|---|---|
| Classer « haut risque » par défaut | Obligations lourdes injustifiées |
| Ignorer le secteur | On rate le risque spécifique (secret, sécurité) |
| Risque sans obligation rattachée | Non actionnable |
| Traiter le risque « plus tard » | Architecture non conforme |

| Symptôme | Cause probable |
|---|---|
| Le DPO conteste la classification | pas de justification AI Act |
| PII oubliées | pas de revue RGPD au cadrage |
| Risques tous au même niveau | pas de sévérité différenciée |

## Pour aller plus loin

- AI Act — Annexe III : https://artificialintelligenceact.eu/annex/3/
- CNIL — IA et RGPD : https://www.cnil.fr/fr/intelligence-artificielle/ia-comment-etre-en-conformite-avec-le-rgpd

## Vérification (checklist apprenant)

- [ ] J'ai classé le système (AI Act) + justifié.
- [ ] 5-7 risques avec sévérité 🔴/🟠/🟡.
- [ ] Chaque risque a une obligation rattachée (article).
- [ ] Les risques spécifiques au secteur sont identifiés.
- [ ] Les 🔴 sont traités dans l'architecture cible.

> 💡 **Récap — Risques + AI Act** : classer le système (haut risque / limité / minimal) **et** justifier ; 5-7 risques 🔴/🟠/🟡 chacun rattaché à une obligation (article) ; traiter les 🔴 **dans l'architecture**, pas après. Les risques diffèrent selon le secteur tiré.

### À retenir

- Le livrable se juge sur sa **clarté pour le destinataire**, pas sur sa longueur.
- **Chiffrer** plutôt qu'affirmer : un nombre vaut mieux qu'un adjectif.
- **Sobriété** : recommander le plus simple qui résout le besoin, et **dire ce qu'on écarte**.
- Distinguer ce qu'on **sait** de ce qui reste **à clarifier** (questions ouvertes).
- Tracer ses **choix** et leur **raison** — c'est ce qui se défend en restitution.
