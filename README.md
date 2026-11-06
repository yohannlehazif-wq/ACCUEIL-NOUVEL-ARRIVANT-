# Mission Accueil RESTEV 85

Jeu pédagogique interactif sur l'accueil sécurité des nouveaux salariés.

## Publication sur GitHub Pages

1. Créer un nouveau dépôt GitHub public ou privé.
2. Déposer `index.html` et le dossier `assets` à la racine du dépôt.
3. Ouvrir **Settings > Pages**.
4. Dans **Build and deployment**, choisir **Deploy from a branch**.
5. Sélectionner la branche `main` et le dossier `/ (root)`, puis **Save**.
6. Attendre environ 1 à 3 minutes et ouvrir l'adresse fournie par GitHub Pages.

## Test local

Ne pas ouvrir seulement `index.html` si le dossier `assets` a été déplacé. Conserver exactement cette structure :

- index.html
- assets/
  - entrepot-circulation.jpg
  - maintenance-consignation.jpg
  - produits-chimiques.jpg
  - machine-production.jpg

Pour un test local fiable, lancer un serveur HTTP dans le dossier :

```bash
python -m http.server 8000
```

Puis ouvrir `http://localhost:8000` dans Edge, Chrome ou Firefox.
