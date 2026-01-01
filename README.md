# Big Data Pipeline avec Airflow et Docker

## Description

Ce projet met en place un **pipeline Big Data complet** utilisant **Apache Airflow** pour l’orchestration, **PostgreSQL** comme base de données, et **Docker** pour la containerisation.  

Le pipeline permet de gérer automatiquement des tâches de traitement de données, depuis l’ingestion jusqu’au stockage et à l’analyse.

Le projet inclut :  

- Orchestration avec **Airflow 2.8.1**  
- Base de données **PostgreSQL 13** pour Airflow  
- Gestion des DAGs Big Data dans le dossier `dags`  
- Stockage des fichiers de sortie dans le dossier `data`  
- Exécution en **docker-compose** pour simplifier le déploiement  

---

## Prérequis

- [Docker](https://www.docker.com/get-started) >= 20.10  
- [Docker Compose](https://docs.docker.com/compose/install/) >= 1.29  
- Système : Windows / Linux / MacOS  
## Accès à l’interface web Airflow

URL : http://localhost:8081

Login : admin

Password : admin

## Structure du projet
Pipeline_Big_Data/
│
├── dags/              # DAGs Airflow (ex : bigdata_pipeline_complete.py)
├── data/              # Données d’entrée et de sortie
├── docker-compose.yml # Définition des services (Airflow + Postgres)
└── README.md        
