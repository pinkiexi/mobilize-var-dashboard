# Risk Dashboard — VaR · ICAAP · Stress Tests

Dashboard interactif de gestion des risques financiers.


## Fonctionnalités

- **VaR** — 3 méthodes : paramétrique (loi normale), historique, Monte Carlo
- **Expected Shortfall** — CVaR au-delà du seuil de confiance
- **Stress tests macroéconomiques** — recul PIB, hausse taux, choc systémique
- **ICAAP / Bâle III** — adéquation des fonds propres, ratios CET1 et Tier 1

## Stack

HTML · CSS · JavaScript · Chart.js


## Interprétation des résultats

**VaR paramétrique** : suppose une distribution normale des rendements. 
Rapide à calculer mais sous-estime le risque en présence de queues épaisses.

**VaR historique** : basée sur les 252 derniers jours ouvrés. 
Plus réaliste car elle reflète les vrais mouvements de marché, sans hypothèse distributionnelle.

**Monte Carlo** : 10 000 simulations de scénarios. 
La plus robuste, capte les non-linéarités et les cas extrêmes.

**Expected Shortfall (CVaR)** : mesure la perte moyenne au-delà du seuil VaR. 
Complète la VaR en quantifiant la sévérité des pertes dans la queue de distribution.

**Stress tests** : les 4 scénarios modélisent des chocs macroéconomiques 
distincts (canal du crédit, canal des taux, choc systémique) et leur impact 
sur les pertes, le taux de défaut et la consommation de capital.

**ICAAP**  compare le capital disponible (CET1) aux exigences réglementaires 
Bâle III et aux besoins estimés sous stress. Le dashboard signale en rouge 
quand le capital devient insuffisant sous un scénario adverse.

## Auteur

Hanane Chahri - École Centrale Casablanca / École Centrale de Lyon
