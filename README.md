#  TP R‚seau - Routing 

Ce projet contient la topologie Cisco Packet Tracer du TP de routage statique et switching.

## ?? Objectifs du TP
- Configurer les interfaces des routeurs
- Mettre en place le routage statique
- Tester la connectivit‚ entre les r‚seaux
- Sauvegarder la configuration sur chaque ‚quipement

## ?? Commandes utiles

### Ajouter une route statique :
    ip route <r‚seau> <masque> <next-hop | interface>

### Supprimer une route statique :
    no ip route <r‚seau> <masque> <next-hop | interface>

### Sauvegarder la configuration :
    wr
    copy running-config startup-config

### V‚rifications :
    show ip route
    show running-config
    ping <adresse>

## ?? Fichiers
- topologie.pkt
- README.md

## ?? Auteur
Projet r‚alis‚ dans le cadre du TP R‚seau - Routing 

