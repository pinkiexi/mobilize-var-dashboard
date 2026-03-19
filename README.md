# Risk Dashboard - VaR · ICAAP · Stress Tests

Dashboard interactif de gestion des risques financiers.


## Fonctionnalités

- **VaR** : 3 méthodes : paramétrique (loi normale), historique, Monte Carlo
- **Expected Shortfall** : CVaR au-delà du seuil de confiance
- **Stress tests macroéconomiques** : recul PIB, hausse taux, choc systémique
- **ICAAP / Bâle III** : adéquation des fonds propres, ratios CET1 et Tier 1

## Stack

HTML · CSS · JavaScript · Chart.js


## Interprétation

Ce dashboard m'a permis de mieux comprendre les concepts abordés lors de 
l'entretien. Voici ce que j'en ai retenu :

**VaR**  il existe plusieurs façons de la calculer (paramétrique, historique, 
Monte Carlo), chacune avec ses hypothèses et ses limites. La méthode 
paramétrique suppose une distribution normale, ce qui peut sous-estimer 
les pertes extrêmes.

**Expected Shortfall**  va plus loin que la VaR en mesurant ce qui se passe 
au-delà du seuil, ce qui la rend plus pertinente pour les cas extrêmes.

**Stress tests**  permettent de simuler des chocs macroéconomiques concrets 
(chute du PIB, hausse des taux) et d'observer leur transmission sur le 
portefeuille via les défauts et la consommation de capital.

**ICAAP**  compare le capital disponible aux besoins estimés sous stress. 
C'est ce qui permet de savoir si une banque reste solvable dans un scénario adverse.

*Je suis consciente que ces modèles sont des simplifications, 
l'objectif était d'apprendre en codant.*

## Auteur

Hanane Chahri - École Centrale Casablanca / École Centrale de Lyon
