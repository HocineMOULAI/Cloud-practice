# Lab 06 - Elastic Load Balancer

## Objectif
Mettre en place un Elastic Load Balancer (ELB) afin de répartir le trafic entre plusieurs instances EC2 et garantir une haute disponibilité du service web.

## Étapes principales
1. Lancer plusieurs instances EC2 (ex. 2 instances Amazon Linux)
2. Créer un Elastic Load Balancer (type Application Load Balancer).
3. Définir les sous-réseaux publics et attacher le Security Group (port 80 ouvert).
4. Créer un Target Group et y enregistrer les instances EC2.
5. Associer le Target Group au Load Balancer.
6. Vérifier que l’accès au DNS du Load Balancer redirige vers les différentes instances.
7. Simuler l’arrêt d’une instance et constater que le trafic est automatiquement redirigé vers l’instance restante.

## Résultat
- Le trafic est distribué automatiquement entre plusieurs instances.
- En cas d’indisponibilité d’une instance, le service reste accessible via le Load Balancer.
- Amélioration de la tolérance aux pannes et de la haute disponibilité.

## Compétences acquises
- Création et configuration d’un Elastic Load Balancer.
- Association d’instances EC2 à un Target Group.
- Vérification du fonctionnement de la répartition de charge.
- Compréhension de l’importance des Load Balancers pour l’élasticité et la résilience des applications.
