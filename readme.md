# Taller de redes neuronales 

# Integrantes:

- Jhoan Sebastian Andica 1859966-3743
- Diego Fernando Delgado 1859819-3743
- David Rios Gonzales 1765662-3743

Para desarrollar el perceptron multicapa se seleccióno del DataSet de clasificación de asteroides de la nasa.


Como parte del preprocesamiento del DataSet se seleccionaron las siguientes columnas:

* Magnitud absoluta
* Diametro estimado en kilometros minimo
* Diametro estimado en kilometros maximo
* Fecha aproximada de colisión 
* Velocidad relativa en kilometros por hora 
* Margen de error en kilometros 
* Inclinación 
* Periodo orbital
* Perihelion distance
* Aphelion distance

Luego del entrenamiento de la red neuronal la salida que debe retornar es 1 o 0 donde se determina si el asteroide es riesgoso o no.

Debido a que el dataset esta desbalanceado, mas o menos en una proporción de 6 a 1, se determina que se debe entrenar el modelo usando una muestra aleatoria de 0 para entrenar el modelo.


