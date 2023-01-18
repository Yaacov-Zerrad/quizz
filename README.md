# quizz
a quizz app

ne pas oublier quant tu fini de travailler cmd
```
git add .
```
```
git commit -m "le travaille que tu as avancer :)"
```
```
git push
```
## les technologie
BACK-END:
- python flask
- API de QUIZZ: 
    [jservice](https://jservice.io/).
- API de traduction:
    [apertium]( https://github.com/apertium/apertium-python).

FRONT-END:
- html
- css (avec [bootstrap](https://getbootstrap.com/))
- js (appel API avec fetch)

## 1. demarer une appli flask
on va commencer avec flask de python c'est un framework facile mais peut etre apres on changera parce qu'il
il faut dabors faire le cerveau et apres on peut l'implemante ou on voudra

Pour cree une app flask suis les instruction de ce [lien](https://www.digitalocean.com/community/tutorials/how-to-make-a-web-application-using-flask-in-python-3) jusqu'a l'etape 4 qui est sur la base de donnee car pour l'intant on en fais pas.

Il y aura une erreur quand tu ferra flask run il faut que tu met ces commande dans le terminal

    # le nom  du fichier que tu as fais
    FLASK_APP=app.py 
    # pour debuge
    FLASK_DEBUG=1 
    pour ne pas avoir a recharger la page quand il on fait des changement
    TEMPLATES_AUTO_RELOAD=1 
    # for run
    flask run

quant tu arrive au html tu peux suivre les instructions du css,  le plus important c'est d'apprendre a afficher ta page html avec les **block de contenue**, (il met un lien de bootsrap c'est super pour le css)..

## 2. cree une api de traduction
- dans un nouveau ficher qui s'appel translate.py
 **les variables doivent etre aficher dans le terminal par un print()**
- pour faire runer le fichier tu fais 
``` 
python translate.py 
```
- **on implementera dans l'appli apres**
## 3. cree api de question
- [apprendre request](https://www.digitalocean.com/community/tutorials/how-to-get-started-with-the-requests-library-in-python-fr)
- dans un nouveau ficher qui s'appel quizz.py
 **les variables doivent etre aficher dans le terminal par un print()**
- pour faire runer le fichier tu fais 
``` 
python quizz.py 
```
- **on implementera dans l'appli apres**
## 4. mixer les api 
- mettre en fonction des fichiers quizz et translate 
- il faudra les mettre en pack grace a un fichier ```__init__.py``` vide
-importer les fonctions puis les utiliser
# FRONT-END
## 1. afficher la question
- grace au variable de flask comme apprie dans le debut
- il faut utiliser bootsrap 
## 2. faire un formulaire de reponse
- utiliser bootsrap  (il y a un onglet form tu a juste a copier et arranger le code)
