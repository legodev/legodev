# Aprendiendo **_Markdown:_**

Este es mi primer párrafo, siempre y cuando no haya dado un enter el párrafo seguirá siendo el mismo.
 
Lorem ipsum dolor sit amet consectetur adipisicing elit. Iure nesciunt quas possimus, eum sapiente nemo voluptas quos nulla dolor repudiandae veritatis voluptatibus sint vel fugit reiciendis consequatur laudantium aliquid placeat!.

Aplicando **negrita** y _cursiva_.

Ahora **_ambas_**.

# Sección de **_encabezados_**

# Encabezado 1
## Encabezado 2
### Encabezado 3
#### Encabezado 4
##### Encabezado 5
###### Encabezado 6

    Ya en el encabezado 5 y 6 no hay casi   diferencia más allá de la sintaxis.

En tecnología al símbolo **#** se le denomina **almohadilla** o **gato** y en inglés **hash**.

# **Links**

[ Youtube ](https://youtube.com)

[ ] Los corchetes contienen el texto que se mostrará.

( ) Los paréntesis contienen la URL a la cuál va a redirigir dicho link.

[Aprendiendo _Markdown_](#aprendiendo-markdown)

[Sección encabezados](#sección-de-encabezados)

    Todos los encabezados funcionan también como un ancla para los links.



# **Imágenes**

![Satoru Gojo](https://img.youtube.com/vi/gG3Jkj4-6p0/hqdefault.jpg) 

    Funciona como un link normal pero la diferencia está en que antes de los corchetes va el siguiente símbolo de exclamación !.


# Línea divisoria

Para hacer una línea divisoria se escribe 3 guiones medios. ---

Esto hace que semánticamente haya una división entre un tema y otro.



# Listas

### Listas ordenadas

1. Primer elemento.
1. Segundo elemento.
1. Tercer elemento.
1. Cuarto elemento.

### Listas desordenadas

* Primavera
    * 22 de Septiembre 
* Verano
    * 21 de Diciembre
* Otoño
    * 20 de Marzo
* Invierno
    *  21 de Junio

#### Segunda lista

- Enero
- Febrero
- Marzo
- Abril


    
Para una lista ordenada se utiliza siempre el mismo número y automáticamente lo transpila a una lista ordenada.
    
    Para una lista desordenada sirven asteriscos (*) como guiones (-).
    
    Se puede hacer una sublista agregando debajo otro elemento.

# Citas
>
> "El conocimiento es poder." - Sir Francis Bacon.

> "La libertad consiste en ser dueños de la propia vida." - Platón.

> "Dios ha muerto" - Friedrich Nietzsche.
>
    Se ponen con el símbolo >.

# Tablas 

| Nombre | Edad | Correo |
| --- | --- | --- |
| Leonardo | 21 | leonardo@gmail.com
| Pedro | 27 | pedro@gmail.com
| Carla | 24 | carla@gmail.com
| Valentina | 18 | valentina@gmail.com

    Las tablas deben de tener siempre un encabezado seguido de columnas vacías tal que así. | --- | --- | --- |.
    El | (pipe o barra vertical) indica que habrá una tabla.
    Si tenemos 3 columnas las que irán vacías serían 3.
    
# Códigos

Si quisiéramos introducir código en un párrafo se puede hacer muy facilmente con backticks o comillas graves: `const`. Si el código fuera más extenso con 3 backticks al inicio y al final de dicho código se puede hacer también.

### Ejemplo con una función

```js
function suma () {
    return a + b;
}
```

De saber el lenguaje de programación se puede poner después de los 3 backticks del inicio para que se muestre como tal.

# Fin de Markdown 👽