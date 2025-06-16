# Sum-Eau - France
(FRANCAIS)

**Suivi du SRAS-CoV2 dans les eaux usées hexagonales et Corses.**

Ces données présentent la surveillance du SRAS-CoV2 (syndrome respiratoire aigu sévère, coronavirus 2), responsable du COVID, dans les eaux usées dans 54 collectivités, sur les 30 dernières semaines.

Les données ouvertes utilisées dans les documents sont disponibles sur datagouv.fr ([lien direct](https://www.data.gouv.fr/fr/datasets/surveillance-du-sars-cov-2-dans-les-eaux-usees-sumeau/)) et leur description explique que :

> Les valeurs présentées dans le document sur datagouv sont calculées à partir du ratio entre la concentration de SRAS-CoV2 (cg L<sup>-1</sup>) et la concentration de NH<sub>4</sub><sup>+</sup> (mg L<sup>-1</sup>) dans les eaux usées. Les données sont ensuite modifiées en utilisant une régression de type LOESS, ce qui explique que les valeurs peuvent changer entre les mises à jour.


**Documents dispobibles dans ce repertoire :**
Deux fichiers R markdown, un exemple des graphique obtenus et une cartographie des stations :
- **Donnees-SumEau_colors.Rmd** (pour faire un pdf des villes par ordre alphabétique)
- **DonneesSumEau_2025_color_Région.Rmd** (pour faire un html par région avec sommaire cliquable, à publier [sur notre site](https://associationarra.wordpress.com/suivi-regional-sumeau/))
- **Un exemple de suivi avec son explication :**

![Suivi Sum'Eau à Amiens](Explication_circulation_SumEau.png)

Les niveaux de circulation sont calculés par quartile (blanc : 0-25%, jaune : 25-75%, rouge : 75-100%) en prenant en compte **tout** l'historique des données (même si le graphique ne représente que les 30 dernières semaines les circulations représentent les niveaux depuis le début des mesures), et pour chaque station (les méthodologies peuvent différer selon les stations/entreprises qui font les dosages). 

- **Carte des stations d'eaux usées suivies par Sum'Eau :**

![Carte des stations d'eau usées suivies avec Sum'Eau](mapSumEau.png)

Le dossier "historique" contient des données historiques de la version pdf par ville (Donnees-SumEau_colors.Rmd).


ENGLISH: Follow-up of French SARS-CoV2 concentration in waste waters.
