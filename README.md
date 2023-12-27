# **Final Group Project: Bank Subscription**
____
__National Technological University, Buenos Aires__\
__Industrial Engineering__\
__Data Science - Course I5521__
____
Students: Acosta, Bruno and Bartolomeo, Agustin

## clusterai2023
In this repository, the practical work carried out for the 2023 data science class is published.

A bank wants to predict how many clients will subscribe to a marketing campaign. To achieve this, they share a dataset with a client portfolio of 45,211 individuals with 17 variables showing some characteristics of clients in the bank.

A deep study of the dataset will be conducted to understand the data being worked on and the trends in the data, followed by a transformation of the variables. With the transformed dataset, several machine learning models will be trained with the aim of finding the one that predicts whether a client will subscribe or not in the best possible way.

## File Description:
### bank_subscription (1).csv
This CSV file contains the data used in this project. It has the following columns:

1. Age: Client's age
2. Job: Client's job type
3. Martial Status: Marital status
4. Education: Client's highest education level
5. Credit: Whether the client has credit debt or not
6. Balance (euros): Average account balance in the year
7. Housing loan: Whether the client has home insurance or not
8. Persona loan: Whether the client has loans or not
9. Contact: Client's contact type (cellular or telephone)
10. Last Contact Day: Last contact day with the client in the month
11. Last Contact Month: Last contact month with the client in the year
12. Last Contact Duration: Duration of the last contact with the client measured in seconds
13. Campaign: Number of contacts to the client during this campaign, including the last contact.
14. Pdays: Number of days passed since the last contact with the client from a previous campaign. -1 means no previous contact
15. Previous: Number of previous contacts before this campaign for each client
16. Poutcome: Performance of the previous marketing campaign for this client
17. Subscription: Whether the client agrees to the campaign (1) or not (0). **Variable to predict.**
### clusterai_bruno_acosta_transformations.ipynb
This file contains all the functions that transform the dataset so that it can be processed by machine learning models. They are imported using the ipyn library.

### clusterai_bruno_acosta_eda.ipynb
This file contains the exploratory data analysis.

### clusterai_bruno_acosta_transformations.ipynb
This file contains the training and analysis of various machine learning models, followed by dimensionality reduction and new model training.

### clusterai_reporte_acosta.pdf
This is the final report detailing the algorithms used and the results obtained.

____
# _Spanish_


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
