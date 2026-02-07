#  Analyse de la Performance Énergétique - Occitanie (DPE)


##  Contexte du Projet

Ce projet a été réalisé pour le compte de **GreenTech Solutions**, mandaté par **Enedis**.  
L'objectif est de fournir aux collectivités locales (Mairies) un outil de pilotage pour analyser la performance énergétique du parc immobilier (Neuf et Ancien) en région Occitanie, avec un focus sur la Haute-Garonne (31).

L'outil permet d'identifier les passoires thermiques, de suivre les émissions de GES et d'orienter les politiques de rénovation.
##  Accès à l'Application
> **[Cliquer ici pour ouvrir le Rapport Power BI](https://app.powerbi.com/groups/me/reports/a600b325-af13-48fd-9a14-bb6bf4b4bd9b?ctid=a51a6642-5911-4306-a13c-f4731ab9c63f&pbi_source=linkShare)**

##  Fonctionnalités Clés

* **Tableau de Bord Général :** Vue synthétique des KPIs (Nombre de logements, Coût moyen énergie, Surface moyenne).
* **Cartographie Interactive :** Visualisation géographique des logements par étiquette DPE.
* **Comparateur de Territoires :** Module dédié permettant de comparer les indicateurs de deux communes côte à côte.
* **Sécurité Avancée (RLS) :** Mise en place du *Row-Level Security* pour restreindre l'accès aux données : un Maire ne voit que sa propre commune.

##  Stack Technique

* **Outil :** Microsoft Power BI Desktop.
* **ETL (Extract Transform Load) :** Power Query pour la fusion des données (Sources : CSV Neufs & Existants).
* **Modélisation :** Architecture unifiée (Table Maîtresse consolidée) optimisée pour la performance de lecture.
* **Langage :** DAX (Data Analysis Expressions) pour les mesures dynamiques.

##  Structure du Dépôt

* `projet.pbix` : Le fichier source Power BI contenant le rapport et le modèle de données.
* `Dossier_Conception_UI_UX.docx` : Maquettes graphiques (Figma)  avant développement  et interface finale. (**[Voir la Maquette](https://scheme-dab-66876623.figma.site/)**)
* `Documentation_Technique.docx` : Explications détaillées sur l'architecture, le RLS et les performances.
* `Documentation_Fonctionnelle.docx` : Guide utilisateur à destination des Mairies.
* `data/` :  Dossier contenant les jeux de données bruts.




## 👤 Auteur
* meryem.chouki@univ-lyon2.fr
* sharon.guedj@univ-lyon2.fr
* ulrick.berthon@univ-lyon2.fr


