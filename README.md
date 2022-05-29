# Servicio-Social

### ¡Bienvenido! 

En este repositorio podras encontrar dos carpetas con los siguientes nombres:

- Python Codigos
- Simulaciones NetLogo.

En la carpeta **Python Codigos** se encuentran los siguientes archivos:

- SIR_model_interactive 

En el cual se desarrolló el modelo SIR de una forma interactiva, esto con la finalidad de observar de una manera más dinamica el cambio de las gráficas del
modelo SIR dependiendo de los parámtros asignados.

- CovidCDMX

El objetivo de este código es reproducir el modelo SIR, pero con la información de uso libre del sector salud de la Ciudad de México, para poder ejecutar este código
se requiere la base donde se recopila toda la información de los contagios en México, anexo el link en donde pueden encontrar dicha base https://datos.gob.mx/busca/dataset/informacion-referente-a-casos-covid-19-en-mexico

para ejecutar este código, se necesita cargar la base de datos e ingresar una fecha de inicio y una fecha final, la finalidad de estas dos fechas 
es buscar en la base de datos de la Ciudad de México todos los enfermos y recuperados en este intervalo de tiempo. Estas fechas junto con la base de datos
son importantes, pues son tomadas como parametros para las funciones **CalculoEnfermos** y **recuperados**

Algo muy importante por mecionar es que en este código, los filtros de la base de datos, se realizaron con base en la metodología propuesta por el Conacyt, se anexa el link 
donde puedes encontrar dicha metodología https://datos.covid-19.conacyt.mx/#DOView.

En la carpeta **Simulaciones NetLogo** se encuentran dos simulaciones: 

*Nota: Para poder ejecutar estas simulaciones se necesita tener instalado NetLogo.* 

- RedMetro 

Esta es una simulación que trata de modelar el comportamiento de la Ciudad de México y la red de transporte colectivo Metro, durante el periodo de la contigencia epidemiológica en la Ciudad de México. 

En esta simulacion al presionar el boton setup, se realizara lo siguiente, se dividira el entorno por cada Alcaldía que hay en la Ciudad de México y también se creara 
la red del Metro de la Ciudad de México.

Al precionar el boton de "go" se pondrán en movimiento las tortugas creadas en el mundo, las cuales también puden subirse a alguna de la estación del metro y viajar.

Así mismo esta simulación cuenta con tres "deslizadores", con los cuales podremos ajustar la infecciosidad de la enfermedad, los dias en los que tarda en recuperarse una persona y la duración de la enfermedad en cada uno de los individuos. 
