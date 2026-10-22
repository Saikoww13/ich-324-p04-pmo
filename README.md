# ICH-324-P04-<vos initials>

Module npm d'exemple réalisé dans le cadre du module ICH-324 (Packages et dépendances).

## Fonctions
- `hello(name)` : retourne `Hello, <name>!`
- `shout(word)` : retourne le mot en majuscules suivi de `!!!`

## Installation
```bash
npm install ich-324-p04-xx
```

## Étapes réalisées
1. Initialisation du projet avec `npm init` (nom en minuscules, imposé par npm)
2. Initialisation du dépôt Git et push sur GitHub
3. Ajout du code dans `index.js`
4. Création d'un access token granulaire sur npmjs.com (read/write, 90 jours)
5. Configuration du token : `npm config set //registry.npmjs.org/:_authToken="<token>"`
6. Publication : `npm publish --access public`
7. Vérification sur npmjs.com et avec `npm view ich-324-p04-<vos initials>`
