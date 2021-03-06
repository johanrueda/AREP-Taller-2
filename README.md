# Arquitecturas empresariales - Taller 2
El objetivo de este programa es calcular la media y la desviación estándar de una lista de números que se leen desde un archivo dentro de los archivos del programa. Para esto se hace uso de una lista doblemente enlazada donde cada nodo contiene el valor.

## Prerequisitos

Conocimientos basicos sobre media y desviación estandar de la muestra de una población, ademas de un lista doblemente encadenada

- Funciones
  - Calculo de la desviacion estandar.
  - Calculo de la media.


## Descarga y instalación

Para clonar este repositorio basta con copiar la siguiente linea en un Shell de cualquier sistema operativo

**“git clone https://github.com/Edyesid/AREP-taller-01.git”**

Es recomendable tener instalado maven en su computadora para poder visualizar de una mejor manera las pruebas y compilación del taller. para esto dirijase al pagina de maven y siga los pasos de instalación.

**https://maven.apache.org/install.html**

Una vez que tenga maven en su computadora, dirijase a la carpeta raiz del taller-1 y para compilar el proyecto se deber introducir el siguiente comando:

**mvn package**

Para poder ejecutar el programa introduce el siguiente comando, una vez el servicio este corriendo podras abrir la pagina desde el browser con la siguiente dirección http://localhost:4567/

**mvn exec:java -Dexec.mainClass="edu.escuelaing.arep.app.App"**

![compilar](images/compilar.png)

## Pruebas  [![CircleCI](https://circleci.com/gh/Edyesid/AREP-Taller-2.svg?style=svg)](https://circleci.com/gh/Edyesid/AREP-Taller-2)

Se muestran los dos ejemplos que estan en el pdf del taller 

Se usan los siguientes datos (prueba por cada columna)

![tabla](images/tabla.png)

Para cada columna se deberian obtener los siguientes resultados

![resultado](images/resultado.png)

Finalmente estos son los datos obtenidos del programa, los cuales concuerda con los de la tabla anterior

![prueba1](images/prueba1.png)

Para las pruebas de la pagina web se realizaron los calculos con los mismos datos de las pruebas anteriores y estos fueron los resultados

![prueba2](images/prueba2.png)
![prueba3](images/prueba3.png)

En el caso que el usuario no halla insertado datos o los halla insertado mal se mostrara el siguiente aviso

![prueba4](images/prueba4.png)

## Construido

[Eclipse](https://www.eclipse.org/) plataforma de código abierto para el desarrollo de aplicaciones

## Heroku

[Ver pagina](https://peaceful-ocean-49993.herokuapp.com/)

## Autor

Edwin Yesid Rodriguez Maldonado

## Licencia

GNU GENERAL PUBLIC LICENSE
