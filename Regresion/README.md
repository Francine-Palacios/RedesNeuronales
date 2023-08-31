# Observaciones


Hay varios tipos de modelo, en la mayoria de los casos usaremos un modelo secuencial, es decir tendremos la linea de codigo  (luego de crear las capas) : 

        modelo= tf.keras.Sequential([capa_1, capa_2, salida]) 

El modelo "Sequential" solo hace referncia al orden en que iran las capas.

Tambien realizaremos algunas configruacion en la compilacion, frecuentemente usaremos la linea 

        modelo.compile(
                optimizer= tf.keras.optimizer.Adam(alpha) 
                loss= 
                )

El optimizador "Adam" le permite a la red sabe como ajustar los pesos y sesgos eficientemente para que aprenda y no desaprenda. El parametrio numerico alpha  representa la tasa de aprendizaje, es decir que tanto ajustar los pesos y sesgos. Entre mas chico mejor pero perdemos eficiencia, y si es mayor la compilacion sera mas rapida pero con mucho mas error. 

Respecto a "loss"  (funcion de perdida ), puede ser cualquier medida del error, comunmente se usa el error cuadratico medio "means_squared_error", la cual considera que una poca cantidad de errores grandes es peor que una gran cantidad de errores pequeños.


