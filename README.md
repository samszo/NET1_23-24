# NET1_23-24
Support de cours du Web sémantique et Hypermedia

## Exercice 1 : Créer votre propre vocabulaire
- créer un fichier : vocab.ttl
- copier les prefix de fup8.ttl
- coller dans le fichier vocab.ttl
- changer le prefix : @prefix fup8: <https://jardindesconnaissances.univ-paris8.fr/onto/fup8#> .
par @prefix [le prefix que vous avez défini]: <https://jardindesconnaissances.univ-paris8.fr/onto/[le prefix que vous avez défini]#> .
- copier coller la ligne : <https://jardindesconnaissances.univ-paris8.fr/onto/fup8> a owl:Ontology ;
    dcterms:title "Formation Université Paris 8" .
- remplacer par : <https://jardindesconnaissances.univ-paris8.fr/onto/[le prefix que vous avez défini]> a owl:Ontology ;
    dcterms:title "Le nom du vocabulaire que bous avez choisi" .
- créer les class nécessaire avac le modèle :
  [le prefix que vous avez défini]:[le code de la class que vous avez défini] a rdfs:Class ;
    rdfs:label "[le nom de la class que vous avez défini]" ;
    rdfs:domain o:Resource ;
    vs:term_status "experimental" .
- créer les propriété suivant le modèle :
  [le prefix que vous avez défini]:[le code de la propriété que vous avez défini] a rdf:Property ;
    rdfs:label "[le nom de la propriété que vous avez défini]" ;
    rdfs:domain o:Resource ;
    vs:term_status "experimental" .

## Exercice 2 : Importer votre vocabulaire
- se rendre sur la page d'importation du vocabulaire : https://net-24.jardindesconnaissances.fr/admin/vocabulary/import
- remplir le formulaire :
    - le nom du vocabulaire : texte libre
    - le namespace uri
    - le prefix
- télécharger le vocabulaire sur ma machine
- choisir le fichier que vous avez télécharger
- cliquer sur Import

## Exercice 3 : Créer vos ressources template
cf. https://omeka.org/s/docs/user-manual/content/resource-template/

## Exercice 4 : créer des items sur la base des resources template
cf. https://omeka.org/s/docs/user-manual/content/items/#add-an-item
- mettre en place des relations entre les items en choisissant comme valeur d'une propriété une ressource omeka

## Exercice 5 : créer une analyse de votre base de connaissances 
- à la racine de votre github créer un fichier : analyse.md
- expliquer votre travail concernant :
 - le vocabulaire
 - les ressource template
 - les items
- illustrer en créant un lien vers la base omeka par exemple : https://net-24.jardindesconnaissances.fr/admin/item/250

## Exercice 6 : activer les github pages de votre repository
https://cours-web.ch/git/github-pages.html

