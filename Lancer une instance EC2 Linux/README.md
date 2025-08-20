# Lab 02 - Lancer une instance EC2 Linux

## Objectif
Lancer une instance EC2 Linux, s’y connecter en SSH.

## Étapes principales
1. Lancement d’une instance EC2 Linux (Amazon Linux 2).
2. Association d’un groupe de sécurité avec accès SSH (port 22).
3. Création d’une paire de clés SSH depuis la console AWS.
4. Connexion à l’instance via `ssh -i "ma-cle.pem" ec2-user@<public-ip>`.

## Résultats
- Instance Linux accessible en SSH.
- Sécurité assurée avec un groupe de sécurité restreint.

## Compétences acquises
- Création et gestion d’instances EC2.
- Gestion des clés SSH.
- Notions de base sur la sécurisation des accès réseau.
