# Catalogue Cardpedia

Catalogue public des cartes Cardpedia : **une page de Wikipédia en français = une carte**.
Il est servi tel quel par GitHub Pages et lu par le site Cardpedia (jamais en entier : par
tranches, index et listes paginées).

- Point d'entrée : [`manifest.json`](https://katomn10.github.io/cardpedia-catalogue/manifest.json) (version courante, effectifs, fichiers).
- Fichiers d'une version : `v/<version>/…`, immuables, vérifiables avec `v/<version>/checksums.sha256`.
- Format (schéma 1) : faces des cartes par tranches de 256 numéros, résumés, index identifiant → numéro,
  listes triées (numéro, vues, nom) par rareté et catégorie, recherche par début de titre. Fichiers JSON compressés (gzip).
- Versions : chaque version est une [Release](https://github.com/katomn10/cardpedia-catalogue/releases)
  (archive du site, registre des identifiants, rapport de construction). Retour arrière : relancer le
  workflow « Publier le catalogue » avec une version précédente.

## Contenu et licence

Textes extraits de **Wikipédia en français** (contributeurs de Wikipédia), sous licence
[CC BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/deed.fr) ; chaque carte renvoie à son article.
Images : liens vers Wikimedia Commons (non copiées), sous leurs licences respectives.
Vues mensuelles : statistiques de consultation publiées par la Wikimedia Foundation.

Ce dépôt ne contient que des données publiques : aucun compte, aucune donnée de joueur, aucun secret.
