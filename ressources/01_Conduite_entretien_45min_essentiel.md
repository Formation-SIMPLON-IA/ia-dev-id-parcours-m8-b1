# Conduire un entretien client de 45 min — Mini-cours

> Brief associé : M8-B1
> Durée de lecture : ~25 min
> Pré-requis : aucun (posture consultant)

## Pourquoi cette techno ?

Un client dit rarement ce dont il a **besoin** — il exprime une **demande**
(« on veut de l'IA »). L'entretien de cadrage sert à creuser sous la demande pour
trouver le besoin réel, les données, les contraintes et les critères de succès. En
45 minutes, sans préparation, on passe à côté de l'essentiel. C'est la compétence
**la plus exigeante du parcours sur CT3** (définir le périmètre) — et le quotidien
du consultant IA.

## Concepts clés

- **Demande ≠ besoin** : « un assistant qui rédige » (demande) cache souvent
  « gagner du temps sans risque » (besoin). On reformule, on ne recopie pas.
- **Questions par catégorie** : préparer 10-15 questions réparties en *besoin
  métier / données / contraintes (RGPD, secret, sécurité) / indicateurs et seuils /
  volumétrie / critères de succès*.
- **Écoute active** : noter ce qui est **dit** ET ce qu'on **interprète** —
  séparément. Relancer quand le client reste vague.
- **Le « pourquoi pas déjà fait ? »** : révèle les vrais obstacles (budget, données
  manquantes, échecs passés).
- **Question imposée — volumétrie labellisée** : « combien d'exemples, labellisés
  comment, et est-ce suffisant pour la famille de modèle envisagée ? ». Peu de
  données + modèle complexe = surapprentissage garanti ; c'est une question de
  certif (C4) et elle conditionne l'arbitrage ML/DL de M8-B2.
- **Gérer le temps** : 45 min = ~5 min/catégorie + marge. Ne pas s'enliser sur un
  point.
- **Posture** : consultant qui cadre, pas développeur qui propose une techno tout
  de suite.

## Exemple minimal qui tourne

```text
Catégorie « Données » :
- Quelles données avez-vous DÉJÀ ? Sous quel format ? Depuis quand ?
- Sont-elles annotées / catégorisées ?
- Contiennent-elles des données personnelles ?
- Qui y a accès, où sont-elles stockées ?
- (imposée) Combien d'exemples, labellisés comment — et est-ce suffisant
  pour la famille de modèle envisagée ?
```

## Exercice guidé

Pour ton cas tiré, avant l'entretien :
1. Écris 2-3 questions par catégorie (6 catégories → 12-15 questions).
2. Repère **la** question qui révélera le besoin réel (souvent « pourquoi
   maintenant ? » ou « qu'est-ce qui vous fait perdre du temps ? »).
3. Prépare une relance si le client reste vague (« pouvez-vous me donner un
   exemple concret ? »).

## Pièges fréquents

| Piège | Conséquence |
|---|---|
| Recopier la demande | On rate le besoin réel |
| Proposer une techno en entretien | On cadre une solution avant le problème |
| Pas de questions sur les données | Cadrage hors-sol |
| Ne pas distinguer dit/interprété | Notes ambiguës, cadrage faux |
| S'enliser sur un point | On n'a pas le temps de tout couvrir |

| Symptôme | Cause probable |
|---|---|
| Cadrage = la demande recopiée | pas de reformulation / écoute active |
| Données floues dans le cadrage | catégorie « données » bâclée en entretien |
| On a « oublié » le RGPD | pas de catégorie « contraintes » préparée |

## Pour aller plus loin

- *Just Enough Research* (Erika Hall) : https://www.mulebooks.com/just-enough-research
- Cf. mini-cours M3-B1 (entretien) — capitalisation.

## Vérification (checklist apprenant)

- [ ] J'ai préparé 10-15 questions réparties par catégorie.
- [ ] J'ai distingué *dit* / *interprété* dans mes notes.
- [ ] J'ai reformulé le besoin (pas recopié la demande).
- [ ] J'ai couvert données + contraintes + indicateurs.
- [ ] J'ai posé la question imposée sur la volumétrie labellisée.
- [ ] J'ai tenu les 45 min (gestion du temps).

> 💡 **Récap — Conduite d'entretien** : demande ≠ besoin ; questions par catégorie (besoin/données/contraintes/KPI/volumétrie/succès) ; noter dit vs interprété ; relancer quand c'est vague. En 45 min, la préparation fait tout — c'est le geste CT3 le plus exigeant du parcours.
