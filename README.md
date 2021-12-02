# Data-Quality-Project
Data Quality Project est un projet académique du module Qualité de données (DQ) en Master 2 DATASCALE à l'université de Versailles Saint Quentin En Yvelines, encadré par Mme Zoubida KEDAD.

### Sujet de projet
Ce projet est un projet d’intégration et qualité de données d'un dataset de données "pollution", qui sont prises par soit des capteurs mobiles ou bien des captures fixes dans des stations differentes.
Ces données sont collectés dans trois departements differents (Paris, Hauts de seine et Yvelines). Ce projet a pour but d’intégrer ces données de tables sources afin de définir des tables cibles, les évaluer et améliorer leur qualité par la suite, et cela passant par différentes étapes
de qualités de données et en répondant aux critères de qualité imposé par le projet (Granularité des données et hétérogénéité des échelles, Complétude des données, Conformité à un format et Détection et élimination des doublons).

Le sujet de projet se situe ici: [Data Quality project subject](./Docs/Sujet%20de%20Projet%20DQ.pdf).
 
### Datasets 
Comme décrit dans le sujet de projet, on a les datasets donné par l'encadrant du projet qui commencent par des SnumeroDeSource_xxx.xls qui representent les données sources, et les résultats des traitements éffectués sur les données sources nous donnent les fichiers C_xxx.xls qui sont les données cibles,
qui ont été mis au tests de qualités. 
<br>
[Datasets des sources](./Datasets/Sources)
<br>
[Datasets des cibles](./Datasets/Cibles)
 
### Utiles utilisées
#### ETL Talend
Comme le suggère leur sigle E-T-L, les opérations ETL suivent généralement une séquence en trois étapes : Extraction-Transformation-Chargement (L pour le terme anglais « Load »). Il est de plus en plus fréquent que les données soient extraites (E)
de leurs emplacements sources, puis chargées (L) dans un data warehouse cible, ou que les données soient transformées (T) après le chargement (L).
<br>Dans ce projet on a utilisé ETL Talend for data integration.
[Download Talend](https://www.talend.com/products/integrate-data/)

#### JDK Java
[Download JDK](https://www.oracle.com/java/technologies/downloads/)

### Compte rendu du projet
Pour plus d'informations sur ce projet, que çà soit sur coté conception et la réalisation de la qualité des données, tout est expliqué en details dans ce compte rendu.
Je vous invites à le lire [Compte rendu.pdf](./Docs/Compte%20rendu.pdf) 

### Fichiers Joints
Vous trouverez ici les fichiers joints, en ZIP qui permet lancer le projet réalisé sur l'ETL TALEND.
[DATA QUALITY](./DATA%20QUALITY%20p.zip) 

Dans ce Zip je vous recommande l'ETL TALEND 8 pour le faire marcher, pas Talend 7. 
[Talend 8 download](https://sourceforge.net/projects/talend-studio/files/latest/download) 
