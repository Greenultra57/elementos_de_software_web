1. ¿Por qué los enlaces son verdes y no rojos?
R/ Esto es debido a las especificaciones, por así decirlo, a equivale a 1 y la especificación del color verde vale más de 1. Por eso el color verde es el que domina y no el rojo ya que la especificación es mucho más mayor que la otra.

2. Hacer que los enlaces sean rojos.
R// En este caso hay dos formas: La primera sería que se use el mismo código de especificación del color verde pero en vez de ese color se use el rojo, la cosa es que aquí el rojo ya dominaría debido a que aquí el orden del codigo importa, aunque la especificación valga lo mismo, el orden de arriba-abajo vale más.

La otra forma sería usar "!important", más o menos así (de esto fue tomado de IA): a {
  color: red !important;
}

La razón de esto es porque "!important" es una especificación es demasiado grande que las demás.

3. Rehacer el HTML usando <div> en lugar de <ul> y <li>. ¿Qué pasa?
R// Se rompe el CSS porque se usa el ul y li, por esto se pierde la semantica

4. Comentar el CSS que no se puede tocar y reescribir este CSS usando una clase por selector para que se vea igual.
R// El diseño se queda igual, pero el CSS deja de depender de ul y li. Esto hace que ahora dependa de las clases, haciendolo algo más flexible y que se pueda volver a usar.