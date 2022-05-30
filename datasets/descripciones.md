# Descripción de los data sets

## Dataset 1: Convertidores de energía marítima 1

Este dataset contiene la potencia generada en dos plantas convertidores de energía marítima en Perth y Sydney (Australia).

+ energia_total: (Variable respuesta) La potencia total generada
+ pais: El país en el que se encuentra la planta
+ A1,... A16: Energía absorbida por cada uno de 16 puntos

Archivo: energy_data01.csv

## Dataset 2: Convertidores de energía marítima 2

Este dataset contiene la potencia generada en dos plantas convertidores de energía marítima en Adelaide y Tasmania (Australia).

+ Variable respuesta: La potencia total generada
+ Pais: El país en el que se encuentra la planta
+ A1,... A16: Energía absorbida por cada uno de 16 puntos

Archivo: energy_data02.csv

## Dataset 3: Dispositivo de Parkinson

Este dataset tiene 16 medidas biomédicas de voz de 42 pacientes diagnosticados con Parkinson que participaron en un estudio de 6 meses.

+ ID: ID del paciente
+ `motor_UPDRS` (variable objetivo 1): Unified Parkinson's Disease Rating Scale (UPDRS) registrada en el motor del dispositivo del paciente.
+ `total_UPDRS` (variable objetivo 2): Unified Parkinson's Disease Rating Scale (UPDRS) registrada total del dispositivo del paciente.
+ edad: Edad en años
+ genero: Mujer u hombre
+ `dias_estudio`: Días desde que se incorporaron en el estudio.
+ `bio1`,...`bio16`: 16 medidas de voz biomédicas

¿Hay diferencias en la variable respuesta que escogió entre pacientes?

Archivo: parkinson.csv

## Dataset 4: Aspas aerodinámicas de la NASA

Este dataset se obtuvo de la NASA y consiste de diversas pruebas aerodinámicas y acústicas de secciones bidimensionales y tridimensionales de secciones de aspas aerodinámicas conducidas en un túnel de viento anecoico.

+ `frecuency`: Frecuencia en Hertz
+ `angle`: Ángulo de ataque en grados
+ `chord`: Longitud del cordón en metros
+ `free_stream`: Velocidad en metros por segundo
+ `thickness`: Espesor de desplazamiento del lado de succión en metros
+ `sound_pressure`: (Variable respuesta) Nivel de presión del sonido en decibeles

Archivo: airfoil.csv

## Dataset 5: Bicicletas en Seul

El datase contiene el conteo de bicicletas públicas rentadas por hora en el Seoul Bike Sharing System de Seúl.

La variable respuesta de interes es `Rented Bike Count`

Archivo: SeoulBikeData.csv

## Dataset 6: Métricas en Facebook

El dataset contiene información de las publicaciones en Facebook durante 2014 en la página (de FB) de una empresa de cosméticos.

Incluye 7 características que se conocen previos a la publicación del post y 12 características para evaluar el impacto de la publicación

La variable respuesta de interés es `Lifetime Post Total Reach`

Archivo: facebook_cosmetic_data.csv

## Dataset 7: Mercado accionario de Estanbul

Este data set incluye los rendimientos del mercado accionario de Estanbul (ISE). Además el data set incluye el rendimiento de otros 7 índices internacionales: SP, DAX, FTSE, NIKKEI, BOVESPA, MSCE_EU, MSCI_EM del 5 de Jun de 2009 al 22 de Febrero de 2011.

La variable respuesta es ISE

Archivo: estanbul_data.csv

# Sugerencia para la lectura de los datasets

Usar

`read.csv("direccion_url")`

donde las direcciones url son por ejemplo para los datos de las bicicletas:

https://raw.githubusercontent.com/EduardoSelimMM/ProyectosRegresion/main/datasets/SeoulBikeData.csv
