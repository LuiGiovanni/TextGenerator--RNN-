# TextGenerator -RNN-
## Introduccion

Nosotros, como seres humanos racionales, podemos crear historias y pequeños textos con, al menos, una pequeña apariencia de racionalidad. ¡Pero! ¿Qué pasa con las computadoras? ¿Cómo ellos (si este es el término correcto a usar) racionalizan lo que están "escribiendo"? En este proyecto intentamos hacer un programa para crear pequeños diálogos o escenas de un libro famoso llamado "Guerra y paz" de León Tolstói. y ver si pueden crear oraciones lógicas ... al menos mejor que mi escritura.

## Libro
El libro que utilizo se llama *War and Peace* por León Tolstói, el cual cuenta con 3196212 caracteres en total y 82 caracteres los cuales son utilizados

## Implementacion
Para ejecutar una corrida ejecutas el archivo *recurrent_keras.py* y cada 10 epochs el programa guardara un "checkpoint" para tener un lugar de donde reiniciar para no tener que volver a re-entrenarlo
```
python recurrent_keras.py
```

## Resultados
Lamentablemente en ubuntu el entrenamiento crasheaba asi que no llegue lejos con los epochs descubri que windows, por alguna razon, no crasehaba las corridas en la titan asi que actualmente lo estoy corriendo ahi. Adjuntare los resultados lo mas pronto posible ademas de algunos avances.
