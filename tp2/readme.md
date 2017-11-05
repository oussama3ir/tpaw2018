TP2


Master 3IR | 3ir2018.slack.com
TP AW #2 : HTML & Javascript

Validation de formulaire en JavaScript.

Support technique : http://www.w3schools.com/js/default.asp

Master 3IR | 3ir2018.slack.com
TP AW #2 : HTML & Javascript

# Validation de formulaire en JavaScript.

Support technique : http://www.w3schools.com/js/default.asp

Le formulaire permettra de saisir les informations suivantes :
* Nom
* Prénom 
* Date de naissance
* Adresse postale
* Adresse mail

1. Plate-forme de développement : 
* [Visual Studio Code](https://code.visualstudio.com), Eclipse ou un Éditeur de texte (notepad++, emacs, …)
* Navigateur web (Google Chrome ou Mozilla Firefox)

2. Formulaire HTML
    1. Dans le votre dossier “TP2”, créer un fichier index.html
    2. Écrire le code HTML pour reproduire le formulaire suivant
        1. ![Texte alternatif](https://raw.githubusercontent.com/bilelz/tpaw2018/master/tp2/TP2table.jpg "texte pour le titre, facultatif")
        2. vous pouvez utiliser un tableau HTML pour aligner tous les éléments
        3. Documentation sur les formulaires : [http://www.w3schools.com/html/html_form_attributes.asp](http://www.w3schools.com/html/html_form_attributes.asp)
        4. Pour la date de naissance, utilisez l’attribut  ` placeholder="JJ/MM/AAAA" ` pour indiquer à l’utilisateur le format 
        5. Code HTML pour le bouton de validation 
        ` <input type="button" value="Valider"/> `

3. Espace d’information pour la validation du formulaire
    1. Sous votre formulaire, écrire un endroit pour afficher les messages d’erreur
    ` <div id="error"> </div> `
        1. cette DIV doit avoir cette mise en forme via du CSS
            * couleur de fond : rose
            * padding : 5px
            * bordure : 1px de couleur noire
            * ![Texte alternatif](https://raw.githubusercontent.com/bilelz/tpaw2018/master/tp2/TP2table2.jpg "texte pour le titre, facultatif")      
