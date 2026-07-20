# CV en ligne — Victor Blanche

Site CV façon "une" de journal sportif, prêt à être publié avec **GitHub Pages**.

## Structure du dossier

```
victor-blanche-cv/
├── index.html      → la page du site (déjà prête)
└── images/         → à compléter avec tes photos (voir liste ci-dessous)
```

## Images à ajouter dans le dossier `images/`

Le code fait référence à ces fichiers, à déposer tels quels dans `images/` (mêmes noms, sensibles à la casse) :

- `watermarked_img_9537871781102113045.png` (photo bannière "À la Une")
- `photo_Golf-De-Villennes_1600194028.jpg`
- `Gemini_Generated_Image_y5begsy5begsy5be.png`
- `images.jpg` (université de Budapest)
- `image0 (10).jpeg` (tennis / Roland-Garros)
- `image0 (9).jpeg` (équipe de volley)

Les autres images (Unsplash) sont déjà en ligne et n'ont rien à ajouter.

> Astuce : si un nom de fichier contient un espace (ex. `image0 (10).jpeg`), garde-le exactement identique — GitHub Pages gère les espaces dans les noms de fichiers.

## Mise en ligne sur GitHub Pages

1. Crée un nouveau dépôt sur GitHub (par exemple `victor-blanche-cv`), public.
2. Dans le dossier `victor-blanche-cv/` sur ton ordinateur, ajoute tes images dans `images/`.
3. Initialise et pousse le dépôt :
   ```bash
   cd victor-blanche-cv
   git init
   git add .
   git commit -m "Site CV initial"
   git branch -M main
   git remote add origin https://github.com/<ton-pseudo>/victor-blanche-cv.git
   git push -u origin main
   ```
4. Sur GitHub : va dans **Settings → Pages**.
5. Dans "Build and deployment", choisis **Source : Deploy from a branch**, branche `main`, dossier `/ (root)`.
6. Clique **Save**. Le site sera disponible après 1-2 minutes à l'adresse :
   `https://<ton-pseudo>.github.io/victor-blanche-cv/`

## Personnalisation rapide

- Coordonnées (téléphone, e-mail, LinkedIn) : dans la sidebar tout en bas du fichier `index.html`, section `<aside class="sidebar">`.
- Titre / accroche : dans l'onglet "À la Une", balises `.title-highlight` et `.title-rest`.
