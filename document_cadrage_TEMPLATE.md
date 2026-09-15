# Document de cadrage — _ton cas_ (À COMPLÉTER — 5 pages max)

> **Livrable principal.** Lisible par le persona client (pas un dev). Renomme en
> `document_cadrage.md`. Les analyses (besoin, données, risques, KPI) se font
> **directement ici** : pas de fichiers séparés. Le schéma vit dans
> `schema_archi_cible.md`, tes notes brutes dans `notes_entretien.md`.

## 1. Synthèse exécutive (½ page)
_1 paragraphe : besoin réel + solution proposée + 2-3 indicateurs clés._

## 2. Besoin métier et contexte (½ page)
_Demande exprimée (citation) vs **besoin réel reformulé** (1 paragraphe max).
Contraintes révélées en entretien (budget, équipe, confidentialité…)._

## 3. Données (½ page) — mini-cours `02`
| Donnée | Existante / à acquérir | Volume, qualité estimée | Personnelle ? |
|---|---|---|---|
| | | | |

_Ce que tu n'as pas demandé en entretien n'existe pas : écris-le en question ouverte._

## 4. Risques et conformité (1 page) — mini-cours `04` et `07`

**Usage réel** (3 lignes) : _qui utilise la sortie, ce qu'elle déclenche, qui peut la contredire._

**Qualification AI Act** : _niveau + cas du texte (ou pourquoi aucun) + condition de bascule._

**RGPD** : _base légale proposée et pourquoi ; profilage ? art. 22 (2 conditions) ?_

| Risque (éthique, métier, conformité) | Sévérité 🔴/🟠/🟡 | Obligation ou raison | Traitement dans l'archi |
|---|---|---|---|
| | | | |

**Sécurité du modèle** — selon l'**exposition** de ton archi (batch interne ≠ API
publique ≠ agent) : 2-3 menaces plausibles, les autres écartées en 1 ligne.
Mitiger ≠ supprimer.

| Menace | Plausibilité sur CE cas | Mitigation proposée | Risque résiduel |
|---|---|---|---|
| | | | |

## 5. Architecture cible et sobriété (1 page) — mini-cours `05`
_Renvoi à `schema_archi_cible.md` (Mermaid ≥ 4 composants). LLM retenu ou refusé :
justifie en 3 lignes. Ce que tu écartes, et pourquoi._

## 6. Indicateurs, seuils, prochaines étapes (1 page) — mini-cours `03`
| Indicateur | Cible | Seuil d'acceptabilité | Comment on le mesure |
|---|---|---|---|
| | | | |

_Prochaines étapes (3-5) + **questions ouvertes** au client._
