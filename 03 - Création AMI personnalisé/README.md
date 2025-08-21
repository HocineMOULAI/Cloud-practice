# Lab 03 - Création d’une AMI personnalisée et démarrage d’instance depuis AMI perso

## Objectif
Créer une AMI personnalisée à partir d’une instance EC2 configurée, puis lancer une nouvelle instance basée sur cette AMI afin de répliquer automatiquement la configuration.

## Étapes principales
1. Lancer une instance EC2 Linux (Amazon Linux 2) avec un script User Data qui installe Apache et configure une page web.
2. Vérifier l’accessibilité de la page web depuis le navigateur via l’IP publique de l’instance.
3. Depuis la console AWS, créer une AMI à partir de cette instance (Actions > Image et modèles > Créer une image).
4. Attendre la fin du processus de création de l’AMI.
5. Lancer une nouvelle instance EC2 à partir de cette AMI personnalisée.
6. Vérifier que la page web est automatiquement disponible sans configuration supplémentaire.

## Résultat
- Une AMI personnalisée créée et stockée dans AWS.
- Une instance EC2 lancée directement depuis cette AMI, avec Apache et la page web déjà configurés.
- Réplicabilité assurée : déploiement rapide d’environnements identiques.

## Compétences acquises
- Création et gestion d’AMI personnalisées.
- Démarrage d’instances EC2 à partir d’une image personnalisée.
- Compréhension de la standardisation et de l’automatisation du provisioning sur AWS.
