#Documentation du tuto git hub avec git


##initialisation du dépôt

`````bash
 git init
 git remote add origin SSH_REPO
 `````

 ##Rédiger un commit

 ```
 Titre du commit

 Description de notre commit avec des informations sur l'evolution su projet

 ```


 ##Envoyer un commit sur le dépôt distant 


 ```bash
 git add .
 git commit -m "Titre du commit"
 git push origin main
 ```

 ## Création d'une branch

 ```bash
 git checkout -b nom_branche
 ```
 
## Pour les bonnes pratiques on vas integrer les notion de revus de code .Pour cela on vas créer une branche, faire des modifications, les envoyer sur le depot distant, puis créer un pull request pour demander une revue de note.