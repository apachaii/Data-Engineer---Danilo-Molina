# Desafio Data Engineer / Danilo Molina

## Librerias Utilizadas:
 - pandas
 - emoji

## Dataset:
 - farmers-protest-tweets-2021-2-4.json

 ## Contexto:

 Se solicita resolver los siguientes problemas de programacion en python:

1. Los top 10 tweets más retweeted.
2. Los top 10 users en función a la cantidad de tweets que emitieron.
3. Los top 10 días donde hay más tweets.
4. Los top 10 hashtags más usados.
5. Los top 10 emojis más usados.
6. Los top 10 users más influyentes en función de lo retweeted de sus tweets.

Para ello se debe considerar el dataset farmers-protest-tweets-2021-2-4.json , el cual contiene una serie de tweets de una protesta de granjeros. El dataset consta de las siguientes Columnas:

| Campos            |
|------------------|
| url            |
| date           |
| content        |
| renderedContent |
| id             |
| user           |
| outlinks       |
| tcooutlinks    |
| replyCount     |
| retweetCount   |
| likeCount      |
| quoteCount     |
| conversationId |
| lang           |
| source         |
| sourceUrl      |
| sourceLabel    |
| media          |
| retweetedTweet |
| quotedTweet    |
| mentionedUsers |

Los campos utilizados en este ejercicio son:

| Campos Utilizados | Contenido del campo                            |
|-------------------|------------------------------------------------|
| date              | Fecha del tweet                                |
| content           | Contenido del tweet                            |
| user              | Contiene un objeto con informacion del usuario |
| retweetCount      | Cantidad de retweets                           |

Fuente: https://developer.twitter.com/en/docs/twitter-api/v1/data-dictionary/object-model/tweet