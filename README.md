# libergot — site des applications

Site statique publié par GitHub Pages : <https://benjamingott.github.io/>.
Du HTML et une feuille de style, sans étape de build.

| Page | Adresse |
| --- | --- |
| Accueil | `/` |
| Mon marque-page (MyBookmark) | `/mybookmark/` |
| Mon marque-page — politique de confidentialité | `/mybookmark/confidentialite/` |

Les anciennes adresses `/biblivre/…` (le premier nom de l'app) redirigent vers
`/mybookmark/…`.

## Ajouter une application

1. Copier le dossier `mybookmark/` sous le nom de la nouvelle app, adapter les
   textes et l'icône (`assets/img/`).
2. Ajouter sa carte dans la liste `.apps` de `index.html`.

## Nom de domaine

Pour passer sur un domaine à soi : *Settings → Pages → Custom domain*, puis
créer chez le registraire un enregistrement `CNAME` vers
`benjamingott.github.io`. Les liens du site sont relatifs à la racine
(`/mybookmark/…`) et continuent de fonctionner. Penser à mettre à jour l'URL de
confidentialité dans la Play Console et chez Meta.
