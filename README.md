# Tanagra2

Tanagra est un outil d'identification, d'analyse sentimentale et de cartographie de noms de lieux.

A partir d'un texte, l'outil utilise la suite SpaCy pour la reconnaissance d'entités nommées de lieu. Aucune désambiguisaiton des lieux reconnus n'est encore effectuée (travail en cours). Ensuite, une analyse des sentiments du contexte est effectuée à l'aide du modèle Bert-base-multilingual-uncased-sentiment. Cela permet de donner un score positif, négatif ou neutre.
Les lieux sont alors géolocalisés à l'aide de la base Geonames, puis cartographiés avec le sentiment associé, à l'aide de la librairie Folium.

### Présentation [ici](https://docs.google.com/presentation/d/e/2PACX-1vQ5aoQBDFlTA8NEMKifMyFl8aDnST7k8zlwyAPjznLi_HTeOiCHhlWVgHYMqAltvGV0ZCTHwIJlbhZQ/pub?start=false&loop=false&delayms=3000)
### Lien vers le notebook: https://github.com/obtic-sorbonne/Tanagra2/tree/main

Ancienne version web : https://github.com/obtic-sorbonne/Tanagra/tree/main
