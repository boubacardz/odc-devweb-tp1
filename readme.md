# ODC - Formation - Revision 
## HTML & CSS : Concepts fondamentaux et bonnes pratiques

### Objectif du travail

Ce travail vise à évaluer la capacité de l’apprenant à :
- Comprendre les concepts fondamentaux du HTML et du CSS
- Rechercher des informations fiables
- Expliquer les bonnes pratiques du développement web
- Structurer une réflexion claire et logique

# Consignes de travail
- Travail en groupe (binome)
- Réponses rédigées et argumentées
- Illustrer avec des exemples si nécessaires
- Document clair et structuré (Power point, Canvas)

---

# PARTIE 1 — Recherche et compréhension du HTML

1. Présentez le HTML et expliquez son rôle dans la création d’un site web.
```bash
# 1. Présentation du HTML et son rôle
Le HTML (HyperText Markup Language) est le langage de balisage utilisé pour structurer le contenu d’un site web.
Il permet de définir les éléments d’une page comme les titres, paragraphes, images, liens et formulaires.
Le HTML constitue la structure d’une page, tandis que le CSS gère son apparence.
```
2. Décrivez la structure de base d’un document HTML et expliquez la fonction de chaque partie.
```html
# 2 Un document HTML se compose de :
- <!DOCTYPE html> : informe le navigateur du type de document
- <html> : élément racine
- <head> : contient les métadonnées (titre, encodage, styles)
- <body> : contient le contenu visible de la page

<!DOCTYPE html>
<html lang="fr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>
    ...
</body>
</html>
```


3. Expliquez la différence entre les balises sémantiques et les balises génériques, en donnant des exemples.
```bash
# Balises sémantiques vs balises génériques
Balises sémantiques : donnent du sens au contenu
Exemples : 
    <header>, <nav>, <main>, <article>, <footer>
Balises génériques : n’ont pas de signification particulière
Exemples : 
    <div>, <span>
Les balises sémantiques améliorent l’accessibilité et le SEO.
```

4. Analysez l’importance de la hiérarchie des titres (h1 à h6) dans une page web.
```bash
# Importance de la hiérarchie des titres
Les titres (h1 à h6) structurent le contenu de manière logique.

Un seul <h1> par page

Les titres doivent être utilisés dans l’ordre
Cela facilite la lecture, l’accessibilité et le référencement naturel.
```

5. Expliquez le rôle des attributs id et class et précisez leurs différences.
```bash
 # 5. Rôle des attributs id et class
id : identifiant unique pour un élément
class : peut être utilisé sur plusieurs éléments
L’attribut id est souvent utilisé pour le JavaScript ou l’ancrage, tandis que class sert principalement au CSS.
```

6. Montrez l’importance de l’attribut alt dans les images du point de vue de l’accessibilité.
```bash
# 6. Importance de l’attribut alt
L’attribut alt décrit une image lorsque celle-ci ne s’affiche pas.
Il est essentiel pour :
- Les personnes utilisant des lecteurs d’écran
- Le référencement des images
- Les connexions lentes
```

7. Expliquez l’utilité des formulaires HTML et le rôle des balises associées.
```bash
# 7. Utilité des formulaires HTML
Les formulaires permettent de collecter des données utilisateur.
Balises principales :
 <form> : conteneur
 <input> : champs
 <label> : description
 <textarea> : texte long
 <button> : soumission
```
8. Comparez les méthodes GET et POST et précisez dans quels cas les utiliser.
```bash
 # 8. Méthodes GET et POST
GET : données visibles dans l’URL, utilisé pour la recherche
POST : données cachées, utilisé pour les formulaires sensibles (connexion)
```
9. Définissez la notion d’accessibilité web et expliquez son lien avec le HTML.
```bash
# 9. Notion d’accessibilité web
L’accessibilité web vise à rendre les sites utilisables par tous, y compris les personnes en situation de handicap.
Le HTML contribue à l’accessibilité grâce à une structure claire et des balises adaptées.
```
10. Montrez pourquoi un HTML bien structuré est essentiel pour le référencement (SEO).
```bash
# 10. HTML et référencement (SEO)
Un HTML bien structuré permet aux moteurs de recherche de mieux comprendre le contenu, ce qui améliore le classement du site.
```

# PARTIE 2 — Bonnes pratiques en HTML

11. Expliquez pourquoi l’utilisation des balises sémantiques est considérée comme une bonne pratique.
```bash
# 11. Utilisation des balises sémantiques
Elles améliorent la compréhension du contenu, l’accessibilité et le SEO.
```

12. Analysez l’importance de l’indentation et de la lisibilité du code HTML.
```bash
#12. Indentation et lisibilité du code
Un code bien indenté est plus facile à lire, à maintenir et à corriger, surtout en travail d’équipe.
```

13. Justifiez la séparation entre le contenu (HTML) et la présentation (CSS).
```bash
# 13. Séparation HTML / CSS
Le HTML gère le contenu, le CSS gère l’apparence.
Cette séparation facilite la maintenance et la réutilisation du code.
```

14. Expliquez pourquoi la déclaration <!DOCTYPE html> est indispensable.
```bash
# 14. Importance du DOCTYPE
La déclaration <!DOCTYPE html> garantit un affichage cohérent sur tous les navigateurs.
```

