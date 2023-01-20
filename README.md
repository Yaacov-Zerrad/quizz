# quizz
a quizz app


## NE PAS NOMMER LES FICHIER AVEC DE MAJUSCULE NI LES FONCTIONS NI LES VARIABLES

#### ne pas oublier quant tu fini de travailler cmd aussi non tu perd ton travail
```
git add .
```
```
git commit -m "le travaille que tu as avancer :)"
```
```
git push
```
### Les technologie
BACK-END:
- python avec le framework flask
- API de QUIZZ: 
    [jservice](https://jservice.io/).
- API de traduction:
    [apertium]( https://github.com/apertium/apertium-python).

FRONT-END:
- html
- css (avec [bootstrap](https://getbootstrap.com/))
- js (appel API avec fetch)

### 1. Demarrer une appli flask
On va commencer avec flask de python c'est un framework facile mais peut etre apres on changera parce qu'il
il faut dabors faire la logique de l'appli et apres on peut l'implemente ou on voudra

Pour cree une app flask suis les instruction de ce [lien](https://www.digitalocean.com/community/tutorials/how-to-make-a-web-application-using-flask-in-python-3) jusqu'a l'etape 4 qui est sur la base de donnee car pour l'intant on en fais pas.

Il y aura une erreur quand tu ferra flask run il faut que tu met ces commande dans le terminal (car il sont pas a jour les leur , c'est possible qu'il y a des autres bug)

    # le nom  du fichier que tu as fais
    export FLASK_APP=app.py 
    # pour debuge
    export FLASK_DEBUG=1 
    # pour ne pas avoir a recharger la page quand il on fait des changement
    export TEMPLATES_AUTO_RELOAD=1 
    # for run
    flask run

Quant tu arrive au html tu peux suivre les instructions du css,  le plus important c'est d'apprendre a afficher ta page html avec les **block de contenue** et boostrap, (il met un lien de bootsrap c'est super pour le css)..

### 2. Cree une api de traduction
- Dans un nouveau ficher qui s'appel translate.py
 **les variables doivent etre aficher dans le terminal par un print()**
- Pour faire runer le fichier tu fais 
``` 
python translate.py 
```
- **On implementera dans l'appli apres**
### 3. cree api de question
- [Apprendre request](https://www.digitalocean.com/community/tutorials/how-to-get-started-with-the-requests-library-in-python-fr)
- dans un nouveau ficher qui s'appel quizz.py
 **les variables doivent etre aficher dans le terminal par un print()**
- Pour faire runer le fichier tu fais 
``` 
python quizz.py 
```
- **On implementera dans l'appli apres**
### 4. mixer les api 
- Mettre en fonction des fichiers quizz et translate 
- Il faudra les mettre en pack grace a un fichier ```__init__.py``` vide
-Importer les fonctions puis les utiliser
# FRONT-END
### 1. Afficher la question
- Grace au variable de flask comme apprie dans le debut
- Il faut utiliser bootsrap 
### 2. Faire un formulaire de reponse
- Utiliser bootsrap  (il y a un onglet form tu a juste a copier et arranger le code)
