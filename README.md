# Test FastAPI Application

Une application FastAPI simple avec support des templates et fichiers statiques.

## Installation

1. Cloner le repository :

```bash
git clone <votre-url-github>
cd <nom-du-dossier>
```

2. Créer un environnement virtuel et l'activer :

```bash
python -m venv venv
source venv/bin/activate  # Pour Linux/Mac
# ou
venv\Scripts\activate  # Pour Windows
```

3. Installer les dépendances :

```bash
pip install -r requirements.txt
```

## Lancement de l'application

Pour lancer l'application, exécutez :

```bash
python main.py
```

L'application sera accessible à l'adresse : http://localhost:8000

## Structure du projet

```
.
├── main.py
├── requirements.txt
├── static/
│   ├── css/
│   │   └── style.css
│   └── js/
│       └── main.js
└── templates/
    └── index.html
```
