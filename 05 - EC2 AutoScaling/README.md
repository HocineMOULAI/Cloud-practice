# Lab 05 - EC2 Auto Scaling Group

## Objectif
Mettre en place un Auto Scaling Group basé sur un modèle de lancement afin d’assurer la tolérance aux pannes d’instances EC2.

## Étapes principales
1. Créer un **Launch Template** avec :
   - une AMI Amazon Linux
   - un type d’instance (ex. t3.micro)
2. Créer un **Auto Scaling Group (ASG)** à partir du modèle de lancement.
3. Définir la capacité désirée (ex. 2 instances) ainsi que les bornes min et max.
5. Simuler une panne en arrêtant ou supprimant une instance EC2.
6. Constater que l’ASG relance automatiquement une nouvelle instance pour maintenir la capacité.

## Résultat
- L’Auto Scaling Group maintient en permanence le nombre d’instances défini.
- La suppression ou l’arrêt d’une instance entraîne automatiquement son remplacement.

## Compétences acquises
- Création et utilisation d’un Launch Template.
- Mise en place et configuration d’un Auto Scaling Group.
- Compréhension du mécanisme de tolérance aux pannes et de haute disponibilité.
