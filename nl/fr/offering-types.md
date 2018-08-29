---


copyright:
  years: 2018
lastupdated: "2018-07-01"


---

{:shortdesc: .shortdesc}
{:codeblock: .codeblock}
{:screen: .screen}
{:tip: .tip}
{:new_window: target="_blank"}

# Types d'offre de tiers
{: #offering-types}

Vous pouvez mettre à disposition une offre de tiers en tant que service de facturation intégrée ou en tant que service de référence dans {{site.data.keyword.Bluemix}}.
{:shortdesc}

Lorsque vous mettez à disposition votre offre de tiers en tant que service de facturation intégrée, les utilisateurs peuvent effectuer une sélection parmi différents plans de tarification IBM répertoriés sur la page des détails de catalogue dans la console {{site.data.keyword.Bluemix_notm}}. De plus, les utilisateurs peuvent automatiquement créer une instance de votre offre de tiers.

Lorsque vous mettez à disposition votre offre de tiers en tant que service de référence, les utilisateurs sont redirigés sur votre site Web à partir de la page des détails de catalogue de la console {{site.data.keyword.Bluemix_notm}}. A partir de votre site Web, les utilisateurs créent des comptes et obtiennent les données d'identification requises pour connecter à l'aide d'un programme votre offre de tiers à une application créée à partir d'{{site.data.keyword.Bluemix_notm}}.

## Comparaison des types d'offre
{: #compare}

Le tableau suivant compare de manière détaillée les différentes types d'offre de tiers.

|  | Service de facturation intégrée  | Service de référence |
|---|---|---|
| **Intégration** | L'intégration est gérée via le tableau de bord PWB (Provider Workbench) et la console de gestion des ressources. Le fournisseur de l'offre est chargé de développer un courtier OSB, de l'héberger et de le tester ainsi que de publier son offre. Pour cela, il suit plusieurs procédures en libre service. | L'intégration est gérée via le tableau de bord PWB. Le processus d'intégration en libre-service dure environ deux semaines. |
| **Déploiement** | Le déploiement est effectué dans la plateforme {{site.data.keyword.Bluemix_notm}} | Services reposant sur une API uniquement |
| **Facturation**  |  Dans le modèle de facturation intégrée, l'utilisateur reçoit une seule facture pour l'offre IBM et l'offre de tiers intégrée. | Dans le modèle de référence, le fournisseur facture l'utilisateur et conserve l'intégralité des recettes.  |
| **Exemple** | [PowerAI](https://console.bluemix.net/catalog/services/powerai) | [API Accern](https://console.bluemix.net/catalog/services/accern-api) |
{: caption="Tableau 1. Comparaison des différents types d'offre de tiers" caption-side="top"}
