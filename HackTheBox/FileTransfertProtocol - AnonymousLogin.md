# Analyse de vulnérabilité — [FileTransfertProtocol - Anonymous login]  
**Date :** 01/10/2025  
**Niveau :** Débutant  
**Durée estimée :** -1 heures

##  Contexte
- **Plateforme :** HackTheBox 
- **Catégorie :** Résaux - TCP/IP
- **Objectif :** Comprendre la vulnérabilité / Récupérer le flag 


## Environnement
- **VM / OS utilisé :**  Parrot
- **Outils utilisés :** nmap, ftp  
<!-- **Notes :** versions d’outils si pertinent -->



## Reconnaissance

J'ai commencer par scanner les ports de ma cible avec `sudo nmap -sV {target_IP}` l'option `-sV` pour "scan Version" permet d'afficher les version¨s des ports ouvert
