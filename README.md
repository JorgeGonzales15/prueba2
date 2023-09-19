# Capítulo III: Requirements Specification

## 3.1. To-Be Scenario Mapping.
En esta parte se utilizó el “TO-BE Scenario Mapping” para ello se hizo una representación visual de cómo deberían ser los procesos después de implementar las mejoras y cambios sugeridos. Es una parte crucial de la metodología de mejora de procesos y ayuda a las organizaciones a visualizar cómo podrían ser sus operaciones optimizadas en el futuro. Se utilizó la herramienta Miro.

![ToBe](https://github.com/JorgeGonzales15/SW51-GreatMinds-OpenSource/assets/104078975/364e9acb-a307-4de6-95f4-20148221907f)

## 3.2. User Stories.

|Epic ID|Título de épica|Descripción de la épica|
| - | - | - |
|EP01|Definición de funcionalidades de la aplicación web|Como usuario deseo que la aplicación posea características funcionales variadas para que me sirva de ayuda al momento de cultivar, vender y planificar.|
|EP02|Opciones relacionadas a la cuenta del usuario|Como usuario deseo poder realizar acciones de creación, actualización y otras relacionadas a una cuenta para poder guardar las configuraciones y utilizarlas desde distintos dispositivos|
|EP03|Definición de estructura del landing page |Como usuario deseo disponer de un landing page con información pertinente para conocer mejor acerca de la aplicación web |
|EP04|Definición de requisitos no funcionales|Como usuario deseo que la aplicación web cumpla con estándares de rendimiento y optimización para utilizarla sin inconvenientes |

| Epic/Story | Título | Descripción | Criterios de Aceptación | Relacionado con (Epic ID) |
| - | - | - | - | - |
|HU-01|Registro de cuenta|Como usuario, quiero poder registrarme en la aplicación para acceder a las funcionalidades disponibles.|<p>Escenario 01: Usuario registra su cuenta</p><p>Caso 1:</p><p>Dado que el usuario se encuentra en la sección de registro </p><p>Cuando el usuario ingrese sus datos para el registro</p><p>Entonces su cuenta es registrada en la aplicación.</p><p></p>|EP02|
|HU-02|Inicio de sesión|Como usuario, quiero iniciar sesión para poder ingresar a mi cuenta|<p>Escenario 01: Usuario inicia sesión</p><p>Caso 1:</p><p>Dado que el usuario ha registrado su cuenta previamente,</p><p>Cuando el usuario ingrese su dirección de correo electrónico y contraseña válida,</p><p>Entonces se le permite ingresar a su cuenta y acceder a las funcionalidades.</p><p></p>|EP02|
|HU-03|Explorar productos agrícolas|Como comercializador quiero observar los productos disponibles para poder realizar los pedidos|<p>Escenario 01: Comercializador explora productos disponibles</p><p>Caso 1:</p><p>Dado que el comercializador ha iniciado sesión en la aplicación,</p><p>Cuando el comercializador navegue a la sección de productos agrícolas,</p><p>Entonces se le muestran los productos disponibles para explorar.</p><p></p>|EP01|
|HU-04|Realizar pedidos de productos|Como comercializador, quiero poder realizar los pedidos de productos agrícolas para poder realizar las entregas|<p>Escenario 01: Comercializador realiza un pedido de productos</p><p>Caso 1:</p><p>Dado que el comercializador ha explorado los productos y ha seleccionado los que desea pedir,</p><p>Cuando el comercializador confirma el pedido y especifica las cantidades,</p><p>Entonces se registra el pedido y se notifica al comercializador sobre el proceso de entrega.</p><p></p>|EP01|
|HU-05|Seguimiento de Pedidos y Entregas|Como comercializador, quiero poder observar el estado de los pedidos y entregas para poder sentirme más tranquilo|<p>Escenario 01: Comercializador sigue el estado de un pedido en curso</p><p>Caso 1:</p><p>Dado que el comercializador ha realizado un pedido y desea rastrear su estado,</p><p>Cuando el comercializador accede a la sección de seguimiento de pedidos,</p><p>Entonces se le proporciona información actualizada sobre el estado del pedido.</p><p></p>|EP01|
|HU-06|Acceder a Calificaciones y Reseñas|Como comercializador, quiero acceder a las calificaciones y reseñas dejadas por los agricultores para saber sobre la valoración de mis servicios|<p>Escenario 01: Comercializador accede a las calificaciones y reseñas</p><p>Caso 1:</p><p>Dado que el comercializador desea evaluar la satisfacción de los agricultores con sus productos,</p><p>Cuando el comercializador accede a la sección de calificaciones y reseñas,</p><p>Entonces puede ver las evaluaciones y comentarios proporcionados por los agricultores.</p><p></p>|EP01|
|HU-07|Observar registro de pedidos y entregas realizadas|Como comercializador, quiero observar los pedidos y entregas realizadas, para poder tomar decisiones de acuerdo al análisis de los registros|<p>Escenario 01: Comercializador analiza registros de pedidos y entregas</p><p>Caso 1:</p><p>Dado que el comercializador busca tomar decisiones informadas sobre su operación,</p><p>Cuando el comercializador accede a los registros de pedidos y entregas realizadas,</p><p>Entonces puede analizar los datos para identificar tendencias y patrones.</p><p></p>|EP01|
|HU-08|Planificar actividades agrícolas|Como agricultor, quiero ingresar los datos correspondientes para la planificación de las actividades agrícolas|<p>Escenario 01: Agricultor planifica actividades para un ciclo de cultivo</p><p>Caso 1:</p><p>Dado que el agricultor ha ingresado a la sección de planificación,</p><p>Cuando el agricultor ingresa los datos relevantes para las actividades agrícolas,</p><p>Entonces el sistema registra el plan y lo refleja en el calendario.</p><p></p>|EP01|
|HU-09|Registro de gastos y ganancias|Como agricultor, quiero registrar los gastos y las ganancias relacionadas con mis actividades agrícolas para poder llevar un control financiero|<p>Escenario 01: Agricultor registra gastos y ganancias para un ciclo de cultivo</p><p>Caso 1:</p><p>Dado que el agricultor desea llevar un registro financiero detallado,</p><p>Cuando el agricultor ingresa los gastos y las ganancias relacionados con sus actividades,</p><p>Entonces el sistema almacena los registros para su consulta posterior.</p><p></p>|EP01|
|HU-10|Gestión de Insumos Agrícolas|Como agricultor, quiero llevar un registro de los insumos agrícolas utilizados para analizarlo y tomar decisiones de acuerdo a ello|<p>Escenario 01: Agricultor registra uso de insumos en un cultivo</p><p>Caso 1:</p><p>Dado que el agricultor necesita mantener un registro de los insumos utilizados,</p><p>Cuando el agricultor ingresa los insumos utilizados en un cultivo específico,</p><p>Entonces el sistema registra la información para su análisis y planificación.</p><p></p>|EP01|
|HU-11|Control de Plagas|Como agricultor, quiero tener herramientas para identificar y controlar las plagas para que no puedan afectar los cultivos|<p>Escenario 01: Agricultor registra observaciones de plagas en un cultivo</p><p>Caso 1:</p><p>Dado que el agricultor detecta signos de plagas en sus cultivos,</p><p>Cuando el agricultor registra las observaciones y los detalles de las plagas identificadas,</p><p>Entonces el sistema proporciona recomendaciones para el control y seguimiento de las plagas.</p><p></p>|EP01|
|HU-12|Atender pedidos|Como usuario deseo ver los pedidos que tengo de manera rápida y fácil en una pantalla |<p>Escenario 01:</p><p>El usuario agricultor quiere atender un pedido que le interesó.</p><p>Caso 01:</p><p>Dado que el usuario necesita vender sus productos</p><p>Cuando reciba un pedido dentro de la aplicación</p><p>Entonces podrá atenderlo accediendo a sus productos y seleccionando uno de ellos para ver aceptar o rechazar el pedido</p>|EP01|
|HU-13|Visualización de características de la aplicación web|Como usuario deseo ver las principales características de la aplicación para decidir si usar el producto en mi trabajo|<p>Escenario 01:</p><p>El usuario visita la landing page.</p><p>Caso 01:</p><p>Dado que el usuario necesita una aplicación para aumentar la calidad de sus cultivos </p><p>Cuando el usuario busque en el navegador “Harvest Management”</p><p>Entonces accede a la landing page y visualiza las funcionalidades que le ofrece la aplicación web</p>|EP03|
|HU-14|Landing Page responsive|Como usuario deseo visitar la landing page desde cualquier dispositivo|<p>Escenario 01:</p><p>El usuario visita la landing page desde su celular</p><p>Caso 01:</p><p>Dado que el usuario necesita visitar la landing page desde un dispositivo remoto</p><p>Cuando visite la landing page desde el navegador de su celular</p><p>Entonces la landing page con su diseño responsive puede visualizarse adecuadamente en el navegador del dispositivo móvil</p>|EP03|
|HU-15|Botón Call to Action|Como usuario deseo ir a la aplicación web desde un solo botón |<p>Escenario 01: </p><p>El usuario quiere dirigirse a la aplicación web</p><p>Caso 01: </p><p>Dado que el usuario desea usar la aplicación web</p><p>Cuando esté en la sección donde se encuentre el botón call to action y lo uso</p><p>Entonces será dirigido a la aplicación web</p>|EP03|
|HU-16|Visualización de botones y texto amplia y notoria|Como usuario deseo ver los botones y la información de las secciones o pantalla para una mejor navegación|<p>Escenario 01:</p><p>El usuario quiere navegar por la aplicación sin forzar la vista</p><p>Caso 01:</p><p>Dado que el usuario desea ver los productos visualmente grandes </p><p>Cuando quiera analizar si el producto es de la calidad que espera</p><p>Entonces podrá visualizar el producto mejor y proseguir con la compra</p><p></p>|EP04|
|HU-17|Sistemas de búsqueda y paginación|Como usuario deseo encontrar los productos de manera rápida para no perder tiempo |<p>Escenario 01:</p><p>El usuario quiere encontrar un producto que compró hace unas semanas</p><p>Caso 01:</p><p>Dado que el usuario desea ver una compra que hizo hace semanas</p><p>Cuando quiera buscarlo en la sección de “Mis compras”</p><p>Entonces podrá buscarlo directamente en una barra de búsqueda</p>|EP04|


## 3.3. Impact Mapping.
Se utilizó el Impact Mapping para definir y visualizar los objetivos y resultados deseados en el proyecto para cada uno de los segmentos. Se utilizó la herramienta UXPressia.

![ImpactMap](https://github.com/JorgeGonzales15/SW51-GreatMinds-OpenSource/assets/104078975/3ef9ef91-be98-451c-89b6-fae6e3ce98d5)
![ImpactMap](https://github.com/JorgeGonzales15/SW51-GreatMinds-OpenSource/assets/104078975/659162bf-af13-4dab-8226-02ac018ed162)

## 3.4. Product Backlog.

| #Orden | User Story Id | Título | Descripción | Story Points (1 / 2 / 3 / 5 / 8) |
| - | - | - | - | - |
|01|HU01|Registro de cuenta|Como usuario, quiero poder registrarme en la aplicación para acceder a las funcionalidades disponibles.|2|
|02|HU02|Inicio de sesión|Como usuario, quiero iniciar sesión para poder ingresar a mi cuenta|3|
|03|HU03|Explorar productos agrícolas|Como comercializador quiero observar los productos disponibles para poder realizar los pedidos|3|
|04|HU04|Realizar pedidos de productos|Como comercializador, quiero poder realizar los pedidos de productos agrícolas para poder realizar las entregas|8|
|05|HU05|Seguimiento de Pedidos y Entregas|Como comercializador, quiero poder observar el estado de los pedidos y entregas para poder sentirme más tranquilo|8|
|06|HU06|Acceder a Calificaciones y Reseñas|Como comercializador, quiero acceder a las calificaciones y reseñas dejadas por los agricultores para saber sobre la valoración de mis servicios|2|
|07|HU07|Observar registro de pedidos y entregas realizadas|Como comercializador, quiero observar los pedidos y entregas realizadas, para poder tomar decisiones de acuerdo al análisis de los registros|2|
|08|HU08|Planificar actividades agrícolas|Como agricultor, quiero ingresar los datos correspondientes para la planificación de las actividades agrícolas|5|
|09|HU09|Registro de gastos y ganancias|Como agricultor, quiero registrar los gastos y las ganancias relacionadas con las actividades agrícolas para poder llevar un control financiero|3|
|10|HU10|Gestión de Insumos Agrícolas|Como agricultor, quiero llevar un registro de los insumos agrícolas utilizados para analizarlo y tomar decisiones de acuerdo con ello|3|
|11|HU11|Control de Plagas|Como agricultor, quiero tener herramientas para identificar y controlar las plagas para que no puedan afectar mis cultivos|3|
|12|HU-12|Atender pedidos|Como usuario deseo ver los pedidos que tengo de manera rápida y fácil en una pantalla|8|
|13|HU-13|Visualización de características de la aplicación web|Como usuario deseo ver las principales características de la aplicación para decidir si usar el producto en mi trabajo|5|
|14|HU-14|Landing Page responsive|Como usuario deseo visitar la landing page desde cualquier dispositivo|8|
|15|HU-15|Botón Call to Action|Como usuario deseo ir a la aplicación web desde un solo botón|5|
|16|HU-16|Visualización de botones y texto amplia y notoria|Como usuario deseo ver los botones y la información de las secciones o pantalla para una mejor navegación |3|
|17|HU-17|Sistemas de búsqueda y paginación|Como usuario deseo encontrar los productos de manera rápida para no perder tiempo|5|

# Capítulo IV: Product Design

## 4.1. Style Guidelines.
### 4.1.1. General Style Guidelines.


Mediante la aplicación Ayni se busca que los usuarios gocen de una interfaz que transmite formalidad, profesionalismo y la serenidad que transmiten los paisajes de campos de cultivo de Perú. Por ello, el equipo tomó la decisión de emplear recursos visuales que capten la atención de los segmentos objetivos y que sean fáciles de identificar. Como estrategia se utilizaron colores pasivos, con temperaturas frías (verde y azul) junto con fuentes tipográficas con diferentes tamaños y espaciados ligeramente amplios, con el propósito de generar placer visual y lograr que el texto sea más visible. Cabe destacar que no se emplearán texturas, pues se busca mantener un aspecto mini

**Brand Overview**

El producto solución Ayni, surge a partir de la necesidad de mejorar la calidad de los productos de cultivo a través de mejorar los procesos y el flujo de ganancias de los productos y de los comerciantes respectivamente. A partir de esto, se propuso desarrollar una aplicación web que facilitará la planificación de cultivos, entre otras funciones con el fin de atender las necesidades previamente mencionadas.

**Brand Name**

El nombre del producto es Ayni. Este nombre nació de la lengua quechua para referirse al trabajo común y a la reciprocidad, que es lo que se desea para los clientes, nosotros les damos una aplicación web eficiente para ayudar a sus rutinas de cultivo y ellos nos dan el reconocimiento por facilitarles la tarea. Por otro lado, el logo de Ayni representa la esperanza y la vida a través de una hoja verde.

![Ayni Logo](https://github.com/JorgeGonzales15/SW51-GreatMinds-OpenSource/assets/104078975/ceb29e85-3c65-4758-85e6-feae0881ad60)


**Colores**

Colores primarios: El color primario empleado para el diseño del producto y para el logotipo es una escala de colores similares a la celeste aguamarina, el cual es una mezcla entre azul y verde que transmite balance, armonía, seguridad y novedad. Estas características permiten elaborar una interfaz no intrusiva, donde el fondo pasa desapercibido y como consecuencia, indirectamente otorga mayor prioridad al texto.

![Colores primarios](https://github.com/JorgeGonzales15/SW51-GreatMinds-OpenSource/assets/104078975/4a45a2af-990a-44f4-b4f8-7db5d0fc5133)

Colores secundarios: Como color secundario se seleccionó una escala de verdes, los cuales transmiten sentimientos tales como armonía, serenidad, sensación de crecimiento y están arraigados a conceptos como prestigio y bonanza económica, lo cual encaja a la perfección con el enfoque que buscamos potenciar de los agricultores.

![Colores secundarios](https://github.com/JorgeGonzales15/SW51-GreatMinds-OpenSource/assets/104078975/4e048e5c-9a84-459d-9965-e4891e8f2e3b)

Colores adicionales: Como colores adicionales se seleccionaron blanco, negro y dos tonalidades diferentes de rojo. Estos serán empleados dentro de la tipografía, botones y mensajes de la aplicación. El blanco también será empleado para algunos fondos que requieran que la visibilidad del texto resalte con mayor ímpetu.

![Adicionales](https://github.com/JorgeGonzales15/SW51-GreatMinds-OpenSource/assets/104078975/f7790537-54c7-4226-92bc-11323d7cf5b0)

**Tipografia:**

El equipo seleccionó la fuente de letra Archivo, un estilo tradicional y fácil de leer. La separación del interletraje es de 0,15 px, el interlineado es de 0,5 px y el tamaño de la fuente varía dependiendo de la finalidad de uso, por ejemplo, para los títulos se opta por un tamaño de 56 px, y para el texto redactado por el usuario 27 px. 

![Tipografia](https://github.com/JorgeGonzales15/SW51-GreatMinds-OpenSource/assets/104078975/2e9abaf9-db14-4c7f-b000-2a60df98a8c6)

Tono de comunicación y lenguaje aplicado
El tipo de lenguaje a emplear será serio y formal junto con entusiasmo y serenidad. Dado que se agregarán mejoras y pasos que captarán la atención del usuario. Asimismo, se agregaron elementos para perfeccionar la interfaz y diseño final para los clientes.


### 4.1.2. Web Style Guidelines.

La página web está diseñada para mostrarse en el dispositivo que se esté usando, ya sea desde una computadora o dispositivo móvil, el sitio web estará disponible en ambas plataformas para proporcionar una mejor experiencia de usuario. Además, el patrón de diseño web usado es Flat Design, para que el usuario tenga una alta comprensión y una fácil interacción al momento de estar en la interfaz. 

Se utilizará el patrón 
