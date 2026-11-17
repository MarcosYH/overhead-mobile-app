# Overhead

Application mobile Expo / React Native (Expo Router).

## Démarrer

```bash
npm install
npx expo start
```

## Structure

```
src/
  app/          # Écrans et layouts (Expo Router)
  components/   # Composants réutilisables (ui/ pour les primitives)
  constants/    # Thème, couleurs, espacements
  hooks/        # Hooks personnalisés
  services/     # Appels API / accès aux données
  types/        # Types TypeScript partagés
  utils/        # Fonctions utilitaires
```

## Vérifications

```bash
npx expo lint
npx tsc --noEmit
```
