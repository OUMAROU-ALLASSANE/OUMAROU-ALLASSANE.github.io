# Portfolio — Abdoul Malick Oumarou Allassane

Site statique, aucune dépendance. Tout le contenu vit dans les objets JavaScript
en bas de `index.html` (`SITE`, `T`, `FACTS`, `ABOUT`, `SKILLS`, `TIMELINE`,
`TESTIMONIALS`, `PROJECTS`, `COURSES`, `EDU`, `AWARDS`). Modifier ces objets suffit :
le HTML se génère tout seul, en français et en anglais.

## Structure

    index.html                   le site complet (HTML + CSS + JS)
    assets/curriculum_vitae.pdf  le CV derrière le bouton « CV (PDF) »
    assets/img/                  photos et captures d'écran
    assets/video/                les rendus du pipeline animpipe
    .nojekyll                    sert les fichiers tels quels sur GitHub Pages

## Prévisualiser

Ouvrir `index.html` dans un navigateur. Il faut l'ouvrir **depuis ce dossier** :
sorti d'ici, il ne trouve plus `assets/` et les images apparaissent cassées.

## Publier sur GitHub Pages (glisser-déposer, sans ligne de commande)

1. Sur github.com, connecté au compte **OUMAROU-ALLASSANE** : bouton **+** en haut
   à droite → **New repository**.
2. Repository name : exactement `OUMAROU-ALLASSANE.github.io`.
   Visibilité **Public**. Ne cocher ni README, ni .gitignore, ni licence.
   → **Create repository**.
3. Sur la page du dépôt vide, cliquer le lien **uploading an existing file**.
4. Dans le Finder, ouvrir ce dossier `portfolio-malick`, faire **Cmd+A** pour tout
   sélectionner, et faire glisser la sélection dans la fenêtre du navigateur.

   Important : glisser **le contenu** du dossier (index.html, assets, README.md),
   pas le dossier `portfolio-malick` lui-même. Sinon le site se retrouve dans un
   sous-dossier et la page d'accueil reste vide.

   Le fichier `.nojekyll` est masqué dans le Finder ; **Cmd+Maj+.** l'affiche.
   Il est facultatif ici.
5. En bas de la page : **Commit changes**.
6. Onglet **Settings** → **Pages** dans le menu de gauche → Source :
   *Deploy from a branch*, branche `main`, dossier `/ (root)` → **Save**.
7. Une à deux minutes plus tard, le site est en ligne :
   **https://oumarou-allassane.github.io**

## Mettre à jour plus tard

Refaire l'étape 3-5 avec le fichier modifié : GitHub remplace la version
précédente. Le site se met à jour en une minute environ.

## À compléter

- Une photo de profil dont tu détiens les droits (`assets/img/photo_profil.jpg`).
- Captures d'écran du prototype Unity « Frenzied Escape ».
- Une recommandation de David Lessard sur le rôle de chef d'équipe.
- Le CV : la version actuelle date de 2023 et annonce une recherche de stage.
