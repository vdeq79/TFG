# Modelos de Markov ocultos y aplicaciones a la biología

> Trabajo de Fin de Grado realizado por XuSheng Zheng y tutorizado por Lidia Fernández Rodríguez.

## Descripción
En el presente trabajo se estudian los modelos de Markov ocultos (HMMs), un modelo estadístico capaz de inferir sobre estados ocultos a partir de una sucesión de observaciones relacionadas. Se presentan los elementos que constituyen un modelo de Markov oculto y los algoritmos asociados haciendo uso de conocimientos matemáticos y probabilísticos.

Las aplicaciones de los HMMs son muy variadas, en este trabajo se centra en las aplicaciones a la biología. Utilizando librerías de Python [hmmlearn](https://hmmlearn.readthedocs.io/en/latest/) y [NumPy](https://numpy.org/), se han implementado un ejemplo sencillo de reconocimiento de patrones genéticos mediante el uso de HMM y dos variantes de HMMs que se emplean para el análisis de secuencias biológicas. Dichas implementaciones se encuentran en la carpeta [src](https://github.com/vdeq79/TFG/tree/main/src) de este repostorio y son archivos de Jupyter Notebook con celdas directamente ejecutables. Las depencias que se requieren para la ejecución de dichos archivos son:
- Python >= 3.10
- NumPy >= 1.24.3
- hmmlearn >= 0.3.0