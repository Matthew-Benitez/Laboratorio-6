# Laboratorio 6
1. OBJETIVOS
- Objetivo General:
   
   - Utilizar el teorema de Thévenin para utilizarlo prácticamente dentro de distintios circuitos eléctricos.
   
- Objetivos Específicos:
 
   - Determinar la resistencia equivalente dentro del circuito.
   - Determinar el voltaje que circula en una resistencia para obtener la fuente de voltaje de Thévenin.
   - Obtener el circuito simplificado de Thévenin y comprobar que la corriente y el voltaje que pasan por la resistencia son las mismas.
   
2. MARCO TEÓRICO
   
   ![image](https://user-images.githubusercontent.com/76133212/108288009-ccfb9580-7159-11eb-82cf-7d5c1e920320.png)

   
4. DIAGRAMAS
   - Modelo Del Circuito
   
   ![image](https://user-images.githubusercontent.com/75439689/108273068-155a8980-7141-11eb-9c75-171ccb45f0cc.png)

   *Figura 3.1*
   
   - Materiales Del Circuito
   
   ![image](https://user-images.githubusercontent.com/75439689/108273129-273c2c80-7141-11eb-97c2-a097f8bb2f31.png)
   
   *Figura 3.2*
   
   - Circuito Armado

   ![image](https://user-images.githubusercontent.com/75439689/108273213-43d86480-7141-11eb-91cb-2f60aebcf6ab.png)

   *Figura 3.3*
   
   - Mediciones de Voltaje y Corriente a través de R5
   
   ![image](https://user-images.githubusercontent.com/75439689/108273360-73876c80-7141-11eb-965b-dd38a73e533a.png)
   
   *Figura 3.4*
   
   - Mediciones de Resistencia y Voltaje de Thévenin
   
   ![image](https://user-images.githubusercontent.com/75439689/108273378-797d4d80-7141-11eb-89ff-b5e4d3256676.png)
   ![image](https://user-images.githubusercontent.com/75439689/108273538-ae89a000-7141-11eb-88a3-030de9ffd77a.png)
   
   *Figura 3.5 y 3.6*
   
   - Circuito de Thévenin
   
   ![image](https://user-images.githubusercontent.com/75439689/108273617-c6612400-7141-11eb-975e-95599b706744.png)
   ![image](https://user-images.githubusercontent.com/75439689/108273631-cb25d800-7141-11eb-8bf3-0eeae2a5db22.png)
   
   *Figura 3.7 y 3.8*
   
4. LISTA DE COMPONENTES
   
   ![image](https://user-images.githubusercontent.com/75439689/108274097-7040b080-7142-11eb-98c0-d9c431c00f0b.png)
   
   *Figura 4.1*

5. EXPLICACIÓN

  5.1. Procedimiento

  5.2. Responda las siguientes preguntas:
    
   - ¿Cuántas divisiones por cuadro abarca la amplitud pico de la señal de salida?
    
     La amplitud pico de la señal de salida abarca unos 2 y ¼ de cuadro.
    
   - ¿En qué valor está posicionada la perilla VOLTS/DIV?

     Está posicionado en 3
    
   - ¿Cuántas divisiones por cuadro abarca un ciclo completo de la señal de salida?

     Horizontalmente abarca 4 cuadros, y verticalmente abarca 4 y medio de cuadros.

   - ¿En qué valor está posicionada la perilla TIME/DIV?

     Está posicionado en 0.1ms
  
  5.3. ¿Cuál es la amplitud de voltaje y el periodo de la señal que aparece en la pantalla del osciloscopio?
    
   - Amplitud de voltaje: 6.85(V)
    
   - Periodo: 0.0004(s)
  
  5.4. Determine la frecuencia natural (Hz) y la frecuencia angular (rad/s) de la señal de salida.
   
   - f: 2500(Hz)
    
   - ω: 15707.96(rad/s)
  
  5.5. Con el multímetro digital mida el voltaje de salida en RL:
  
   - 4.823 (V)
  
  5.6. Compare el voltaje medido en el punto 7.5.5. y el obtenido en el punto 7.5.7.
  
  ¿Coinciden? 
  
  No
  
  ¿Por qué?
  
  Debido a que el voltaje de salida, el cual es calculado por el multímetro es el Voltaje RMS (es un voltaje equivalente que representa el valor de voltaje DC que producirá el mismo efecto de calentamiento o disipación de potencia en el circuito, como esta tensión de CA.) es diferente al voltaje de amplitud de la fuente de C.A. en el resistor. El voltaje RMS representa el 0.707 de la amplitud de voltaje.

6. CONCLUSIONES

   - Aplicar el Teorema de Thévenin resulta práctico al momento de analizar un circuito complejo con un número elevado de elementos, ya que este teorema permite obtener un circuito equivalente al original pero mucho más sencillo debido a que este sólo consta de la conexión en serie de la fuente de voltaje (VTH), la resistencia de Thévenin (RTH) y la resistencia o la carga la cuál se desea estudiar.
   - La precisión del Teorema de Thévenin es alta, ya que en el cálculo del error se obtuvo un porcentaje de 1.03% en las mediciones y un 0.01% en los cálculos (comparando entre los valores del circuito orginial y el circuito equivalente de Thévenin). Lo cual indica que emplear este Teorema resulta útil y práctico.
   - El concepto que maneja el Teorema de Thévenin (el de obtener un circuito equivalente al original pero con una mínima cantidad de elementos) se puede dar en la construcción de diversos aparatos o dispositivos electrónicos con el fin de abaratar costos en la producción de dichos aparatos ya que contendrían menos elementos.
 
 
7. BIBLIOGRAFÍA

   - Floyd, T. L. (2007). Principios de circuitos eléctricos (Octava ed.).
