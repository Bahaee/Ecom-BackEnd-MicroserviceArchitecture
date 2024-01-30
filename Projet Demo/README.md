# Projet E-commerce avec Microservices

## Introduction
Ce projet met en œuvre une architecture de microservices pour un système e-commerce. Les microservices incluent le service customer et une gateway.

## Technologies Utilisées
- Spring Boot
- Spring Cloud
- Consul
- (Autres technologies utilisées dans le projet)

## Structure du Projet
Le projet est organisé comme suit :

ecom/
|-- service-customer/
|-- gateway-service/
|-- config-service/
|-- (Autres services et modules)


Chaque service a sa propre structure interne avec des fichiers de configuration, des classes de contrôleur, etc.

## Démarrage de Consul
Pour exécuter Consul localement, utilisez la commande suivante :
```bash
consul agent -server -bootstrap-expect=1 -data-dir=your_data_directory -ui -bind=your_ip_address
```

## Configuration

Les configurations des différents services sont stockées dans le dossier "ecom". Assurez-vous de commettre les changements pour déclencher les mises à jour.

# Services

## Service Customer

Le service customer utilise la dépendance REST de Spring pour gérer les fonctionnalités liées aux clients. Assurez-vous d'avoir démarré le service avec les configurations nécessaires.

## Gateway Service

La gateway service agit comme une passerelle pour rediriger le trafic vers les microservices appropriés. Assurez-vous que la configuration est correctement définie.

# Déploiement

(Ajoutez des instructions de déploiement ici, y compris les étapes pour construire et exécuter les services.)

# Tests

(Ajoutez des instructions pour les tests, y compris les dépendances et les commandes nécessaires.)

# Contributions

Les contributions sont les bienvenues! Si vous souhaitez contribuer, veuillez suivre ces étapes :
1. Fork du projet
2. Création d'une branche pour la fonctionnalité ou la correction
3. Soumission d'une pull request

# Licence

Ce projet est sous licence BAHAE. Voir le fichier LICENSE.md pour plus de détails.

