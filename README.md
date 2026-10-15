# app.chenevia.com

Petite page qui renvoie vers l'appli Chenevia Production (Google Apps Script, compte Google de Chenevia).

- L'adresse de l'appli est dans `index.html` et `404.html` (variable `APPLI`) : c'est la seule chose à changer si l'appli déménage.
- Les paramètres de l'adresse (`?lot=…`) sont transmis.
- Domaine : entrée CNAME « app » chez OVH vers `chenevia.github.io.` ; https par GitHub Pages.
- L'appli ne montre aucune donnée sans connexion par code personnel.
