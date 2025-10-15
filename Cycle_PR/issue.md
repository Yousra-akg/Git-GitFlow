## Contexte
Les utilisateurs ne peuvent pas filtrer les produits sur le site.
On veut leur permettre de trier par prix et catégorie pour améliorer l’expérience.

## User Story
En tant qu’utilisateur, je veux filtrer les produits par prix et catégorie afin de trouver rapidement ce que je cherche.

## Critères d’acceptation
- Given : L’utilisateur est sur la page produits.
- When : Il choisit une catégorie et un intervalle de prix.
- Then : La liste des produits s’actualise avec les bons résultats.

## Portée
- In scope : Filtre par prix et catégorie
- Out of scope : Recherche texte libre

## Notes techniques
- Endpoint API : `/products?price_min=&price_max=&category=`
- UI : dropdown catégories + slider prix
- Risques : performance sur gros catalogue

## Tests
- Test unitaire sur fonction de filtrage
- Test HTTP sur `/products`
- Test UI : vérifie réaction aux clics

## Pièces jointes
- Maquette UI
- GIF de l’effet attendu
