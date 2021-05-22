[Índice](../readme.md) / [Anterior](../estilos/selector_universal.md) / [Siguiente](../estilos/selectores_css.md)

# Selector de atributo:

Los selectores de atributo selecciona elementos basándose en el valor de un determinado atributo.

```
|-----------|---------------------------------------------------------------------------------------------------|
|Sintaxis:  | [attr] [attr=value] [attr~=value] [attr|=value] [attr^=value] [attr$=value] [attr*=value]         |
|Ejemplo:   | [id] seleccionará todos los elementos que tengan el atributo "id" establecido (a cualquier valor).|
|-----------|---------------------------------------------------------------------------------------------------|
```

Un ejemplo de definición de una regla CSS con un selector del atributo **id**:

```css
[id] {
    font-size: medium;
}
```
Esta regla CSS define que los elementos que tenga definido el atributo **id** tenga un tamaño de letra medio

En el código de un documento HTML el uso de atributo se vería del siguiente modo:

```html
<h2 id="tituloCitas">Citas famosas</h2>
```


