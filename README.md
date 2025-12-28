# 🌍 ESG Pulse | Carbon Tracking SaaS

![Status](https://img.shields.io/badge/Status-Production-green) ![Tech](https://img.shields.io/badge/Stack-Supabase_Vercel-blue)

**ESG Pulse** est une plateforme SaaS "Serverless" dédiée au pilotage et à l'audit des émissions carbone (Scopes 1, 2 & 3). Conçue pour répondre aux exigences de traçabilité de la CSRD.

## 🚀 Fonctionnalités Clés

* **⚡ Ingestion Temps Réel :** Saisie sécurisée des consommations via interface web responsive.
* **🔒 Intégrité des Données :** Calcul automatique des tCO2e via *Stored Generated Columns* (PostgreSQL) pour éviter toute manipulation humaine.
* **🔮 Oracle Prédictif :** Algorithme de projection linéaire pour anticiper le dépassement des quotas annuels.
* **📊 Data Visualization :** Tableau de bord exécutif avec répartition dynamique (Chart.js).
* **📂 Audit Ready :** Export CSV instantané pour interopérabilité avec Excel/ERP.

## 🛠 Architecture Technique

Ce projet démontre une approche **Cloud-Native** moderne :

1.  **Frontend :** HTML5 / JavaScript (Vanilla) / Chart.js
2.  **Backend / Database :** Supabase (PostgreSQL + Row Level Security)
3.  **Hébergement / CI-CD :** Vercel (Déploiement continu depuis GitHub)
4.  **Sécurité :** Gestion des accès via API Keys et Policies RLS.

## 📈 Cas d'usage

Développé pour démontrer la faisabilité d'outils agiles dans le contexte de la transition énergétique :
* Suivi multi-sites décentralisé.
* Pilotage "Flash" pour Comex.
* Alternative aux fichiers Excel macro-dépendants (Shadow IT).

---
*Projet développé par Yannick Hochmann - Expert Climat & IT Architect.*
