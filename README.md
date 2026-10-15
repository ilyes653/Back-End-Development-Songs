---

### 2. `README.md` pour le dépôt **`Back-End-Development-Songs`**

```markdown
# 🎵 Back-End Development - Songs Service

## 📋 Description
Ce service backend, construit avec **Flask** et connecté à une base de données **MongoDB** (via PyMongo), gère le catalogue des chansons, les endpoints de santé (`/health`), ainsi que les requêtes de mise à jour et de suppression.

---

## 🛠️ Stack Technique
* **Framework :** Flask
* **Base de données :** MongoDB / PyMongo
* **Outils de test :** cURL, Postman

---

## ⚙️ Utilisation (cURL)
* Vérifier l'état de santé du service :
  ```bash
  curl -i http://localhost:5000/health
