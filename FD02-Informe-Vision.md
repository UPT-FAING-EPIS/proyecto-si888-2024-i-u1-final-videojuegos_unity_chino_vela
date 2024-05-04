<center>

[comment]: <img src="./media/media/image1.png" style="width:1.088in;height:1.46256in" alt="escudo.png" />

![./media/media/image1.png](./media/logo-upt.png)

**UNIVERSIDAD PRIVADA DE TACNA**

**FACULTAD DE INGENIERIA**

**Escuela Profesional de Ingeniería de Sistemas**

**Proyecto *Proyecto Dungeon Gunner***

Curso: *DISEÑO Y CREACIÓN DE VIDEOJUEGOS*

Docente: *Patrick José Cuadros Quiroga*

Integrantes:

***Oswaldo Jesus Chino Conde	(2019063322)***

***Abraham Jesús Vela Vargas	(2019063322)***

**Tacna – Perú**

***2024***

**  
**
</center>
<div style="page-break-after: always; visibility: hidden">\pagebreak</div>

|CONTROL DE VERSIONES||||||
| :-: | :- | :- | :- | :- | :- |
|Versión|Hecha por|Revisada por|Aprobada por|Fecha|Motivo|
|1\.0|OCC|OCC|OCC|03/05/2024|Versión Original|












**Sistema *{Nombre del Sistema}***

**Documento de Visión**

**Versión *{1.0}***
**

<div style="page-break-after: always; visibility: hidden">\pagebreak</div>

|CONTROL DE VERSIONES||||||
| :-: | :- | :- | :- | :- | :- |
|Versión|Hecha por|Revisada por|Aprobada por|Fecha|Motivo|
|1\.0|MPV|ELV|ARV|10/10/2020|Versión Original|


<div style="page-break-after: always; visibility: hidden">\pagebreak</div>


