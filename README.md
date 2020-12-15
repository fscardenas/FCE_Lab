# Laboratorio-1-FCE_Lab_4872
Fundamentos de Circuitos Eléctricos Laboratorio "Informes"

Integrantes: Cárdenas Freddy  &  Vásquez Juan 
UNIVERSIDAD DE LAS FUERZAS ARMADAS-ESPE

DEPARTAMENTO DE ELÉCTRICA Y ELECTRÓNICA

CARRERA DE INGENIERÍA ELECTRÓNICA Y AUTOMATIZACIÓN

PERIODO         	                :       Noviembre 2020 – Abril 2021

ASIGNATURA     	                :        Fundamentos de Circuitos Eléctricos 

TEMA	                            : 	Informe de laboratorios

NOMBRES       	          	:           Freddy Stalin Cárdenas Carrera 
					Juan Sebastián Vásquez Hurtado 

NIVEL-PARALELO           :            Segundo

DOCENTE       	 	:           Ing. Darwin Alulema MSc.

FECHA DE ENTREGA       :       	15/12/2020

NRC 				:	4872
 
SANGOLQUI - ECUADOR

2020



1.	Tema: Leyes De Kirchhoff
2.	Objetivos

1.1 Objetivo General

●	Analizar y comprender mediante la simulación la Ley de Kirchhoff de Voltajes y la Ley de Kirchhoff de Corrientes.
1.2 Objetivos Específicos

●	Comparar datos obtenidos en la simulación y datos obtenidos mediante cálculos medidos y calculados.

●	Demostrar la aplicación de las leyes Kirchhoff en el circuito simulaciones y recopilación de datos.
3.	Marco Teórico 

