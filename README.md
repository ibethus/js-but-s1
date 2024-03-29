# Résumé du cours - JavaScript Vanilla

[![Deploy](https://github.com/ibethus/js-but-s1/blob/main/.github/workflows/deploy.yml/badge.svg?branch=main)](https://github.com/ibethus/js-but-s1/blob/main/.github/workflows/deploy.yml)


## Description
Ce dépôt reprend toutes les notions abordées lors d'une introduction au JavaScript Vanilla moderne. 

## Générer les slides en local

1. Télécharger `reveal.js`, le dézipper dans le répertoire `slides` et nommer le répertoire `reveal.js` : https://github.com/hakimel/reveal.js/archive/master.zip


2. Lancer les commandes suivantes :
```
docker container run --rm -ti -u $(id -u):$(id -g) -v $(pwd):/documents asciidoctor/docker-asciidoctor:1.65 

asciidoctor-revealjs index.adoc
```

3. Ouvrir le fichier index.html généré.