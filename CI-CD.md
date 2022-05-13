# TP ORGA SCRUM MASTER

## CI - CD

### Schéma
Un schéma technique expliquant comment l’intégration continue fonctionne (Outils,
Cloud, Docker, Kubernetes). Notre CI - CD sera lancé automatiquement avec l'outil Github Actions.

![Alt text](images/IC.png?raw=true "Title")

### Deploy
- Le deploiement sera réalisé sur un cluster Kubernetes GCP (Google Cloud Platform) qui contient des images Docker. Une sauvegarde des images sera aussi réalisé sur un Jfrog.

### Operate
- Nous utiliserons un Jira pour suivre plus facilement les tâches.

### Monitor
- Pour le monitoring, nous utiliserons Datadog avec des alerteurs pour un suivi de la production 24h/24.

### Plan
- L'outils Slack sera utiliser pour communiquer avec les équipes.

### Code
- Pour le code, nous utiliserons Github pour le versionning et la facilité de mise en relation du code.

### Build
- La construction des applications sera réalisé avec Docker pour récupérer les images.

### Test
- Les tests seront réalisés avec un des outils comme mocha, sinon, cerberus.