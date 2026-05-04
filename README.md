# DIU26
Prácticas Diseño Interfaces de Usuario (Tema: Hamburguerserías) 

* [Guiones de prácticas](GuionesPracticas/)
* [Case Study](Guia_CaseStudy.md)
* [Hall of fame](https://github.com/mgea/DIU/tree/master/hall_of_fame) 
* [Recursos/plantillas en Figma](https://www.figma.com/design/BN2IR0q2clOSplfMmalh9K/DIU_Toolkit_Framework--2026-)


El documento **README.md** del repositorio UX_CaseStudy es el esqueleto del documento de caso de estudio UX de la aplicación a desarrollar. 
Ahora mismo es un "esqueleto" que contiene y organiza la información que se espera en cada paso. 
Se tiene que redactar correctamente y eliminar todo lo que no sea necesario, respetando la estructura general del proceso. 
Se puede "mejorar" o innovar pero siguiendo un criterio claro y legible. Se **valorará la calidad de la exposición del Caso de Estudio y la información incluida**. 


<br><br>


# Pasos

* **Datos del proyecto** (en cabecera del documento) 
  * Nombre del proyecto, logotipo, tipología (depende del grupo de prácticas) y breve descripción del proyecto
  * Datos del equipo (nombre del grupo, grupo de prácticas al que pertenece y nombre de miembros).
  * Elmiminar todos los elemento que no sean necesarios
 
* **Información desglosada en pasos**
  * Organizar información del Caso de Estudio en 5 pasos (que corresponde a las 5 prácticas)  
  * Incluir la información más relevante para comprender y explicar objetivos y resultados de cada paso
  * La **documentación que sea de apoyo** para ese Paso irá en una carpeta (P1,...P5) que estará indexada desde cada apartado.
  * Usar tamaños de imágenes y documentos de apoyo que sean fácilmente legibles en entorno Github (PDF, .md)  
  * Finalizar cada paso con una **breve conclusión de lo aprendido en ese paso y para qué nos servirá**

 
* **Conclusión final**
  * Terminar con un apartado específico de **conclusiones** finales y valoración de las prácticas, indicando cómo se ha seguido la metodología UX y
   valoración (positiva /negativa) de los resultados obtenidos. ¿Qué se ha aprendido del proceso? ¿Qué se puede mejorar? 


<br><br>


# Proceso de Diseño 

## Paso 0. My UX-Case Study

**Grupo**: DIU3_AntonioManueldePablosPancorbo/AlbertoRodriguezFernandez.COMPIS  

**Curso**: 2026 

**Actualizado**: 04/05/2026

**Nombre del Proyecto**: Wall Street Burguer    
 
**Descripción**: Nuestra propuesta transforma la plataforma digital de Goiko en un entorno interactivo y gamificado, inspirado en el mercado de valores. Bajo el concepto de explorar 'Sabores con encanto', hemos rediseñado su web para que el precio de las hamburguesas fluctúe en tiempo real según la demanda de la comunidad. Las burgers menos populares bajan de precio para ser 'rescatadas', incentivando a los usuarios a probar recetas diferentes mediante un botón de 'Invertir'. Todo esto se apoya sobre una interfaz rápida y optimizada, integrando filtros de alérgenos accesibles y solucionando los problemas de usabilidad detectados en el diseño actual de Goiko.                

**Logotipo y Slogan**: 

![Logotipo](./P3/Logo.png)

*Goiko's Change. Tu cartera de inversión nunca tuvo tan buena pinta.*

**Miembros y nombre del equipo**:
 * :bust_in_silhouette:  ANTONIO MANUEL DE PABLOS PANCORBO    :octocat: https://github.com/amdepabloss    
 * :bust_in_silhouette:  ALBERTO RODRÍGUEZ FERNÁNDEZ     :octocat: https://github.com/AlbertoRodriguezFernandez


<br><br><br><br>


## Paso 1. UX User & Desk Research & Analisis 


### 1.a User Reseach Plan
![Método UX](img/Competitive.png) 
-----

El sector de las hamburguesas gourmet ha transformado el concepto tradicional de comida rápida en una experiencia premium y altamente demandada. Para nuestro caso de estudio hemos seleccionado la plataforma digital de Goiko, ya que representa un punto de contacto crítico donde los usuarios exploran la carta, personalizan sus pedidos y gestionan reservas.

El objetivo principal de este plan de investigación de usuarios es comprender en profundidad cómo interactúan diferentes perfiles de clientes con la web, desde un estudiante universitario buscando una cena rápida hasta un grupo de amigos planeando un evento. Nuestra estrategia de investigación se estructurará en varias fases clave: primero, realizaremos un análisis competitivo frente a otras marcas del sector para establecer un marco de referencia. Posteriormente, definiremos a nuestros usuarios objetivo mediante la creación de "Personas" y trazaremos sus "Journey Maps" para visualizar sus pasos, emociones y puntos de fricción reales.

A través de este enfoque práctico, evaluaremos la usabilidad general del sitio, la arquitectura de la información y la claridad visual. Buscaremos detectar oportunidades de diseño que permitan optimizar el flujo de interacción, garantizando que la experiencia digital del usuario esté a la misma altura que la calidad de su oferta gastronómica.

* [📄 Ver nuestro Plan de Investigación de Usuarios (PDF)](./P1/Plan_Investigacion_Usuarios.pdf)


<br><br>


### 1.b Competitive Analysis
![Método UX](img/Competitive.png) 
-----

Para entender cómo mejorar la web de Goiko, hemos comparado nuestra página con dos de las hamburgueserías más fuertes y conocidas a nivel local en Granada: **Mostaza Green Burger** y **Kannibal Smash Burger**.

| Característica a evaluar | Goiko (Nuestro caso) | Mostaza Green Burger (Competidor 1) | Sancho Casual Burger (Competidor 2) |
| :--- | :--- | :--- | :--- |
| **Facilidad para ver la carta** | Bien, pero tiene tantas fotos grandes que a veces cuesta encontrar rápido lo que buscas. | Muy fácil, directa al grano y separada por secciones claras. | Muy sencilla, pensada sobre todo para elegir rápido y pedir. Dividida en diferentes apartados |
| **Reservas y pedidos online** | Tiene un menú para pedir que te redirige a páginas externas. | Te informa bien, pero para pedir a veces dependes de apps externas. | Tiene un menú para pedir que te redirige a páginas externas. |
| **Información de alergias** | La información está, pero tienes que buscarla y no destaca a simple vista. | Cuando se accede a la carta, hay un apartado de alérgenos pero no es muy intuitivo | Una vez dentro de la carta, debajo de cada hamburguesa aparecen los alérgenos. Muy intuitivo |
| **Diseño visual (Atractivo)** | Muy moderno, llamativo y da sensación de sitio caro y de calidad. | Estilo muy urbano y moderno, pega mucho con la ciudad de Granada. | Diseño muy simple, parece más un menú digital de pedir que una web completa. |

**Justificación**

Hemos elegido a Mostaza Green y Sancho Casual Burger porque son competencia directa de Goiko en Granada: venden hamburguesas de estilo *smash* y gourmet, y su público son jóvenes y estudiantes. Elegir competencia local nos sirve para ver qué están acostumbrados a usar los granadinos cuando quieren cenar fuera.

Al ver la tabla comparativa, sacamos una conclusión muy clara: las webs de Granada van mucho más "al grano". Mientras que la web de Goiko a veces te marea con animaciones, anuncios de nuevas hamburguesas y fotos gigantes, sitios como Sancho Casual Burger te ponen la carta delante casi al instante para que no pierdas el tiempo. Mostaza Green, por su parte, consigue tener un diseño muy chulo sin llegar a ser pesado.

Nuestra conclusión es que para mejorar Goiko deberíamos aprender de la competencia de Granada: hay que intentar que la web sea más directa, más rápida de leer y, sobre todo, poner mucho más fácil y a la vista la información de los ingredientes y las alergias para no frustrar a los clientes.

* [📄 Ver nuestro Análisis Competitivo (PDF)](./P1/Analisis_Competitivo.pdf)


<br><br>


### 1.c Personas
![Método UX](img/Persona.png) 
-----

Para nuestro caso de estudio de Goiko, hemos seleccionado dos perfiles de usuarios muy habituales en este tipo de restaurantes de comida rápida premium, pero con necesidades y "puntos de dolor" completamente distintos a la hora de usar la plataforma digital.

<br>

**Persona 1: Irene, la foodie intolerante** <br>

![Ficha de Irene en Figma](./P1/foto_ficha_persona1.png)

Irene (28 años) es una diseñadora gráfica local que trabaja desde casa. Le encanta pedir comida a domicilio los viernes para desconectar ("delivery"). Hemos elegido a este perfil porque es celíaca. Representa al usuario que necesita **información de alérgenos** urgente. Su mayor miedo al usar la web de Goiko es no encontrar la opción de "pan sin gluten" o no poder dejar una nota al restaurante sobre la contaminación cruzada al hacer su pedido.

* [📄 Ver nuestra persona Irene](./P1/foto_ficha_persona1.png)

<br><br>

**Persona 2: Pedro, el organizador Erasmus** <br>

![Ficha de Pedro en Figma](./P1/foto_ficha_persona2.png)

Pedro (22 años) es un estudiante italiano de Erasmus en Granada. Es muy social y siempre le toca organizar las cenas de su grupo. Hemos elegido a este perfil porque representa al usuario que necesita usar el **sistema de reservas** de la web. Su principal frustración es no poder ver rápido la disponibilidad para grupos grandes y no entender si puede separar la cuenta, ya que su presupuesto de estudiante es ajustado. Puede que en la imagen, no aparente la edad que tiene, pero es debido a su enorme frustación lo que le hace parecer mayor.

* [📄 Ver nuestra persona Pedro](./P1/foto_ficha_persona2.png)


<br><br>


### 1.d User Journey Map
![Método UX](img/JourneyMap.png) 
----

Para crear nuestros mapas de experiencia, hemos diseñado dos escenarios que son tremendamente habituales en el día a día de una hamburguesería como Goiko. Hemos puesto a nuestros usuarios a intentar cumplir sus objetivos principales para ver dónde la web les ayuda y dónde les genera frustración.

<br>

**Journey 1: Irene y el pedido a domicilio sin gluten** <br>

![Journey de Irene en Figma](./P1/foto_viaje_persona1.png)

Irene intenta pedir una cena a domicilio un viernes por la noche. Hemos elegido esta experiencia porque el "delivery" es uno de los servicios más usados en Goiko. Es una situación muy realista y común: un usuario con restricciones alimentarias (celiaquía) que necesita seguridad. En su viaje, vemos cómo la emoción de Irene cae en picado al darse cuenta de que la información de alérgenos no está clara durante el proceso de compra y no tiene un campo de texto libre para avisar a la cocina, generándole mucha ansiedad.

* [📄 Ver nuestro journey de Irene](./P1/foto_viaje_persona1.png)

<br><br>

**Journey 2: Pedro y la reserva para un grupo grande** <br>

![Journey de Pedro en Figma](./P1/foto_viaje_persona2.png)

Pedro intenta reservar una mesa para 8 personas un sábado por la noche. Hemos elegido esta experiencia porque las cenas de grupos de jóvenes y estudiantes son un pilar básico de este tipo de restaurantes. Es un caso de uso súper habitual. En su viaje, vemos cómo Pedro se frustra porque el sistema de reservas le pone trabas para grupos grandes, obligándole a dar vueltas por la web buscando un teléfono o intentando descifrar si en el local les dejarán pagar por separado.

* [📄 Ver nuestro journey de Pedro](./P1/foto_viaje_persona2.png)


<br><br>


### 1.e Usability Review
![Método UX](img/usabilityReview.png) 
----

Para terminar esta primera fase, hemos evaluado la web oficial de Goiko usando una plantilla de revisión de usabilidad (Checklist). Esto nos sirve para ponerle una "nota" objetiva a la página y ver exactamente en qué apartados técnicos y de diseño flaquea.

* **Enlace al documento:** [📄 Ver revisión de usabilidad de Goiko](./P1/Revision_Usabilidad.pdf)
* **URL evaluada:** https://www.goiko.com
* **Valoración numérica:** 65 / 100 (Riesgo moderado / Bueno)

<br>

**Comentario sobre la revisión:**

Al hacer el análisis detallado, nos hemos dado cuenta de que la web de Goiko tiene bastantes "luces y sombras":

* **Puntos fuertes:** Visualmente es espectacular y cumple muy bien su objetivo de dar hambre. Las fotos son de altísima calidad, la marca tiene muchísima personalidad y es un puntazo que tengan su propio sistema integrado para pedir a domicilio y reservar, sin depender siempre de apps externas.

<br>
  
* **Puntos débiles:** Tanta foto gigante, animaciones y vídeos hacen que la web cargue lenta en móviles si no tienes buena cobertura. Además, peca de querer enseñarte demasiadas promociones (pop-ups) de golpe, lo que marea un poco. Lo que más le penaliza la nota es que la información crucial, como los alérgenos o el teléfono de contacto para problemas, está demasiado escondida. En resumen: es muy bonita, pero a veces poco práctica si el usuario va con prisas.


<br><br>


### 1.f Conclusión 
----

Como consultores expertos en Experiencia de Usuario (UX), hemos realizado una auditoría integral del sitio web oficial de Goiko. Nuestra evaluación concluye que, si bien la plataforma destaca por un diseño visualmente espectacular y una identidad de marca sobresaliente (obteniendo una puntuación general de usabilidad de 65/100), presenta deficiencias significativas en rendimiento, flexibilidad y control del usuario.

El análisis revela que la interfaz está fuertemente orientada al marketing puro, priorizando imágenes y vídeos de altísima resolución. Esto penaliza severamente los tiempos de carga en dispositivos móviles con conexiones estándar, frustrando a usuarios en movimiento. Además, la atención del usuario compite constantemente contra una sobrecarga de pop-ups y banners promocionales.

Mediante el modelado de usuarios (Personas) y mapas de experiencia (Journey Maps), hemos detectado "puntos de dolor" críticos al salir del flujo ideal (Happy Path). El motor de reservas es excesivamente rígido: bloquea solicitudes de grupos grandes sin ofrecer alternativas digitales, rompiendo la experiencia y obligando al usuario a recurrir a la llamada telefónica tradicional. Por otro lado, el proceso de pedido a domicilio falla en un aspecto vital como es la salud. La ausencia de filtros rápidos de alérgenos y la imposibilidad de dejar notas abiertas a la cocina genera gran ansiedad e inseguridad en clientes con restricciones alimentarias.

En conclusión, Goiko.com es un producto digital estéticamente brillante, pero necesita evolucionar hacia un enfoque verdaderamente centrado en el usuario (User-Centric). Recomendamos aligerar la carga multimedia, dotar de flexibilidad a los formularios e implementar flujos de ayuda más accesibles.


<br><br><br><br>


## Paso 2. UX Design  


### 2.a Reframing / Ideacion: Feedback Capture Grid / Empathy Map 
![Método UX](img/feedback-capture-grid.png) 
----

A modo de conclusión de la práctica anterior, observamos que competidores locales como *Sancho Casual Burger* ofrecen plataformas funcionales pero extremadamente monótonas ("añadir al carrito y pagar"). El sector carece de innovación y gamificación en la experiencia de compra. Para estructurar nuestro rediseño, primero analizamos a nuestros usuarios tipo (Mapa de Empatía) y luego recogemos los hallazgos técnicos (Malla Receptora).

<br>

#### Empathy Map de nuestros Usuarios

![Empathy Map de nuestros Usuarios en Figma](./P2/Empathymap.png)

* [📄 Ver nuestro Empathy Map de Usuarios](./P2/Empathymap.png)

<br>

#### Feedback Capture Grid (Malla Receptora)

![Feedback Capture Grid en Figma](./P2/FeedbackCaptureGrid.png)

* [📄 Ver nuestro Feedback Capture Grid](./P2/FeedbackCaptureGrid.png)

<br>

#### Problema e Hipótesis (Propuesta de Valor)

**El Problema:**
La plataforma actual de Goiko es visualmente espectacular, pero estática, pesada y frustrante para usuarios con necesidades específicas (dietas restrictivas o gestión de grupos). Además, la experiencia de pedir comida a domicilio se ha estandarizado tanto en la competencia que ha perdido el factor sorpresa, lo que dificulta dar salida a los productos menos populares del menú y no genera un *engagement* real con el público joven y digital.

**Nuestra Hipótesis (Goiko's Change made by Compis):**
Creemos que transformando la experiencia de compra tradicional en un entorno interactivo y gamificado inspirado en el mercado de valores (*Trading UI*), lograremos aumentar masivamente la retención del usuario. Al hacer que los precios fluctúen en tiempo real para "salvar" las hamburguesas menos demandadas (botón "Invertir"), incentivamos la exploración del menú. Si acompañamos esta interfaz divertida con una arquitectura técnica limpia, flujos de reserva transparentes desde el primer clic y filtros de alérgenos accesibles, mejoraremos la usabilidad general del servicio fusionando eficacia con entretenimiento.


<br><br>


### 2.b ScopeCanvas
![Método UX](img/ScopeCanvas.png)
----

Mediante el uso de ScopeCanvas mostramos nuestra propuesta de valor mediante su propósito, necesidades, objetivos, acciones y métricas:

![ScopeCanvas en Figma](./P2/ScopeCanvas.png)

* [📄 Ver nuestro ScopeCanvas](./P2/ScopeCanvas.png)


<br><br>


### 2.c User Flow (task) Analysis 
----

#### User map
| Tarea | Usuario Invitado | Cliente Registrado | Administrador    
| ------------- | ------- | ------- | ------- |
| **Ver Ticker de bolsa en vivo** | Alta | Alta | Media |
| **Registrarse** | Alta | - | Alta |
| **Iniciar sesión** | - | Alta | Alta |
| **Consultar carta clásica (precios fijos)** | Alta | Alta | Baja |
| **Invertir / Comprar Burger (Mercado)** | Media | Alta | Baja |
| **Reservar mesa y "Congelar" precio** | Media | Alta | Baja |
| **Añadir al Carrito** | Alta | Alta | Baja |
| **Gestionar "Mi Cartera" (Alertas)** | - | Media | Baja |

*-Nota: En los task flow el hecho de haber iniciado sesión o no, no es relevante por lo que se omite para simplificar el diagrama. El usuario puede navegar y comprar/reservar sin estar registrado.*

<br>

#### 1. Task flow: Reserva de mesa con precio congelado

- Este flujo describe el proceso desde que se entra en el mercado de hamburguesas para ver sus precios y
  se termina reservando una mesa para un día concreto y así congelar el precio de la hamburguesa para ese día

![UserFlowBookTable](./P2/UserFlowBookTable.png) 

* [📄 Ver nuestro UserFlowBookTable](./P2/UserFlowBookTable.png) 

<br>

#### 2. Task flow: Inversión en Hamburguesa

- Este flujo describe el proceso desde que el usuario detecta una oportunidad en el Mercado de hamburguesas hasta que confirma su compra (la de una hamburguesa con precio variable)

![UserFlowBookTable](./P2/UserFlowInvestBurger.png) 

* [📄 Ver nuestro UserFlowBookTable](./P2/UserFlowInvestBurger.png) 


<br><br>


### 2.d IA: Sitemap + Labelling 
----

![SiteMap](./P2/Sitemap.png) 

* [📄 Ver nuestro SiteMap](./P2/Sitemap.png)

<br>

Término | Significado     
| ------------- | ------- |
| **Home page** | Punto de entrada principal. Presenta el "Ticker" en vivo con las variaciones de precios y las ofertas más destacadas. |
| **Mercado de Hamburguesas** | Panel dinámico donde los usuarios visualizan las burgers cuyo precio fluctúa según la demanda y popularidad social. |
| **Carta clásica** | Menú tradicional de Goiko. Contiene los productos icónicos con precios fijos para usuarios que buscan rapidez sin variaciones. |
| **Restaurantes** | Localizador geográfico de establecimientos físicos. |
| **Conócenos** | Sección corporativa que incluye la historia de la marca, resolución de dudas (FAQ) y canales de atención al cliente. |
| **Inicio sesión / Registro** | Portal de acceso para usuarios. Permite desbloquear las funciones de "Mi cartera", ver pedidos anteriores y administrar el perfil. |
| **Carrito** | Pasarela intermedia de revisión de productos seleccionados antes de confirmar la compra final o el envío. |
| **Reservar mesa** | Funcionalidad para asegurar sitio en el local. Para el "Mercado de Hamburguesas" permite al usuario "congelar" el precio actual de su burguer de mercado. |
| **Hacer pedido** | Flujo final de transacción para envíos a domicilio (Delivery) o recogida en local (Take Away). |
| **Administrar perfil** | Panel de configuración de datos personales, direcciones de envío y métodos de pago guardados. |
| **Mi cartera** | Espacio de fidelización donde se gestionan las alertas de precios bajos y las hamburguesas marcadas como favoritas. |
| **Pedidos anteriores** | Historial detallado de compras realizadas y seguimiento del "ahorro" obtenido al invertir en el mercado. |
| **Footer** | Pie de página con acceso directo a redes sociales (Síguenos), información legal y datos rápidos de contacto. |


<br><br>


### 2.e Wireframes
![Método UX](img/Wireframes.png) 
----

En esta sección, se podrán ver tanto los bocetos en papel como los wireframe Lo-Fi a continuación:

* [📄 Ver nuestros bocetos](./P2/Bocetos.pdf) 

<br>

De aquí en adelante, se encontrará los bocetos Lo-Fi:

- Wireframe de la Landing Page: 
![Wireframe Landing Page](./P2/WireframeLandingPage.png)

* [📄 Ver nuestro Wireframe Landing Page](./P2/WireframeLandingPage.png)

<br>

- Wireframe del Mercado de Hamburguesas:  

![Wireframe Burger Market](./P2/WireframeBurgerMarket.png)

* [📄 Ver nuestro Wireframe Burger Market](./P2/WireframeBurgerMarket.png)

<br>

- Wireframe de Mi Cartera:  

![Wireframe Mi Cartera](./P2/WireframeCartera.png)

* [📄 Ver nuestro Wireframe Mi Cartera](./P2/WireframeCartera.png)

<br>

- Wireframe de Mi Carrito:  

![Wireframe Mi Carrito](./P2/WireframeCarrito.png)

* [📄 Ver nuestro Wireframe Mi Carrito](./P2/WireframeCarrito.png)


<br><br>


### 2.f Conclusión 
----

A lo largo de esta segunda práctica, hemos logrado transformar una idea disruptiva en una arquitectura sólida y centrada en el usuario (UX). Partiendo de la investigación y empatía inicial (Empathy Map y Malla Receptora), confirmamos la necesidad de romper con la monotonía de las aplicaciones de delivery tradicionales. Esto nos llevó a consolidar nuestra propuesta de valor: gamificar la experiencia de Goiko convirtiéndola en un dinámico "Mercado de Valores".

Mediante el uso de herramientas estratégicas como el ScopeCanvas y el análisis de tareas (User Flows), hemos diseñado flujos lógicos para asegurar que mecánicas innovadoras —como "invertir" en hamburguesas cuyo precio fluctúa o "congelar" su valor al reservar una mesa— resulten naturales e intuitivas. La Arquitectura de la Información (Sitemap) nos ha permitido organizar este nuevo ecosistema de forma coherente.

Todo este trabajo se materializa en los wireframes Lo-Fi, donde hemos alcanzado un equilibrio perfecto entre la temática financiera (con elementos como el ticker en vivo, las gráficas de rendimiento en "Mi Cartera" y rangos como el Lobo de Wall Street) y la usabilidad pura. Además, el diseño integra de forma orgánica las soluciones a los pain points reales detectados en nuestros usuarios, implementando funcionalidades clave como la división de pagos en grupo y la gestión de alérgenos directamente en el carrito de compra.

En definitiva, hemos construido un esqueleto interactivo, altamente diferenciador y justificado en las necesidades del usuario, sentando las bases idóneas para afrontar con garantías la futura fase de diseño visual y prototipado de alta fidelidad (UI).


<br><br><br><br>


## Paso 3. Mi UX-Case Study (diseño)


### 3.a Moodboard
![Método UX](img/moodboard.png)
-----

![Moodboard](./P3/Moodboard.png) 

* [📄 Ver nuestro Moodboard](./P3/Moodboard.png)

<br>

El moodboard de Wall Street Burgers refleja la fusión perfecta entre la elegancia de un club financiero y la indulgencia de GOIKO. Visualmente, la propuesta se apoya en una paleta que combina el ocre bronce, evocando el lujo y el pan tostado, con rojos vibrantes diseñados para alertar sobre las caídas de precios, todo sobre un fondo crema limpio. La tipografía mezcla el carácter rotundo y clásico de Oswald para los titulares, con la precisión técnica de Inter para facilitar la lectura de los valores de mercado. Todo este universo visual sirve de marco para un tono de voz de "bróker gamberro", que transforma el menú en una bolsa de valores gamificada donde el usuario entra para invertir con hambre y comerse el mercado.


<br><br>


### 3.b Guidelines
![Método UX](img/guidelines.png) 
----

Para el desarrollo visual de *Wall Street Burgers*, hemos prescindido de frameworks rígidos y hemos optado por construir un **Design System ligero y personalizado**, enfocado en la modularidad y la escalabilidad de nuestra interfaz web.

<br>

#### 1. Foundations (Cimientos del Sistema)
Utilizando plugins de Figma para la generación de estilos, hemos definido nuestras bases visuales (Design Tokens):
*   **Sistema de Color:** Hemos documentado nuestra paleta en escalas (ej. `color-primary-600`), definiendo el Ocre Bronce para la identidad corporativa, el Crema como fondo neutro para evitar fatiga visual, y el Rojo Vivo como color de *feedback* y alerta para los CTAs principales y las "caídas de mercado".
*   **Arquitectura Tipográfica:** Escala modular utilizando **Oswald** para los H1-H3 (titulares llamativos) e **Inter** para el *Body* y las etiquetas de datos (garantizando legibilidad en los números cambiantes del mercado).

<br>

#### 2. Metodología Atomic Design
Hemos estructurado nuestros componentes de menor a mayor complejidad para facilitar el ensamblaje de los wireframes Hi-Fi:
*   **Átomos:** Elementos base indivisibles. Estilos de texto, tokens de color, iconos (flechas de tendencias, trofeos de usuario), botones simples y contenedores básicos.
*   **Moléculas:** Agrupaciones funcionales. Tarjetas de producto (Foto + Nombre + Precio + Variación + Botón), barras de búsqueda, e indicadores de rendimiento de la cartera.
*   **Organismos:** Secciones complejas como el Header de navegación, el "Ticker" dinámico de precios (el banner rojo animado), y el Footer legal.

A través del siguiente enlace, se podrá ver nuestro Diseño Atómico realizado en Figma, organizado en distintas páginas donde se pueden encontrar: átomos, moléculas, organismos y los bocetos finales.

* [🔗 Ver el proyecto interactivo directamente en Figma](https://www.figma.com/design/EcflaKpYL0jVP59BLETOzQ/Dise%C3%B1o-Sistema?m=auto&t=szcr0lgR3elgUFrY-1)

<br>

#### 3. Patrones de Diseño IU y Layout Web
Siguiendo las directrices de diseño web y la usabilidad en desktop, hemos aplicado los siguientes patrones:
*   **Patrón de Lectura en "F":** Hemos estructurado el layout asumiendo que el usuario escaneará la pantalla de izquierda a derecha y de arriba a abajo. Por ello, el logo y el menú principal se ubican en la esquina superior izquierda, seguido de la navegación transversal. El "Ticker" de precios capta la atención inmediatamente debajo en el primer barrido visual horizontal.
*   **Ubicación de CTAs (Call to Action):** Los botones principales de conversión (como "INVERTIR" o "FINALIZAR COMPRA") se han ubicado estratégicamente en la ruta visual del usuario, alineados a la derecha o destacados con el color de mayor contraste (Rojo Vivo) para incitar a la acción rápida, simulando la urgencia del *trading*.
*   **Header y Footer predecibles:** Para reducir la carga cognitiva frente a una propuesta tan novedosa, mantenemos la estructura clásica de navegación superior y cierre legal/social en la parte inferior.


<br><br>


### 3.c Maquetas
![Método UX](img/mockup.png) 
----

#### HI-FI de la Landing Page 

![HI-FI de la Landing Page](./P3/WireframeHiFiLandingPage.png)

* [📄 Ver nuestro HI-FI de la Landing Page](./P3/WireframeHiFiLandingPage.png)

<br>

#### HI-FI del Mercado de Hamburguesas 

![HI-FI del Burguer Market](./P3/WireframeHiFiMercadoHamburguesas.png)

* [📄 Ver nuestro HI-FI del Burguer Market](./P3/WireframeHiFiMercadoHamburguesas.png)

<br>

#### HI-FI de Mi Cartera

![HI-FI de Mi Cartera](./P3/WireframeHifiCartera.png)

* [📄 Ver nuestro HI-FI de Mi Cartera](./P3/WireframeHifiCartera.png)

<br>

#### HI-FI de Mi Carrito 

![HI-FI de Mi Carrito](./P3/WireframeHifiCarrito.png)

* [📄 Ver nuestro HI-FI de Mi Carrito](./P3/WireframeHifiCarrito.png)


<br><br>


### 3.d Conclusión
----

El desarrollo del prototipo Hi-Fi de *Wall Street Burgers* ha sido un reto superado con éxito gracias a la combinación de metodologías ágiles de diseño y el apoyo de herramientas de IA. 

Nuestro principal acierto ha sido la definición inicial de un **UX Writing potente** ("bróker gamberro") y un Moodboard muy claro. Esto nos permitió tomar decisiones de UI rápidas y coherentes. La interfaz destaca por su alto contraste y su capacidad de gamificar una acción tan cotidiana como pedir comida a domicilio. El uso del "Ticker" de precios y las tarjetas de fluctuación aportan un dinamismo que engancha visualmente al usuario desde el primer segundo.

El proceso se ha optimizado enormemente gracias a:
1.  Herramientas de IA Generativa:Han sido fundamentales en las fases iniciales para generar el *copywriting* motivador, afinar el tono de voz de la marca, generar las imágenes inspiracionales del moodboard y ayudarnos a traducir los conceptos financieros complejos a una interfaz de usuario comprensible.

<br>
 
2.  Figma + Plugins: La utilización de plugins para la generación de fundaciones (escalas de color y tipografía) y librerías como *Lucide* para la iconografía, nos ahorró horas de trabajo manual. 

<br>

3.  Atomic Design: Al construir primero los átomos y moléculas en Figma usando *Componentes* y *Auto Layout*, el ensamblaje final de las pantallas Hi-Fi (Landing Page, Mercado, Cartera y Carrito) fue un proceso casi automático, garantizando una consistencia visual perfecta en todo el proyecto.

<br>

En conclusión, la integración del diseño atómico junto con la asistencia de la IA nos ha permitido crear un prototipo robusto, visualmente impactante y listo para las siguientes fases de evaluación funcional.


<br><br><br><br>


## Paso 4. Pruebas de Evaluación 

### 4.a Reclutamiento de usuarios 
![Método UX](img/usability-testing.png)
-----

>>> Breve descripción del caso asignado (llamado Caso-B) con enlace al repositorio Github
>>> Tabla y asignación de personas ficticias (o reales) a las pruebas. Exprese las ideas de posibles situaciones conflictivas de esa persona en las propuestas evaluadas. Mínimo 4 usuarios: asigne 2 al Caso A y 2 al caso B.



| Usuarios | Sexo/Edad     | Ocupación   |  Exp.TIC    | Personalidad | Plataforma | Caso
| ------------- | -------- | ----------- | ----------- | -----------  | ---------- | ----
| User1's name  | H / 18   | Estudiante  | Media       | Introvertido | Web.       | A 
| User2's name  | H / 18   | Estudiante  | Media       | Timido       | Web        | A 
| User3's name  | M / 35   | Abogado     | Baja        | Emocional    | móvil      | B 
| User4's name  | H / 18   | Estudiante  | Media       | Racional     | Web        | B 


### 4.b Diseño de las pruebas 
![Método UX](img/usability-testing.png) 
-----

>>> Planifique qué pruebas se van a desarrollar. ¿En qué consisten? ¿Se hará uso del checklist de la P1?



### 4.c Cuestionario SUS
![Método UX](img/Survey.png) 
----

>>> Como uno de los test para la prueba A/B testing, usaremos el **Cuestionario SUS** que permite valorar la satisfacción de cada usuario con el diseño utilizado (casos A o B). Para calcular la valoración numérica y la etiqueta linguistica resultante usamos la [hoja de cálculo](https://github.com/mgea/DIU19/blob/master/Cuestionario%20SUS%20DIU.xlsx). Previamente conozca en qué consiste la escala SUS y cómo se interpretan sus resultados
http://usabilitygeek.com/how-to-use-the-system-usability-scale-sus-to-evaluate-the-usability-of-your-website/)
Para más información, consultar aquí sobre la [metodología SUS](https://cui.unige.ch/isi/icle-wiki/_media/ipm:test-suschapt.pdf)
>>> Adjuntar en la carpeta P4/ el excel resultante y describa aquí la valoración personal de los resultados 


### 4.d A/B Testing
![Método UX](img/ABtesting.png) 
-----

>>> Los resultados de un A/B testing con 3 pruebas y 2 casos o alternativas daría como resultado una tabla de 3 filas y 2 columnas, además de un resultado agregado global. Especifique con claridad el resultado: qué caso es más usable, A o B?

### 4.e Aplicación del método Eye Tracking 
![Método UX](img/eye-tracking.png)
----

>>> Indica cómo se diseña el experimento y se reclutan los usuarios. Explica la herramienta / uso de gazerecorder.com u otra similar. Aplíquese únicamente al caso B.


![experimento](img/experimentoET.png)  
>>> Cambiar esta img por una de vuestro experimento. El recurso deberá estar subido a la carpeta P4/  

>>> gazerecorder en versión de pruebas puede estar limitada a 3 usuarios para generar mapa de calor (crédito > 0 para que funcione) 


### 4.f Usability Report de B
![Método UX](img/usability-report.png) 
-----

>>> Añadir report de usabilidad para práctica B (la de los compañeros) aportando resultados y valoración de cada debilidad de usabilidad. 
>>> Enlazar aqui con el archivo subido a P4/ que indica qué equipo evalua a qué otro equipo.

>>> Complementad el Case Study en su Paso 4 con una Valoración personal del equipo sobre esta tarea


<br><br><br><br>


## Paso 5. Exportación y Documentación 


### 5.a Exportación a HTML/React
![Método UX](img/usabilityReview.png) 
----

>>> Breve descripción de esta tarea. Las evidencias de este paso quedan subidas a P5/


### 5.b Documentación con Storybook
![Método UX](img/usabilityReview.png)
----

>>> Breve descripción de esta tarea. Las evidencias de este paso quedan subidas a P5/


<br><br><br><br>


## Conclusiones Finales y Valoración de las Prácticas


>>> Opinión FINAL del proceso de desarrollo de diseño siguiendo metodología UX y valoración (positiva /negativa) de los resultados obtenidos. ¿Qué se puede mejorar? Recuerda que este tipo de texto se debe eliminar del template que se os proporciona 




