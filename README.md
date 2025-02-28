# 📌 Projet PFE - Application de Merchandising

## 📝 Description
Cette application backend, développée avec Laravel, permet la gestion des produits, la synchronisation des stocks et la gestion des points de vente. Elle a été réalisée dans le cadre de mon stage chez INOVTEAM.

## 🚀 Fonctionnalités
- 🔹 **Gestion des produits** : ajout, modification, suppression  
- 🔹 **Gestion des stocks** : synchronisation en temps réel  
- 🔹 **Gestion des points de vente** : consultation et reporting  
- 🔹 **Authentification sécurisée**  

## 🛠 Technologies utilisées
- **Framework** : Laravel 10  
- **Langage** : PHP 8.2  
- **Base de données** : MySQL  
- **Autres** : API REST, JWT pour l'authentification  

## 📂 Installation
1. **Cloner le projet**  
   ```bash
   git clone https://github.com/aya-sahmi/Projet_PFE.git
   cd Projet_PFE
   ```

2. **Installer les dépendances**  
   ```bash
   composer install
   ```

3. **Configurer l’environnement**  
   ```bash
   cp .env.example .env
   php artisan key:generate
   ```

4. **Créer la base de données**  
   - Modifier le fichier `.env` avec les accès MySQL  
   - Lancer la migration :  
     ```bash
     php artisan migrate
     ```

5. **Lancer le serveur local**  
   ```bash
   php artisan serve
   ```

## 📜 Licence
Ce projet est privé et appartient à INOVTEAM.
