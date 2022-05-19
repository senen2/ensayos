Como está estructurada la memoria.

Que sabemos

Está compuesta de redes de neuronas

Cada neurona es una célula que recibe señales de otras neuronas y envía una señal a varias neuronas.

Las señales que recibe las pondera y las promedia, y de acuerdo al resultado envía su señal a otras.

En el simulador que se utiliza en ML, las neuronas están organizadas en capas secuenciales. Cada capa recibe la información de la capa anterior, la procesa y la envía a la capa siguiente. Cada neurona recibe información proveniente de todas las neuronas de la capa anterior, suma toda la información recibida cada una multiplicada por un factor, que es el conocimiento que tiene. A esta suma le aplica una función y el resultado lo envía a todas las neuronas de la capa siguiente.

En este simulador la sumas que van para la capa final se condensan en una respuesta, por lo general softmax.

Las letras las aprendemos, principalmente, reconociendo, después escribiendo. Aprendemos primero a escuchar y luego a hablar. Podemos leer un libro, pero no escribirlo. En general primero reconocemos y luego generamos.

En ML, se lee la información a reconocer, se pasa por la red y se obtiene una respuesta. Esta respuesta se compara (resta) con la realidad y luego se hacen ajustes a todos los pesos en la red para que la próxima vez se reconzca correctamente. Al principio se le dan unos pesos al azar para que tenga algo con que arrancar.

Con el cerebro es algo igual, se le pide al niño que diga que letra es y luego se le dice cual es la real. Claro que al principio se le deben haber mostrado varios ejemplos sin pedirle nada, como para que tenga algo con que arrancar.

Este con que arrancar resuelve el problema del bucle infinito planteado en los primeros ensayos.

Nos parece que el cerbro guarda algunas muestras de lo que ha reconocido para poder utilizarlo luego cuando se refiera a ese concepto. Por ejemplo, al hablar de un perro la memoria devuelve un perro conocido, tal vez el más conocido o más usado o el anterior recordado con respoecto al tema. Por ejemplo, si se está hablando en perros que hacen popó en la calle uno no recuerda a chubaka sino a uno de los perros de la calle.

Asi es también cuando recuerda algo no físico como la felicidad. Se trae una pequeña sensación de lo que significa y es suficiente. Si se quiere profundizar ya se traen más cosas.

