# Examen RVRA Ordinaria

## Realidad Virtual

### XR-Interaction-Toolkit

**Crear una aplicación de realidad virtual**

* Al mover o rotar la cabeza, lo veremos reflejado en el entorno virtual, lo mismo con los mandos.

* Habrá una mesa con dos cubos, uno de estos lo tendremos que poder agarrar con la mano derecha, el otro no.

* No queremos que se puedan agarrar cosas a distancia.

* Con el cubo agarrado, cuando apretemos cualquier botón, éste cambiará de color.

* Podremos dejar el cubo en un `SocketInteractor` que habrá encima de la mesa.

* Habrá otra mesa en frente a la que podremos teletransportarnos, solo con la mano izquierda.


## Realidad Aumentada

### XR-Interaction-Toolkit

**Crear una aplicación para interactuar con el entorno real**

* La app debe de instanciar un plano semitransparente al detectar el suelo.

* Tenemos que poder colocar 'farolas' en el plano. Una farola es un cilindro alargado con un cubo en la parte superior.

* Tenemos que ser capaces de seleccionar la farola. Al hacerlo, aparecerá un cubo semitransparente de color verde en la base de ésta para hacer ver que está seleccionada.

* Al seleccionar la farola, deberá cambiar a otro color. (Con que lo haga una vez basta)

> Las farolas no se deben poder rotar ni escalar.

> No es necesario hacer una build

### Vuforia

**Crear una aplicación de reconocimiento de imágenes**

* La app debe reconocer la imagen 'pen1' y colocar un borde rojo alrededor de ésta.

* Habrá un botón en pantalla al abrir la app. Éste se habilitará cuando se reconozca la imagen 'keyboard' y se desabilitará cuando se deje de reconocer.

> Para habilitar / deshabilitar un botón podemos usar la propiedad `interactable`.

> No es necesario hacer una build