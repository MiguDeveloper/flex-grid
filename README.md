## FLEX

### Dirección de los elementos flexibles(FLEX-DIRECTION).
La ajustaremos mediante la propiedad flex-direction que podrá tomar los siguientes valores:
- row: es la opción por defecto y ajustará los elementos flexibles de izquierda a derecha.
- row-reverse: igual que la anterior pero de derecha a izquierda.
- column: ajustará los elementos flexibles en columna, de arriba a abajo.
- column-reverse: igual que la de arriba pero de abajo a arriba.

### El ajuste de los elementos flexibles(FLEX-WRAP)
- no-wrap: es el valor por defecto y fuerza para que siempre los elementos estén en la misma línea aunque esto suponga que se salgan del contenedor (les haya dado o no les haya dado anchura).
- wrap: provoca un salto de línea si la anchura de los elementos (fijada por nosotros o por el contenedor) es superior a la del contenedor.
- wrap-reverse: lo mismo que arriba pero de abajo a arriba.

## Juntando la alineación y el ajuste(FLEX-FLOW)
- flex-flow: flex-direction flex-wrap

### Alineación horizontal(JUSTIFY-CONTENT)
- justify-content: space-between;

### Alineación vertical(ALIGN-ITEMS)
- align-items: center

### Alineación vertical-wrap(tengo varias lineas de elementos flexibles)
- align-content: center

## GRID

Para empezar a maquetar usando GRID lo primero que tenemos que hacer es definir cuál de nuestras etiquetas HTML se va a convertir en el contenedor GRID. Una vez lo hemos decidido le daremos una de estas propiedades:

- display:grid si queremos que nuestra rejilla (nuestro grid) sea un elemento de bloque.
- display:inline-grid si queremos que nuestro grid sea un elemento en línea.
Para este curso, con el objeto de que los ejemplos se muestren de manera más clara, usaremos la primera de ellas.

Una vez hemos asignado esta propiedad al contenedor, todos los elementos que contiene pasan a convertirse de manera automática en elementos del GRID cuya colocación y propiedades podremos empezar a modificar desde el contenedor.

### Definición de la estructura del GRID
Normalmente el primer paso que daremos para maquetar con GRID es definir la estructura que va a tener nuestra rejilla. Es un paso importante y para evitar problemas después es conveniente realizar una reflexión sobre ello.

Una vez hemos decidido que estructura queremos usaremos una serie de propiedades para definirla. Las más importantes para empezar son, bajo mi punto de vista, las siguientes:

- grid-template-columns: Para definir el número y tamaño de las diferentes columnas de mi estructura. Debo de poner tantos valores de anchura como columnas quiero que tenga el GRID.
- grid-template-rows: Para definir el número y tamaño de las diferentes filas de mi estructura. Debo de poner tanto valores de altura como filas quiero que tenga el GRID.
- grid-row-gap: Para establecer la separación entre las diferentes columnas.
- grid-column-gap: Para establecer la separación entre las diferentes filas.
En los dos último simplemente estamos expresando distancias pero los dos primeros tienen muchas posibilidades así que vamos a mostrar varios ejemplos:
