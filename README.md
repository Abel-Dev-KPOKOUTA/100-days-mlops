# 🚀 Planning MLOps - 100 Jours

## 📋 Vue d'ensemble

Ce planning vous mènera de débutant à compétent en MLOps en 100 jours. Chaque phase construit sur la précédente pour créer un portfolio solide.

---

## 🎯 Phase 1 : Fondations (Jours 1-20)

### **Semaine 1 : Setup & Git (Jours 1-7)**

**Jour 1** : Configuration environnement
- Installer Python, VS Code, Git
- Créer compte GitHub
- Setup de votre tracker MLOps ✅ (déjà fait!)

**Jour 2** : Git Basics
- `git init`, `git add`, `git commit`
- Créer votre premier repo : `100-days-mlops`
- Commit quotidien de votre progression

**Jour 3** : Git Branching
- `git branch`, `git checkout`, `git merge`
- Créer une feature branch
- Faire votre premier Pull Request

**Jour 4** : GitHub avancé
- README.md professionnel
- .gitignore pour Python
- GitHub Issues et Projects

**Jour 5** : Markdown & Documentation
- Syntaxe Markdown complète
- Documenter un projet
- Créer votre README de portfolio

**Jour 6** : Environnements virtuels Python
- `venv`, `virtualenv`, `conda`
- requirements.txt
- Bonnes pratiques d'isolation

**Jour 7** : Révision & Mini-projet
- Créer un repo avec structure complète
- Documentation + tests simples
- Premier article LinkedIn sur votre progression

---

### **Semaine 2 : Python pour ML (Jours 8-14)**

**Jour 8** : NumPy essentiels
- Arrays, indexing, slicing
- Opérations vectorielles
- Broadcasting

**Jour 9** : Pandas basics
- DataFrames, Series
- Lecture CSV, Excel
- Exploration de données

**Jour 10** : Pandas avancé
- Groupby, merge, join
- Pivoting et reshaping
- Gestion des données manquantes

**Jour 11** : Visualisation avec Matplotlib
- Plots de base
- Subplots et figures
- Personnalisation

**Jour 12** : Seaborn & visualisations avancées
- Statistical plots
- Heatmaps, pairplots
- Thèmes et styles

**Jour 13** : Scikit-learn introduction
- Train/test split
- Premier modèle (Régression linéaire)
- Métriques d'évaluation

**Jour 14** : Mini-projet EDA
- Dataset Kaggle simple (Titanic, House Prices)
- Analyse exploratoire complète
- Rapport en Jupyter Notebook

---

### **Semaine 3 : Docker & Conteneurisation (Jours 15-21)**

**Jour 15** : Docker basics
- Installation Docker
- `docker run`, `docker ps`, `docker stop`
- Images vs Containers

**Jour 16** : Dockerfile
- Créer votre premier Dockerfile
- `FROM`, `RUN`, `COPY`, `CMD`
- Build et tag d'images

**Jour 17** : Docker pour Python
- Image Python officielle
- Installer des dépendances
- Conteneuriser un script Python

**Jour 18** : Docker Compose
- YAML basics
- Services multiples
- Volumes et networks

**Jour 19** : Docker best practices
- Multi-stage builds
- .dockerignore
- Optimisation de taille d'image

**Jour 20** : Projet Docker
- API Flask simple conteneurisée
- Docker Compose avec DB
- Documentation complète

---

## 🔧 Phase 2 : MLOps Tools (Jours 21-50)

### **Semaine 4 : MLflow (Jours 21-27)**

**Jour 21** : MLflow introduction
- Installation et setup
- Interface UI
- Concepts : experiments, runs, artifacts

**Jour 22** : MLflow Tracking
- `mlflow.log_param()`
- `mlflow.log_metric()`
- `mlflow.log_artifact()`

**Jour 23** : Logging de modèles
- `mlflow.sklearn.log_model()`
- Sauvegarder et charger modèles
- Model registry

**Jour 24** : Comparaison d'expériences
- Multiple runs
- Comparer hyperparamètres
- Visualiser résultats

**Jour 25** : MLflow Projects
- MLproject file
- Reproductibilité
- Paramètres d'entrée

**Jour 26** : MLflow Models
- Model signature
- Model serving
- Déploiement local

**Jour 27** : Projet MLflow
- Pipeline complet tracké
- Multiple expériences
- Best model selection

---

### **Semaine 5 : Versioning des données (Jours 28-34)**

**Jour 28** : DVC (Data Version Control)
- Installation et init
- `dvc add`, `dvc push`, `dvc pull`
- Remote storage (local)

**Jour 29** : DVC pipelines
- `dvc.yaml`
- Stages et dépendances
- `dvc repro`

**Jour 30** : DVC avec cloud
- Setup S3/GCS
- Remote storage cloud
- Collaboration

**Jour 31** : DVC Metrics & Plots
- Tracking de métriques
- Graphiques de performance
- Comparaison de versions

**Jour 32** : Git + DVC workflow
- Branching avec données
- Merge de datasets
- Bonnes pratiques

**Jour 33** : Great Expectations
- Data validation
- Expectations suites
- Data quality checks

**Jour 34** : Projet Data Pipeline
- Pipeline avec DVC
- Validation avec Great Expectations
- Documentation complète

---

### **Semaine 6-7 : APIs & Déploiement (Jours 35-48)**

**Jour 35** : FastAPI basics
- Première API
- Routes et endpoints
- Query parameters

**Jour 36** : FastAPI avancé
- Request body (Pydantic)
- Response models
- Status codes

**Jour 37** : Déployer un modèle ML avec FastAPI
- Load model
- Prediction endpoint
- Error handling

**Jour 38** : Testing d'APIs
- Pytest pour FastAPI
- TestClient
- Tests unitaires et intégration

**Jour 39** : Documentation API
- Swagger UI automatique
- OpenAPI specs
- Exemples de requêtes

**Jour 40** : Docker + FastAPI
- Conteneuriser l'API
- Multi-stage build
- Healthcheck

**Jour 41** : Base de données avec API
- SQLAlchemy
- CRUD operations
- Async database

**Jour 42** : Authentication & Security
- OAuth2
- JWT tokens
- API keys

**Jour 43** : Monitoring de l'API
- Logging
- Prometheus metrics
- Health endpoints

**Jour 44** : Flask alternative
- Comparaison Flask vs FastAPI
- Simple ML API en Flask
- Choix du framework

**Jour 45** : Streamlit pour ML
- Interface utilisateur
- Dashboard interactif
- Visualisations

**Jour 46** : Gradio
- Interface ML rapide
- Démo de modèle
- Partage facile

**Jour 47** : Cloud basics (Heroku)
- Déployer FastAPI sur Heroku
- Environment variables
- Logs et debugging

**Jour 48** : Projet API complète
- API ML production-ready
- Tests complets
- Documentation + déploiement

---

## ☁️ Phase 3 : Cloud & Production (Jours 49-70)

### **Semaine 8 : AWS Basics (Jours 49-55)**

**Jour 49** : AWS introduction
- Compte AWS
- IAM users et roles
- Console vs CLI

**Jour 50** : EC2
- Lancer une instance
- SSH connection
- Déployer une app

**Jour 51** : S3
- Buckets et objects
- Permissions
- Versioning

**Jour 52** : AWS Lambda
- Serverless functions
- Triggers
- Lambda pour ML inference

**Jour 53** : API Gateway
- REST API
- Lambda integration
- Deploy API

**Jour 54** : SageMaker introduction
- Notebooks
- Training jobs
- Endpoints

**Jour 55** : Mini-projet AWS
- Pipeline complet sur AWS
- S3 → Lambda → API Gateway

---

### **Semaine 9 : Kubernetes basics (Jours 56-62)**

**Jour 56** : Kubernetes concepts
- Pods, Services, Deployments
- Architecture K8s
- Minikube installation

**Jour 57** : Premier déploiement K8s
- YAML manifests
- kubectl basics
- Deploy une app

**Jour 58** : Services et networking
- ClusterIP, NodePort, LoadBalancer
- Ingress
- DNS

**Jour 59** : ConfigMaps et Secrets
- Configuration externe
- Variables d'environnement
- Sensitive data

**Jour 60** : Persistent storage
- PersistentVolumes
- PersistentVolumeClaims
- StatefulSets

**Jour 61** : Helm
- Charts
- Templating
- Package management

**Jour 62** : Projet K8s
- Déployer API ML sur K8s
- Scaling
- Rolling updates

---

### **Semaine 10 : CI/CD (Jours 63-70)**

**Jour 63** : GitHub Actions basics
- Workflows
- Triggers (push, PR)
- Actions marketplace

**Jour 64** : CI pour Python
- Linting (flake8, black)
- Tests automatiques
- Coverage

**Jour 65** : CD avec GitHub Actions
- Build Docker image
- Push to registry
- Deploy

**Jour 66** : Testing avancé
- Unit tests
- Integration tests
- End-to-end tests

**Jour 67** : Pre-commit hooks
- Setup pre-commit
- Formatters automatiques
- Quality gates

**Jour 68** : GitLab CI alternative
- .gitlab-ci.yml
- Pipelines
- Runners

**Jour 69** : Jenkins introduction
- Pipeline as code
- Jenkinsfile
- Plugins

**Jour 70** : Projet CI/CD complet
- Pipeline bout en bout
- Tests + Build + Deploy
- Monitoring du pipeline

---

## 🎓 Phase 4 : Advanced MLOps (Jours 71-90)

### **Semaine 11 : Monitoring & Observability (Jours 71-77)**

**Jour 71** : Prometheus
- Metrics collection
- PromQL
- Alerting

**Jour 72** : Grafana
- Dashboards
- Visualisations
- Alerting

**Jour 73** : Model monitoring
- Data drift detection
- Prediction monitoring
- Performance metrics

**Jour 74** : Logging avec ELK
- Elasticsearch
- Logstash
- Kibana

**Jour 75** : Tracing distribué
- Jaeger
- OpenTelemetry
- Debugging microservices

**Jour 76** : Alerting strategies
- Alert fatigue
- SLOs/SLIs
- Runbooks

**Jour 77** : Projet monitoring
- Dashboard complet
- Alertes configurées
- Incident response

---

### **Semaine 12 : Feature Stores & Advanced (Jours 78-84)**

**Jour 78** : Feature Store concept
- Pourquoi feature stores?
- Feast introduction
- Setup local

**Jour 79** : Feast features
- Feature definitions
- Online vs Offline store
- Feature serving

**Jour 80** : Model serving patterns
- Batch vs Real-time
- A/B testing
- Canary deployments

**Jour 81** : Kubeflow introduction
- Pipelines
- Components
- Orchestration

**Jour 82** : Airflow pour ML
- DAGs
- Operators
- Scheduling

**Jour 83** : Model retraining strategies
- Trigger-based
- Scheduled
- Performance-based

**Jour 84** : Projet orchestration
- Pipeline complet automatisé
- Retraining automatique
- Monitoring intégré

---

### **Semaine 13 : Sécurité & Gouvernance (Jours 85-90)**

**Jour 85** : ML Security basics
- Model poisoning
- Adversarial attacks
- Defense strategies

**Jour 86** : Data privacy
- GDPR compliance
- PII handling
- Anonymization

**Jour 87** : Model explainability
- SHAP
- LIME
- Interpretability

**Jour 88** : Model governance
- Model cards
- Audit trails
- Compliance

**Jour 89** : Cost optimization
- Cloud cost monitoring
- Resource optimization
- Budget alerts

**Jour 90** : Révision Phase 4
- Consolidation
- Documentation
- Portfolio update

---

## 🏆 Phase 5 : Projet Final (Jours 91-100)

### **Jours 91-95 : Conception**
- Choisir un use case réel
- Architecture design
- Tech stack selection
- Planning détaillé

### **Jours 96-98 : Développement**
- Implémentation
- Tests
- Documentation

### **Jour 99 : Déploiement**
- Production deployment
- Monitoring setup
- Final testing

### **Jour 100 : Présentation**
- Article de blog détaillé
- Vidéo démo
- Portfolio update
- LinkedIn post
- Célébration! 🎉

---

## 📚 Ressources quotidiennes recommandées

### **Documentation officielle**
- MLflow docs
- Docker docs
- Kubernetes docs
- FastAPI docs

### **Livres**
- "Designing Machine Learning Systems" - Chip Huyen
- "Building Machine Learning Pipelines" - O'Reilly
- "Introducing MLOps" - O'Reilly

### **Cours en ligne**
- Made With ML (gratuit)
- Full Stack Deep Learning
- MLOps Zoomcamp (DataTalks.Club)

### **Chaînes YouTube**
- ArjanCodes
- Patrick Loeber
- Yannic Kilcher (pour theory)

### **Communautés**
- MLOps Community Slack
- r/mlops
- LinkedIn groups

---

## 🎯 Objectifs de fin de parcours

À la fin des 100 jours, vous aurez :

✅ **Portfolio GitHub** avec 15+ projets
✅ **Blog** avec 10+ articles techniques
✅ **Présence LinkedIn** active
✅ **Compétences certifiables** en MLOps
✅ **Projet de fin** déployé en production
✅ **Réseau** dans la communauté MLOps

---

## 💡 Conseils pour réussir

1. **Consistance > Intensité** : 1-2h par jour, tous les jours
2. **Documenter tout** : Blog, GitHub, LinkedIn
3. **Construire en public** : Partagez votre progression
4. **Poser des questions** : Communautés, forums
5. **Faire des projets** : Theory + Practice
6. **Réviser régulièrement** : Spaced repetition
7. **Networking** : Connecter avec d'autres apprenants
8. **Ne pas être perfectionniste** : Done > Perfect

---

## 📊 Métriques de succès

- [ ] 100 commits GitHub consécutifs
- [ ] 10 projets publics sur GitHub
- [ ] 5 articles de blog techniques
- [ ] 1 projet end-to-end déployé
- [ ] 500+ connections LinkedIn
- [ ] Contribué à 1 projet open source

---

**Prêt à commencer ce voyage ? Votre Jour 1 est déjà fait avec ce tracker ! 🚀**

*N'oubliez pas : Le voyage est aussi important que la destination. Profitez de chaque jour d'apprentissage !*