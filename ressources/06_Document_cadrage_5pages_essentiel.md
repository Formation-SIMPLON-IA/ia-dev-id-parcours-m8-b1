# Document de cadrage en 5 pages — Mini-cours

> Brief associé : M8-B1
> Durée de lecture : ~20 min
> Pré-requis : entretien mené, notes prises — les analyses se rédigent **dans** le document

## Pourquoi cette techno ?

Le document de cadrage est le **livrable client** qui synthétise tout : il convertit
votre analyse en un document **décisionnel** que le client (Devalle, Bonnemain,
Lefranc, Combaud) peut lire et **valider**. 5 pages max : assez pour être complet,
assez court pour être lu. C'est l'exercice de synthèse et de communication qui
boucle le cadrage (CT5/CT6).

## Concepts clés

- **5 pages, 6 sections, un seul fichier** : synthèse exec / besoin+contexte / données /
  risques & conformité / archi+sobriété / KPI+étapes. Pas de fichiers d'analyse à
  recopier : on écrit directement ici.
- **Synthèse exécutive d'abord** : 1 paragraphe qui dit le besoin, la solution
  proposée et les indicateurs clés — la seule partie que lira un décideur pressé.
- **Lisible par le persona** : pas un seul terme technique non défini. « classifieur
  de texte » oui, `TF-IDF` à expliquer ou éviter.
- **Sobriété argumentée** : la section archi contient 3 lignes justifiant le choix
  (ou non) d'un LLM — c'est noté.
- **Chiffrer** : reprendre les KPI chiffrés, pas des généralités.
- **Questions ouvertes** : finir par ce qui reste à clarifier (preuve de lucidité).

## Exemple minimal qui tourne

```markdown
## Page 1 — Synthèse exécutive
CapGroup trie 80 tickets/jour à la main. Nous proposons un classifieur de texte
(ML classique, sans LLM) : tri 60 → 10 min/jour, précision > 85 %, RGPD assuré.
```

## Exercice guidé

À partir de tes analyses :
1. Rédige la **synthèse exécutive** (1 paragraphe : besoin + solution + KPI).
2. Remplis les 6 sections du template (½ à 1 page chacune).
3. Relis-toi du point de vue du **client** : comprend-il en 5 min sans jargon ?

## Pièges fréquents

| Piège | Conséquence |
|---|---|
| Document de 12 pages | Pas lu par le décideur |
| Jargon technique non défini | Le client décroche |
| Pas de synthèse exec | On ne sait pas l'essentiel |
| Sobriété non argumentée | Critère manqué |
| Pas de KPI chiffrés | Cadrage non actionnable |

| Symptôme | Cause probable |
|---|---|
| Le client redemande « donc ? » | pas de synthèse claire |
| Document trop technique | écrit pour un dev, pas le persona |
| Reco LLM non justifiée | section sobriété absente |

## Pour aller plus loin

- Pyramide de Minto (structurer) : https://en.wikipedia.org/wiki/Barbara_Minto
- Cf. M7-B1 (rapport 2 lectorats) — communication décideur.

## Vérification (checklist apprenant)

- [ ] 5 pages max, 6 sections, un seul fichier.
- [ ] Synthèse exécutive en tête (besoin + solution + KPI).
- [ ] Lisible par le persona client (pas de jargon non défini).
- [ ] Sobriété argumentée (LLM retenu/refusé : 3 lignes).
- [ ] KPI chiffrés + questions ouvertes.

> 💡 **Récap — Document de cadrage** : 5 pages, 6 sections, un seul fichier, **synthèse exécutive en tête** ; lisible par le persona (pas de jargon non défini) ; KPI chiffrés ; sobriété argumentée (LLM retenu/refusé en 3 lignes) ; finir par les questions ouvertes. C'est le livrable client qui se valide.

### À retenir

- Le livrable se juge sur sa **clarté pour le destinataire**, pas sur sa longueur.
- **Chiffrer** plutôt qu'affirmer : un nombre vaut mieux qu'un adjectif.
- **Sobriété** : recommander le plus simple qui résout le besoin, et **dire ce qu'on écarte**.
- Distinguer ce qu'on **sait** de ce qui reste **à clarifier** (questions ouvertes).
- Tracer ses **choix** et leur **raison** — c'est ce qui se défend en restitution.
