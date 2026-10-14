# Hub de connaissances — prototype gratuit

Ce dossier fournit une maquette interactive dans le style d'un portail personnalisé : accueil, bibliothèque, recherche, catégories, fiches modifiables, liens externes, export local via le navigateur et démonstration de rôles.

## Démarrer tout de suite
- Décompressez le ZIP.
- Ouvrez `index.html` dans votre navigateur.
- Les fiches de démonstration et les modifications sont enregistrées dans le stockage local de ce navigateur.

## Publier gratuitement
1. Créez un dépôt GitHub personnel.
2. Ajoutez les fichiers de ce dossier au dépôt.
3. Pour un hébergement statique, activez GitHub Pages dans Settings > Pages, en choisissant la branche `main` et le dossier `/root`.
4. GitHub fournira une URL publique de type `https://votre-nom.github.io/nom-du-depot/`.

## Limite essentielle
Cette version est une **maquette fonctionnelle locale**, pas un portail sécurisé multi-utilisateur. Les rôles servent uniquement à montrer l'interface : ils ne protègent pas réellement les données. Le stockage est propre au navigateur et ne synchronise pas les fiches entre collaborateurs. N'y entrez pas de données confidentielles.

Pour une version d'entreprise partagée, il faudra connecter l'interface à Supabase Auth et à une base de données avec des règles RLS testées, puis publier le site. Supabase propose un forfait gratuit limité, mais les conditions d'utilisation de Vercel Hobby indiquent une restriction aux usages personnels/non commerciaux : pour un usage d'entreprise sur Vercel, vérifiez les conditions actuelles et ne supposez pas que le déploiement commercial sera autorisé gratuitement. Voir https://vercel.com/docs/plans/hobby et https://supabase.com/pricing.
