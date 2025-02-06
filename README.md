# Selección de características 

En este ejercicio seleccionaré las diferentes variables de una base de datos de vinos para poder determinar la calidad de algún vino, para esto hare uso de librerías especializadas. Se realizará un proceso de selección de características hacia adelante y de eliminación hacia atrás en una regresión lineal múltiple.

Los datos originales se obtuvieron de UCI Machine Learning Repository:   
https://archive.ics.uci.edu/dataset/186/wine+quality

Y se reportaron originalmente en "Modeling wine preferences by data mining from physicochemical properties" en la revista "Decision Support Systems":  
https://www.sciencedirect.com/science/article/abs/pii/S0167923609001377?via%3Dihub

Las ligas se encuentran si quieres verificar las bases de datos, si deseas probar la funcionalidad del código usa la base de datos que se proporciona como descargable ya que los datos fueron modificados para trabajar con ellos de manera más sencilla.

La base de datos cuenta con la siguiente información:  
  
* “acidezFija”. La acidez fija del vino, medida en gramos de ácido tartárico por decímetro
cúbico.  
* “acidezVolatil”. La acidez volátil del vino, medida en gramos de ácido acético por
decímetro cúbico.  
* “acidoCitrico”. Gramos de tácito cítrico por decímetro cúbico.  
* “azucarResidual”. Gramos de azúcar por decímetro cúbico.  
* “cloruros”. Gramos de cloruro de sodio por decímetro cúbico.  
* “dioxidoAzufreLibre”. Miligramos de dióxido de azufre libre por decímetro cúbico.  
* “dioxidoAzufreTotal”. Miligramos de dióxido de azufre total por decímetro cúbico.  
* “densidad”. Medida en gramos por centímetro cúbico.  
* “pH”. Valor del vino en la escala de pH.  
* “sulfatos”. Gramos de sulfato de potasio por decímetro cúbico.  
* “alcohol”. volumen percentil de alcohol en el vino.  
* “calidad”. Mediana de la calidad otorgada por al menos tres catadores, en escala del 0
(muy malo) al 10 (excelente)  
