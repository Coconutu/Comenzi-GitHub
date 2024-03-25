git init//Configurare git
git config --global user.email sebastian.daniel.adrian@gmail.com
git config --global user.name "Coconutu"
ca sa aflam datele de autentificare: git config --list

//Versiune locala
git init - anuntam ca vrem sa se initializeze un istoric al versiunilor
git add . - vrem sa salvam tot ce este in director, se pune punct
git commit -m "added message to start learning vcs"

//Versiune github (trebuie sa cream replica a repositoriului local)

git remote add origin https://github.com/Coconutu/Java.git
git branch -M main
git push -u origin main

Cum salvam updates dupa ce facem modificari ?

git add HelloWorld.java
git commit -m "Added Hello World program"
git push //sincronizare cu github

Daca vrem sa adaugam colaboratori la un proiect, intram in repository, settings, collaborators si adaugam dupa username.
Daca vrem sa colaboram la un proiect, copiem adresa HTTPS a proiectului, si intram la Open Git Bash here ->git clone https://github.com/Coconutu/Java.git (adica adresa proiectului pentru care vrem sa colaboram)

Daca vrem sa aducem cea mai recenta versiune de pe github
git pull


