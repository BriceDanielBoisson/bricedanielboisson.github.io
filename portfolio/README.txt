PORTFOLIO (statique) — Déploiement GitHub Pages

1) Modifiez le contenu
   - Ouvrez index.html et remplacez le nom, la bio, les liens et la liste de projets (tableau 'projects' dans le <script> JS).
   - Remplacez /assets/profile.jpg par votre photo (gardez le même nom de fichier), et ajoutez votre cv.pdf à la racine si besoin.

2) Mettez en ligne sur GitHub
   - Créez un nouveau dépôt (public), par ex. 'brice-portfolio'.
   - Uploadez tous les fichiers contenus dans ce dossier (index.html, le dossier assets, etc.).

3) Activez GitHub Pages
   - Dans Settings → Pages:
       • Source: "Deploy from a branch"
       • Branch: main / root
   - Enregistrez. L’URL sera du type: https://<votre-user>.github.io/brice-portfolio/

Astuce: Si vous nommez le repo exactement '<votre-user>.github.io', l’URL sera directement https://<votre-user>.github.io

Support: Ce site n’a pas besoin de build (juste HTML + Tailwind CDN).