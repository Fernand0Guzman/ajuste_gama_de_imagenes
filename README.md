# Ajuste gama de imagenes
Este repositorio contiene la información para realizar el ajuste gama en imágenes digitales
Que es parte de la clase de Procesamiento digital de imagenes en UNITEC

## Que es el ajuste gamma

La correcion gamma es una forma especial de aumento 
de contraste diseñada para mejorar el contraste en areas
muy claras o muy obscura

Esto se logra modificando valores medios, 
particularmente los medios bajos


## COMO SE IMPLEMENTA EL AJUSTE GAMMA

Ajustando los valores de intensidad de la imagen 
(el brillo y el contraste)

El constraste en fotografia es el efecto que se produce al destacar un elemento
sobre los demas en una misma imagen.

Podemos definirlo como la diferencia entre el tono mas negro 
y blanco en una imagen

una forma de lograrlo es implementando una función que actue sobre la intensidad de cada uno de los pixeles de forma puntual.


## Función Matematica para elaborar el ajuste gamma

se puede implementar sobre una imagen en escala 
de grises o sobre una imagen en color real RGB.

![formula gamma](https://user-images.githubusercontent.com/114626285/192912907-6b1ba01e-b082-46c1-9f7b-65cd44497334.jpg)



## COMO ELEGIR GAMMA

-Para gamma = 1 no hay ninguna corrección. No se modifica la imagen

-Para gamma menor > 1 hay una gran corrección en el contraste para valores 
pequeños del color de entrada mientras que una pequeña corrección en 
el contraste para valores grandes. 

El brillo aumenta más para valores intermedios del color de entrada.

-Para gamma  mayor < 1  hay una pequeña corrección en el contraste para valores 
pequeños del color de entrada  mientras que una gran corrección en el contraste 
para valores grandes. 

El brillo disminuye más para valores intermedios del color de entrada.




# Ejemplo de Imagenes con ajuste gama

Valor de gamma 1.5

![rayos x 1](https://user-images.githubusercontent.com/114626285/192912102-60a6bc02-0210-42b1-9f0a-4502d63dd7bd.jpg)


Valor de gamma 4.5

![montañas](https://user-images.githubusercontent.com/114626285/192912377-6e245d6f-469e-4c52-ae1e-d56319c59c09.jpg)


Valor de gamma 2.0

![MANOTAS rayos x](https://user-images.githubusercontent.com/114626285/192912661-4f36399a-3a3a-4434-a220-10d610dd9c8a.jpg)

# Codigo (SCRIP MATLAB)

[ajuste gamma scrip.txt](https://github.com/Fernand0Guzman/ajuste_gama_de_imagenes/files/9669799/ajuste.gamma.scrip.txt)

# Conclusiones

El ajuste gamma sirve para modificar imagenes y mejorarla en si aumentando el brillo y la obscuridad dependiendo el caso ya que eso nos sirve
primordialmente en el PDI(procesamiento digital de imagenes)
Como pudimos ver esta formula nos sirvio bastante para analizar el tema de el ajuste gamma ya que nos permitio 
aumentar el brillo de alguna imagenes obscuras o reducirlo de ser el caso.
Matlab en este caso no sirvio de mucho ya que como este software tiene muchas utilidades practicas en el PDI pudimos observar de mejor manera las operaciones
que se llevaron acabo dirante el proceso.
