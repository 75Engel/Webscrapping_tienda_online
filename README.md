# Proyecto_tienda_online
Proyecto para el estudio de una tienda online, donde se realizará una obtención de datos (Webscrapping), análisis de la información existente y predicción de sugerencias

---
## Descripción del proyecto:

Se realizará una toma de datos existentes en una página web de una tienda online, mediante Webscrapping, obteniendo la información relevante del producto, precio sin rebajar y precio rebajado, datos de los diversos usuarios que han comentado sobre las compras realizadas de cada producto y su valoración.

Posteriormente se realizará un estudio, que queda por definir en una primera parte, sobre los productos existentes.

En este estudio vamos a ver cuántos de los productos que ofrecen tienen un descuento y se realizará un estudio para agregar un campo nuevo a los mismos que definan a los mismos y poder así hacer predicciones en relación con los gustos/compras anteriores de los usuarios que han comentado.

Indicar que dado que no se dispone de la información real sobre el número de usuarios que tiene la página web y las compras reales que se han realizado, se supondrá que sólo realizan compras los usuarios que han comentado y que además el 100% de las compras realizadas son las comentadas.

Finalmente se hará un estudio sobre las valoraciones de los usuarios de los productos en relación con sus aportaciones a la página. Esta valoración se realizará con metodología de NLP.

---
## Metodología:

En una primera parte se realizará un proceso de recopilación de la información de cada uno de los productos existentes.

En una segunda parte se utilizarán las librerías de numpy, pandas, matplolib y seaborn de Python para el tratamiento de los datos y visualización de los mismos.

En una tercera parte se utilizará la librería de Sklearn para realizar modelado de los datos. 

Previamente, generaremos una nueva variable donde agregar diversos #tags y agrupar con ellos los diversos productos en grandes grupos.

Con esta nueva variable y otras existentes haremos predicción de gustos de los usuarios.

Un una última fase, se hará un estudio sobre la calidad de los productos en función de las valoraciones de los usuarios existentes y ver si se puede utilizar en una última fase para mejorar los procesos de recomendaciones de los usuarios.

