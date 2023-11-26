# Análisis exploratorio de tweets mediante el las técnicas: Análisis semántico latente (LSA) y Asignación latente de Dirichlet (LDiA)

¿Quiéres hacer un análisis automátizado de miles de documentos, comentarios o textos y tener claro el tema que abordan? Esto te interesa.

El análisis semántico latente (LSA, en inglés) es una técnica de aprendizaje no supervizado que parte de los siguientes pilares: 

- La hipótesis distribucional establece que las palabras con significado similar aparecen frecuentemente juntas. 
- La descomposición de valor singular (SVD por sus siglas en inglés) a partir de una técnica matemática. Esta descomposición es utilizada para encontrar la estructura semántica escondida de las palabras que se encuentran en un documento.

La matriz de documento-termino sobre el corpus del texto se lee de la siguiente forma: Cada renglón en la columna representa palabras únicas en el documento y cada columna representa un documento simple, el proceso es alcanzado por la SVD.

El SVD factoriza la matriz documento-término en tres matrices: U, L y V. Las primeras dos son matrices ortonormales y L es una matriz singular (su determinante no existe o no es invertible), tal y como se ilustra a continuación:

![image.png](https://github.com/RodGuarneros/LSA_Topics_in_Twitter_NLP/blob/main/humor.jpg)

