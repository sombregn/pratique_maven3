# 🚀 SpringBoot: Module Maven 3

Ce projet vise a mettre en place un module module maven.Comme suit.
3. Modules maven avec gestion des plugins
Créer un projet maven nomée commandes : projet parent
le projet parent est juste un projet maven
Créer les modules maven suivants : services, web
services sera un projet gere le metier de l'application
web est une application angular

---

## 📋 Table des matières
- [Objectif](#-objectif)
- [Prérequis](#-prérequis)
- [Installation](#-installation)
- [Lancement du projet](#-lancement-du-projet)
- [Captures d'écran](#-captures-décran)

---

## 🎯 Objectif
L'objectif de ce projet est de créer un module maven avec Springboot et aussi une App Angualr comme module integre.

---

## 📦 Prérequis
Avant de commencer, assurez-vous d'avoir les éléments suivants installés sur votre machine :

- **Java 17** ou version supérieure 
- **Maven** pour la gestion des dépendances
- **Angular CLI: 18.1.2**
- **Node: 20.18.0**
- **Package Manager: npm 10.8.2**

---

## 🛠 Installation

### 1. Cloner le projet
Commencez par cloner le dépôt GitHub sur votre machine locale :
- **git clone https://github.com/sombregn/pratique_maven3.git**

### 2. Accéder au répertoire du projet
Accédez au répertoire du projet cloné :
- **cd pratique_maven3**

🚀 Lancement du projet
### 1. Build de l'application
Compilez et construisez l'application avec Maven :
- **mvn clean install**

### 2. Lancer l'application
Démarrez l'application Spring Boot :
Rdv dans les modules 
- **cd services**
- **mvn spring-boot:run**
- **Démarrez l'App Angular**
- **cd web**
- **npm i**
- **ng serve**
- **Vous pouvez également lancer l'application directement depuis votre IDE en appuyant sur le bouton Run.**

### 🌐 URLs d'accès sur Navigateur
Une fois l'application lancée, vous pouvez accéder aux services via les URLs suivantes :
- **Application: http://localhost:4200**

### 📸 Captures d'écran
Pour visualiser des captures d'écran de l'application et résultats, consultez le dossier captures dans le projet.

### 📝 Remarque
Assurez-vous que maven et Java est bien installé et configurée.
