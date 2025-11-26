# TP 13 : Automatisation et Déploiement Spring Boot avec Bash

---

### Réalisé par

**Abla MARGHOUB**

### Encadré par

**Pr. Mohamed LACHGAR**

### Module

**Techniques de Programmation Avancée**

### Établissement

**École Normale Supérieure - Université Cadi Ayyad**



## 1. Objectif du TP

* Créer et configurer un projet Spring Boot.
* Gérer la structure d’un projet Java moderne.
* Automatiser le démarrage, l’arrêt et le déploiement via des scripts Bash.
* Lire et analyser les logs de l’application.

---

## 2. Architecture du TP

### 2.1 Stack technologique

| Technologie         | Rôle dans le projet                            |
| ------------------- | ---------------------------------------------- |
| **Java 21**         | Langage de programmation                       |
| **Spring Boot**     | Framework pour créer l’application Web         |
| **Spring Data JPA** | Gestion des interactions avec la base H2       |
| **H2 Database**     | Base de données en mémoire                     |
| **Lombok**          | Génération automatique de code boilerplate     |
| **Maven**           | Gestion du build et des dépendances            |
| **Bash**            | Scripts pour automatiser démarrage, stop, logs |

---

### 2.2 Structure du projet

<img width="439" height="874" alt="image" src="https://github.com/user-attachments/assets/bc3a90ff-f76e-48dd-9a6e-d7c05cb84b52" />

* **src/** : Contient le code Java et les ressources de l’application.
* **scripts/** : Contient les scripts Bash pour gérer l’application.
* **pom.xml** : Fichier Maven pour gérer les dépendances et le build.

---

## 3. Résultat attendu

<img width="719" height="434" alt="image" src="https://github.com/user-attachments/assets/86bd45d4-c74b-444c-8b11-a794a835a149" />

### 3.6 Aperçu des scripts

| Script    | Fonction                               |
| --------- | -------------------------------------- |
| run.sh    | Démarre l’application en arrière-plan  |
| stop.sh   | Arrête l’application en cours          |
| logs.sh   | Affiche les dernières lignes des logs  |
| deploy.sh | Compile et déploie la nouvelle version |

