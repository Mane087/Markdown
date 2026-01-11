# Markdown
Markdown es un lenguaje de marcado ligero creado por John Gruber y Aaron Swartz que trata de conseguir la máxima legibilidad y facilidad de publicación tanto en su forma de entrada como de salida

## Titulos:

Para poder agregar un titulo dentro de archivos .md(markdown) se hace mediante el simbolo de " # ". Al agregar titulos el simbolo de " # " se puede usar de 1 a 6 representando el nivel y tamaño del titulo. Esto es similar a la etiqueta "h" que hay en HTML que va desde el 1 al 6.
```
# Titulo 1
## Titulo 2
### Titulo 3
#### Titulo 4
##### Titulo 5
###### Titulo 6
```

## Formatos de texto:

En los archivos .md(markdown) para darle formato al texto se hace mediante los siguientes simbolos:
```
** ** negritas
~~ ~~ tachado
_ _ cursiva
```
**Este** es un ~~ejemplo~~ que usa esos _simbolos_.

**~~_Tambien se pueden combinar dentro de la misma oracion_~~**.


## Enlaces:

Para poner un enlace dentro de un archivo .md(markdown) se puede pegar directamente el enlace:

Mi GitHub: https://github.com/Mane087
```
Mi GitHub: https://github.com/Mane087
```
Tambien se pueden personalizar los enlaces para que diga lo que tu quieras en lugar de solo mostrar el enlace se hace de la siguiente forma:

Mi GitHub: [Mane087](https://github.com/Mane087)
```
Mi GitHub:[Mane087](https://github.com/Mane087)
```
El texto que queremos que diga se encierra entre " [] " seguido del link encerrado entre " () " sin espacios al principio o al final de cada llave.

Otra forma de mostrar enlaces es encerrandolos dentro de los simbolos de " < link > " pero de esta forma igual queda el link tal cual sea agregado:

<https://github.com/Mane087>
```
<https://github.com/Mane087>
```

## Mostrar imagenes:

Para mostrar imagenes dentro de los archivos .md(markdown) se hace de la siguiente forma: 

![TITULO PARA LA IMAGEN](https://geekytheory.com/content/images/2014/03/markdown_inte-1024x630.png)
```
![TITULO PARA LA IMAGEN](www.ejemplo_link_de_imagen.com)
```

## Listas:

Para mostrar listas en archivos .md(markdown) de puede hacer de dos formas mediante el simbolo de " - " para listas no ordenadas, a las cuales se les puede dar identacion con precionando la tecla " TAB " y para listas ordenadas se usa " 1. "

**LISTA NO ORDENADA**

- texto 1
- texto 2
  - texto 2-1
  
**LISTA ORDENADA**
1. texto 1
2. texto 2


## Citar

Para citar dentro de archivos .md(markdown) se hace mediante el uso del simbolo " > "
>Ejemplo de una cita
```
>Ejemplo de una cita
```
---
## Resaltar texto

Para resaltar texto dentro de un archivo .md(markdown) se hace mediante el simbolo de " ` " o si son varias lineas a resaltar como por ejemplo un bloque de codigo se usan " ``` " al inicio y al final del bloque de codigo o texto

Ejemplo de una linea de texto/codigo: `console.log()`

Ejemplo de bloque de codigo
```Elixir
def function do
IO.inspect()
end
```
---
## Tablas 

En los archivos .md(markdown) se puden agregar tablas usando el simbolo de  " | "
| columna 1 | columna 2 | columna 3 |
| -         | -         | -         |
| texto 1   | texto 2   | texto 3   |
```
| columna 1 | columna 2 | columna 3 |
| -         | -         | -         |
| texto 1   | texto 2   | texto 3   |
```

## Alertas
Las alertas, también conocidas como llamadas o advertencias, son una extensión de Markdown basada en la sintaxis de blockquote que se puede utilizar para resaltar información importante. En GitHub, se muestran con colores e iconos distintivos para indicar la importancia del contenido.

Utiliza las alertas solo cuando sean cruciales para el éxito del usuario y limítalas a una o dos por artículo para evitar sobrecargar al lector. Además, debes evitar colocar alertas consecutivas. Las alertas no se pueden anidar dentro de otros elementos.

Para añadir una alerta, utiliza una línea de cita bloque especial que especifique el tipo de alerta, seguida de la información de la alerta en una cita bloque estándar. Hay cinco tipos de alertas disponibles:
``` text
> [!NOTE]
> Useful information that users should know, even when skimming content.

> [!TIP]
> Helpful advice for doing things better or more easily.

> [!IMPORTANT]
> Key information users need to know to achieve their goal.

> [!WARNING]
> Urgent info that needs immediate user attention to avoid problems.

> [!CAUTION]
> Advises about risks or negative outcomes of certain actions.
```
> [!NOTE]
> Información útil que los usuarios deben conocer, incluso cuando leen el contenido por encima.

> [!TIP]
> Consejos útiles para hacer las cosas mejor o más fácilmente.

> [!IMPORTANT]
> Información clave que los usuarios deben conocer para alcanzar su objetivo.

> [!WARNING]
> Información urgente que requiere la atención inmediata del usuario para evitar problemas.

> [!CAUTION]
> Avisa sobre los riesgos o consecuencias negativas de ciertas acciones.
