# 🏥 Projet RSX101 – Réseau Hospitalier Sécurisé (OSPF Multi-Aire)

## 📌 Description
Ce projet a pour objectif de **concevoir, structurer et sécuriser le réseau informatique d’un hôpital**, en se concentrant sur les **couches 1 à 4 du modèle OSI** (physique à transport), avec l’intégration d’un **routage dynamique OSPF multi-aire**.

Le réseau doit garantir :
- Une **communication fiable et sécurisée** entre les services hospitaliers  
- La **priorisation des flux critiques**  
- Une **architecture scalable, redondante et maintenable**  
- Une **segmentation logique** via **VLANs** et **DMZ**

Le projet est réalisé dans un **cadre académique (RSX101)** et repose sur une **conception logique et une simulation réseau**, sans contraintes budgétaires.

---

## 🧠 Services hospitaliers pris en compte
- Urgences  
- Chirurgie  
- Radiologie  
- Laboratoires  
- Administration  
- Accès Internet  

Les flux critiques (ex. *Urgences ↔ Radiologie*, *Chirurgie ↔ Laboratoire*) sont identifiés et priorisés.

---

## 🌐 Architecture réseau
- Backbone en **fibre optique**
- Segmentation par **VLAN**
- **Routage inter-VLAN**
- **Réseau OSPF multi-aire**
  - Aire 0 : backbone
  - Aires secondaires par service
- Isolation des réseaux via **DMZ**
- Prise en compte de la **haute disponibilité** et de la **maintenance (MCO/MCS)**

---

## 🛠️ Outils utilisés
- **Cisco Packet Tracer** : conception et simulation du réseau  
- **GitHub** : gestion collaborative du projet  
- **PDF** : rendu final du rapport  

---

## 📂 Contenu du dépôt
- 📁 Fichier Packet Tracer (`.pkt`)
- 📄 Rapport final au format PDF
- 📊 Matrice de flux
- 🌐 Plan d’adressage IP
- ⚙️ Configurations routeurs et switches
- 🧩 Schéma logique d’implémentation

---

## 👥 Travail en équipe
Le projet est réalisé en groupe avec :
- Un **fichier Packet Tracer unique**
- Une **répartition claire des rôles** (architecture, VLAN/flux, sécurité & documentation)
- Un **suivi des versions** pour assurer la cohérence du travail

---

## 🎯 Objectif pédagogique
Ce projet vise à mettre en pratique :
- La **conception d’un réseau complexe**
- Le **routage dynamique OSPF**
- La **segmentation et la sécurisation réseau**
- La **documentation technique professionnelle en Markdown**
