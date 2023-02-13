# AnimeSynopsis

Projet d'initiation au nlp.

## Problématique :

Créer un programme de reconnaissance de synopsis. Savoir si ce dernier est celui d'un anime ou d'un film. 

Les data sont issues de kaggle grâce à ces datasets :</br>
https://www.kaggle.com/code/hernan4444/get-synopsis-from-anime-html-files/data?select=anime_with_synopsis.csv
https://www.kaggle.com/datasets/linggarmaretva/movie-synopsis-dataset

Lien vers le huggingface du projet :</br>
https://huggingface.co/spaces/theopg1/animeSynopsis

## Contenu :
Le projet contient: 
- le dossier Data possédants les fichers csv et xlsx pour l'entrainement et la validation
- le fichier model.ipynb qui permet de créer et entrainer l'ia pour crée le fichier model.pkl
- le fichier app.ipynb qui nous permet grâce à gradio d'avoir une interface visuel pour utiliser notre ia en local ou sur des sites comme huggingface par ex
- le fichier app.py qui est une version .py de notre jupyter généré automatiquement grâce à ce dernier pour garder l'essentiel
- un fichier requirements.txt pour les librairies

```bash
AnimeSynopsis 
├── data
│   ├── anime_synopsis.csv
│   ├── movie_synopsis.xlsx
│   ├── synopsis.csv
│   └── synopsis.xlsx
├── app.ipynb
├── app.py
├── model.ipynb
└── requirements.txt
```
