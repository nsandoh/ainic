---
layout: post
title:  Modela problemas complejos con redes neuronales gráficas y obten grandes resultados!
---

![_config.yml]({{ site.baseurl }}/images/aplicaciones.png)
<p> Un grafo corresponde a un grupo de objetos o nodos definidos a través de características y sus conexiones o arcos hacia otros nodos, estas conexiones también pueden contemplar características, y finalmente vectores de contexto . Estas simples, pero poderosas estructuras permiten modelar sistemas y sus relaciones, tales como redes sociales, estructuras químicas, organizaciones, publicaciones e investigadores y sistemas recomendadores. El desarrollo de las GNN ha permitido a través de operaciones convolucionales representar grafos de manera vectorial para por ejemplo detectar patrones tales como fraudes en transacciones o difusión de fake news en redes sociales.</p>

 <p>Las redes neuronales gráficas o basadas en grafos (GNN) han tenido un boom en los últimos años y es de los sectores de investigación más atractivos, lo cual de acuerdo al profesor titular de Standford, Jure Leskovec, se debe a su capacidad de modelar relaciones complejas gracias a su gran flexibilidad. El creciente interés tanto por parte de la academia como las industrias, ha impulsado que librerías como Tensorflow en 2022 hayan incorporado módulos de GNN dentro de sus funcionalidades.</p>
 
 ![_config.yml]({{ site.baseurl }}/images/grafos.png)

<p> En la imagen anterior, se muestra una estructura gráfica donde existen nodos de item y de clientes, ambos con sus respectivas características, los arcos entre nodos de clientes indican si estos son amigos, mientras que los arcos entre item y cliente indican si existió compra, finalmente hay un vector de contexto que aplica para toda la estructura gráfica. Este tipo de estructura puede ser útil para sistemas recomendadores, a través de técnicas como predicción de arco, lo cual permite modelar de probabilidad de que un cliente adopte un nuevo producto en función de sus características, su comportamiento de compra y el comportamiento y características de sus contactos. </p>

 ![_config.yml]({{ site.baseurl }}/images/Captura de Pantalla 2022-12-19 a la(s) 21.28.15.png)
 
 ### Desafios de las redes neuronales gráficas
 
<p> Las GNN aunque son muy útiles para resolver una amplia variedad de problemas, también presentan algunos desafíos:</p>
<ol>
<li>Escalabilidad: Algunos grafos pueden ser muy grandes y complejos, lo que puede dificultar el procesamiento y entrenamiento de las GNNs.</li>
<li>Desbalance de tamaño de nodos: Los grafos pueden tener nodos de diferentes tamaños, lo que puede dificultar la generalización y el rendimiento de las GNNs.</li>
<li>Falta de etiquetas de nodo: En algunos casos, puede ser difícil obtener etiquetas de nodo para entrenar las GNNs, lo que puede limitar su rendimiento.</li>
<li>Pérdida de información: Al procesar los grafos a través de capas de procesamiento, es posible que se pierda información importante.</li>
<li>Dificultad para interpretar los resultados: A veces puede ser difícil interpretar los resultados obtenidos a partir de las GNNs debido a su complejidad.</li>
<li>Requisitos de hardware: El entrenamiento y el procesamiento de las GNNs pueden requerir un hardware de alta potencia y pueden ser costosos de implementar.</li>
