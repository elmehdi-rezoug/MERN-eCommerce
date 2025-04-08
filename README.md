# 🚗 Gestion de location de voitures

Une application web développée avec **MongoDB, Express, React, Node** pour gérer une boutique de PC à vendre. Elle permet aux utilisateurs d’ajouter, modifier, supprimer et consulter leurs commandes. L’interface est claire et moderne.

---

## 🛠️ Technologies utilisées

- **Express**
- **JavaScript**
- **MongoDB**
- **Docker / Docker Compose**

---

## ⚙️ Instructions de build et d’exécution locale

```bash
# Cloner le dépôt
git clone https://github.com/elmehdi-rezoug/MERN-eCommerce.git
cd MERN-eCommerce

# Installer les dépendances du backend
npm install
npm start

# Accéder au frontend
cd frontend

# Installer les dépendances du frontend
npm install
npm start
```

Accéder à l’application sur : [http://localhost:3000](http://localhost:3000)

---

## 🐳 Lien vers l’image Docker

> Vous pouvez publier l’image avec :

```bash
docker login
docker build -t elmehdir/mern-backend:latest -f Dockerfile .
docker build -t elmehdir/mern-frontend:latest -f Dockerfile.frontend .
docker push elmehdir/mern-backend:latest
docker push elmehdir/mern-frontend:latest
```

---

## 🧰 Commandes utiles

### Pour lancer l'application

Il suffit de placer le fichier `docker-compose.yml` dans un dossier et d’exécuter la commande suivante :

```bash
docker compose up -d
```

Cette commande effectuera le pulling des images depuis Docker Hub et exécutera les services, car le fichier contient la configuration nécessaire à l’exécution.

---

## 👨‍💻 Auteur

- **Marwane Mallouk**  
📧 elmehdirezoug100@gmail.com  
[GitHub](https://github.com/elmehdi-rezoug)

---
