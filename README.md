# The Math Behind the Magic: Neural Networks, Theory and Practice
## Encuentro Nacional de Ingeniería Matemática 2024
### **Joaquín Fontbona, Javier Maass, Claudio Muñoz y Diego Olguín.**

El curso tiene como objetivo abordar los resultados teórico-matemáticos más importantes de las redes neuronales, conectándolos con aplicaciones del mundo real. Se explorarán conceptos clave como las arquitecturas de red, el teorema de aproximación universal y la optimización mediante descenso de gradiente estocástico.

Se combinarán discusiones teóricas con tutoriales prácticos, enfocándose en la aplicación de redes neuronales convolucionales para la clasificación de imágenes, así como en el uso de redes neuronales informadas por física (PINNs) para la simulación de sistemas físicos o regidos por ecuaciones diferenciales.

Las actividades prácticas se desarrollarán en PyTorch, por lo que se recomienda tener conocimientos intermedios de Python. Todo el trabajo de programación se realizará en la nube, por lo que no será necesario instalar ningún software para las sesiones. Además, se abordarán aspectos técnicos como GitHub y el uso de GPU, sin requerir experiencia previa.

* Sesión 1: Red neuronal feedforward. **[ [Google Colab](https://colab.research.google.com/drive/111KBDu5xadyCN5pge4GbJYVnG5faweR_?usp=sharing) ] [ [Notebook](https://github.com/diegoolguinw/Math_Behind_Magic/blob/main/Notebooks/Sesi%C3%B3n%201.ipynb) ] [ [Slides](https://github.com/diegoolguinw/Math_Behind_Magic/blob/main/Slides/Sesi%C3%B3n%201.pdf) ]**
    - Problema de aprendizaje y solución para problema de regresión.
    - Definición de una red neuronal feedforward.
    - Teorema de aproximación universal.
    - Descenso de gradiente estocástico.
    - Tutoriales en PyTorch: creación de redes neuronales feedforward, visualización de aproximación y de optimización vía redes suficientemente anchas con descenso de gradiente estocástico. Aplicación a clasificación de imágenes y motivación de redes neuronales convolucionales.
 
* Sesión 2: Redes neuronales convolucionales. **[ [Google Colab](https://colab.research.google.com/drive/1Z5xoo9sP6gu--kZ7TGJR70TsrpNecsyT?usp=sharing) ] [ [Notebook](https://github.com/diegoolguinw/Math_Behind_Magic/blob/main/Notebooks/Sesi%C3%B3n%202.ipynb) ] [ [Slides](https://github.com/diegoolguinw/Math_Behind_Magic/blob/main/Slides/Sesi%C3%B3n%202.pdf) ]**
    - El problema de entrenar redes neuronales con SGD: underfitting, overfitting, entre otros. ¿Cómo detectar estos problemas, cómo solucionarlos?
    - Redes neuronales convolucionales (CNN): reduciendo el overfitting con un cambio de arquitectura.
    - Aspectos teóricos de las CNN y redes equivariantes.
    - Tutoriales en PyTorch: Visualizando el underfitting y el overfitting. Regularización L2, Dropout y Batch Normalization. Ejemplo de aplicación de redes neuronales convolucionales.
 
* Sesión 3: Todo es una red neuronal feedforward. **[ [Google Colab](!Coming soon!) ] [ [Notebook](¡Coming soon!)  ] [ [Slides](¡Coming soon!) ]**
    - Physics Informed Neural Networks (PINNs): más allá de la información de los datos. Resultados teóricos para EDO.
    - DeepONets: una red para dominar muchas ecuaciones. Teorema de aproximación universal para operadores.
    - Generative Adversarial Networks: el comienzo de la inteligencia artificial generativa.
    - Tutoriales en PyTorch: aplicación de PINNs a un modelo de EDO en epidemiología y estimación de parámetros. Aplicación de DeepONet para crear un red neuronal que actúa como integrador.
