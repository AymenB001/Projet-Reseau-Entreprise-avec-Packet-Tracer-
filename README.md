# Projet-Reseau-Entreprise-avec-Packet-Tracer-

Ce projet est une simulation d’un réseau d’entreprise réalisée avec **Cisco Packet Tracer**.  
L’objectif est de reproduire l’infrastructure typique d’une PME et de mettre en place les services réseaux essentiels :  
- Segmentation en VLAN  
- Routage inter-VLAN  
- Attribution dynamique d’adresses IP (DHCP)  
- Accès Internet via NAT  
- Règles de sécurité (ACL)  

Ce projet est conçu pour démontrer mes compétences pratiques en réseautique et support technique.

---

## 🛠️ Objectifs techniques
- Créer une topologie réseau incluant :  
  - Routeur, switchs et plusieurs PC/serveurs  
  - Trois VLAN distincts (Finance, RH, IT)  
- Mettre en place le routage inter-VLAN sur le routeur  
- Configurer un serveur DHCP pour l’attribution automatique des adresses IP  
- Simuler un accès Internet avec NAT  
- Restreindre l’accès via des **ACL** (par exemple : bloquer Finance d’accéder au VLAN IT)  

---

Captures d'écran pour chaque étape du projet complétées 

Création des PCs et topologie physique
  - Capture : les 4 PC + les switchs + le routeur posés

Configuration VLANs sur les switchs
-  Capture : console du switch avec show vlan ou le schéma VLAN

Trunk entre switchs
-  Capture : console ou schéma montrant le lien trunk

Routage inter-VLAN sur le routeur
-  Capture : console avec show ip route ou ping réussi entre VLANs

DHCP en action
-  Capture : PC avec IP reçue automatiquement

Ping / test Internet via NAT
-  Capture : ping réussi vers le cloud ou PC Internet simulé

ACL
-  Capture : ping bloqué entre Finance et RH + ping OK depuis Admin

