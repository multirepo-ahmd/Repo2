## Objectif: Séparer les application en repository different:
## Trois repo chaque repo contien un docker file , le quatrieme contient un docker  compose
# Repo  1 et 2 : Submodule du github 
Cette méthode n'est pas efficace , car : 
    - On vas créer un sous module  repo1 dans le repo2 ,ce qui change la structure demandé pour
    le projet.
    - En plus y'a le probleme des sous module qui sont pas ajour par rapport au repo de base ,
    par exemple la , le fichier .py du sous module repo1 est vide alors que dans le repo1 lui meme le fichier n'es pas vide.