[![Open in MATLAB Online]]
# Proyecto Final: Sistema auditivo

## Información de los estudiantes
Fonseca Diaz Iván De Jesús \[22212383]; l22212383@tectijuana.edu.mx

Rafael Herrera Aguilar \[22212258]; l22212258@tectijuana.edu.mx

Modelado de Sistemas Fisiológicos

Ingeniería Biomédica

## Docente
Dr. Paul Antonio Valle Trujillo; paul.valle@tectijuana.edu.mx

Departamento de Ingeniería Eléctrica y Electrónica, Tecnológico Nacional de México/IT Tijuana, Blvd. Alberto Limón Padilla s/n, Tijuana, C.P. 22454, B.C., México.

## Descripción de la asignatura

El modelizado de sistemas fisiológicos es una herramienta importante en Ingeniería Biomédica, permite comprender el funcionamiento del cuerpo humano, así como diseñar y evaluar terapias y dispositivos médicos; se define como el proceso de formular modelos matemáticos o computacionales que representan el comportamiento y la interacción de los sistemas biológicos y fisiológicos. Esta asignatura pretende aportar al perfil del Ingeniero Biomédico la capacidad de realizar investigación científica en el área de Biología de Sistemas con la finalidad de dirigir y participar en equipos de trabajo interdisciplinarios en contextos nacionales e internacionales, así como de proporcionar soluciones informáticas para resolver problemas en el campo de la Ingeniería Biomédica con ética profesional; lo anterior al proporcionar al estudiante bases sólidas para modelizar sistemas y diseñar controladores para la solución de problemas en las áreas de atención médica y del sector industrial médico. La construcción de analogías entre circuitos eléctricos y sistemas fisiológicos para la formulación de modelos matemáticos y el diseño de controladores mediante la experimentación in silico brindan herramientas de gran aplicación en el quehacer profesional del Ingeniero Biomédico.

La asignatura de Modelado de Sistemas Fisiológicos forma parte del plan de estudios de la carrera en Ingeniería Biomédica con la siguiente competencia general del curso: Utiliza las propiedades de los circuitos RLC para describir la dinámica de sistemas fisiológicos, obtener modelos matemáticos y aplicar el control clásico, esto con el objetivo de integrar los principios de la Ingeniería de Control, la Electrónica Analógica y las Ciencias de la Computación con la Anatomía y Fisiología del cuerpo humano para proporcionar descripciones cuantitativas y cualitativas de sistemas fisiológicos complejos con el objetivo de modelizar, analizar, controlar, ilustrar y predecir su dinámica tanto en el corto como en el largo plazo.

## Objetivos

1. Construir el circuito RLC que describe al sistema.
2. Calcular la función de transferencia.
3. Determinar el modelo de ecuaciones integro-diferenciales.
4. Calcular el error en estado estacionario y la estabilidad en lazo abierto.
5. Emular y simular la respuesta del circuito en Simulink/Simscape a la señal sinusoidal.
6. Sintonizar las ganancias de un controlador PID para eliminar el error entre la entrada y la salida del sistema control-caso.

## Descripción detallada del sistema

El sistema auditivo inicia por el oído externo donde entra las ondas sonoras, pasando por el conducto auditivo hasta llegar al tímpano, el cual es una membrana tensa que cuando llegan las ondas sonoras vibra transfiriendo esa vibración hacia los huesecillos. El oído medio empieza a partir del lado contrario del tímpano respecto al oído externo, hay un espacio lleno de aire en el que se encuentran tres huesos pequeños conocidos como huesecillos, funcionando para transmitir las vibraciones desde las vibraciones hasta el oído interno. 

1. La baja impedancia acústica que se presenta en el oído externo por el aire que hay o alguna pequeña obstrucción como la cera que se encuentra en el oído se puede representar como una resistencia pequeña R1. 
2. La elasticidad del tímpano que permite la vibración y transmisión de las ondas sonoras se puede representar como un capacitor C1. 
3. La impedancia que se presenta en el espacio de aire en el oído medio se puede modelar con una resistencia más o menos de la misma cantidad R2. 
4. La masa de los huesecillos dando una oposición inerte del movimiento por la vibración se modela con un inductor L. 
5. La elasticidad de los tendones de los huesecillos para su vibración, se modela con un capacitor C2. 

La señal de entrada Ve(t) que se tomó para el circuito RLC es una señal sinusoidal, debido a que, las ondas sonoras se constituyen por señales 
sinusoidales, manejándose por las mismas propiedades siendo la amplitud y la frecuencia. Esta señal sinusoidal representa la onda sonora originada por la voz humana y Vo(t) siendo la señal captada después de pasar por todo el sistema auditivo hasta el oído medio. 

La enfermedad modelada es la otitis media, la cual es una infección de oído, provocando que se encuentre líquido en el espacio donde se encuentran los huesillos, evitando la vibración del tímpano y por lo tanto menor captación de ruido. La enfermedad se modela aumentando la resistencia R2 debido a la obstrucción por el líquido generado por la infección dentro del oído medio. 

Palabras clave: Circuito RLC; Controlador PI; Sistema auditivo; Modelo matemático; Simulaciones numéricas.

## Lista de archivos incluidos en el repositorio
1. Cuaderno computacional de MATLAB [.mlx].
2. Modelo de Simulink [.slx].
3. Imagen con los parámetros del controlador.
4. Imágenes de las simulaciones [.pdf y .png].
5. Evidencia del análisis matemático: función de transferencia, modelo de ecuaciones integro-diferenciales, error en estado estacionario y estabilidad en lazo abierto.

## Referencias
\[1] P. A. Valle, Syllabus para Modelado de Sistemas Fisiológicos, Tecnológico Nacional de México / Instituto Tecnológico de Tijuana, Tijuana, B.C., México, 2025. Permalink: https://biomath.xyz/course/

\[2] M. C. Khoo, Physiological Control Systems Analysis Simulation, and Estimation, 2nd ed. Piscataway, New Jersey, USA: IEEE Press, 2018, Section 4, Page 93.

\[3] N. S. Nise, Control Systems Engineering, 8th ed. Hoboken, New Jersey, USA: John Wiley & Sons, 2020.

\[4] T. Kind, T. J. Faes, J. W. Lankhaar, A. Vonk-Noordegraaf & M. Verhaegen, "Estimation of three-and four-element Windkessel parameters using subspace model identification", IEEE Transactions on Biomedical Engineering, vol. 57, issue 7, pp. 1531-1538, Jul 2010. https://doi.org/10.1109/TBME.2010.2041351
