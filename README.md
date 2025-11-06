# WorkflowBase – Apprentissage GitHub Actions (CI/CD)

Ce dépôt a pour objectif de maîtriser les bases et les fonctionnalités avancées de GitHub
Actions à travers une série d’exercices pratiques simulant des cas réels de 
CI/CD (Intégration Continue / Déploiement Continu).

---

## Pourquoi ce projet

Ce projet a été créé dans le cadre de mon apprentissage du DevOps et des outils d’automatisation.  
L’objectif est de comprendre comment mettre en place des workflows capables d’exécuter
des tâches répétitives automatiquement : tests, déploiements, gestion de dépendances, notifications, etc.  

Il s’agit d’une base expérimentale, où chaque fichier YAML représente une étape clé dans la mise en œuvre de processus CI/CD.  
À terme, ce projet me permet de développer une vision complète de l’automatisation dans le cycle de vie d’un logiciel.

---

## Objectif du projet

Mettre en pratique les concepts clés de GitHub Actions :
- Création de workflows automatisés
- Gestion des déclencheurs (push, pull request, cron, etc.)
- Utilisation de variables d’environnement et de secrets
- Téléchargement d’artéfacts
- Tests unitaires et intégration continue
- Déploiement sur GitHub Pages ou Docker Hub
- Notifications et pipelines multi-plateformes

Ce projet me permet d’acquérir des compétences solides pour automatiser les processus 
de développement et intégrer un pipeline CI/CD complet dans différents contextes (Node.js, Docker, Flutter, etc.).

---
Chaque fichier `.yml` correspond à un exercice ou un cas pratique spécifique.  
Les exercices sont progressifs, du plus simple au plus avancé.

---

## Exercices réalisés

### Exercice 1 – Workflow de base
- Création d’un workflow simple affichant "Hello World" dans les logs.

### Exercice 2 – Déclencheur sur Push et Pull Request
- Déclenchement automatique sur `push` et `pull_request`.
- Vérification du code via `npm install` et `npm run lint`.

### Exercice 3 – Variables d’environnement
- Définition et affichage d’une variable `MESSAGE="Déploiement réussi"`.

### Exercice 4 – Secrets GitHub
- Utilisation d’un secret `API_KEY` pour simuler un accès sécurisé à une API.

### Exercice 5 – Téléchargement d’artéfacts
- Génération et sauvegarde d’un fichier `report.txt` comme artéfact de build.

### Exercice 6 – Jobs dépendants
- Création d’un job `build` suivi d’un job `test` dépendant du premier.

### Exercice 7 – Tests unitaires Node.js
- Installation de Node.js et exécution des tests automatisés.

### Exercice 8 – Cron Job
- Exécution automatique d’un workflow chaque jour à 8h.

### Exercice 9 – Déploiement GitHub Pages
- Déploiement automatique d’un site statique depuis la branche `main`.

### Exercice 10 – Docker Build & Push
- Construction et publication d’une image Docker sur Docker Hub via secrets.

### Exercice 11 – Badge de statut
- Ajout d’un badge reflétant l’état du workflow dans le README.

### Exercice 12 – Pipeline Flutter
- Installation, tests et génération d’un APK pour une app Flutter.

### Exercice 13 – Tests multi-OS
- Exécution d’un workflow sur Ubuntu, macOS et Windows via matrices.

### Exercice 14 – Notifications
- Configuration d’alertes Slack/Email en cas d’échec d’un workflow.

### Exercice 15 – Intégration PostgreSQL
- Utilisation d’un service PostgreSQL pour tester des connexions et requêtes.
## Compétences mises en avant

| Domaine | Compétences clés |
|----------|------------------|
| CI/CD | Création de workflows, tests automatisés, pipelines multi-étapes |
| GitHub Actions | Déclencheurs, secrets, artefacts, matrices |
| DevOps | Automatisation, intégration continue, déploiement |
| Docker | Construction et push d’images |
| Monitoring | Badges de statut, notifications en cas d’erreur |

---

## À propos

Abdoulaye Traoré  
Étudiant en Développement Web à MyDigitalSchool Paris  
Passionné par le développement full-stack et les processus DevOps.  
[Profil GitHub](https://github.com/abdoultra
