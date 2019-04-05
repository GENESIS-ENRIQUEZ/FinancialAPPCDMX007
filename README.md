# Aplicación financiera

## Preámbulo

El banco más importante del país ha lanzado una nueva aplicación móvil al
mercado para que sus usuarios puedan visualizar sus gastos mensuales y fomentar
el ahorro. Luego de tener algunos meses en el mercado, el
equipo detrás de este nuevo producto ha decidido contratar a una
agencia/consultora de UX que los ayude a definir la dirección y evolución del
producto. Tú has sido elegida como la consultora líder de UX y se te ha asignado el proyecto para hacer un diagnóstico, evaluar el desempeño de la aplicación y proponer los cambios necesarios para optimizar el producto.


## Introducción

### Contexto

Durante la primera semana de entendimiento de los requerimientos, el Product
Manager del equipo les brinda el contexto:

>“Todo empezó hace un año cuando vimos que en EEUU y Europa estaban saliendo
  nuevas aplicaciones financieras que nos llamaron la atención. Unas se enfocan
  en darle visibilidad a sus usuarios sobre los gastos, otras en facilitar pagos
  a terceros y otras a fomentar el ahorro. Inspirados en un par de ellas,
  decidimos lanzar una nueva aplicación. Decidimos que era mejor crear un
  producto desde cero - en lugar de modificar la aplicación actual de banca
  móvil - para poder desarrollarla con un equipo totalmente nuevo, en el
  laboratorio de innovación, bajo prácticas ágiles. Sabemos que no es ideal que
  nuestros usuarios tengan que usar dos aplicaciones, pero desarrollar con un
  equipo nuevo que corra ágil nos da mayor libertad.

