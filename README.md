<div align="center">

# Alexis Claudeon

### Data Analyst junior · SQL · Power BI · Python · dbt

[![CDI, disponible immédiatement](https://img.shields.io/badge/CDI-disponible%20imm%C3%A9diatement-2E7D5B?style=for-the-badge)](#contact)
[![Orléans, mobile région parisienne](https://img.shields.io/badge/Orl%C3%A9ans%20(45)-mobile%20r%C3%A9gion%20parisienne-1a3c6e?style=for-the-badge)](#contact)

[![LinkedIn](https://img.shields.io/badge/LinkedIn-alexis--claudeon-1a3c6e?style=for-the-badge)](https://www.linkedin.com/in/alexis-claudeon)
[![E-mail](https://img.shields.io/badge/E--mail-alexis.claudeon%40outlook.fr-1a3c6e?style=for-the-badge)](mailto:alexis.claudeon@outlook.fr)

</div>

---

## En bref

Data Analyst junior en reconversion depuis la logistique. Depuis octobre 2025, j'ai conçu en autonomie **3 chaînes de données de bout en bout**, puis **3 projets métier** : migration SAS, détection de fraude, process mining des achats SAP.

- **Des tableaux de bord qui répondent à une question** : Power BI et Tableau, mesures DAX, KPIs.
- **Des chiffres vérifiés** : tests dbt, recettes de non-régression, contrôles de conformité, tests statistiques.
- **Le terrain** : préparateur de commande chez Deret Logistique, j'utilisais le WMS au quotidien et je connais les données de production logistique de l'intérieur.

**Je cherche un CDI de Data Analyst au sein d'une équipe data**, à Orléans ou en région parisienne.

---

## Projets

<table>
<tr>
<td width="50%" valign="top">

<a href="https://github.com/Alexis45140/p2p-process-mining-sap"><img src="https://raw.githubusercontent.com/Alexis45140/p2p-process-mining-sap/main/docs/page1_processus.png" alt="Tableau de bord Power BI du processus d'achat"></a>

### [Process mining des achats SAP](https://github.com/Alexis45140/p2p-process-mining-sap)

*Les achats suivent-ils le circuit prévu, de la commande au paiement ?*

**655 lignes payées avant réception**, environ 1,75 M€, repérées par 4 contrôles de conformité sur 251 652 lignes de commande réelles.

`Python` `PM4Py` `SQL` `dbt` `DuckDB` `Power BI`

</td>
<td width="50%" valign="top">

<a href="https://github.com/Alexis45140/bank-sas-migration"><img src="https://raw.githubusercontent.com/Alexis45140/bank-sas-migration/main/powerbi/dashboard.png" alt="Tableau de bord Power BI de la campagne bancaire"></a>

### [Migration SAS bancaire](https://github.com/Alexis45140/bank-sas-migration)

*Une migration de SAS vers Dataiku et Python change-t-elle un chiffre ?*

**Dataiku et Python identiques à SAS** sur 41 188 clients (recette de non-régression), puis 4 recommandations de ciblage confirmées par des tests du χ² et une régression logistique.

`SAS` `Dataiku` `Python` `statsmodels` `Power BI` `DAX`

</td>
</tr>
<tr>
<td width="50%" valign="top">

<a href="https://github.com/Alexis45140/fraud-bank"><img src="https://raw.githubusercontent.com/Alexis45140/fraud-bank/main/powerbi/page1_comparaison_regles.png" alt="Tableau de bord Power BI comparant les règles de contrôle"></a>

### [Détection de fraude bancaire](https://github.com/Alexis45140/fraud-bank)

*Comment repérer presque toutes les fraudes sans noyer l'équipe de contrôle sous les alertes ?*

**99,1 % des fraudes détectées** au lieu de 0,2 %, pour 318 alertes par jour : 8 règles de contrôle comparées sur 6,36 M de transactions simulées.

`Python` `KNIME` `Power BI` `DAX`

</td>
<td width="50%" valign="top">

<a href="https://github.com/Alexis45140/football-data-pipeline"><img src="https://raw.githubusercontent.com/Alexis45140/football-data-pipeline/main/images/football_dashboard_preview.png" alt="Tableau de bord Power BI des transferts de football"></a>

### [Pipeline Football](https://github.com/Alexis45140/football-data-pipeline)

*Comment fiabiliser une ingestion d'API quotidienne ?*

**500 transferts** extraits d'une API en Python, chargés dans BigQuery et transformés avec dbt. Cron quotidien GitHub Actions, 10 tests dbt, arrêt au premier échec.

`Python` `BigQuery` `dbt` `GitHub Actions` `Docker` `Power BI`

</td>
</tr>
<tr>
<td width="50%" valign="top">

<a href="https://github.com/Alexis45140/Employee-Data-Analysis-Insights-Performance-SQL"><img src="https://raw.githubusercontent.com/Alexis45140/Employee-Data-Analysis-Insights-Performance-SQL/main/outputs/05_tableau_dashboard.png" alt="Tableau de bord Tableau des KPIs RH"></a>

### [Analyse RH](https://github.com/Alexis45140/Employee-Data-Analysis-Insights-Performance-SQL)

*Quels départements paient le plus, et les données sont-elles fiables ?*

Salaire moyen **39 % plus élevé** en Sales qu'en Human Resources, sur 300 000 lignes. 7 marts métier, tests dbt (unicité, aucun salaire négatif).

`SQL` `MySQL` `dbt` `Tableau`

</td>
<td width="50%" valign="top">

<a href="https://github.com/Alexis45140/Google-Data-Analytics-Steam-Case-Study"><img src="https://raw.githubusercontent.com/Alexis45140/Google-Data-Analytics-Steam-Case-Study/main/Visualisation/graphique_final_steam.png" alt="Graphique prix et satisfaction des jeux Steam"></a>

### [Étude de marché Steam](https://github.com/Alexis45140/Google-Data-Analytics-Steam-Case-Study)

*Quel prix de lancement pour un jeu indépendant ?*

**Prix recommandé à 19,99 €**, tiré du KPI Success Rate calculé en SQL et de la corrélation prix et satisfaction en R.

`SQL` `MySQL` `R`

</td>
</tr>
</table>

**Aussi** : [Retail, couche ML](https://github.com/Alexis45140/dbt-snowflake-retail-analytics). Le montant d'un achat se prédit-il ? Clustering K-means en 3 groupes, puis Random Forest corrigé d'une fuite de données : MAE 483,72 € contre 448,01 € pour la baseline (moyenne), il ne la bat pas. `dbt` `Snowflake` `BigQuery` `scikit-learn` `Tableau`

---

## Compétences

| Ce que je fais | Avec |
|---|---|
| **Tableaux de bord et reporting** | `Power BI` `DAX` `Power Query` `Tableau` `Excel (TCD)` |
| **SQL** | `CTE` `fonctions de fenêtrage` `MySQL` `BigQuery` `Snowflake` `DuckDB` |
| **Qualité des données** | `tests dbt` `recettes de non-régression` `contrôles de conformité` |
| **Statistiques** | `statistiques descriptives` `tests du χ²` `régression logistique` `SciPy` `statsmodels` `R` |
| **Chaînes de données** | `Python` `pandas` `dbt Core` `GitHub Actions` `Docker` `Git` |
| **SAS et outils visuels** | `SAS` `Dataiku` `KNIME` |

---

## Formation et certifications

- **Certifications 2026** : Google Data Analytics · TOSA Python · Generative AI for Data Analysts (IBM)
- **Programme Grande École**, cycle pré-master (bac+3), BSB

---

## Contact

[LinkedIn](https://www.linkedin.com/in/alexis-claudeon) · alexis.claudeon@outlook.fr