**INDICE GENERAL**
#
[1.	Introducción](#_Toc52661346)

1.1	Propósito

1.2	Alcance

1.3	Definiciones, Siglas y Abreviaturas

1.4	Referencias

1.5	Visión General

[2.	Posicionamiento](#_Toc52661347)

2.1	Oportunidad de negocio

2.2	Definición del problema

[3.	Descripción de los interesados y usuarios](#_Toc52661348)

3.1	Resumen de los interesados

3.2	Resumen de los usuarios

3.3	Entorno de usuario

3.4	Perfiles de los interesados

3.5	Perfiles de los Usuarios

3.6	Necesidades de los interesados y usuarios

[4.	Vista General del Producto](#_Toc52661349)

4.1	Perspectiva del producto

4.2	Resumen de capacidades

4.3	Suposiciones y dependencias

4.4	Costos y precios

4.5	Licenciamiento e instalación

[5.	Características del producto](#_Toc52661350)

[6.	Restricciones](#_Toc52661351)

[7.	Rangos de calidad](#_Toc52661352)

[8.	Precedencia y Prioridad](#_Toc52661353)

[9.	Otros requerimientos del producto](#_Toc52661354)

b) Estandares legales

c) Estandares de comunicación	](#_toc394513800)37

d) Estandaraes de cumplimiento de la plataforma	](#_toc394513800)42

e) Estandaraes de calidad y seguridad	](#_toc394513800)42

[CONCLUSIONES](#_Toc52661355)

[RECOMENDACIONES](#_Toc52661356)

[BIBLIOGRAFIA](#_Toc52661357)

[WEBGRAFIA](#_Toc52661358)


<div style="page-break-after: always; visibility: hidden">\pagebreak</div>

**<u>Informe de Visión</u>**

1. <span id="_Toc52661346" class="anchor"></span>**Introducción**

    La creación de videojuegos es un proceso complejo que involucra múltiples aspectos de ingeniería de software, desde el diseño inicial hasta el desarrollo y la implementación final. En el ámbito académico, donde los estudiantes aprenden y aplican estas técnicas, es crucial tener un sistema que permita una experiencia práctica efectiva y eficiente. "Dungeon Gunner" es un proyecto que busca integrar conocimientos de diseño, desarrollo de software, y gestión de proyectos, en un entorno controlado que simula desafíos reales de la industria de los videojuegos.

    Este proceso de creación de videojuegos no solo requiere habilidades técnicas, sino también una gestión eficaz de la configuración del software, que supervisa y controla los cambios en el desarrollo del juego. Este proyecto ofrece a los estudiantes la oportunidad de trabajar en un ambiente que refleja un ciclo de desarrollo de software real, facilitando la transición de teorías y conceptos a aplicaciones prácticas dentro de un marco de trabajo estructurado.

    1.1	Propósito

        El propósito de este documento es presentar una visión clara del proyecto "Dungeon Gunner", destacando cómo se integrarán las habilidades de programación y diseño gráfico en un juego de plataforma 2D. Este documento servirá de guía para todas las fases del proyecto, desde la concepción hasta la implementación final, y ayudará a identificar y organizar a los interesados y usuarios que participarán directamente en el desarrollo del juego.


    1.2	Alcance

        El alcance de "Dungeon Gunner" abarca el desarrollo completo del juego, incluyendo la creación de niveles, mecánicas de juego, control de personajes y enemigos, y la implementación de gráficos y efectos sonoros. El proyecto busca no solo proporcionar una herramienta educativa para los estudiantes, sino también generar un producto que pueda demostrar sus capacidades de desarrollo en un entorno competitivo y profesional.

    1.3	Definiciones, Siglas y Abreviaturas

        •	2D: Dos Dimensiones. Refiere a gráficos que se proyectan en un plano horizontal y vertical, utilizados en el diseño de juegos que no requieren representación de profundidad.
        •	Unity: Motor de desarrollo de videojuegos que permite crear juegos en 2D y 3D. Utilizado para desarrollar "Dungeon Gunner".
        •	C# (C Sharp): Lenguaje de programación orientado a objetos desarrollado por Microsoft, utilizado en Unity para la lógica de programación del juego.
        •	IDE (Entorno de Desarrollo Integrado): Aplicación de software que proporciona facilidades comprehensivas a los programadores para el desarrollo de software. Visual Studio es un ejemplo utilizado en este proyecto.
        •	Sprite: Gráfico bidimensional que es integrado o controlado en un escenario más grande, generalmente en videojuegos.
        •	AI (Inteligencia Artificial): Simulaciones de procesos de inteligencia humana por máquinas, especialmente sistemas computacionales. En "Dungeon Gunner", se refiere a la lógica detrás de los movimientos y comportamientos de los enemigos.
        •	GUI (Interfaz Gráfica de Usuario): Medio de interacción entre el usuario y los dispositivos digitales, implementado en el juego para menús, mapas y otras funciones.
        •	FPS (Frames Por Segundo): Unidad de medida para la velocidad de reproducción de video y animaciones digitales, crucial para la fluidez del juego.
        •	Bug: Error o fallo en un videojuego que produce resultados no deseados o imprevistos.
        •	Debugging: Proceso de identificar y corregir errores en el software.
        •	Asset: Cualquier recurso de juego, incluidos gráficos, sonidos, códigos de programación y otros elementos digitales utilizados para construir el juego.


    1.4	Referencias

        1.	I Unity Documentation: Documentación oficial de Unity que proporciona guías completas sobre el desarrollo de juegos, programación en C#, y uso del motor Unity.
        •	Enlace: Unity Documentation
        2.	Microsoft C# Documentation: Documentación oficial de Microsoft sobre el lenguaje de programación C#, utilizado para la programación de scripts en Unity.
        •	Enlace: Microsoft C# Docs
        3.	"Game Programming Patterns" por Robert Nystrom: Libro que ofrece patrones de diseño para el desarrollo de videojuegos, ayudando a resolver problemas comunes en la programación de juegos.
        •	Disponible en: Game Programming Patterns
        4.	"The Art of Game Design: A Book of Lenses" por Jesse Schell: Este libro proporciona una visión profunda sobre el proceso de diseño de videojuegos, enfocándose en cómo crear experiencias de juego más envolventes y efectivas.
        •	Disponible en: The Art of Game Design



    1.5	Visión General

        Dungeon Gunner es un videojuego de plataforma 2D que sirve como un eje central en la educación práctica de diseño y desarrollo de videojuegos en la Universidad Privada de Tacna. Este proyecto no solo está diseñado para fortalecer las habilidades técnicas y creativas de los estudiantes, sino también para integrar de manera efectiva a todos los participantes del curso en un proceso colaborativo y dinámico de creación.

<div style="page-break-after: always; visibility: hidden">\pagebreak</div>

2. <span id="_Toc52661347" class="anchor"></span>**Posicionamiento**

    2.1	Oportunidad de negocio

        El proyecto "Dungeon Gunner" presenta una oportunidad única para fusionar la educación teórica con la experiencia práctica en desarrollo de videojuegos, ofreciendo a los estudiantes de la Universidad Privada de Tacna una formación integral. Este juego no solo tiene como objetivo facilitar la aplicación práctica de habilidades de programación y diseño, sino también mejorar la eficiencia y efectividad del aprendizaje mediante la automatización de procesos y la reducción de los tiempos de desarrollo. A través de este proyecto, los estudiantes podrán experimentar directamente la satisfacción de crear un producto funcional y atractivo, mientras adquieren habilidades cruciales que incrementan su empleabilidad y preparación para la industria del videojuego, garantizando así un alto nivel de calidad educativa y satisfacción general.

    2.2	Definición del problema

        En el ámbito académico de la programación y diseño de videojuegos, a menudo se observa una desconexión entre los conocimientos teóricos impartidos y su aplicación práctica en proyectos reales. Los estudiantes enfrentan desafíos como la falta de experiencia en el manejo de proyectos completos, desde la conceptualización hasta la implementación y el lanzamiento. Esto conduce a retrasos en los proyectos estudiantiles, errores no detectados durante las fases de desarrollo y una preparación inadecuada para los desafíos del entorno laboral real. Además, la falta de una plataforma integrada para la gestión y revisión de cambios en tiempo real limita la capacidad de los estudiantes para adaptarse y responder eficazmente a los problemas y cambios durante el ciclo de vida del desarrollo del software.

        "Dungeon Gunner" se propone abordar estos problemas al proporcionar una experiencia de desarrollo realista y controlada, donde los estudiantes pueden aprender a gestionar y ajustar sus proyectos activamente. El juego servirá como un caso de estudio vivo, donde las actualizaciones, cambios y la gestión del proyecto son elementos centrales, permitiendo a los estudiantes ver el impacto directo de sus decisiones y trabajo en un producto final.


<div style="page-break-after: always; visibility: hidden">\pagebreak</div>

3. <span id="_Toc52661348" class="anchor"></span>**Vista General del Producto**

    3.1	Resumen de los interesados

    | EInteresados | Representante | Papel |
    |--------------|--------------|--------------|
    | Chino Conde, Oswaldo Jesus| FRepresentante del Cliente, jefe de Proyecto| Representante de la aprobación del financiamiento, responsable de la ejecución del proyecto|
    | Vela Vargas, Abraham| Analista/Programador| Desarrolla sistemas y aplicaciones de software|



    3.2	Resumen de los usuarios

        Los usuarios son todas aquellas personas involucradas directamente en el uso del sistema. A continuación, se presenta una lista de los usuarios:

    | Nombre               | Descripción                                                               |
    |----------------------|---------------------------------------------------------------------------|
    | 1. Estudiantes       | Desarrollan y prueban el juego.                                           |
    | 2. Profesor          | Supervisa el proyecto y dirige el equipo.                                 |
    | 3. Compañeros de Curso| Colaboran en la revisión y pruebas del juego.                            |
    | 4. Usuarios Externos | Jugadores externos que pueden probar el juego para ofrecer feedback.      |
    | 5. Comité Académico  | Evalúa el juego como parte del resultado del curso y sugiere mejoras.     |




    3.3	Entorno de usuario

        El cliente podrá registrarse e identificarse para ingresar al sistema dependiendo del nivel de privilegios que se otorga a cada usuario.

    | Perfiles de Usuario | Descripción |
    |---------------------|-------------|
    | **Representante**   | Ing. Patrick José Cuadros Quiroga |
    | **Tipo**            | Entiende y conoce el estado actual del desarrollo de videojuegos y tiene una visión a largo plazo sobre la integración de prácticas educativas en tecnología. |
    | **Descripción**     | Autoridad de supervisión y aprobación académica. El Ing. Cuadros Quiroga es fundamental en la estructuración de los criterios de evaluación y en asegurar la alineación del proyecto con los objetivos educativos del curso. |
    | **Responsabilidades** | Gerente - Representante: Supervisa el desarrollo del proyecto "Dungeon Gunner" y tiene autoridad sobre la aprobación de las fases del proyecto. Asegura que el proyecto cumpla con los estándares académicos y los objetivos de aprendizaje. Proporciona dirección estratégica para la integración de nuevas tecnologías y metodologías en el curso. |
    | **Criterios de Éxito** | El éxito es la finalización del proyecto dentro del tiempo estimado del curso académico. Debe haber una percepción general de que el proyecto satisface las necesidades educativas de los estudiantes y contribuye positivamente a su preparación profesional. |
    | **Implicación**     | Revisor principal de los requisitos y entregables del proyecto. Participa en las revisiones periódicas y proporciona retroalimentación crítica para las mejoras del juego. |
    | **Entregables**     | Documentación de revisión de proyecto. Evaluaciones de desempeño del estudiante. Informe final de proyecto. |
    | **Comentarios de Problemas** | Ninguno identificado hasta la fecha. |




    3.4	Perfiles de los interesados

    | Perfiles de Interesados | Detalles |
    |-------------------------|----------|
    | **Representante**       | Jefe del proyecto |
    | **Tipo**                | Responsable de la ejecución del proyecto |
    | **Descripción**         | Usuario Experto |
    | **Responsabilidades**   | - Asegurar que todas las fases del proyecto "Dungeon Gunner" cumplan con los objetivos establecidos.<br> - Coordinar y supervisar las actividades del equipo de desarrollo para garantizar la calidad y la coherencia del juego.<br> - Gestionar la integración de todos los componentes del juego, desde la programación hasta el diseño artístico. |
    | **Criterios de Éxito**  | - La finalización exitosa del juego conforme a los requisitos y estándares del curso.<br> - La satisfacción general de los estudiantes y el docente con el resultado final del proyecto.<br> - Cumplimiento de los plazos establecidos para las entregas de las diferentes etapas del proyecto. |
    | **Implicación**         | - Tomar decisiones clave sobre el diseño y las características del juego.<br> - Proporcionar dirección técnica y apoyo a los estudiantes.<br> - Validar y aprobar los entregables del proyecto. |
    | **Entregables**         | - Planificación completa del proyecto.<br> - Documentación técnica y de diseño del juego.<br> - Versión final del juego "Dungeon Gunner". |
    | **Comentarios de Problemas** | Ninguno identificado hasta la fecha, preparado para abordar cualquier desafío que pueda surgir durante el desarrollo. |


    3.5	Perfiles de los Usuarios

    | Perfil de Usuario Administrador | Detalles |
    |---------------------------------|----------|
    | **Representante**               | Administrador |
    | **Descripción**                 | Administrador responsable de gestionar y supervisar toda la plataforma de desarrollo del juego. |
    | **Tipo**                        | Asigna y gestiona los privilegios y roles de los usuarios dentro del entorno de desarrollo del juego |
    | **Responsabilidades**           | - Gestiona y supervisa todos los aspectos técnicos del proyecto.<br> - Asegura el acceso y la integridad de la base de datos del proyecto.<br> - Mantiene el control sobre la documentación técnica y el avance del proyecto.<br> - Supervisa y controla las versiones y revisiones del juego. |
    | **Criterios de Éxito**          | - El éxito del administrador se mide por la estabilidad y eficiencia del entorno de desarrollo.<br> - Asegurar que todos los miembros del equipo tengan los recursos necesarios para cumplir sus tareas.<br> - Satisfacción de los desarrolladores con las herramientas y recursos proporcionados. |
    | **Implicación**                 | - Responsable de tomar decisiones críticas relacionadas con la tecnología y la infraestructura del proyecto.<br> - Proporciona y valida toda la información técnica necesaria para el desarrollo del juego. |
    | **Entregables**                 | - Informes de estado y rendimiento del sistema.<br> - Documentación actualizada de la configuración y administración del sistema. |
    | **Comentarios de Problemas**    | Ninguno hasta la fecha; preparado para resolver cualquier desafío técnico que pueda surgir durante el desarrollo del proyecto. |


    3.6	Necesidades de los interesados y usuarios

    | Necesidades | Prioridad | Inquietudes | Solución Actual | Solución Propuesta |
    |-------------|-----------|-------------|-----------------|--------------------|
    | Sistema de gestión de proyectos de desarrollo del juego | Alta | Necesidad de organizar y gestionar los recursos, tareas y avances del proyecto. | No existe | Desarrollar un módulo dentro del sistema de desarrollo que permita gestionar recursos, tareas y avances del proyecto. |
    | Gestión de la documentación y artefactos del juego | Alta | Requerir un sistema que permita gestionar y revisar la documentación y artefactos generados en el desarrollo del juego. | No existe | Implementar una plataforma de gestión documental integrada al entorno de desarrollo para almacenar, gestionar y revisar los documentos del proyecto. |
    | Interfaz del sistema debe ser fácil de usar | Alta | La interfaz debe permitir una navegación intuitiva y eficiente para todos los usuarios involucrados. | No existe | Desarrollar una interfaz de usuario clara y amigable con tecnología web moderna que facilite la interacción con el sistema. |
    | Sistema debe ser rápido y eficiente | Media | El sistema debe cargar y responder rápidamente para no interrumpir el flujo de trabajo de desarrollo. | No existe | Optimizar el backend del sistema para asegurar tiempos de respuesta rápidos y un rendimiento eficiente. |


<div style="page-break-after: always; visibility: hidden">\pagebreak</div>

4. <span id="_Toc52661349" class="anchor"></span>**Estudio de
    Factibilidad**

    4.1	Perspectiva del producto

        El proyecto "Dungeon Gunner" ofrece un enfoque innovador y educativo para el desarrollo de videojuegos en un entorno académico. Al centrarse en la creación de un juego de plataforma 2D, el sistema no solo está diseñado para enseñar a los estudiantes los principios básicos y avanzados de la programación y el diseño de juegos, sino también para mejorar la gestión y colaboración dentro de los equipos de proyecto.

    4.2	Resumen de capacidades

        A continuación, se mostrará un listado con los beneficios que obtendrá el cliente a partir de la implementación del proyecto:

    | Beneficio del Cliente                            | Características que lo Apoyan |
    |--------------------------------------------------|-------------------------------|
    | Gestión eficiente de usuarios                    | El sistema contará con un módulo de mantenimiento automatizado para la gestión de usuarios. |
    | Gestión y administración automatizada de proyectos | El sistema incluirá un módulo de proyecto que permitirá gestionar y administrar los proyectos y sus entregables de manera automatizada, facilitando también la asignación de equipos. |
    | Generación y gestión ágil de solicitudes de cambios | Existirá un módulo de cambios dedicado a gestionar y procesar las solicitudes de cambios eficientemente. |
    | Seguridad y respaldo de la información          | El sistema asegurará la seguridad mediante respaldos regulares de la base de datos y la información de los documentos generados, junto con sus revisiones. |


    4.3	Suposiciones y dependencias

        Suposiciones:
        •	Permisos de Implementación: Se asume que todos los permisos necesarios para la implementación y el despliegue del juego "Dungeon Gunner" han sido obtenidos. Esto incluye permisos de software, uso de herramientas y plataformas de desarrollo, y cualquier autorización académica requerida.
        •	Base para Nuevos Módulos: "Dungeon Gunner" actuará como la base principal sobre la cual se podrán desarrollar futuros proyectos y módulos relacionados con el curso. No depende de sistemas previos, lo que facilita la adaptación y expansión según los requisitos futuros del curso.

        Dependencias:
        •	Conexión a Internet: Es esencial que todos los usuarios, especialmente los estudiantes y profesores, tengan acceso a una conexión a internet estable. Esta conexión es crucial para el acceso a recursos en línea, actualizaciones del juego, y colaboración en tiempo real.
        •	Dispositivos Necesarios: Los usuarios deben tener acceso a dispositivos adecuados, ya sean móviles o de escritorio, para desarrollar y probar el juego. Esto asegura que los estudiantes puedan trabajar tanto en el aula como de manera remota.
        •	Capacitación en Uso de la Aplicación: Se presupone que los usuarios tienen el conocimiento necesario o recibirán la formación adecuada para utilizar las herramientas y plataformas de desarrollo asociadas al proyecto.


    4.4	Costos y precios

    | Descripción          | Costo     |
    |----------------------|-----------|
    | Costo General        | S/. 890.00  |
    | Costo Operativo      | S/. 3,250.00 |
    | Costo del Ambiente   | S/. 2,000.00 |
    | Costo de Personal    | S/. 9,300.00 |
    | **Total**            | **S/. 15,440.00** |

    4.5	Licenciamiento e instalación

        En el desarrollo del juego "Dungeon Gunner", es fundamental asegurar que todas las herramientas y software utilizados estén debidamente licenciados para evitar cualquier inconveniente legal. Dado que el proyecto utiliza principalmente Unity, una plataforma líder para el desarrollo de juegos, se deben gestionar las licencias apropiadas para el uso educativo y de desarrollo.

        Costos de Licenciamiento:
        La licencia de Unity para educadores y estudiantes suele ser gratuita bajo ciertas condiciones, pero para uso comercial o a gran escala, se requiere una licencia pagada. Considerando que el proyecto es para fines académicos, se optará por la versión gratuita siempre que cumpla con los términos y condiciones de Unity.

        Implementación del Software: El proceso de implementación de "Dungeon Gunner" incluye dos componentes principales:

        Base de Datos:

        Descripción: Se utilizará una base de datos para manejar toda la información relacionada con el progreso del juego, los puntajes de los usuarios, y otros datos relevantes.

        Instalación y Configuración: Se proporcionarán instrucciones detalladas para configurar la base de datos en un entorno local o en la nube, dependiendo de las necesidades del curso y la disponibilidad de los recursos.

        Servidor de Aplicaciones:

        Descripción: Para soportar el juego en línea y permitir múltiples usuarios, se configurará un servidor de aplicaciones.

        Instalación: Las instrucciones incluirán la instalación del servidor de aplicaciones y la configuración necesaria para soportar el juego, incluyendo detalles sobre cómo desplegar el juego y hacerlo accesible para los estudiantes y evaluadores.


<div style="page-break-after: always; visibility: hidden">\pagebreak</div>



5. <span id="_Toc52661350" class="anchor"></span>**Características del producto**

    El juego DungeonGunner se desarrollará con las siguientes funciones.
    1.	Autenticación de Usuario
    2.	Gestión de Metodologías de Desarrollo
    3.	Control de Versiones de Proyectos
    4.	Administración de Usuarios
    5.	Registro y Gestión de Cambios
    6.	Ordenación de Cambios
    7.	Gestión de Activos del Juego (Assets)
    8.	Planificación de Proyectos


<div style="page-break-after: always; visibility: hidden">\pagebreak</div>

6. <span id="_Toc52661351" class="anchor"></span>**Restricciones**

    1.	Dependencia de Conexión a Internet: El funcionamiento del sistema web y el acceso a la base de datos requieren una conexión de internet estable.
    2.	Presupuesto Limitado: El desarrollo del proyecto no debe exceder el costo total estimado de S/. 15,440.00, como se detalla en el documento de factibilidad.
    3.	Registro de Usuarios: El administrador del sistema es responsable de registrar a todos los usuarios, incluyendo el jefe de proyectos.
    4.	Modularidad del Sistema: El sistema debe ser diseñado de manera modular para facilitar su adaptación en diferentes ambientes y contextos de uso.
    5.	Ausencia de Auditoría: El proceso de desarrollo del sistema web no incluye un proceso de auditoría formal, lo cual puede limitar la verificación formal de calidad y seguridad.


<div style="page-break-after: always; visibility: hidden">\pagebreak</div>

7. <span id="_Toc52661352" class="anchor"></span>**Rangos de Calidad**

    Disponibilidad:
    
    •	La aplicación web de "Dungeon Gunner" será accesible a través de los navegadores más populares: Safari, Google Chrome y Microsoft Edge.
    •	Estará disponible 24/7, sujeta a una conexión estable a internet.

    Seguridad:

    •	Se requerirá autenticación de usuario para acceder a la aplicación, asegurando el acceso seguro y controlado.
    •	Las conexiones serán protegidas y monitoreadas para mantener la integridad y confidencialidad de los datos.

    Adaptabilidad:

    •	La interfaz de la aplicación será responsiva, asegurando una buena usabilidad y visibilidad en diferentes dispositivos y tamaños de pantalla.

    Rendimiento:

    •	Los tiempos de respuesta de la aplicación serán optimizados para no superar un segundo en condiciones normales de conexión a internet, mejorando así la experiencia de usuario.


<div style="page-break-after: always; visibility: hidden">\pagebreak</div>

8. <span id="_Toc52661353" class="anchor"></span>**Precedencia y Prioridad**

    La priorización de las características del sistema "Dungeon Gunner" se establece para garantizar que el desarrollo se enfoque en los aspectos más cruciales para el éxito del proyecto. Las características se ordenan de la más importante a la menos importante como sigue:
    1.	Participación de los Participantes:
    •	Prioridad máxima para asegurar que todos los usuarios, especialmente los estudiantes, estén activamente involucrados y comprometidos con el uso del sistema.
    2.	Control y Monitoreo en Tiempo Real:
    •	Esencial para la gestión efectiva del proyecto, permitiendo a los usuarios y al profesorado supervisar el progreso y realizar ajustes en tiempo real.
    3.	Interfaces Amigables y Sencillas:
    •	Importante para asegurar que el sistema sea fácil de usar y accesible para todos los usuarios, independientemente de su experiencia técnica.
    4.	Gestión de Tareas Muy Fáciles de Realizar:
    •	Aunque crucial, esta característica tiene una prioridad ligeramente menor en comparación con las demás, con el enfoque en que la gestión de tareas sea intuitiva pero integral dentro del diseño del sistema.


<div style="page-break-after: always; visibility: hidden">\pagebreak</div>

9. <span id="_Toc52661354" class="anchor"></span>**Otros requerimientos del producto**

    Estándares legales

    •	Protección de Datos Personales: El juego "Dungeon Gunner" cumplirá con las normativas locales e internacionales de protección de datos personales, asegurando que toda información de los usuarios sea manejada de manera segura y confidencial.

    Estándares de Comunicación

    •	Estándares Web: El sistema utilizará tecnologías estándar web como HTML, TCP/IP, y HTTP para garantizar compatibilidad y accesibilidad en diferentes plataformas y dispositivos.

    Estándares de Cumplimiento de la Plataforma

    •	Gestión de Seguridad de la Información: Se seguirán las prácticas recomendadas por el estándar ISO/IEC 27001 para asegurar la integridad y seguridad de la información del proyecto.

    Estándares de Calidad y Seguridad

    •	ISO/IEC 25010: El desarrollo de "Dungeon Gunner" se alineará con el estándar ISO/IEC 25010, que define características de calidad del software como funcionalidad, fiabilidad, usabilidad, eficiencia, mantenibilidad, y seguridad. Este enfoque garantizará que el juego no solo funcione eficazmente sino que también ofrezca una experiencia de usuario segura y satisfactoria.


<div style="page-break-after: always; visibility: hidden">\pagebreak</div>

<span id="_Toc52661355" class="anchor"></span>**CONCLUSIONES**

•	Viabilidad y Beneficio: 

Se concluye que "Dungeon Gunner" cumple con los objetivos de aprendizaje y desarrollo profesional planteados, ofreciendo un buen retorno de la inversión educativa y técnica para los estudiantes y la institución educativa.

<div style="page-break-after: always; visibility: hidden">\pagebreak</div>

<span id="_Toc52661356" class="anchor"></span>**RECOMENDACIONES**

•	Adopción de Buenas Prácticas:

Se recomienda seguir las mejores prácticas y lecciones aprendidas de proyectos similares, y adherirse a metodologías de gestión de proyectos como PMBOK para asegurar la calidad y el éxito del desarrollo del juego.

<div style="page-break-after: always; visibility: hidden">\pagebreak</div>

<span id="_Toc52661357" class="anchor"></span>**BIBLIOGRAFIA**

<div style="page-break-after: always; visibility: hidden">\pagebreak</div>

<span id="_Toc52661358" class="anchor"></span>**WEBGRAFIA**

<div style="page-break-after: always; visibility: hidden">\pagebreak</div>
