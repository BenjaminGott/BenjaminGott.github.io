# libergot — site des applications

Site statique publié par GitHub Pages : <https://benjamingott.github.io/>.
Du HTML et une feuille de style, sans étape de build.

| Page | Adresse |
| --- | --- |
| Accueil | `/` |
| Biblivre | `/biblivre/` |
| Biblivre — politique de confidentialité | `/biblivre/confidentialite/` |

## Ajouter une application

1. Copier le dossier `biblivre/` sous le nom de la nouvelle app, adapter les
   textes et l'icône (`assets/img/`).
2. Ajouter sa carte dans la liste `.apps` de `index.html`.

## Nom de domaine

Pour passer sur un domaine à soi : *Settings → Pages → Custom domain*, puis
créer chez le registraire un enregistrement `CNAME` vers
`benjamingott.github.io`. Les liens du site sont relatifs à la racine
(`/biblivre/…`) et continuent de fonctionner. Penser à mettre à jour l'URL de
confidentialité dans la Play Console et chez Meta.
