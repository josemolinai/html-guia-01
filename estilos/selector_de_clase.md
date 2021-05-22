[Índice](../readme.md) / [Anterior](../estilos/selector_de_tipo.md) / [Siguiente](../estilos/selector_de_id.md)

# Selector de clase:

Los selectores de clase seleccionan todos los elementos que tienen el atributo **class** especificado:

```
|-----------|-----------------------------------------------------------------|
|Sintaxis:  | .nombredeclase                                                  |
|Ejemplo:   | .cita seleccionará cualquier elemento que tenga la clase "cita".|
|-----------|-----------------------------------------------------------------|
```

Un ejemplo de definición de una regla CSS con un selector de clase:

```css
.cita {
    border: 2px dotted black;
}
```
Esta regla CSS crea la clase **cita** y define que tendrá un borde de 2 pixeles de grosor (_2px_), de estilo punteado (_dotted_) y de color negro (_black_).

En el código de un documento HTML el uso de la clase **cita** se podría ver del siguiente modo:

```html
    <div class="cita">
        <!----
            Otro contenido HTML
        ---->
    </div>
```


