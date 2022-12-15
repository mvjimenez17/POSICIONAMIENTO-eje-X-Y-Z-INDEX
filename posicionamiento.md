# ¿Qué es el flujo normal del HTML?

__El flujo normal (normal flow) en HTML es el orden natural en el que los elementos aparecen en pantalla, es decir, los elementos aparecerán colocados tal como estén ordenados en el código HTML solo si no se aplica ningún CSS que cambie la forma en la que se comportan.__

# 🤔¿Qué es un elemento posicionado?
Un elemento posicionado es aquel elemento que ha salido de su flujo normal a través de la propiedad position, además adquiere nuevas propiedades. La propiedad position establece en que punto de la pagina comenzara a posicionarse, mostrarse o dibujarse el elemento que se haya establecido en el código HTML.

# Los diferentes tipos de posicionamiento son los siguientes:

• static (valor por defecto)
• relative (El elemento se coloca relativo al flujo normal)
• absolute (El elemento se coloca respecto a su contenedor posicionado mas cercano)
• fixed (El elemento se coloca respecto al viewport)
• sticky (Es una combinación entre relative y fixed).

*Todos los elementos HTML son posicionados como estáticos por defecto, esto es, para hacer que el elemento fluya en el orden natural de la pagina, es decir, que el elemento siempre será posicionado de acuerdo al flujo normal de la pagina.*

Al tener un elemento posicionado podemos moverlo en los 3 ejes y corresponden a cinco propiedades:
↔️ Eje X:
• right(mover el elemento desde la parte derecha hacia la izquierda)
• left(mover el elemento desde la parte izquierda hacia la derecha)
↕️ Eje Y:
• top (mover el elemento desde la parte superior hacia la inferior)
• bottom(mover el elemento desde la parte inferior hacia la superior)
🔄 Eje Z-Index:
• z-index(cuando dos o mas elementos se solapan, podemos decidir cual aparece primero y cual por detrás de el).

⚠️ Las propiedades top, right, bottom, left y z-index no funcionaran y no serán habilitadas para los elementos con posicionamiento estático por lo tanto los elementos no se podrán mover o desplazar.
En la propiedad z-index solo se especifica un numero entero positivo/negativo, no se usa unidades tales como pixeles o porcentajes. La propiedad z-index toma un valor numérico entre 0 y ±2147483647 en la mayoría de los navegadores comunes. Es recomendable no usar valores consecutivos como: 1,2,3,4...