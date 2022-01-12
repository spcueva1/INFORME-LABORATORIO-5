# INFORME-LABORATORIO-5

# 1) OBJETIVOS

 Objetivo general:

Comprobar experimentalmente el Teorema de Thévenin en un circuito resistivo, mediante calculos escritos y utilizando simuladores.

Objetivos especificos:

- Identificar la resisten L del circuito, para realizar el análisis correcto del Teorema de Thévenin.

- Calcular el voltaje de Thévenin y la resistencia equivalente de Thévenin para lograr obtener valores precisos. 

- Diseñar en algún simulador facilitado por el docente el esquema propuesto y tomar los valores correspondientes segun lo indicado.



# 2) Marco teorico

Teorema de Thévenin.

Los valores del voltaje y de la resistencia equivalentes dependen de los valores del circuito original. Cualquier circuito resistivo puede ser simplificado, pese a su complejidad, con respecto a dos terminales de salida. 

Un circuito eléctrico puede representarse con un circuito dual o equivalente, representado por una sola fuente de voltaje en serie con  una resistencia. El valor de la fuente de voltaje se conoce como el “voltaje de Thévenin” y la resistencia en serie como “resistencia de Thévenin”.

El voltaje de Thévenin (VTH) es el voltaje en circuito abierto entre las terminales del circuito para el cual se requiere el equivalente de Thévenin.

La resistencia de Thévenin (RTH) es la resistencia equivalente vista de la terminal del circuito para el equivalente de Thévenin, con las fuentes de alimentación en cero.

Cualquier componente conectado entre estas dos terminales “ve” efectivamente a VTH en serie con RTH. Como lo define el teorema de Thevenin.

Aunque un circuito equivalente de Thevenin no es el mismo que su circuito original, actúa igual en función del voltaje y de la corriente de salida.

![](MT 1)

En seguida se coloca el equivalente de Thevenin de dicho circuito en una caja idéntica con, de nuevo, solamente las terminales de salida expuestas. Se conectan resistores de carga idénticos entre las terminales de salida de cada caja. A continuación se conecta un voltímetro y un amperímetro para medir el voltaje y la corriente con cada una de las cargas como indica la figura. Los valores medidos serán idénticos (omitiendo las variaciones de tolerancia), y no se podrá determinar cuál caja contiene el circuito original y cuál
contiene el equivalente de Thevenin. Es decir, en función de las observaciones basadas en cualesquiera mediciones eléctricas, ambos circuitos parecen ser el mismo circuito. Esta condición en ocasiones se conoce como equivalencia terminal porque ambos circuitos lucen igual desde el “punto de vista” de las dos terminales de salida.

Para encontrar el equivalente de Thevenin de cualquier circuito, se determina el voltaje equivalente, VTH, y la resistencia equivalente, RTH, vistos desde las terminales de salida. 

![](MT 2)

Mapa conceptual


# 3) Explicacion de procedimiento

Primero plasmamos en el simulador el ejercicio propueto en la guia. De esta maner analizamos lo pedido y comenzamos a resolver.

Para las fuetes de voltaje hacemos un circuto cerrado es decir eliminamos esa fuente.

Para esto debemos remplazar primero la de 20 vol y despues remplazamos la segunda fuente de 12 vol y asi al final de los resultados realizamos una suma algebraica para obtener la intensidad que sircula por esa parte del circuito.

Para calcular las resistencias equivalentes dependiendo el caso utilizamos ley de ohm, circuitos serie paralelo y mas.

![](https://github.com/spcueva1/Informe-Laboratorio-4/blob/6272e6211d4eee6435ceedde3cd225115f612a47/Info%204/Imagen2.44.png)


 Cálculos:
 
Usando la fuente de 20v, es decir remplazando por un circuito cerrado a mi funete de voltaje de 12v.

Req1=1/(1/0,82+1/2,2)=0,597kΩ

RT=Req2=1+0,597=1,597Ω

It=20/1,597=12,523mA

Divisor de corriente.

Ix=(2,2/(2,2+0,82))*12,523= 9,12mA

VA=9,122*0,82=7,48 V

Usando la fuente de 12v, es decir remplazando por un circuito cerrado a mi funete de voltaje de 20v.

Req1=1/(1/1k+1/2,2k)=687,5Ω

Req2=820+687,5=1507,5Ω

Ieq2=12/1507,5=7,960*10^(-3) A

VA=820*7,96*10^(-3)=6,5272 V

Req3=1/(1/1507,5+1/470)=358,29Ω

It=12/358,29=0,03349A

Divisor de corriente.

Ix=(47/(1507,5+47))*0,03349= 7,96mA




![](https://github.com/spcueva1/Informe-Laboratorio-4/blob/475898bd59676e59ec1f1bd9aa3a773a2fe28b23/info%204.1/inf%204%20calculo.png)


Simulacion en Tinkercard:

Imagen 1 simulador

![](https://github.com/spcueva1/Informe-Laboratorio-4/blob/5bfd649ec4a609af45a37ce7dc1c57f6e1faa201/info%204.1/Simula%20ima%201.jpg)

Imagen 2 simulador

![](https://github.com/spcueva1/Informe-Laboratorio-4/blob/5bfd649ec4a609af45a37ce7dc1c57f6e1faa201/info%204.1/Simula%20ima%202.jpg)

Imagen 3 simulador

![](https://github.com/spcueva1/Informe-Laboratorio-4/blob/5bfd649ec4a609af45a37ce7dc1c57f6e1faa201/info%204.1/Simula%20ima%203.jpg)


# 4) Respuesta a interrogantes y cálculo de error.

Resultados:

![](https://github.com/spcueva1/Informe-Laboratorio-4/blob/9c9ec0d6893ae6cfca7a6437609089c43786a97b/respuesta%20inf%204%20(2).png)


Se logro comprabar que los resutlados del  simulado es igual a los valores que encontramos dentro de el analisis por superposición, los cuales fueron evaluados por los conocimientos adquiridos, y por lo tanto obtuvimos lo propuesto en el ejercicio.

El calculo de error, si se lo evalua, este tendra un resultado de +-0,025% de error ya que corresponde a los valores exactos, tanto medidos, simulados y calculados.

# 5) Video

https://youtu.be/FNPo62Q5EE4


# 6) Conclusiones.

- Se ha diseñado el ejercicio propuesto por el docente, donde se obtuvieron los datos correctos en la aplicación de la Ley de Thévenin.


# 7) Bibliografia

- M. (2021b, abril 2). Teorema de superposición. MiElectrónicaFácil.com. Recuperado 27 de diciembre de 2021, de https://mielectronicafacil.com/analisis-de-circuitos/teorema-de-superposición/#pasos-del-teorema-de-superposición.

- Salazar, A. (2012). 3. Análisis de superposición 3.1. 35–62. http://wwwprof.uniandes.edu.co/~ant-sala/cursos/FDC/Contenidos/03_superposición.pdf



