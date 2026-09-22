# Analyse égalité femmes-hommes

## Contexte

Dans le cadre d’un cabinet de conseil en transformation digitale de plus de 150 salariés, ce projet répond à un besoin RH : automatiser la préparation d’un diagnostic sur l’égalité professionnelle entre les femmes et les hommes.

L’objectif est d’aider les équipes RH à suivre plusieurs indicateurs, à préparer les éléments nécessaires à la publication annuelle de l’index d’égalité femmes-hommes et à identifier des pistes d’amélioration.

## Données

Les données proviennent d’un Système d’Information des Ressources Humaines (SIRH).

Elles comprennent notamment :

- les salaires et rémunérations ;
- l’âge et l’ancienneté ;
- le temps de travail ;
- les promotions ;
- le service d’appartenance ;
- le nombre d’accidents ;
- le niveau de satisfaction moyen.

Les données étant nominatives à l’origine, elles ont été traitées afin de respecter les exigences du **RGPD**. Le diagnostic repose sur des données agrégées, sans exposer d’informations individuelles.

## Démarche

Le projet a été réalisé avec **KNIME**.

Le workflow permet de :

- importer et contrôler les données issues du SIRH ;
- préparer, nettoyer et agréger les données ;
- vérifier leur cohérence ;
- produire des graphiques pour le diagnostic ;
- générer un fichier CSV.

Au moins cinq indicateurs liés à l’égalité professionnelle sont calculés et visualisés dans le workflow.

## Résultats

L’analyse permet de comparer plusieurs indicateurs selon le sexe et les services de l’entreprise.

Les résultats mettent en évidence des écarts plus ou moins marqués selon :

- l’indicateur étudié ;
- le sexe ;
- le service concerné.

Le workflow facilite la reproduction du diagnostic lors des campagnes suivantes et fournit une base claire pour suivre les évolutions dans le temps.

## Limites et pistes d’amélioration

Les analyses dépendent de la qualité et de l’exhaustivité des données renseignées dans le SIRH.

Les prochaines étapes pourraient inclure :

- l’intégration de nouvelles campagnes annuelles ;
- le suivi de l’évolution des écarts dans le temps ;
- l’ajout d’autres indicateurs RH ;
- la mise en place d’un tableau de bord pour diffuser les résultats ;

## Outils utilisés

- KNIME
- CSV
