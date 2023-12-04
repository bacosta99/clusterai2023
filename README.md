# **Trabajo Final Grupal: Bank Subscription**
____
__Universidad Tecnológica Nacional, Buenos Aires__\
__Ingeniería Industrial__\
__Ciencia de Datos - Curso I5521__
____
Alumnos: Acosta, Bruno y Bartolomeo, Agustin

## clusterai2023
En este repositorio se publica el trabajo practico realizado para la clase de ciencia de datos del año 2023

Un banco quiere predecir cuantos clientes se suscribirán a una campaña de marketing. Para ello, comparten un data set con una cartera de clientes de 45,211 personas con 17 variables que muestran algunas características de los clientes en el banco.

Se realizará un estudio profundo del data set, para entender con que datos estamos trabajando y cuales son las tendencias de sus datos; seguido de una transformación de las variables. Con el data set transformado, se entrenarán varios modelos de machine learning con el objetivo de encontrar el que predice si un cliente se va a subscribir o no de la mejor manera posible.
## Descripción de archivos:
### bank_subscription (1).csv
En este archivo csv se encuentran los datos con los que se trabajan en este proyecto.
El mismo tiene las siguientes columnas:
1.	Age: Edad del cliente
2.	Job: Tipo de empleo del cliente
3.	Martial Status: Estado civil 
4.	Education: Educación máxima alcanzada por el cliente
5.	Credit: Si tiene deuda de crédito o no
6.	Balance (euros): Promedio de saldo en la cuenta en el año
7.	Housing loan: Si tiene seguro de hogar o no
8.	Persona loan: Si tiene prestamos o no
9.	Contact: Tipo de contacto del cliente (celular o teléfono)
10.	Last Contact Day: Ultimo día de contacto con el cliente en el mes
11.	Last Contact Month: Ultimo mes de contacto con el cliente en el año
12.	Last Contact Duration: Duración del último contacto con el cliente medido en segundos
13.	Campaign: Cantidad de contactos al cliente durante esta campaña, incluye el último contacto.
14.	Pdays: Cantidad de dias que pasaron del último contacto con el cliente de una campaña anterior. -1 significa que no hubo contacto previo
15.	Previous: Cantidad de contactos previos a esta campaña para cada cliente
16.	Poutcome: Performance de la campaña de marketing anterior para este cliente
17.	Subscription: Si el cliente accede a la campaña (1) o no (0). **Variable a predecir.**
### clusterai_bruno_acosta_transformaciones.ipynb
En este archivo se encuentran todas las funciones que transforman el data set para que pueda ser procesado por los modelos de machine learning.
Se importan por medio de la libreria ipyn.
### clusterai_bruno_acosta_eda.ipynb
En este archivo se encuentra el análisis exploratorio de los datos.
### clusterai_bruno_acosta_transformations.ipynb
En este archivo se encuentra el entrenamiento y análisis de varios modelos de machine learning, seguido por una reducción de dimensionalidad y nuevo entrenamiento de modelo.
### clusterai_reporte_acosta.pdf
Este es el reporte final donde se detallan los algoritmos usados y los resultados obtenidos.