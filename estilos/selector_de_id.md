[Índice](../readme.md) / [Anterior](../estilos/selector_de_clase.md) / [Siguiente](../estilos/selector_universal.md)

# Selector de Id:

Los selectores de ID seleccionan un elemento basándose en el valor de su atributo id. 

_Solo puede haber un elemento con un determinado ID dentro de una página web_.

```
|-----------|----------------------------------------------------------------------------|
|Sintaxis:  | #nombredeid                                                                |
|Ejemplo:   | #tituloCitas seleccionará cualquier elemento que tenga el Id "tituloCitas".|
|-----------|----------------------------------------------------------------------------|
```

Un ejemplo de definición de una regla CSS con un selector de Id:

```css
#tituloCitas {
    font-family: 'Times New Roman', Times, serif;
}
```
Esta regla CSS define que los elementos cuyo sea **tituloCitas** deben mostrar de manera preferente una fuente de las familias _'Times New Roman'_, _Times_ o _serif_.


En el código de un documento HTML el uso del id **tituloCitas** se podría ver del siguiente modo:

```html
<h2 id="tituloCitas">Citas famosas</h2>
```


