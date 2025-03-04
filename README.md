# projet-vue-kylian

Ce modèle devrait vous aider à démarrer le développement avec Vue 3 dans Vite.

## Configuration IDE recommandée

[VSCode](https://code.visualstudio.com/) + [Volar](https://marketplace.visualstudio.com/items?itemName=Vue.volar) (et désactivez Vetur).

## Support des types pour les imports `.vue` en TypeScript

TypeScript ne peut pas gérer les informations de type pour les imports `.vue` par défaut, donc nous remplaçons la CLI `tsc` par `vue-tsc` pour la vérification des types.  
Dans les éditeurs, nous avons besoin de [Volar](https://marketplace.visualstudio.com/items?itemName=Vue.volar) pour que le service de langage TypeScript reconnaisse les types `.vue`.

## Personnaliser la configuration

Voir la [référence de configuration de Vite](https://vite.dev/config/).

## Configuration du projet

```sh
npm install
```

### Compilation et rechargement à chaud pour le développement

```sh
npm run dev
```

### Vérification des types, compilation et minification pour la production

```sh
npm run build
```

### Exécuter les tests unitaires avec [Vitest](https://vitest.dev/)

```sh
npm run test:unit
```

### Lint avec [ESLint](https://eslint.org/)

```sh
npm run lint
```
