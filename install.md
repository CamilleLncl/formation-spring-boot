`Installation de l'environnement pour la formation Spring Boot`

``Ajout Maven et JDK10``

* Créer un dossier "tools" où vous le souhaitez dans votre architecture
* Copier le contenu de la clef USB fournie dans ce dossier

`` Windows ``

Ajout de JAVA_HOME au Path : 
* Ouvrir le gestionnaire de variable d'environnements 
    * rechercher variable dans le menu démarrer
    * onglet "Paramètres système avancés" => bouton "Variabls d'environnement"
* Créer une variable JAVA_HOME pour l'utilisateur courant ayant pour valeur le chemin vers votre dossier "jdk10"
* Sélectionner la variable Path
* Cliquer sur "Modifier..."
* Cliquer sur "Nouveau"
* Ajouter "JAVA_HOME/bin"

De la même façon, créer une variable MAVEN_HOME.

``OSX et Ubuntu``

Ajout de JAVA_HOME au Path : 
* Aller à votre home : cd ~ (alt + "n" sur OSX)
* Ouvrir le fichier ".bashrc" avec un éditeur de texte
* Ajouter "export JAVA_HOME='chemin vers votre dossier jdk10'"
* Ajouter "export PATH=$JAVA_HOME:$PATH"
* Sauvegarder et fermer l'éditeur
* Ouvrir un nouveau terminal


De la même façon, créer une variable MAVEN_HOME.

``Intellij Idea``

Créer un nouveau projet Java

* Si l'IDE ne propose pas le JDK ajouté précédemment :
    * Cliquer sur "New"
    * Rechercher le dossier "jdk10" dans votre architecture

* Si l'IDE ne trouve pas le Maven ajouté précédemment : 
    * Ouvrir les Settings
        * "Command + ," sur OSX 
        *  "Ctrl + Shift + S" sur Ubuntu et Windows
    * Taper Maven dans la recherche
    * Cliquer sur les points à droite de l'option  "Maven home directory"
    * Rechercher le dossier "maven" ajouté précédemment
    