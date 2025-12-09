# 📡 SAÉ 5.01 - Concevoir, réaliser et présenter une solution technique

> **Infrastructure réseau complète** - Déploiement multi-sites (HQ, Remote, Internet)  
> IUT de Belfort-Montbéliard | Décembre 2025 | Groupe 7

---

## 🎯 Objectif du projet

Concevoir, déployer et présenter une **infrastructure réseau d'entreprise complète** comprenant :
- 3 sites interconnectés (HQ Lyon, Remote WSFR, Internet WorldSkills)
- Services systèmes (Active Directory, DNS, DHCP, Web, Mail)
- Sécurité avancée (PKI, Firewall, VPN)
- Automatisation (Ansible, playbooks Cisco)

**Durée :** 6 jours (08/12 - 17/12/2025)  
**Équipe :** 4 étudiants (1 Pilote Projet, 3 Cyber)

---

## 📋 Architecture

### Sites déployés
| Site | Rôle | Connexion |
|------|------|-----------||
| **HQ** | Siège social (Lyon) | WAN privé + Internet |
| **Remote** | Site distant (WSFR) | Liaison MAN OSPF |
| **Internet** | Zone publique | BGP |

### Services déployés
- 🔐 **Sécurité** : PKI (Root CA + Sub CA), Firewall nftables, OpenVPN
- 🌐 **Réseau** : VLANs, HSRP/VRRP, OSPF, BGP, NAT
- 💻 **Système** : Active Directory, DNS/DNSSEC, DHCP Failover
- 📧 **Applicatif** : Web HA (Docker), Mail (SMTP/IMAP), Partages DFS
- ⚙️ **Automatisation** : Ansible (backup config, NTP, monitoring)


---


## 📊 Gestion de projet

**Méthodologie :** Agile / Scrum
- **Daily Scrum** : 1x/jour (matin + soir)
- **Outil de suivi** : Trello + Gantt TeamGantt
- **Dashboard** : Github

**Responsabilités :**
- 🎯 **Pilote Projet** : Planning, coordination, jalons
- 🔒 **Cyber x3** : PKI, Firewall, VPN, Hardening


---

## 📸 Captures d'écran

### Plan d'adressage IP
![Plan IP](plan_adressage_DNS_Groupe7.jpg)

---


## 👥 Contributeurs

**Groupe 7 - IUT Belfort-Montbéliard**
- Hugo Coston ([@hugo0490](https://github.com/hugo0490)) - Pilote Projet
- Étudiant 2 - Cybersécurité
- Étudiant 3 - Cybersécurité
- Étudiant 4 - Cybersécurité

---

## 📜 Licence

Ce projet est réalisé dans le cadre de la **SAÉ 5.01** à l'IUT de Belfort-Montbéliard.  
© 2025 - Tous droits réservés.
