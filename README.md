# Tanagra2

Tanagra est un outil d'identification, d'analyse sentimentale et de cartographie de noms de lieux.

A partir d'un texte, l'outil utilise la suite SpaCy pour la reconnaissance d'entités nommées de lieu. Aucune désambiguisaiton des lieux reconnus n'est encore effectuée (travail en cours). Ensuite, une analyse des sentiments du contexte est effectuée à l'aide du modèle Bert-base-multilingual-uncased-sentiment. Cela permet de donner un score positif, négatif ou neutre.
Les lieux sont alors géolocalisés à l'aide de la base Geonames, puis cartographiés avec le sentiment associé, à l'aide de la librairie Folium.

### Présentation [ici](https://drive.google.com/file/d/1iG2z97cxiHRYrSAvDa3_7LgPwdURy60q/view?usp=sharing)
### Lien vers le notebook [ici](https://colab.research.google.com/drive/1PIl94Meb6P16IRWMMsAXWrsfy-9vvaFI?usp=sharing)

Ancienne version web [ici](https://github.com/obtic-sorbonne/Tanagra/tree/main)
