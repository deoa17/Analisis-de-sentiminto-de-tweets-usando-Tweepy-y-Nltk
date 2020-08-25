# Análisis-de-sentimiento de tweets usando Tweepy y Nltk
Mediante la API de tweepy vamos a bajar los tweets sobre algún tema usando los hashtags, usaremos NLP para limpiar los tweets y sacaremos una  wordcloud para ver graficamente las palabras que se repiten mas y por ultimo vamos a realizar un análisis de sentimiento usando TextBlob

## 1. Autenticación en Tweepy
Accederemos a la API de twitter, vamos a necesitar las llaves de acceso solicitadas en twitter developer

## 2. Creamos una función para extraer los tweets dependiendo el hashtag
Se recomienda revisar la documentación para ver toda la amplia informacón que se peude extraer de la API https://developer.twitter.com/en/docs

## 3. Extracción de la data
Extraemos los tweets usando el hashtag para introducir el tema que deseamos conocer

## 4. Trasformamos el dataframe con tecnicas de NLP
Vamos a realizar una limpieza de los tweets usando nltk y expresiones regualres

## 5. Graficamos una Word Cloud
Creamos una grafica para ver las palabras mas usadas, Ejemplo: #Apple

![alt text](https://github.com/deoa17/Analisis-de-sentimeinto/blob/master/WordCloud.png)

## 6. Analisis de sentimiento de los tweets extraidos
Con ayuda de la libreria TextBlob realizaremos el analisis de sentimiento de los tweets extraidos

## 7. Resultados
Sacaremos los indicadores de tendencia central y grafiremos un histograma para ver resultados
