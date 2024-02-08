# NET1_23-24
Support de cours du Web sémantique et Hypermedia

Exercice 1 : Créer votre propre vocabulaire
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
