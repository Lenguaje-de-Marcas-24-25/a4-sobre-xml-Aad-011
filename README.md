[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/fGeLcsqO)
# A5-SOBRE-XML
## 1 --> Características del XML
- Extensible, se pueden definir nuevas etiquetas.
- Versátil, separa contenido, estructura y presentación.
- Estructurado, se pueden modelar datos a cualquier nivel de complejidad
- Validable, cada documento se puede validar frente a un DTD/Schema
- Abierto, independiente de empresas, SO, lenguajes de programación
- Sencillo, facil de aprender y de usar
## 2 --> Estructura del XML y sus reglas sintácticas 
- Prólogo --> Contiene una secuencia de instrucciones de procesamiento, se divide en 2 partes:
  - Declaración XML -> Establece la versión de XML.
  - Declaración del tipo de documento -> Establece la estructura del contenido que aparece en el cuerpo.
- Cuerpo --> Contenido de información del documento, organizado como un árbol jerárquico.
## 3 --> En XML qué es un nodo raíz
Es la etiqueta de inicio ha de ser la primera de todas y la de cierre
## 4 --> Indica qué es un elemento vacío
Son marcas para elementos que no contienen ningún contenido.
Ej: < img src=”imagenes/favicon.png”/ >
## 5 --> Qué sentido tiene crear documentos XML bien formado
Asegura que los documentos puedan ser interpretados por los procesadores sin ninguna ambigüedad.
## 6 --> Qué es un espacio de nombres.
Es una recomendación W3C para proporcionar elementos y atributos con nombre único en un archivo XML. Resuelve ambiüedades entre elementos.
## 7 --> Entidades en XML
Las entidades en XML son >, <, ", ', &.
[Ejemplo](Ejemplo.xml)
## 8 --> Comentarios en XML.
Se escriben entre los caracteres "< !--" y  "-->"
[Ejemplo](Ejemplo_comentario.xml)
