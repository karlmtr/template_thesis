# Template LaTeX pour thèse

Donne un template, basé sur la classe **memoir** pour commencer à écrire la thèse, sans apporter de modifications dans l'apparence (je suis beaucoup trop nul à ça...). 
Il utilise le package `subfiles`. Il permet de diviser son document en plusieurs fichiers, pouvant être compiler indépendamment. Très utile quand le document commence à devenir très long, avec beaucoup d'images. 

Pour la bibliographie, le template utilise **biblatex**. 


Le template possède la structure suivante : 

- `build/` : dossier contenant tous les fichiers dû à la compilation. Devrait contenir tous les pdfs produits (main.pdf : le document entier; intro.pdf, theorie.pdf, etc pour les fichiers individuels).
- Chaque partie du document est placé dans un dossier comportant le fichier .tex ainsi qu'un dossier `img/` pour les images. 

