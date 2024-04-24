# Résumé du cours - JavaScript vanilla

[![Deploy](https://github.com/ibethus/js-but-s1/actions/workflows/deploy.yml/badge.svg)](https://github.com/ibethus/js-but-s1/actions/workflows/deploy.yml)


## Description
Ce dépôt présente les notions de base du JavaScript vanilla moderne, tirées du cours suivant : http://js-but1.codenestedu.fr/

## Générer les slides en local

1. Télécharger `reveal.js`, le dézipper dans le répertoire `slides` et nommer le répertoire `reveal.js` : https://github.com/hakimel/reveal.js/archive/master.zip


2. Lancer les commandes suivantes :
```
docker container run --rm -ti -u $(id -u):$(id -g) -v $(pwd):/documents asciidoctor/docker-asciidoctor:1.65 

asciidoctor-revealjs index.adoc
```

3. Ouvrir le fichier index.html généré.