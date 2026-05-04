# 🎊 Invitation Mariage - Rosin & Concilia

Système complet d'invitation électronique avec gestion des invités, QR codes, et dashboard administrateur.

## 📋 Fonctionnalités

### Côté invités (`index.html`)
- 🔐 **Accès sécurisé** avec code unique personnel
- 📝 **Formulaire RSVP** complet
- 🍹 **Sélection des boissons**
- 🎫 **Génération de QR code personnalisé**
- 📱 **Téléchargement du pass d'entrée**

### Côté administrateur (`admin.html`)
- 📊 **Dashboard avec statistiques** (graphiques)
- 👥 **Gestion complète des invités**
- 🔍 **Filtres** (statut, table, recherche)
- 📷 **Scan de QR code** avec caméra
- 📎 **Export CSV** des données
- 🔑 **Génération automatique des codes**

### Utilitaire (`generate-codes.html`)
- ⚡ **Génération en masse** des codes uniques
- 📤 **Export des codes** générés

## 🚀 Installation

### 1. Prérequis
- Compte Firebase (gratuit)
- Compte GitHub (pour GitHub Pages)

### 2. Configuration Firebase

```bash
# Créer un projet Firebase
1. Aller sur https://console.firebase.google.com
2. Créer un nouveau projet "invitation-mariage"
3. Activer Firestore Database (mode test puis production)
4. Activer Authentication (Email/Password)
