
---

```markdown
# Gestion des Praticiens et de leurs Spécialités

## 📌 Description du Projet
Ce projet est une application web développée avec **Laravel** permettant la gestion des praticiens et de leurs spécialités. Il inclut des fonctionnalités comme l'authentification, la recherche de praticiens, ainsi que l'ajout, la modification et la suppression des spécialités associées.

## 🚀 Fonctionnalités
- 🔐 **Authentification** : Connexion sécurisée avec validation des identifiants.  
- 🔍 **Recherche** : Trouver un praticien par son nom.  
- ➕ **Ajout** : Associer plusieurs spécialités à un praticien.  
- ✏️ **Modification** : Modifier les détails d'une spécialité existante.  
- ❌ **Suppression** : Supprimer une spécialité associée à un praticien.  
- 📋 **Listing** : Voir la liste des praticiens et leurs spécialités.  

## 🛠 Technologies Utilisées
- **Back-end** : PHP, Laravel  
- **Front-end** : HTML, CSS, Bootstrap  
- **Base de données** : MySQL  
- **Hébergement** : ISPConfig  
- **Outils** : GitHub, FileZilla, Balsamiq, PHPStorm  

## ⚡ Installation et Configuration
1. **Cloner le projet**  
   ```bash
   git clone https://github.com/mabrouka-triki/gsbepreuve.git
   cd gestion-praticiens
   ```

2. **Installer les dépendances**  
   ```bash
   composer install
   npm install
   ```

3. **Configurer l'environnement**  
   Copier `.env.example` en `.env` et modifier les informations de la base de données.

4. **Générer la clé d'application**  
   ```bash
   php artisan key:generate
   ```

5. **Migrer la base de données**  
   ```bash
   php artisan migrate --seed
   ```

6. **Démarrer le serveur**  
   ```bash
   php artisan serve
   ```

## 📄 Auteurs
- **Triki Mabrouka** - [GitHub](https://github.com/mabrouka-triki)  
```

---
