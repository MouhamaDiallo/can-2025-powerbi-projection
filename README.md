# CAN 2025 — Projection analytique avec Power BI

Analyse prédictive réalisée le 26 décembre 2024, dès la première journée de la Coupe d'Afrique des Nations 2025, pour projeter les équipes les plus susceptibles de remporter le titre.

---

## Contexte

A partir d'une base de données construite manuellement et d'un score analytique composite, le modèle identifiait dès le début de la compétition un Top 6 de favoris, accompagné d'un signal régional fort : probabilité plus élevée de victoire finale pour une équipe d'Afrique de l'Ouest, suivie d'une dynamique solide de l'Afrique du Nord.

---

## Projection initiale (26 décembre 2024)

| Rang prédit | Equipe |
|-------------|--------|
| 1 | Maroc |
| 2 | Sénégal |
| 3 | Côte d'Ivoire |
| 4 | Nigeria |
| 5 | Egypte |
| 6 | Algérie |

---

## Résultats réels de la CAN 2025

| Rang final | Equipe | Région |
|------------|--------|--------|
| 1 — Champion | Sénégal | Afrique de l'Ouest |
| 2 — Finaliste | Maroc | Afrique du Nord |
| 3 | Nigeria | Afrique de l'Ouest |
| 4 | Egypte | Afrique du Nord |
| 5 | Côte d'Ivoire | Afrique de l'Ouest |
| 6 | Algérie | Afrique du Nord |

---

## Bilan du modèle

Le Top 6 prédit correspond exactement au Top 6 final de la compétition. Le signal régional était également correct : le vainqueur est une équipe d'Afrique de l'Ouest, la finale opposait l'Afrique de l'Ouest à l'Afrique du Nord.

Le modèle positionnait le Maroc champion et la Côte d'Ivoire 3ème — le terrain a redistribué les cartes à l'intérieur du même groupe d'équipes, ce qui confirme la cohérence de la projection sans en faire une prédiction exacte au résultat près.

---

## Données utilisées

| Variable | Description |
|----------|-------------|
| Rang FIFA | Classement FIFA de l'équipe |
| Finales CAN | Nombre de finales atteintes sur les 10 dernières éditions |
| Demi-finales CAN | Nombre de demi-finales atteintes sur les 10 dernières éditions |
| Dernier résultat CAN | Résultat à la dernière édition (Champion, Finaliste, Demi, Quart, Autre) |
| Résultat J1 | Résultat du premier match de groupe |
| Buts pour / contre J1 | Buts marqués et encaissés au premier match |

La base de données a été construite manuellement à partir de sources publiques.

---

## Outil

Power BI Desktop — score analytique composite calculé à partir des variables ci-dessus, visualisé sous forme de dashboard interactif.

---

## Auteur

Mouhamad Diallo
Etudiant M1 MIAGE — Aix-Marseille Université
