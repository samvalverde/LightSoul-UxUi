# LightSoul Ux Ui
UX Test Real Life Case

## UI
El UI fue realizado en la herramienta de generación de prototipos Figma. Esta está conformada por 7 pantallas. Dado que es la extensión de la interfaz de Lightsoul, esta UI se enfoca en la aplicación de asistencia con IA. 

### Pantalla #1
En esta pantalla los usuarios pueden acceder a la opción de "Asistencia con IA". Esta opción se encuentra como parte de las pestañas de ayuda al usuario. 

**Interacciones**
- Pestaña para acceder a la asistencia con IA.

### Pantalla #2
La pantalla #2 consiste en el menú de la asistencia con IA. Esta pantalla brinda la opción de subir la fotografía que se desea utilizar para que la IA de su asistencia, así como dos opciones de contribución de la IA.

**Interacciones**
- Botón de regreso a la pantalla #1.
- Sección de consulta de instrucciones.
- Botón "Sugerencias de IA" (opción de asistencia #1)
- Botón "Escoger Lámpara" (opción de asistencia #2)

### Pantalla #3 y Pantalla #4 
La pantalla #3 se accede al clickear en la opción de asistencia "Sugerencias de IA". Esta página muestra sugerencias de muebles y lámparas para la foto inicialmente subida en la pantalla #2. Asimismo, índica el modelo, precio, nombre y material de las sugerencias. Esta pantalla también permite la opción "Shuffle" que cambia los items de sugerencia de la IA en caso que el usuario lo desee. La pantalla #4 contiene las mismas opciones y características que la pantalla #3, pero cambia la lámpara sugerida por la IA para representar la opción de "Shuffle".

**Interacciones**
- Botón de regreso a la pantalla #2.
- Sección de consulta de instrucciones.
- Botón de "Shuffle"
- Fotografía donde al pasar el cursor indica el precio y modelo de las sugerencias.

### Pantalla #5, Pantalla #6 y Pantalla #7
Estas pantallas son las encargadas de representar la opción "Escoger Lámpara" de la pantalla #2. En estas se puede visualizar como se vería una lámpara del catálogo de la tienda dentro del espacio subido en la pantalla #2. Las pantallas #5 y #6 contienen las mismas funcionalidades, pero sirven para representar el cómo al escoger las diferentes lámparas, la IA cambia la visualización de la habitación.  

**Interacciones**
- Botón de regreso a la pantalla #2.
- Sección de consulta de instrucciones.
- Botones para seleccionar la lámpara que se quiere visualizar.
- Fotografía donde al pasar el cursor indica el precio y modelo de la lámpara.
  
## Test de Usabilidad

Para el test de usabilidad, se implementó la herramienta Maze. Esta herramienta permite que diferentes personas prueben el prototipo de Figma para realizar pruebas de usabilidad, estudios de experiencia del usuario, y recopilar datos cuantitativos y cualitativos de forma rápida y eficiente. Maze funciona por medio de "Bloques", en el caso de este prototipo, se utilizaron 7 bloques. 

#### Bloque #1 
Este bloque se encarga de dar una pequeña explicación sobre lo que trata el test de usabilidad.

#### Bloque #2 
En este bloque se tiene la primera misión. Esta misión le solicita a los participantes acceder a la asistencia con IA desde la pantalla #1.

#### Bloque #3 
El bloque #3 realiza la primera encuesta del test de usabilidad. Aquí se le pregunta a los participantes, ¿Qué tan intuitivo considera que es acceder a la asistencia con IA? Donde pueden contestar por medio de una escala númerica del 1-5.

#### Bloque #4
Aquí se continua con la segunda misión de los participantes. En esta se le solicita a los participantes acceder a la opción "Sugerencias de IA" de la pantalla #2. Además, les explica el contesto en el que se encuentran dentro del prototipo.

#### Bloque #5
En este bloque se asigna la tercera y última misión de los participantes. Aquí se le solicita a los participantes acceder a la opción "Escoger Lámpara" de la pantalla #2. Además, les explica el contesto en el que se encuentran dentro del prototipo.

#### Bloque #6
En este bloque se les pregunta a los participantes sobre su experiencia utilizando la asistencia con IA, donde pueden contestar utilizando una escala de emociones del 1-7.

#### Bloque #7
En este último bloque se les pregunta a los participantes si consideran que se deba implementar algo diferente a lo demostrado en el prototipo. Esto lo pueden contestar por medio de un simple input.


## Sujetos de Prueba

Hubieron 7 sujetos de prueba en total, pero desafortunadamente el maze tenía unos errores y 3 de las pruebas se realizaron antes de corregirlos, por lo que no se pudieron tomar en cuenta. Estos son los sujetos que hicieron la prueba en el maze correcto:

1. Estudiante de computadores en el TEC
2. Estudiante de mecatrónica en el TEC
3. Estudiante de microbiología en la UCR
4. AR Trainer en una empresa de seguros.

## Resultados

En la primera sección de la prueba "Acceder a la AI" se obtuvieron los siguientes resultados:
    83.3% Direct success
    16.7% Mission unfinished
    44.4% Misclick rate
    5.3s Avg. duration

Después de esto, en la evaluación del usuario en la escala del 1 al 5 de intuitividad, se obtiene una respuesta positiva con un promedio de 4.5.

Posteriormente, se tiene la segunda pantalla de prueba "Sugerencias de IA" con los resultados:
100% Direct success
0% Mission unfinished
52.4% Misclick rate
10.9s Avg. duration

y la prueba "Escoger lámpara":
100% Direct success
0% Mission unfinished
9.1% Misclick rate
6.8s Avg. duration

Luego en la escala de satisfacción del 1 al 7, parece que se obtuvo una respuesta mayormente positiva con un 6.4 de promedio.

Para finalizar, se notan algunos de los comentarios que se dejaron para ayudarnos a mejorar el sitio web:
"Todo funciona muy bien"
"Me pareció que la IA podría en vez de solamente shuffle de manera superficial, podría shuffle los prodcutos en términos de color y/o estilo. "

## Correcciones

### 1. Mejora en el Diseño Visual

**Comentarios Recibidos:**  
Aunque el prototipo actual ha recibido un feedback positivo, el diseño visual en general tiene áreas significativas que podrían mejorarse, especialmente en cuanto a la paleta de colores, el uso de imágenes e íconos, y las fuentes utilizadas.

**Acciones Propuestas:**
- **Revisar la paleta de colores:** La combinación de colores actual puede beneficiarse de una revisión para asegurar que sea visualmente atractiva y coherente con la marca. Se sugiere considerar un esquema de colores más moderno y estilizado que refleje la naturaleza tecnológica y avanzada de la funcionalidad de IA.
- **Mejorar el uso de imágenes e íconos:** Los íconos y las imágenes deben ser más representativos y llamativos. Se recomienda utilizar íconos que sean más intuitivos y visualmente atractivos, así como imágenes de mayor calidad que refuercen la estética del producto.
- **Optimización de tipografías:** Las fuentes de letra actuales podrían beneficiarse de un ajuste que incluya una tipografía más moderna y que sea fácil de leer en diferentes tamaños de pantalla.

### 2. Refinamiento de la Interacción del Usuario

**Comentarios Recibidos:**  
Los usuarios indicaron que la experiencia de utilizar la asistencia con IA fue en general positiva. Sin embargo, algunos comentarios sugirieron que la funcionalidad de "shuffle" podría beneficiarse de una mayor personalización en términos de color y estilo.

**Acciones Propuestas:**
- **Mejora en la funcionalidad de shuffle:** Implementar una opción avanzada de "shuffle" que permita a la IA no solo cambiar los productos de manera superficial, sino también considerar variaciones en términos de color, estilo y material para ofrecer una experiencia más personalizada y adaptada a las preferencias del usuario.
- **Refinar la experiencia de interacción:** Se recomienda optimizar los flujos de interacción, como la selección y comparación de escenas, para hacerlos más fluidos e intuitivos, asegurando que el usuario pueda navegar entre opciones de manera más eficiente.

### 3. Evaluación de la Asistencia con IA

**Comentarios Recibidos:**  
Los usuarios calificaron la intuición y la facilidad de acceso a la asistencia con IA con puntajes sólidos, pero hay margen para mejorar la claridad y accesibilidad.

**Acciones Propuestas:**
- **Clarificación del acceso a la IA:** Asegurar que los botones y opciones relacionados con la asistencia de IA estén claramente definidos y visibles para el usuario. Puede ser útil añadir descripciones breves o tooltips que orienten mejor a los usuarios sobre cómo usar la asistencia de IA.
- **Optimización del proceso de ayuda:** Revisar el flujo desde la selección de la imagen hasta la obtención de sugerencias de IA para asegurarse de que cada paso esté bien explicado y sea intuitivo, minimizando cualquier posible confusión durante el uso.
