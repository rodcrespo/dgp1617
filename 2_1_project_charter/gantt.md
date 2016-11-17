```{.mermaid width=10000}
gantt
    dateFormat  YYYY-MM-DD
    title Sportacus Gantt

    section Dirección del proyecto

    Definición de los requisitos del sistema  :done, m1, 2016-10-15, 2016-11-04
    Planificación :done, m1_1, 2016-10-15, 2016-10-28
    Gestión de costes y calendario :done, m1_2, 2016-10-18, 2016-10-21
    Administración del proyecto :done, m1_3, 2016-10-20, 2016-10-28
    Gestión de riesgos y calidad :done, m1_4, 2016-10-27, 2016-11-04

    Asignación de las tareas de trabajo :active, m2, 2016-10-31, 2016-11-05


    section Ingeniería del sistema

    Planificación técnica : m3, 2016-11-02, 2016-11-10
    Supervisión técnica : m4, 2016-11-02, 2017-02-04
    Definición de requisitos de negocio : m1_5, 2016-11-02, 2016-11-04
    Definición de requisitos del sistema  : m3_1, 2016-11-02, 2016-11-04


    section Software

    Diseño de la implementación :crit, m5, 2016-11-02, 2016-11-10  
    Desarrollo de software : m6, 2016-11-11, 2017-02-01
    Inicio de sesión  : m6_1, after m5, 2016-11-13
    Gestión de perfil : m6_2, after m5, 2016-11-16
    Inicio de actividad :crit, m6_3, after m6_2, 2016-11-28
    Creación de rankings  : m6_4, after m6_2, 2016-12-02
    Búsqueda preliminar actividades y usuarios  : m6_5, after m6_2, 2016-12-05
    Administrar un grupo e integrar publicidad del mismo  : m6_6, after m6_3, 2016-12-22
    Nuevos rankings a nivel de grupo  : m6_7, after m6_6, 2017-01-13
    Búsqueda ampliada : m6_8, after m6_6, 2017-01-17
    Incorporación mapa  :crit m6_9, after m6_8, 2017-01-28
    Gestión de tablas : m6_10, after m6_8, 2017-02-01


    section Pruebas del sistema

    Pruebas y testing :crit, m7, after m6, 2017-02-04


    section Instalación

    Instalación del sistema :crit, m8, after m7, 2017-02-07
    Prueba y verificación de instalación  :crit, m9, after m8, 2017-02-09
    Monitorización del rendimiento de la instalación  : m10, after m8, 2017-02-22


    section Soporte técnico

    Garantía de calidad : m11, after m9, 2017-08-04

```
