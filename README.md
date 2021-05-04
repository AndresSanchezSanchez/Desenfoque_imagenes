# Desenfoque_imagenes
Se explica sin ninguna librería como funcionan las matrices de convolución para arreglar imágenes desenfocadas

En este cuaderno de Jupyter se pretende explicar como funcionan las matrices de convolución para conseguir destacar ciertos atributos de las imágenes, como pueden ser, destacar bordes, amuentar o disminuir luminosidad, etc. 

En este caso, se explica la convolución con elartefacto del desenfoque, usando la matriz de convolución siguiente:

              m=[[0, -1, 0],[-1, 5, -1],[0, -1, 0]] 
              
que tiene como objetivo hacer un valance de energía de los pixeles que se encuentran alrededor del original con el objetivo de destacar más los cambios de pixeles claros a oscuros y dar sensación de nitidez.

Hay que destacar, que el desenfoque tiene difícil solución y según algunas personas que comparten la información en internet aseguran que es imposible arreglarlo si el desenfoque es muy grande.

En este caso, se ha creado un pequeño proogrma donde primero explica el funcionamiento de las matrices de convolución comparándolas con una librería y se ha creado un pequeño código que simula lo que haría una librería para arreglar el desenfoque en dos fotos pudeiéndose observar los efectos de este filtro comparando la foto original con la tratada.
