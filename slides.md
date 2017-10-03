# Github

## Developement collaboratif
<div class='container'>
  <img class='img-responsive' style="border: none;max-width: 150px;height: auto;" src="images/lewagon.png">
  <img class='img-responsive' style="border: none;max-width: 150px;height: auto;" src="images/github.png">
</div>
 Gabriel de Vareilles

---

![Before: pipeline](images/lowering.jpg)

###### About me: From pipeline to asset pipeline

```note
This is a speaker note. It's only visible in presentation mode.

---
## Le projet: KittyFinder MVP
<div class='container'>
  <img class='img-responsive' style="border: none;max-width: 70px;height: auto;" src="images/black_cat.svg">
</div>
### Les objectifs

1. Définition des User Stories
2. Création de l'App Rails (pour le plaisir des yeux !)
3. Création du repo Github
4. Gestion de projet avec git et Zenhub

---
## Disclaimer

***
  User Stories: As a user I can, ......

---
<p class="pull-left"><em>As a User, I can sign in / log in</em></p>
<p class="pull-left"><em>As a User, I can report a missing Kitty</em></p>
<p class="pull-left"><em>As a User, I can see missing Kitties around me</em></p>
<p class="pull-left"><em>As a User, I can pick a Kitty</em></p>

.....

<p><em>As an Admin, I can see missing Kitties all around the world</em></p>

***

## Création de l'App Rails

        rails new \
        -T --database postgresql \
        -m https://raw.githubusercontent.com/lewagon/rails-templates/master/devise.rb \
        CHANGE_THIS_TO_YOUR_RAILS_APP_NAME

---

## Création du repository Github

        git init
        git add .
        git commit -m "initial commit"

        hub create
        git push -u origin master
        hub browse

---

## Projet Github

1. Issues
2. Project Board
3. Product BackLog

<div class="container">
<img class='img-responsive' style="border: none;max-width: 90px;height: auto;" src="images/zenhub.png">
</div>

***

## Les commandes Github & Bonnes pratiques
<div class="container">
<img class='img-responsive' style="border: none;width: 300px;height: auto;" src="images/git.svg">
</div>
---
## Master

<div class='container'>
  <img class='img-responsive' style="border: none;width: 500px;height: auto;" src="images/master-only.png">
</div>

---
## Master & Develop

<div class='container'>
  <img class='img-responsive' style="border: none;width: 500px;height: auto;" src="images/develop.png">
</div>

***

## Kit minimum de survie sur github

Création d'une nouvelle branche

        git checkout -b <branch_name>

Code sur une branche

        git add ( . / -p)
        git commit -m "commit msg"
        git push origin <branch_name>

Rassembler les branches

        git merge <branch_name>

---

### And Many more....!

        git pull --rebase
        ....

***

Merci de votre attention !

