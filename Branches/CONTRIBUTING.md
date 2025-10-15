# 🌿 Stratégie de branches (GitFlow)

## Branches principales
- **main** → branche stable et déployable à tout moment (protégée)
- **develop** → branche d’intégration (toutes les features sont fusionnées ici avant release)

## Branches temporaires
- **feature/** → développement d’une nouvelle fonctionnalité  
  Exemple : `feature/123-filtrer-projets`
- **release/** → préparation d’une version stable  
  Exemple : `release/1.2.0`
- **hotfix/** → correctif urgent en production  
  Exemple : `hotfix/fix-500-login`

## Nommage
Pattern recommandé :
