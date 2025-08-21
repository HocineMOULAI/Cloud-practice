# Lab 04 - Gestion des groupes de sécurité

## Objectif
Comprendre l’impact des règles d’un groupe de sécurité sur l’accessibilité d’un service web hébergé sur une instance EC2.

## Étapes principales
1. Lancer une instance EC2 Linux avec Apache installé et en cours d’exécution.
2. Créer ou utiliser un groupe de sécurité associé à l’instance.
3. Vérifier l’accès à la page web par défaut :
4. Sans règle HTTP (port 80) → accès refusé.
5. Avec règle HTTP (port 80) → accès autorisé.
6. Supprimer la règle HTTP et constater que l’accès est de nouveau bloqué.

## Résultat
- Mise en évidence du rôle des groupes de sécurité comme firewall virtuel.
- Compréhension de l’impact immédiat de l’ajout ou suppression de règles entrantes.

## Compétences acquises
- Création et modification de groupes de sécurité.
- Gestion des règles d’accès réseau (HTTP, SSH).
- Compréhension du lien entre règles réseau et accessibilité des services.
