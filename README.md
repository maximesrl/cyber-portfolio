# Portfolio – Infrastructure Linux & Cybersécurité Défensive

## À propos

Passionné par les systèmes et la sécurité informatique, je développe de manière autodidacte une expertise progressive en administration Linux et en cybersécurité défensive.
Mon approche est orientée pratique : chaque compétence est construite, testée et documentée dans des environnements de laboratoire réalistes.

## Objectif

Construire une base opérationnelle solide en administration système Linux et en cybersécurité défensive à travers des environnements de laboratoire structurés.

Ce portfolio documente une progression technique cohérente autour de :

- Fondamentaux réseau
- Administration système Linux
- Durcissement de serveurs
- Analyse et détection via les logs (en cours)

L’objectif n’est pas l’accumulation de commandes, mais la maîtrise progressive des mécanismes systèmes et de leurs implications en matière de sécurité.

---

## Organisation des projets

###   1. Network Fundamentals Lab  
Repository : `network-fundamentals-lab`
https://github.com/maximesrl/virtual-network-setup.git

Conception d’un environnement réseau virtualisé permettant d’explorer en profondeur :

- Communication TCP/IP
- Fonctionnement DNS (UDP/TCP, TTL, cache)
- Analyse du handshake DHCP
- Capture et inspection de paquets avec Wireshark
- Analyse d’exposition des services
- Compréhension des ports et processus réseau

Ce projet démontre une compréhension concrète du fonctionnement réel d’un réseau.

---

###  2. Linux System Administration  
Repository : `linux-system-administration`

Simulation d’un environnement multi-utilisateurs inspiré d’un contexte entreprise :

- Gestion des utilisateurs et groupes
- Modèle de contrôle d’accès basé sur les groupes
- Permissions et ownership
- Utilisation du sticky bit (1770)
- Structuration de répertoires par département
- Application du principe de moindre privilège

Ce projet met l’accent sur la conception logique d’un système et la séparation des responsabilités.

---

###  3. Linux Security Hardening  
Repository : `linux-security-hardening`

Mise en place de mesures de sécurisation sur un serveur Linux :

- Politique firewall en "deny by default" (UFW / iptables)
- Filtrage stateful
- Durcissement SSH
- Désactivation du login root à distance
- Déploiement et configuration de Fail2ban
- Analyse des tentatives de brute force
- Vérification et validation des règles

Ce projet reflète une approche défensive et une logique de réduction de surface d’attaque.

---

##  Axe de progression actuel

Développement en cours autour de :

- Analyse des logs système (auth.log, journalctl)
- Corrélation d’événements
- Logique "assume breach"
- Stratégies de segmentation réseau
- Détection d’anomalies

---

##  Méthodologie

Chaque projet suit une démarche structurée :

1. Mise en place de l’environnement
2. Expérimentation contrôlée
3. Observation et validation technique
4. Analyse des implications sécurité
5. Identification des limites et axes d’amélioration

L’objectif est une montée en compétence durable et cohérente.

---

##  Roadmap

Prochaines étapes prévues :

- Laboratoire de centralisation des logs
- Conception de règles de détection
- Architecture firewall avancée
- Segmentation VLAN
- Automatisation Bash
- Simulation de supervision sécurité

---

##  Positionnement

La sécurité n’est pas une option ajoutée à un système :  
elle doit être intégrée dès la conception.

Ce portfolio reflète une transition progressive :
comprendre les systèmes → les structurer → les sécuriser.
