# Youtube data analysis project

El objetivo de este proyecto era analizar data de youtube y crear visualizaciones y wordclouds para tener un mejor paneo de cuales son las tendencias actuales en dicha red social. 
También busqué analizar cuales son los emojis más usados en los comentarios y la relación entre views y likes/dislikes.

## Dependencies

Se recomienda instalar Anaconda para tener acceso a Jupyter Notebooks [Anaconda Python distribution](http://continuum.io/downloads), hay maneras de usar JN sin instalar Conda pero esta es la más sencilla e incluye muchos de los paquetes que utilicé.

Paquetes a instalar:

    pip install plotly
    pip install pandas
    pip install matplotlib
    pip install seaborn
    pip install textblob
    pip install wordcloud
    pip install emoji
    pip install regex


## Files in this repository

`GBcomments.csv` data con comentarios de videos de YouTube de Gran Bretaña

`UScomments.csv` data con comentarios de videos de YouTube de Estados Unidos

`GBvideos.csv` data con información (likes/dislikes, etc.) de los videos más vistos en Gran Bretaña

`USvideos.csv` data con información (likes/dislikes, etc.) de los videos más vistos en Estados Unidos

## Usage

Toda la data en este Notebook así como las visualizaciones creadas son de uso público para cualquiera que las requiera.
