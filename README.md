# 🏡 Kanap — Site e-commerce de canapés (Frontend)

## 🎯 Ma mission

Construire un site e-commerce en **JavaScript** pour la marque **Kanap**, permettant de vendre ses produits en ligne.  
Mon rôle consiste à **intégrer dynamiquement les maquettes du site** via JavaScript, en récupérant les produits et leurs détails depuis une **API**, et à gérer le **panier client**.

---

## 🧰 Technologies utilisées

### 🔹 Framework / Librairies

* **JavaScript** 
* **HTML5 / CSS3**

### 🔹 Outils

* **Git / GitHub**
* **npm**
* **API REST**

---

## 💡 Le projet

Kanap est une marque de canapés vendant exclusivement ses produits en boutique.  
L’objectif est de créer une plateforme e-commerce qui permette :

* la consultation des produits,
* la gestion d’un panier,
* le passage de commandes en ligne.

Le front-end est connecté à une **API** développée par l’équipe back-end, permettant de récupérer les informations produits et gérer les commandes.

---

## 📄 Fonctionnalités principales

### 🏠 Page d’accueil

* Affichage dynamique de tous les produits depuis l’API.
* Liste de produits sous forme de cartes cliquables avec image, nom et prix.

### 📄 Page produit

* Affichage détaillé du produit : image, description, prix, options disponibles.
* Intégration dynamique des données via les **id** et balises HTML prévues par le front-end.

### 🛒 Page panier

* Gestion des articles ajoutés au panier via **local storage**.
* Modification des quantités et suppression d’articles.
* Calcul dynamique du total de la commande.

### ✅ Page confirmation

* Envoi des informations de commande au serveur.
* Affichage du **numéro de commande** récupéré via `URLSearchParams`.

### 🚫 Page 404

* Affichée pour toute route non définie.

---

## ⚙️ Cahier des charges technique

* Intégration des produits via **API REST**.
* Gestion du **panier** avec **local storage**.
* Validation des informations utilisateur (quantité et champs) via **Regex**.
* Application **responsive** (mobile → desktop).
* Code clair, commenté et organisé pour faciliter la maintenance.
* Utilisation des **id** HTML fournis pour injecter dynamiquement les données.

---

## ⚙️ Installation du projet

### 1️⃣ Cloner le dépôt

```bash
git clone https://github.com/Eliaslvr/kanap.git
cd kanap
```

```bash
cd service
npm install
npm start
```