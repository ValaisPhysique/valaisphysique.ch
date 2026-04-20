# Site internet de la Société Valaisanne de Physique

Toutes les commit sur la branche "master" sont automatiquement déployés sur [test.valaisphysique.ch](https://test.valaisphysique.ch).


## Éditer le contenu

Il y a deux types de contenu:
- [des articles](/_posts/)
- [des pages](/_pages/)


## Tests

Pour tester le site en version locale:
1. cloner le repo
2. installer Ruby
3. lancer le serveur avec la commande:

```bash
bundle exec jekyll serve
```

## Images

Pour convertir les affiches des conférences de format PDF en images PNG, on peut utiliser le script ImageMagick:

```
convert -density 300 -quality 85 assets/pdf/affiche.pdf assets/images/affiche.png
```