> Empezamos entrevistando a algunos usuarios y revisando los resultados de un
  estudio de mercado que nos proporcionó el área de marketing. Eso nos dió una
  idea inicial de qué funcionalidades son más relevantes aquí en nuestro
  mercado. Con base en esos resultados, creamos nuestros primeros user personas
  una primaria y una secundaria ( creemos que estas personas no son las que
  nosotros pensábamos inicialmente), y diseñamos y desarrollamos un ‘Producto
  mínimo viable’ (MVP) en 2 meses en iOS. Ese MVP lo hemos lanzado y tenemos
  alrededor de 6 meses de data. Hoy estamos en el proceso de entender los
  resultados iniciales y de sacar una segunda iteración del producto. Y para eso
  las hemos contratado. Toda la documentación de este producto la tenemos en una
  carpeta de [Google Drive](https://drive.google.com/drive/u/0/folders/1NWf4701uKDsCK0eLNI8RXEocrI1g1zqd). Les doy acceso.

> Necesitamos traer una propuesta del nuevo diseño en dos semanas porque tenemos
  que presentarla a nuestro Gerente General en la reunión trimestral. Es
  importante que cualquier cosa que presentemos ya incorpore feedback de testing
  con usuarios. El Gerente General, animado por el crecimiento del número de
  descargas que ha tenido el app, quiere duplicar el presupuesto de Facebook
  Ads… Yo no estoy tan seguro; quisiera que como parte de su trabajo estas
  próximas dos semanas, entendamos ese punto también.”

#  Objetivos iniciales del proyecto:

Hacer un diagnóstico, evaluar el desempeño de la aplicación y proponer los cambios necesarios para optimizar el producto.

# Primer Sprint.

¿Qué herramientas utilice?

1. Sesión de Q&A con Project Manager "Tus finanzas"
![Sesión de preguntas y respuestas](/imagenesRM/insightsPM.png)

2. Pruebas de usabilidad.

Se realizaron 33 pruebas de usabilidad de las cuales:

2.1 Sexo
* 15 F
* 18 M

2.2 Sistema Operativo de dispositivos
* 21 Android
* 9 iOS

2.3 Ocupación
* 9 estudiantes
* 24 empleados

15 de los usuari@s entrevistados ya han tenido interacción con otras aplicaciones bancarias.

Algunos de los insights de estas pruebas:
![Pruebas de usabiliad](/imagenesRM/insightsU.png)

3. Análisis de Funnel Analytics de los primeros 6 meses del MVP

El cliente me entregó un archivo con data de los últimos seis meses. De este archivo se obtuvo el siguiente análisis:

- El call to action en landing page e impresiones en facebook, no esta siendo efectivo. El usuario no está dirigiéndose a app store para descargar la aplicación.

![Impresiones FB & Landing Page](/imagenesRM/impresionesFBLP.png)

- La aplicación no esta cumpliendo su principal funcionalidad. Los usuarios están gastando más en comparación de lo que se está ahorrando. Mi hipotesis es que los usuarios no están capacitados o familiarizados con el hábito del ahorro.

![Gastos vs ahorros](/imagenesRM/ahorrovsgasto.png)

- Hay un porcentaje alto de usuarios con dispositivos android, que llegan a landing page pero al visualizar que esta no se encuentra disponible para su sistema operativo, se van.

![Android vs iOS](/imagenesRM/androidvsios.png)

- Bounce rate alto. Los usuarios entran a landig page y salen rapidamente sin descargar la aplicación.

- Mes con mes, ha aumentado "active devices". Los usuarios si están usando la aplicación pero no están llegando nuevos usuarios.

![Active last 30 days](/imagenesRM/activelast30days.png)

4. Iteración User persona

Con base en las encuestas de usabiliad, se realizó la siguientes iteración de user persona.

![User Persona](/imagenesRM/userpersona.png)

5. Benchmark aplicaciones financieras a nivel nacional y mundial

![Benchmark](/imagenesRM/Benchmark.png)

6. Investigación "consumo de medios y dispositivos 2018, corte financiero"

![Consumo de medios y dispositivos](/imagenesRM/estudioFinanciero.png)

7. Análisis Heurísticas de usabilidad

Se realizó un análisis de las heurísticas de usabilidad. Esto con la finalidad de validar qué tan fácil podría ser utilizar la aplicación por primera vez. También, funciona para "predecir" los errores que el / la usuari@ podrían encontrarse.

Si quieres saber más acerca de esta herramienta, da click [aqií](https://blog.interactius.com/metodolog%C3%ADas-de-ux-evaluaci%C3%B3n-heur%C3%ADstica-parte-i-b5d02b566987).

Algunos de los errores que se encontraron, fueron los siguientes:

![Heurísticas de usabilidad](/imagenesRM/heuristicas.png)

* Pain & Gains

![Pain & Gains](/imagenesRM/paingain.png)

8. Insights primer sprint



- Dependiendo de la edad, cambian las motivaciones de ahorro
- Concepto de seguridad se agudiza entre edades
- Amplio mercado de jóvenes que aún no interactúan con los bancos pero ya cuenta con una percepción
- Las y los usuarios no tienen un hábito de ahorro. Cuando se les que opinan del ahorro tienen una percepción positiva, sin embargo, no realizan está actividad con frecuencia.


# Segundo Sprint.
1. Rediseño de aplicación
2. Pruebas de usabilidad
3. Entrevistas con usuari@s target


* Recomendaciones de próximos pasos para el banco con respecto al app (estas
  recomendaciones tendrán que ser sustentadas por tu investigación):

  * Qué modificaciones se deberían hacer
1. Desarrollar la aplicación para usuarios con dispositivos android
2. Hacer un análisis de la otra aplicación bancaria. Varias usuarios buscaban un complemento de esta aplicación,
con funcionalidades similares a la otra.

  * Cuáles deberían ser los próximos desarrollos
  * En qué se debería invertir el presupuesto de marketing


* Rediseño de la aplicación.

En [este video](https://drive.google.com/file/d/10MbdMC-UGim5wDn-G5nPnMEOIXXZsmzF/view?usp=sharing) puedes encontrar una comparativo del antes y después de la aplicación.

Si estás interesad@ en testear ambos prototipos, da click:
1. [Tus finanzas](https://marvelapp.com/e9h245e/screen/47044706)
2. [Rediseño Tus finanzas](https://marvelapp.com/b9a3jab/screen/55353588)


<!-- ## Otras consideraciones

### 1) Planeamiento y presupuesto

En el reto del marketplace elegiste las tareas que podías
realizar deacuerdo a una lista con puntajes predeterminados que te proporcionamos. Para este reto,
la lista de tareas, el valor en puntos de cada tarea y el presupuesto total
de las actividades a realizar lo crearás tú y lo tendrás que sustentar con tu
coach. Adicionalmente, deberás sustentar con tu coach qué entregables harás
llegar al banco al final de tu investigación y por qué. El coach te aprobará
estos entregables o te dará feedback para mejorarlos.

Cuando hagas tu presupuesto y pienses en los entregables recuerda que el tiempo
de desarrollo de este proyecto es de dos semanas. También, recuerda qué partes
te tomaron más tiempo en el desarrollo del proyecto 1 y los aprendizajes que
tuviste al desarrollar el proyecto 1.
 -->