15. Montrez l’utilité de la balise meta viewport dans le développement moderne.
```bash
# 15. Balise meta viewport
Elle permet l’adaptation du site aux écrans mobiles et est indispensable au responsive design.
```
16. Identifiez les erreurs HTML les plus fréquentes et proposez des solutions.
```bash
# 16. Erreurs HTML fréquentes
Balises non fermées
Mauvaise hiérarchie des titres
Attributs manquants
Solution : validation du code et bonnes pratiques.
```
17. Expliquez l’importance du nommage clair et cohérent des classes.
```bash
# 17. Nommage des classes
Des noms clairs facilitent la compréhension et la maintenance du code CSS.
```
18. Analysez l’impact d’un HTML mal structuré sur l’expérience utilisateur.
```bash
# 18. Impact d’un HTML mal structuré
Un HTML mal organisé nuit à :
- L’expérience utilisateur
- L’accessibilité
- Le référencement
```

# PARTIE 3 — Recherche et compréhension du CSS
19. Présentez le CSS et expliquez son rôle dans la mise en forme d’une page web.
```bash
# 19. Présentation du CSS
Le CSS (Cascading Style Sheets) permet de styliser les pages HTML (couleurs, tailles, disposition).
```

20. Comparez les différentes méthodes d’intégration du CSS dans une page HTML.
```bash
# 20. Méthodes d’intégration du CSS
Inline (déconseillé)
Interne (<style>)
Externe (recommandé)
```
21. Expliquez la notion de sélecteur CSS et donnez des exemples.
```bash
# 21. Sélecteurs CSS
Ils permettent de cibler les éléments HTML.
Exemples : sélecteur de balise, de classe, d’id.
```
22. Décrivez le modèle de boîte (box model) et son importance dans la mise en page.
```bash
# 22. Box Model
Il comprend : contenu, padding, border et margin.
Il est essentiel pour la mise en page.
```

23. Expliquer et comparez les notions de margin, padding et border.
```bash
# 23. Margin, padding et border
**margin**  : espace externe
**padding** : espace interne
**border**  : contour
```

24. Expliquez la propriété display et ses principales valeurs.
```bash
# 24. Propriété display
Elle définit le comportement d’affichage d’un élément 
-block
-inline
-flex, 
-. . .
```

25. Présentez Flexbox et expliquez dans quels cas l’utiliser.
```bash
# 25. Flexbox
Flexbox est utilisé pour aligner les éléments sur une dimension (ligne ou colonne).
```

26. Présentez CSS Grid et expliquez dans quels cas l’utiliser.
```bash
# 26. CSS Grid
Grid permet de créer des mises en page complexes en deux dimensions.
```

27. Comparez Flexbox et Grid dans une logique de mise en page responsive.
```bash
# 27. Flexbox vs Grid
**Flexbox** : alignement simple
**Grid**    : mise en page complète
```

28. Expliquez le concept de responsive design.
```bash
# 28. Responsive design
Le responsive design adapte l’affichage à tous les écrans.
```
29. Décrivez le fonctionnement des media queries.
```bash
# 29. Media queries
Elles permettent d’appliquer des styles selon la taille de l’écran.
```
30. Comparez les unités de mesure (px, %, em, rem, vh, vw).
```bash
# 30. Unités de mesure
px      : fixe
%       : relatif
em, rem : basées sur la taille du texte
vh, vw  : basées sur la taille de l’écran
```

# PARTIE 4 — Bonnes pratiques CSS
31. Analysez les raisons pour lesquelles les styles inline sont déconseillés.
```bash
# 31. Styles inline déconseillés
Ils rendent le code difficile à maintenir et à réutiliser.
```

32. Expliquez l’importance de l’organisation et de la structuration d’un fichier CSS.
```bash
# 32. Organisation du CSS
Un CSS bien structuré améliore la lisibilité et la collaboration.
```

33. Présentez la notion de spécificité en CSS.
```bash
# 33. Spécificité CSS
Elle détermine quelle règle CSS est appliquée en priorité.
```
34. Justifiez pourquoi l’utilisation de !important doit rester exceptionnelle.
```bash
# 34. Utilisation de !important
Son usage excessif complique la maintenance du code.
```

35. Expliquez pourquoi le mobile-first est une bonne pratique.
```bash
# 35. Mobile-first
Cette approche consiste à concevoir d’abord pour le mobile, puis pour les écrans plus grands.
```

36. Analysez l’importance du contraste des couleurs pour l’accessibilité.
```bash
# 36. Contraste des couleurs
Un bon contraste améliore la lisibilité et l’accessibilité.
```

37. Identifiez les erreurs CSS courantes et proposez des bonnes pratiques pour les éviter.
```bash
# 37. Erreurs CSS courantes
Sélecteurs trop complexes
Répétition de styles
Solution : simplifier et factoriser.
```

38. Expliquez l’impact d’un CSS mal optimisé sur les performances d’un site.
```bash
# 38. Impact sur les performances
Un CSS mal optimisé ralentit le chargement du site.
```
39. Montrez comment un CSS bien écrit améliore la maintenabilité d’un projet.
```bash
# 39. Maintenabilité
Un CSS clair et bien organisé facilite les évolutions du projet.
```
40. Analysez l’importance des tests multi-navigateurs.
```bash
# 40. Tests multi-navigateurs
Ils garantissent un affichage cohérent sur tous les navigateurs.
```
