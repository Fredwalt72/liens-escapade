# Liens d'entreprise Escapade

Pages des codes QR affichés à bord. Un seul code par entreprise, deux
informations : il mène à l'application ET il dit quelle entreprise
ouvrir.

- Adresse du code : `https://fredwalt72.github.io/liens-escapade/e/<entreprise>.html?c=<code>`
  (amure, navettes, speyrit, azur)
- App installée : le bouton « Ouvrir dans l'application » (lien
  `escapade://e/<entreprise>?c=<code>`) entre directement dans la
  section de l'entreprise — ni choix, ni code à taper. À partir du
  prochain build, l'adresse https elle-même ouvrira aussi l'app
  (intentFilters Android).
- App pas installée : la page invite à installer, puis à rescanner le
  même code.

À la publication sur Google Play : remplir `LIEN_MAGASIN` dans chaque
page `e/*.html` avec l'adresse de la fiche — le bouton de
téléchargement apparaîtra tout seul.

L'inscription à une sortie continue d'exiger le code du jour du
capitaine : ce code-ci ouvre seulement la section de l'entreprise.
