# Command Center Lite - Landing Page

Landing page pour **Command Center Lite**, un outil de gestion de tournois TCG destiné aux petites boutiques de jeux de société et de cartes à collectionner.

## Fonctionnalités

- Page responsive (mobile, tablette, desktop)
- Formulaire de pré-inscription connecté à Formspree
- Design moderne aux couleurs de l'univers TCG (bleu nuit, or, fond parchemin)

## Structure

```
index.html    # Page unique avec HTML + CSS intégré
```

## Configuration du formulaire

Le formulaire est connecté à [Formspree](https://formspree.io). Pour utiliser votre propre compte :

1. Créez un compte sur formspree.io
2. Créez un nouveau formulaire
3. Remplacez l'ID dans `index.html` :
   ```html
   <form action="https://formspree.io/f/VOTRE_ID" method="POST">
   ```

## Personnalisation

Les couleurs sont définies en variables CSS au début du fichier `index.html` :

```css
:root {
    --primary-color: #1e3a5f;      /* Bleu nuit */
    --accent-color: #d4a017;       /* Or */
    --background-light: #f5f3ef;   /* Fond parchemin */
    ...
}
```

## Licence

MIT
