## **Introducción**

La regresión lineal simple es un método estadístico que se utiliza para modelar la relación entre una variable dependiente y una variable independiente. En este proyecto, se utilizará la regresión lineal simple para predecir el rating de un libro en función de su precio.

## **Objetivos**

Los objetivos de este proyecto son los siguientes:

* Aprender a realizar un análisis de regresión lineal simple
* Aplicar la regresión lineal simple para predecir el rating de un libro
* Evaluar la precisión de la predicción

## **Metodología**

Los datos utilizados en este proyecto son los siguientes:

* Precio del libro (en euros)
* Opinión de los usuarios (puntuación de 1 a 10)
* Los datos se han obtenido de [Amazon](https://www.amazon.com/) (precio) y [Goodreads](https://www.goodreads.com/) (opiniones de los usuarios).

Para realizar el análisis de regresión lineal simple, hemos utlizado **Python**, **Pandas**, **Numpy**, **Scikit learn** y **Matplotlib**.

## Conclusiones

Los resultados del análisis de regresión lineal simple muestran que existe una relación lineal positiva entre el rating del usuario y el precio del libro. Por lo tanto, el modelo puede utilizarse para predecir la opinión del futuro comprador del libro en función de su precio.

La pendiente de 0.13126319271374243 significa que, para cada aumento de 1 euro en el precio de un libro, la opinión del usuario se espera que aumente en 0.13126319271374243 estrellas.

La intersección de 0.36560488502426697 significa que, si el precio de un libro es 0 euros, la opinión del usuario se espera que sea de 0.36560488502426697 estrellas.

En este caso, la pendiente es positiva, lo que significa que, en general, los usuarios tienden a dar mejores opiniones a los libros más caros. Esto podría deberse a que los libros más caros suelen ser de mayor calidad o que los usuarios esperan más de ellos.

## Recomendaciones

Es importante tener en cuenta que esta es solo una predicción y que no siempre se cumplirá. Hay muchos otros factores que pueden influir en la opinión de un usuario, como la calidad del libro, la relevancia para el usuario o las expectativas del usuario.

En base a esto, se podría utilizar un modelo de regresión lineal múltiple, que permite incluir más de una variable independiente en el modelo.