![](https://github.com/JuanSVasquezH/Imagen-ley1kirchhoff/blob/master/x/lk.png)
 
 




4.	Diagramas 
 
 
Figura N.º 1: Diagrama de implementación del circuito eléctrico 

El presente diagrama se lo realizó en las prácticas a partir de previos conocimientos sobre las leyes de Kirchhoff en cuanto a voltajes y corrientes, el diagrama está compuesto de varios componentes circuitillos de los cuales tenemos un circuito con positivo y negativo la cual representa una fuente de corriente en D.C, la cual suministra la energía al circuito, también existen líneas en forma de sic sac que se le conoce como resistencias la cual impiden el paso de la corriente. 

5.	Lista De Componentes 

Cantidad	Material o Equipo	Descripción

1	Fuente de Voltaje de C.D.	     Fuentes de corriente directa (generador de corriente). Las llamadas fuentes de alimentación son un dispositivo que transforma la tensión alterna de la red de suministro, en varias tensiones, que son continuas, y alimentan a los distintos circuitos del aparato electrónico al que se conecta.

2	Multímetros Digitales	Es una herramienta de demostración manipulada para medir dos o más valores eléctricos, principalmente tensión (voltios), corriente (amperios) y resistencia (ohmios).

1	Resistor de 1 kΩ	       Son unos elementos eléctricos cuya función es impedir el paso de la corriente eléctrica a través de ellas.
        La resistencia óhmica de una resistencia se mide en ohmios, así como dos de sus múltiplos: el Kilo-Ohmio (1KΩ) y el Mega-Ohmio (1MΩ=106Ω). El valor resistivo puede ser fijo o variable.

2	Resistores de 2.2 kΩ	

1	Resistor de 1.8 kΩ	

1	Resistor de 3.9 kΩ	

1	Protoboard	       Es una placa de pruebas para electrónica que contiene numerosos orificios en los que es posible insertar cables y otros elementos electrónicos para montar circuitos provisionales o de prueba.

	
  5.1 	Explicación
	Para la elaboración del circuito a implementar  nos ayudamos de la plataforma 	de CADCLAB, ya que es un simulador donde nos facilita la toma de datos de cada 	elemento que complementa el circuito eléctrico, en sí es una plataforma fácil de usar ya 	que una vez cerrado el circuito nos refleja los datos de corriente que pasa por cada rama 	al igual la utilización de los diferentes instrumentos el único inconveniente es que al 	modificar el valor de cada resistencia no es un valor exacto sino un valor aproximado 	el cual se van a simular por ende va a existir un margen de error. 

6.	Procedimiento 

1.	Ingresar en nuestro navegador el siguiente Simulador: https://dcaclab.com/es/lab 

2.	Pulsar el botón iniciar y llenar los espacios en blanco e sesión con cualquier correo electrónico de su preferencia 
  

Figura N.º 2: Inicio de sesión DCACLAB

3.	Una vez ya iniciado sesión, elegir cualquier elemento de la barra de herramientas, es decir con el cual vayamos a trabajar y unir los elementos como muestra en la figura.
  

Figura N.º 3: Implementación de componentes para el circuito a implementar

4.	Luego dar clic en cada elemento para cambiar su valor, el cual dará un valor aproximado al valor real de cada elemento, repetimos este proceso para cada elemento del circuito a implementar.
  

Figura N.º 4: Configuración de cada elemento del circuito

5.	Ya terminado de cambiar todos los elementos al valor que se desee medir, cerramos el circuito.
  

Figura N.ª 5: Circuito Implementado 

6.	Con la ayuda de un multímetro, empezamos a unir los terminales en cada elemento, para la recopilación de datos.
   

Figura N.º 6: Toma de datos mediante el Multímetro 

7.	Descripción De Prerrequisitos Y Configuración 

●		Para la elaboración del presente circuito, tenemos la opción de poder desarrollar las simulaciones en dos programas que son de fácil uso y comprensión para la medición de datos. Uno de ellos es el simulador tinkercad y el otro dcaclab, Sus configuraciones son de fácil acceso para la manipulación de los distintos componentes circuitales.

●		Es importante haber hecho una simulación previa en ambos simuladores para conocer cuál de ellos se acopla a las necesidades necesarias del circuito que se requiera hacer una simulación, a su vez conoces qué características o elementos que dispone cada simulador ya antes mencionado.

8.	Tabulación de Datos



Tabla 1: Resultados obtenidos de voltaje y corriente en cada elemento del circuito.



Tabla 2: Verificación de la LVK



Tabla 3: Verificación la LCK

9.	Cálculos 	

Obtención de Datos
 
- Calculo de voltaje mediante Ley de Ohm
 
 
- Calculo de corriente de cada elemento 
 
 
- Calculo de margen de Error de Voltaje 
 
 
- Calculo de margen de Error de Corriente 
 


10.	Aportaciones 

●		Se comprueba mediante las fórmulas ya conocidas V=IR (Ley de Ohm), que ambas leyes tanto de corriente y voltajes en un circuito cerrado son cero. Es decir que el uso adecuado de las fórmulas y el planteamiento adecuado de las corrientes al usar el método de nodos nos facilita mejor la comprensión del circuito y las leyes en sí. Esto ocurre igual en la sumatoria de los voltajes del circuito.  

●		Tomemos en cuenta que existe una cantidad de carga en el circuito ya que Q=i*t, es decir son fórmulas ligadas a la corriente ya que si tendríamos el tiempo en el cual tarda en pasar la corriente en todo el circuito tendríamos la carga total del circuito o a su vez de cada elemento circuital. 

11.	Conclusiones 

●		Debemos tomar en cuenta que siempre va a existir un margen de error ya que en el simulador propuesto nos da un valor aproximado al real entonces sus dados van a variar.

●		Mientras más alto sea el valor de la resistencia menos paso de corriente va a existir en dicho elemento, al momento de realizar la simulación. 

●		Debemos tomar en cuenta el sentido ya sea de corriente o voltaje, en el cual vamos a calcular los distintos datos ya que estos no servirán para comprobar las dos leyes que se están estudiando en esta presente práctica.  


12.	Bibliografía 

●		Wikipedia (2020), Leyes de Kirchhoff, recuperado de : https://es.wikipedia.org/wiki/Leyes_de_Kirchhoff#:~:text=Las%20leyes%20de%20Kirchhoff%E2%80%8B,en%201846%20por%20Gustav%20Kirchhoff.&text=Estas%20leyes%20son%20utilizadas%20para,punto%20de%20un%20circuito%20el%C3%A9ctrico. 

●		McAllister. W (2017), Leyes de Kirchhoff, recuperado de :https://es.khanacademy.org/science/physics/circuits-topic/circuits-resistance/a/ee-kirchhoffs-laws   

●	SN (2018). Leyes de Kirchhoff , recuperado de: https://www.ecured.cu/Leyes_de_Kirchhoff 

●	Wikipedia.com (2020), Carga Electrica, recuperado de: https://es.wikipedia.org/wiki/Carga_el%C3%A9ctrica#:~:text=En%20concordancia%20con%20los%20resultados,un%20sistema%20aislado%20se%20conserva. 


13.	Anexo
	
  Link diagrama del circuito:
	https://lucid.app/lucidchart/invitations/accept/d9bc4cff-021a-4851-98c8-172a46bf89a8

-	Simulador DCACLab
 

Figura. 1 Circuito a implementar DCACLAB
 

Figura. 2 Simulación de corriente R1
 

Figura. 3 Corriente Fuente
 

Figura. 4 Circuito a implementar Tinkercad

 
Figura. 5 Simulación de voltaje R1
