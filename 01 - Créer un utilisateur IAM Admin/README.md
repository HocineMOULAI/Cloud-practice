# Lab 01 - Créer un utilisateur IAM admin

## Objectif
Créer un utilisateur IAM avec des droits administrateurs pour éviter d’utiliser le compte root au quotidien.

## Étapes principales
1. Se connecter à la console AWS avec le compte root (uniquement pour la configuration initiale).
2. Aller dans le service **IAM**.
3. Créer un **utilisateur** nommé `admin-user`.
4. Lui attribuer la politique d'autorisation `AdministratorAccess`.

## Résultat
- Un utilisateur IAM admin est créé.
- Le compte root n’est plus utilisé pour les tâches quotidiennes.

## Compétences acquises
- Bonne pratique de sécurité AWS (ne pas utiliser le root account).
- Création et gestion d’un utilisateur IAM.
