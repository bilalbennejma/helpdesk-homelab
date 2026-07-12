# 🖥️ Helpdesk Homelab

Labo personnel monté de A à Z pour développer des compétences concrètes en support informatique (helpdesk / technicien IT), en vue d'un poste de Technicien Support Informatique.

## 🎯 Objectif

Ce projet simule les tâches réelles d'un technicien helpdesk N1/N2 : gestion des comptes utilisateurs, résolution d'incidents, ticketing, réseau, déploiement de poste — construit et documenté étape par étape dans un environnement virtualisé.

## 🛠️ Stack technique

- **Virtualisation** : Oracle VirtualBox
- **Annuaire** : Windows Server 2022 / Active Directory (AD DS), GPO
- **Ticketing** : GLPI
- **Réseau** : pfSense, VPN (OpenVPN/WireGuard), TCP/IP
- **Support à distance** : AnyDesk / TeamViewer
- **Automatisation** : PowerShell

## 📁 Structure du repo

| Dossier | Contenu |
|---|---|
| [`01-active-directory`](./01-active-directory) | Installation Windows Server, AD DS, GPO, gestion utilisateurs/groupes |
| [`02-ticketing-glpi`](./02-ticketing-glpi) | Installation GLPI, flux de tickets, fiches procédures |
| [`03-reseau-vpn`](./03-reseau-vpn) | pfSense, VPN, diagnostic réseau (TCP/IP, DNS) |
| [`04-deploiement-remote`](./04-deploiement-remote) | Déploiement de poste, prise en main à distance, scripts PowerShell |

Chaque dossier contient un README détaillé avec captures d'écran expliquant la démarche, les commandes utilisées, et les problèmes rencontrés (et comment ils ont été résolus).

## ✅ Avancement

- [ ] Labo Active Directory
- [ ] Ticketing GLPI + base de connaissances
- [ ] Réseau (pfSense, VPN)
- [ ] Déploiement de poste + support à distance

## 👤 Contact

**Bilal B.** — Étudiant en Licence Informatique, à la recherche d'un poste de Technicien Support IT / Helpdesk.
📧 bilalbennejma@gmail.com
