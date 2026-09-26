# Montageur vidéo simple

Ce projet est un petit logiciel Python pour :
- importer des vidéos et images,
- les assembler dans un ordre choisi,
- ajouter un titre au début,
- optionnellement ajouter une musique de fond,
- exporter le résultat en fichier MP4.

## Fonctionnalités

- Sélection de plusieurs fichiers vidéo/images
- Assemblage séquentiel
- Ajout d’un titre texte
- Sélection d’une piste audio
- Sortie en MP4
- Interface graphique simple avec Tkinter

## Prérequis

- Python 3.10+
- FFmpeg installé et disponible dans le PATH

## Installation

```bash
python -m venv .venv
source .venv/bin/activate  # Windows: .venv\Scripts\activate
pip install -r requirements.txt
```

## Lancer l’application

```bash
python app.py
```

## Exemple d’utilisation

1. Clique sur “Ajouter des médias”
2. Choisis tes vidéos/images
3. Choisis le titre et la musique (optionnel)
4. Choisis le dossier de sortie
5. Clique sur “Créer la vidéo”

## Remarques

- Les fichiers image sont convertis en clips de 3 secondes par défaut.
- Le résultat est exporté en MP4.
- Si tu as des fichiers très lourds, le rendu peut prendre quelques minutes selon ta machine.
