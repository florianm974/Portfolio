# CV — Source LaTeX

La source du CV vit ici (`main.tex`), compilée localement avec LaTeX Workshop
(VSCodium), puis committée avec la PDF à jour à la racine (`cv-marianne-florian.pdf`).

## Flux

1. Modifier `main.tex` dans VSCodium
2. **Ctrl+S** → LaTeX Workshop compile et copie la PDF vers `cv-marianne-florian.pdf`
3. **Ctrl+Alt+V** pour la preview
4. `git add -A && git push` → le site est à jour

## Synchroniser depuis Overleaf (si reprise de la source)

1. Sur Overleaf : **Menu → Télécharger → Projet source (zip)**
2. Extraire le contenu dans ce dossier `cv/`
3. Vérifier que le fichier racine s'appelle bien `main.tex`