# Minuta de la Conferencia de Estaca

Este proyecto contiene la minuta digital para la Sesión General de la Conferencia de Estaca de Aldo Bonzi.

## Estructura del Proyecto

- `index.html`: El archivo principal que contiene toda la estructura y contenido de la minuta.
- `css/style.css`: La hoja de estilos que define la apariencia visual de la minuta.
- `images/`: Carpeta que contiene las imágenes y logos utilizados.

## Minuta de la Reunión

La minuta se encuentra detallada en el archivo `index.html`. Cada parte del programa está organizada en secciones para facilitar su identificación.

- **Encabezado (`<header>`):** Contiene los logos, el título principal y el subtítulo de la sesión.
- **Información de la Sesión (`.session-header`):** Muestra quién preside, dirige, y los pianistas.
- **Programa (`.program-section`):** Es la sección principal que contiene el orden del programa.
    - **Himnos (`.hymn`):** Resaltados con un fondo especial.
    - **Oraciones, Mensajes y Testimonios (`.program-item`):** Cada uno de estos es un ítem del programa.

## Cómo Modificar la Minuta

Para realizar cambios en el contenido de la minuta, debes editar el archivo `index.html`.

### Pasos para Modificar:

1.  **Abre `index.html`** en un editor de texto o código.
2.  **Busca el texto que deseas cambiar.** Por ejemplo, si necesitas cambiar el nombre de quien dará la primera oración, busca "Oración Inicial".

    ```html
    <div class="program-item">
        <strong>Oración Inicial:</strong> Agustina Montaño – Bº Villa Madero
    </div>
    ```

3.  **Reemplaza el texto** por el nuevo contenido.

    ```html
    <div class="program-item">
        <strong>Oración Inicial:</strong> [Nuevo Nombre] – [Nuevo Barrio]
    </div>
    ```

### Modificar Testimonios:

Los testimonios están en una lista. Para agregar o quitar un testimonio, edita la lista `<ul>` correspondiente.

```html
<div class="program-item">
    <strong>4º Testimonios:</strong>
    <ul>
        <li>Linda Piña – Bº Villa Madero</li>
        <li>Francisco Rosella – Bº Aldo Bonzi</li>
    </ul> 
</div>
```

## Realizar Arreglos en el Estilo

Si necesitas hacer cambios en los colores, fuentes o la disposición de los elementos, debes editar el archivo `css/style.css`.

### Clases CSS importantes:

- `.container`: El contenedor principal de la minuta.
- `header`: La sección del encabezado.
- `.program-item`: Estilo para cada elemento del programa.
- `.hymn`: Estilo específico para los himnos.
- `.program-item ul`: Estilo para las listas de testimonios.

Por ejemplo, para cambiar el color de fondo de los himnos, busca la clase `.hymn` en `css/style.css` y modifica la propiedad `background`.
