# Sales Analysis & Customer Performance Dashboard  
# Analyse des Ventes et Performance Clients

---

## Français

### Description

Ce projet consiste à analyser les ventes d’un hypermarché et à construire un tableau de bord décisionnel avec Power BI.  
L’objectif est de suivre les performances commerciales, comparer les ventes aux objectifs, analyser les clients, les catégories de produits et les indicateurs clés de performance.

Le projet met en œuvre un pipeline complet : nettoyage des données, préparation des fichiers, traitement SQL, modélisation, création de mesures DAX et conception d’un dashboard interactif.

### Objectifs du projet

- Nettoyer et préparer les données de ventes.
- Analyser les ventes par catégorie, sous-catégorie, segment client et zone géographique.
- Comparer les ventes réalisées avec les objectifs fixés.
- Suivre les indicateurs clés : chiffre d’affaires, quantité vendue, profit et marge.
- Visualiser les tendances mensuelles et annuelles.
- Construire un tableau de bord interactif pour faciliter la prise de décision.

### Fonctionnalités du dashboard

- Suivi des ventes totales.
- Suivi du profit total.
- Analyse de la marge de profit.
- Comparaison ventes vs objectifs.
- Analyse des ventes par sous-catégorie.
- Analyse des ventes par segment client.
- Analyse géographique des ventes et profits.
- Visualisation des tendances par mois et année.
- Tableau détaillé des clients avec ventes et profits.

### Données utilisées

Le projet utilise plusieurs fichiers de données liés aux ventes et aux objectifs :

- `Hypermarche.csv`
- `Hypermarche_clean.csv`
- `Objectifs_ventes.csv`
- `Objectifs_ventes_clean.csv`

Les données ont été nettoyées et préparées avant leur exploitation dans Power BI.

### Méthodologie

1. **Collecte des données**
   - Importation des fichiers CSV.
   - Analyse de la structure des données.
   - Identification des colonnes utiles pour l’analyse.

2. **Nettoyage et préparation**
   - Traitement des valeurs manquantes.
   - Correction des formats.
   - Nettoyage des colonnes.
   - Préparation des données dans un notebook Jupyter.

3. **Analyse et modélisation**
   - Analyse exploratoire des ventes.
   - Structuration des données.
   - Création de relations entre les tables.
   - Utilisation de SQL pour manipuler et organiser les données.

4. **Création du dashboard**
   - Importation des données dans Power BI.
   - Création de mesures DAX.
   - Construction d’indicateurs clés.
   - Conception de visualisations interactives.

### Technologies utilisées

- Power BI
- DAX
- Power Query
- SQL
- Python
- Pandas
- Jupyter Notebook
- CSV

### Fichiers du projet

- `Sales.pbix` : fichier Power BI du tableau de bord.
- `Tableau de bord.pdf` : aperçu du dashboard final.
- `data_clean.ipynb` : notebook de nettoyage et préparation des données.
- `hypermarche.sql` : script SQL utilisé pour le traitement des données.
- `schema.png` : schéma de modélisation.
- `rapport talend power bi.pdf` : rapport du projet.
- `Hypermarche.csv` : données brutes.
- `Hypermarche_clean.csv` : données nettoyées.
- `Objectifs_ventes.csv` : objectifs de ventes.
- `Objectifs_ventes_clean.csv` : objectifs de ventes nettoyés.

### Résultat

Le projet a permis de construire un tableau de bord Power BI interactif permettant de suivre les performances commerciales, d’analyser les ventes par catégorie et segment, et de comparer les résultats obtenus avec les objectifs définis.

### Aperçu du dashboard

Le tableau de bord présente plusieurs indicateurs clés :

- Total Sales
- Total Quantity
- Profit Margin
- Total Profit
- Sales vs Targets
- Sales by category and sub-category
- Sales by customer segment
- Sales by month and year
- Sales and profit by country

### Auteur

- Wiam BEL MEHDI

---

## English

### Description

This project focuses on analyzing supermarket sales data and building a business intelligence dashboard using Power BI.  
The goal is to monitor sales performance, compare actual sales with targets, analyze customers, product categories, and key performance indicators.

The project follows a complete data analysis workflow: data cleaning, data preparation, SQL processing, data modeling, DAX measures, and interactive dashboard creation.

### Project Objectives

- Clean and prepare sales data.
- Analyze sales by category, sub-category, customer segment, and geographic area.
- Compare actual sales with sales targets.
- Track key indicators such as total sales, quantity, profit, and profit margin.
- Visualize monthly and yearly sales trends.
- Build an interactive dashboard to support decision-making.

### Dashboard Features

- Total sales tracking.
- Total profit tracking.
- Profit margin analysis.
- Sales vs targets comparison.
- Sales analysis by sub-category.
- Sales analysis by customer segment.
- Geographic analysis of sales and profit.
- Monthly and yearly trend visualization.
- Detailed customer table with sales and profit values.

### Data Used

The project uses several sales and target datasets:

- `Hypermarche.csv`
- `Hypermarche_clean.csv`
- `Objectifs_ventes.csv`
- `Objectifs_ventes_clean.csv`

The datasets were cleaned and prepared before being used in Power BI.

### Methodology

1. **Data Collection**
   - Importing CSV files.
   - Understanding the data structure.
   - Identifying relevant columns for analysis.

2. **Data Cleaning and Preparation**
   - Handling missing values.
   - Fixing data formats.
   - Cleaning columns.
   - Preparing the data using a Jupyter Notebook.

3. **Analysis and Modeling**
   - Exploratory sales analysis.
   - Data structuring.
   - Creating relationships between tables.
   - Using SQL to manipulate and organize the data.

4. **Dashboard Creation**
   - Importing data into Power BI.
   - Creating DAX measures.
   - Building key performance indicators.
   - Designing interactive visualizations.

### Technologies Used

- Power BI
- DAX
- Power Query
- SQL
- Python
- Pandas
- Jupyter Notebook
- CSV

### Project Files

- `Sales.pbix`: Power BI dashboard file.
- `Tableau de bord.pdf`: final dashboard preview.
- `data_clean.ipynb`: data cleaning and preparation notebook.
- `hypermarche.sql`: SQL script used for data processing.
- `schema.png`: data model schema.
- `rapport talend power bi.pdf`: project report.
- `Hypermarche.csv`: raw dataset.
- `Hypermarche_clean.csv`: cleaned dataset.
- `Objectifs_ventes.csv`: sales targets dataset.
- `Objectifs_ventes_clean.csv`: cleaned sales targets dataset.

### Result

The project resulted in an interactive Power BI dashboard that helps monitor sales performance, analyze sales by category and segment, and compare actual results with predefined sales targets.

### Dashboard Preview

The dashboard includes several key indicators:

- Total Sales
- Total Quantity
- Profit Margin
- Total Profit
- Sales vs Targets
- Sales by category and sub-category
- Sales by customer segment
- Sales by month and year
- Sales and profit by country

### Author

- Wiam BEL MEHDI
```
