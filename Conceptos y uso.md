# Redes Neuronales


Es una tecnica del aprendizaje automatico, que toma las entradas, los resultados esperados de cada entrada, y asi aprender el algortimo necesario para hacer tal conversion.

### Conceptos 

La red neuronal se separan en capas. Cada capa puede tener 1 o mas neuronas. Cada red debe tener minimo una capa de entrada y una capa de salida , donde se resiven los datos de entrada y se entregan los resultados respectivamente. Pueden haber mas capas que comunmente se les llaman capas ocultas 

Las neuronas se conectan con "conexiones" cada conexion contiene el "peso" valor numerico que da importancia a la conexion. Cada neurona tiene un "sesgo" asociado, que es tambien un valor numerico . Ademas existe la funcion de activacion... 


Los "pesos" y "sesgo" funcionan como parametros de una funcion lineal, donde son la pendiente y el intercepto respectivamente. Es decir un dato para entrar a una neurona se multiplica por el peso, y al salir de la neurona se le suma el sesgo para irse a otra neurona y realizar el mismo procedimiento.




### Uso en Python 

Usaremos frecuentemente  la libreria de Tensorflow, que es una libreria de Google para inteligencia artificial. 

Usaremos tambien el framework Keras, que permite hacer las redes neuronales de manera simple, ahorrando muchas lineas. 

Tambien frecuentemente usaremos capas densa, que son aquellas que tienen conexiones desde cada neurona a todas las neuronas de la siguiente capa.


