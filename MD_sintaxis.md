# Sintasis de Markdown

## Encabezados

Para crear encabezados (hasta un maximo de 6) en markdown colocamos el simbolo: #

Por ejemplo:

~~~
# El encabezado más largo
## El segundo encabezado más largo
hasta llegar a 6
###### El encabezado más pequeño
~~~

![imagen](https://docs.github.com/assets/cb-8119/images/help/writing/headings-rendered.png)

---
## Estilos de texto

Markdown tiene muchos estilos que pueden ser applicador al texto.

Aqui algunos empleos: 

| Estilos | sintaxis |
|:-------------------:|---|
| **Negrita** | ** ** | |
| *Cursiva* | * *|
| ~~Tachado~~| ~~ ~~|
|***negritas curvisa***| *** ***|
|	<sub>Subscript </sub>	|	\<sub> \</sub>|
---
## Citas
Para citar en markdown hay distintas formas. Por ejemplo:

con >:
Esto
~~~
Esto no es una cita.
> Esto es una cita.
~~~
producira:

Esto no es una cita.
> Esto es una cita.

con \``` \```:


Esto:
~~~
```
For the emperor
``` 
~~~

Producira:
```
For the Emperor
```

## Enlaces:

Para crear un texto que contenga un enlace, hemos de hacer lo siguiente:

~~~
[Analisis del ultimo hombre](http://ve.scielo.org/scielo.php?script=sci_arttext&pid=S1315-52162006000300004)
~~~

[Analisis del ultimo hombre](http://ve.scielo.org/scielo.php?script=sci_arttext&pid=S1315-52162006000300004)

## Imagenes

Para colocar una imagen en nuestro archivo Markdown, hemos de hacer lo siguiente:

~~~
![Los pilares de la creacion](https://upload.wikimedia.org/wikipedia/commons/thumb/6/68/Pillars_of_creation_2014_HST_WFC3-UVIS_full-res_denoised.jpg/400px-Pillars_of_creation_2014_HST_WFC3-UVIS_full-res_denoised.jpg)
~~~
![Los pilares de la creacion](https://upload.wikimedia.org/wikipedia/commons/thumb/6/68/Pillars_of_creation_2014_HST_WFC3-UVIS_full-res_denoised.jpg/400px-Pillars_of_creation_2014_HST_WFC3-UVIS_full-res_denoised.jpg)

## Listas:

Las listas pueden clasificarse en ordenas o desordenadas. Para cada una de ellas existe comandos en markdown para invocarlas. Por ejemplo:

### Listas ordenadas:
Estas deben emperzar con un numero seguido de un punto y un espacio.
~~~
1. componente uno 
2. componente dos
3. componente tres
~~~
1. componente uno 
2. componente dos
3. componente tres

### listas desordenadas
Estas deben empezar con un guion (-).
~~~
* componente uno 
* componente dos
* componente tres
~~~
- componente uno 
- componente dos
- componente tres

### Listas anidadas:

Tambien las listas puedes estar anidadas. Un ejemplos seria:

~~~
1. componente uno
   - componente 1.1
2. componente dos
    - componente 2.1
        - componente 2.1.1
3. componente tres
~~~

1. componente uno
   - componente 1.1
2. componente dos
    - componente 2.1
        - componente 2.1.1
3. componente tres

### Listas de tareas:
Estas hacen referencia a las tareas que hay que realizar. Ejemplo: 

~~~
- [x] Actividad uno
- [ ] Actividad dos
- [ ] Actividad tres
~~~
![Lista de tareas](https://docs.github.com/assets/cb-64629/images/help/writing/task-list-rendered-simple.png)

## Citar grupos
Para citar a equipos o personas debemos de colocar una arroba (@)

~~~
@github/support ¿Qué piensas sobre estas actualizaciones?
~~~
![gitsupport](https://docs.github.com/assets/cb-3746/images/help/writing/mention-rendered.png)

## Ocultar contenido:
Para ocultar contenido en nuestro markdown, hacemos los siguiente:

~~~
<!-- Esto no aparecerá -->
~~~
<!-- Esto no aparecerá -->

## Notas al pie de pagina:

Para agreagar notas al pie de pagina, hacemos lo siguiente:

~~~
[^1]: Mi referencia.
[^2]: Every new line should be prefixed with 2 spaces.  
  This allows you to have a footnote with multiple lines.
[^note]:
    Named footnotes will still render with numbers instead of the text but allow easier identification and linking.  
    This footnote also has been made with a different syntax using 4 spaces for new lines.
~~~

![nota al pie de pagina](https://docs.github.com/assets/cb-6343/images/site/rendered-footnote.png)

## Emojis

Para estos, colocamos ": :" y en medio el codigo del emoji al que que queremos hacer referencia. Los codigos de los emojis está disponibles en esta [lista](https://github.com/ikatyang/emoji-cheat-sheet/blob/master/README.md).

Ejemplo:

~~~
hello :grinning:
~~~

hello :grinning: