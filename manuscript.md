---
title: Etapa 2. Ejecución Gobierno. Incremento 1
keywords:
- SOA
- madurez
- gobierno
- FNA
lang: en-US
date-meta: '2023-07-11'
author-meta:
- Harry Wong, ing.
- Wilson Morales, ing.
- Flavio Hernandez, ing.
- Viviana M. Martinez, ing.
header-includes: |
  <!--
  Manubot generated metadata rendered from header-includes-template.html.
  Suggest improvements at https://github.com/manubot/manubot/blob/main/manubot/process/header-includes-template.html
  -->
  <meta name="dc.format" content="text/html" />
  <meta property="og:type" content="article" />
  <meta name="dc.title" content="Etapa 2. Ejecución Gobierno. Incremento 1" />
  <meta name="citation_title" content="Etapa 2. Ejecución Gobierno. Incremento 1" />
  <meta property="og:title" content="Etapa 2. Ejecución Gobierno. Incremento 1" />
  <meta property="twitter:title" content="Etapa 2. Ejecución Gobierno. Incremento 1" />
  <meta name="dc.date" content="2023-07-11" />
  <meta name="citation_publication_date" content="2023-07-11" />
  <meta property="article:published_time" content="2023-07-11" />
  <meta name="dc.modified" content="2023-07-11T20:55:44+00:00" />
  <meta property="article:modified_time" content="2023-07-11T20:55:44+00:00" />
  <meta name="dc.language" content="en-US" />
  <meta name="citation_language" content="en-US" />
  <meta name="dc.relation.ispartof" content="Manubot" />
  <meta name="dc.publisher" content="Manubot" />
  <meta name="citation_journal_title" content="Manubot" />
  <meta name="citation_technical_report_institution" content="Manubot" />
  <meta name="citation_author" content="Harry Wong, ing." />
  <meta name="citation_author_institution" content="Arquitecto SOA, Stefanini" />
  <meta name="citation_author" content="Wilson Morales, ing." />
  <meta name="citation_author_institution" content="Software, Aplicaciones" />
  <meta name="citation_author" content="Flavio Hernandez, ing." />
  <meta name="citation_author_institution" content="SOA, Arquitectura" />
  <meta name="citation_author" content="Viviana M. Martinez, ing." />
  <meta name="citation_author_institution" content="Analista, Proyectos" />
  <link rel="canonical" href="https://hwong23.github.io/fna-dd-f2-e3/" />
  <meta property="og:url" content="https://hwong23.github.io/fna-dd-f2-e3/" />
  <meta property="twitter:url" content="https://hwong23.github.io/fna-dd-f2-e3/" />
  <meta name="citation_fulltext_html_url" content="https://hwong23.github.io/fna-dd-f2-e3/" />
  <meta name="citation_pdf_url" content="https://hwong23.github.io/fna-dd-f2-e3/manuscript.pdf" />
  <link rel="alternate" type="application/pdf" href="https://hwong23.github.io/fna-dd-f2-e3/manuscript.pdf" />
  <link rel="alternate" type="text/html" href="https://hwong23.github.io/fna-dd-f2-e3/v/725ccffc5f7d79fa303364b9e199d60af51be20c/" />
  <meta name="manubot_html_url_versioned" content="https://hwong23.github.io/fna-dd-f2-e3/v/725ccffc5f7d79fa303364b9e199d60af51be20c/" />
  <meta name="manubot_pdf_url_versioned" content="https://hwong23.github.io/fna-dd-f2-e3/v/725ccffc5f7d79fa303364b9e199d60af51be20c/manuscript.pdf" />
  <meta property="og:type" content="article" />
  <meta property="twitter:card" content="summary_large_image" />
  <link rel="icon" type="image/png" sizes="192x192" href="https://manubot.org/favicon-192x192.png" />
  <link rel="mask-icon" href="https://manubot.org/safari-pinned-tab.svg" color="#ad1457" />
  <meta name="theme-color" content="#ad1457" />
  <!-- end Manubot generated metadata -->
bibliography:
- content/manual-references.bib
- content/manual-references.json
manubot-output-bibliography: output/references.json
manubot-output-citekeys: output/citations.tsv
manubot-requests-cache-path: ci/cache/requests-cache
manubot-clear-requests-cache: false
...




<small><em>Los productos contractuales (PR0n) de esta etapa ([Web](https://hwong23.github.io/fna-dd-f2-e3/v/725ccffc5f7d79fa303364b9e199d60af51be20c/))
están basados en el resultado de la consultoría "Arquitectura E-Service",
[Sharepoint STEF@725ccff](https://stefaninilatam.sharepoint.com/:f:/r/sites/PROYECTOARQUITECTURAE-SERVICEFNA/Documentos%20compartidos/General/Repositorio%20SOA/Procesos%20Fase%20II/181-2020.%20E-SERV.%20Fase%202-ETAPA%200.%20docx?csf=1&web=1&e=BiNcBP)
del July 11, 2023.
</em></small>

|    **Versión** del producto 1.725ccff de 11 Jul 2023



<br>

## Autores



+ **Harry Wong, ing.**
  <br>
    · ![Usuario](images/github.svg){.inline_icon width=16 height=16}
    [e_hwong](https://github.com/e_hwong)
    <br>
  <small>
     Arquitecto SOA, Stefanini
  </small>

+ **Wilson Morales, ing.**
  <br>
    · ![Usuario](images/github.svg){.inline_icon width=16 height=16}
    [wmorales](https://github.com/wmorales)
    <br>
  <small>
     Software, Aplicaciones
  </small>

+ **Flavio Hernandez, ing.**
  <br>
    · ![Usuario](images/github.svg){.inline_icon width=16 height=16}
    [fhernandez](https://github.com/fhernandez)
    <br>
  <small>
     SOA, Arquitectura
  </small>

+ **Viviana M. Martinez, ing.**
  <br>
    · ![Usuario](images/github.svg){.inline_icon width=16 height=16}
    [vmmartinez](https://github.com/vmmartinez)
    <br>
  <small>
     Analista, Proyectos
  </small>


::: {#correspondence}
✉ — Enviar mensajes a Harry Wong, ing. \<e_hwong@stefanini.com\>.


:::

<br>



## Objetivo del Documento
Entrega de los productos de la Etapa 3, PR06. Modelos actualizados de los ítems de arquitectura impactados por el proyecto, del proyecto Gobierno SOA: Políticas, flujos de trabajo y personas que ejercitan y conforman (cumplen) con el gobierno SOA del FNA a desplegar a cargo de la oficina de arquitectura.

##  Control de Cambios {.page_break_before}
| Tema           | PRY01 Gobierno SOA FNA     |
|----------------|----------------------------|
| Palabras clave | SOA, E-Service, FNA, Análisis de brecha, GAP, Comparativa              |
| Autor          |                            |
| Fuente         |                            |
| Versión        | 1.725ccff del 11 Jul 2023 |
| Vínculos       | [N003a Vista Segmento SOA FNA](N03a%a20Vsta%20aSegenta%20SOA%20FNA.md) |

<br>

<br>

<div style="page-break-before: always;"></div>
\newpage



## Contenidos
\toc




---
geometry:
  - top=1in
  - bottom=1in
fignos-cleveref: True
fignos-plus-name: Fig.
fignos-caption-name: Imagen
tablenos-caption-name: Tabla
...

<div style="page-break-before: always;"></div>
\newpage

>    E-Service. Fase II
>
>    PRY01. Gobierno SOA del FNA. Contenido de los Productos Contractuales
>
>    Contrato 1812020
>
>    FNA, Stefanini
>
>    11 Jul 2023
>
>    **Versión** 1.725ccff

<br>

# Producto 6: PR06. Modelos actualizados de los ítems de arquitectura impactados por el proyecto
De las primeras actividades de esta consultoría (Organización, Fase I, 2022) fue la organización de la información de arquitectura e ingeniería entregada al proyecto en su momento. El desglose de esta información es como sigue

| Tipo de Entrada      |          |
|----------------------|---------:|
| Aplicación           | 107      |
| Arquitectura         | 352      |
| Funcional            | 61       |
| Información          | 248      |
| Servicios            | 543      |
| **Total Contenidos** | **1311** |

Table: Repositorio FNA (versión 0.1). Elementos de la línea base del repositorio de arquitectura FNA, versión 0.1.

<br>

Esta información constituye lo que llamamos el inventario inicial, línea base, del repositorio de arquitectura, versión 0.1.

A este producto del proyecto, PRY01, y en virtud de las actividades desarrolladas aquí (las cuales han actualizados la línea base de este repositorio) le corresponde hacer entrega de estas modificaciones al FNA.

<br>

**Nota**: los análisis de este producto están dirigidos a cumplir los objetivos del proyecto PRY01, Gobierno SOA: desarrollo, gestión, gobierno de arquitectura y adopción.

<br>

## Justificación
Uno de los objetivos nominales del Gobierno SOA del FNA, objeto de este proyecto, es _aumentar la relevancia de los modelos de arquitectura de la empresa: instrumentos de encuentro para el entendimiento, análisis, y comunicación entre actores (ingenieros, arquitectos y proveedores)_. Los modelos son por tanto el sujeto principal y la evidencia de la existencia del gobierno. De ahí que los modelos de arquitectura del FNA modificados a razón de este proyecto tengan la importancia tal para ser entregados en plena contribuición al repositorio de arquitectura y a este gobierno.

## Contenidos
1. Detalle de ítems de la línea base del FNA actualizados 
1. Repositorio de arquitectura del FNA, actualizado, versión 0.2
1. Herramienta de navegación del repositorio de arquitectura del FNA versión 0.2

<br>

## Criterios de Aceptación
* Repositorio de arquitectura del FNA, actualizado, versión 0.2
* Herramienta de navegación del repositorio de arquitectura del FNA versión 0.2

<br>

## Repositorio de Arquitectura del FNA, versión 0.1
![Artefactos del repositorio de arquitectura del FNA.](images/repofna.png){#fig: width=}

_Fuente: Diagnóstico SOA. E-Service (2022)._


## Modelo de Implementación del PRY01
![Plan de Implementación del Proyecto Gobierno SOA del FNA (PRY01), 2023. Junio 2023 a julio 2023](images/pry1gobierno.jpg){#fig: width=}

_Fuente: Elaboración propia._

<br>


---
geometry:
  - top=1in
  - bottom=1in
fignos-cleveref: True
fignos-plus-name: Fig.
fignos-caption-name: Imagen
tablenos-caption-name: Tabla
...

<div style="page-break-before: always;"></div>
\newpage

>    E-Service. Fase II
>
>    PRY01. Gobierno SOA del FNA. Contenido de los Productos Contractuales
>
>    Contrato 1812020
>
>    FNA, Stefanini
>
>    11 Jul 2023
>
>    **Versión** 1.725ccff

<br>

# Producto 7: PR07. Indicadores de Efectividad de Gobierno y Arquitectura
Más allá de los índices propuestos por el diagnóstico de madurez SOA desarrollado en la Fase 1 de esta consultoría (@eservices1-22), es clave que el FNA mantenga el vínculo de sus activos de tecnología (infraestructura, hardware, software, servicios SOA, ...) con el contexto de negocio de las vicepresidencias de Operaciones, de Crédito, y demás áreas. Esto es, y para los fines de este producto, _el principal indicador del gobierno SOA por desarrollar, mantener y vigilar, es la existencia y vigencia de estos vínculos entre los contextos de negocio y las arquitecturas FNA_, vínculo que extiende su utilidad a la toma de decisiones y selección de proyectos de brecha tecnológica e infraestructura del FNA.

<br>

**Nota**: los análisis de este producto están dirigidos a cumplir los objetivos del proyecto PRY01, Gobierno SOA: desarrollo, gestión, gobierno de arquitectura y adopción.

<br>

## Justificación
De los indicadores de eficacia postulados en este producto, el del _vínculo de los contextos negocio-tecnología SOA_ es el que más valor reporta al gobierno SOA y a las arquitecturas del FNA. Su utilización puede alcanzar a otras disciplinas de gestión TI: identifica y justifica los costos de un cambio en relación al _Valor de negocio_ que este pueda traer. Sirve también como criterio cuantitativo para los procesos de la mayoría de las decisiones de cambio, mejora, inversión, recorte, y otras operaciones propias de la gestión de la tecnología SOA. Por último, es la base para medir la confiabilidad de los modelos, y por ende, de los los análisis que sobre estos los arquitectos de la Oficina de Arquitectura del FNA realicen (ver @eservices7-23). Estas razones elevan a este como el principal indicador de gobierno SOA a desarrollar.

## Contenidos
1. Sistema de métricas (indicadores clave de gestión) del gobierno SOA del FNA 
1. Sistema de métricas (indicadores) de la Oficina de Arquitectura del FNA
1. Consideraciones para el uso y despliegue de tableros de gestión de arquitectura

<br>

## Criterios de Aceptación
* Validación del despliegue de tableros de gestión de la arquitectura FNA
* Lista de indicadores de arquitectura posibles en el FNA

<br>

## Modelo de Implementación del PRY01
![Plan de Implementación del Proyecto Gobierno SOA del FNA (PRY01), 2023. Junio 2023 a julio 2023](images/pry1gobierno.jpg){#fig: width=}

_Fuente: Elaboración propia._

<br>


<div style="page-break-before: always;"></div>
\newpage

| Tema           | Indicadores de Efectividad de Gobierno y Arquitectura: **Sistema de Medidas del Gobierno SOA del FNA**                          |
|----------------|------------------------------------------------------------|
| Palabras clave | SOA, Contexto, Áreas, Procesos, Efectividad, Factibilidad, Medición  |
| Autor          |                                                            |
| Fuente         |                                                            |
| Versión        | **1.725ccff** del 11 Jul 2023                       |
| Vínculos       | [Ejecución Plan de Trabajo SOA](onenote:#N001d.sharepoint.com); [Procesos de Negocio FNA](onenote:#N003a.com) |

<br>

[007na1c. Capacidades y Gobierno SOA](https://uniandes-my.sharepoint.com/personal/ha_wong10_uniandes_edu_co/_layouts/OneNote.aspx?id=%2Fpersonal%2Fha_wong10_uniandes_edu_co%2FDocuments%2FBlocs%20de%20notas%2FHarry%20Alfredo%20%40%20Work&wd=target%28SOA%2FSOA.one%7C54D369EF-B7AB-4AC1-8D87-059C763394A1%2F007na1c.%20Capacidades%20y%20Gobierno%20SOA%7CEE66B38D-4CD5-4280-BFBA-B5FFE3E0A1C7%2F%29)


# Sistema de Medida del Gobierno SOA del FNA
Lo más importante para la mejora de un proceso, en este caso, el de gobierno SOA del FNA, es seleccionar las medidas que mejor resulten para el objeto a optimizar: gobierno SOA. Su desempeño para ser más concreto. A esto se suma que las potenciales medidas deben ser seleccionadas según criterios inherentes al objeto observado. En nuestro caso y contexto, un ejemplo de criterio de seleccieon es el nivel de madurez tecnológico de la empresa. Sin perjuicio de todo lo anterior, la tarea de elaborar un sistema de medidas puede llegar a ser inconmensurable, por un lado; y por otro, muchos indicadores solo abundan en confusión. 

    Nota: en este contexto diferenciamos los conceptos de medición y métricas en la siguiente manera. 
<br>    

Por estas razones, y en arreglo a las reglas prácticas citadas, la de la complejidad de medición y la de confusión cognitiva, tomaremos en este ejercicio la estrategia de _empezar con pocas métricas_.


## Conceptos del Sistema de Medidas del Gobierno SOA del FNA
Aclararemos los dos conceptos más importantes del sistema de medidas propuesto. La medida y la métrica (y cuándo esta es un indicador).

### Medida
Una medida (o su equivalente en este contexto, los indicadores clave de gestión), en apego a la definición inglesa, es todo un aspecto a medir, y por tanto, reúne a varias métricas. Ejemplo: la eficacia del proceso de inversión (...) 

### Métrica
Mientras que la segunda, la métrica, es un dato que pertenece a una medida. Ejemplo: una métrica de eficacia es las solicitudes de trabajo de arquitectura atendidas en un período de tiempo. 

### Indicador (índice)
Esta última se convierte en indicador cuando sintetiza varias métricas en un solo número. Ejemplo de esto último es el índice de retono de valor de una inversión, en el que se incorporan una serie de métricas de riesgo, utilidad, entre otras, y quedan expresadas en un solo valor.

<br>

## Medidas de Desempeño del Gobierno SOA del FNA
El objetivo de los índices de desempeño desarrollados en este capítulo es crear un sistema de medición de gobierno SOA que de cuenta en cifras del progreso (o retroceso) de las capacidades de la arquitectura SOA del FNA. Así mismo, estas métricas e indicadores propuestos del sistema de medición propuesto servirán luego para establecer las tareas para sostener dicho sistema, y las herramientas de gestión, como tableros, que se dispongan sobre este.

<br>

    Nota: capacidad de arquitectura y madurez SOA son conceptos distintos. Sin embargo, en la práctica son susceptibles de equivalencia debido a la corelación positiva observable entre ellos. Es decir, cuando las capaciddades de las arquitecturas aumentan, por lo general, aumenta también el nivel de madurez SOA de una arquitectura. De ahí que consideramos como equivalentes el nivel de desarrollo de las capacidades de la arquitrctura y los niveles de madurez SOA.

<br>

Para efectos del sistema de medición de gobierno SOA del FNA desarrollamos en este ejercicio de gobierno SOA del FNA las dos medidas sintéticas siguientes: 

1. Medida de efectividad de costos de la arquitectura
1. Medida de factibilidad de proyectos de arquitectura

<br>

Estas dos medidas, _efectividad y factibilidad_, que son aplicables a todos los proyectos de arquitectura SOA, y extensibles a otros en cuanto a software, y tecnología se refiere, le dan información a un gobierno tal que puede interceder en dos problemáticas importantes, problemáticas que sin estos datos no podría. Nos referimos a los problemas de inversión de tecnología, que va de la mano del desempeño de los proveedores del FNA; y los problemas de realización o ejecución exitosa de proyectos de arquitectura SOA.

A continuación explicamos estas dos medidas. 

## Medidas de Efectividad de Costos de Inversión en Arquitectura
Es común que los proyectos SOA, y como ya se dijo, también otros proyectos de índole tecnológica como migración de datos, o componentes, que impulsan los proveedores y fabricantes puedan caer en lo que llamaremos el _área de inefectividad de costos de inversión de tecnología_. Ejemplo: implementar SOA para procesos de negocio (nivel de madurez 3, o superior en la mayoría de los marcos de madurez) solo para necesidades intradepartamentales es un derroche de costos. Es inefectivo: cuesta más de lo que se puede aprovechar. 

![Gobierno SOA del FNA Sistema de medición gobierno arquitecturas FNA. Medidas de efectividad de costos de inversión](images/efectividad.png){#fig: width=}

_Fuente: elaboración propia._

<br>

## Medidas de Factibilidad de Proyectos de Arquitectura
Este indicador complementa al anterior desde una perspectiva de ejecución, ya no de costos. Si el índice de efectividad de inversión presentado antes nos dice si esta o aquella iniciativa podrá ser aprovechada o no por el FNA tanto como su costo invertido, este otro indicador es más crítico. 

Este indicador detiene por completo, en el mejor de los casos, un proyecto de trabajo de arquitectura previo a su ejecución si este puntúa muy bajo su nivel de factibilidad. Ejemplo: si las capacidades de arquitectura son básicas (poco desarrolladas) en una empresa, y la dirección decide comprometer a un proveedor en un proyecto de SOA empresarial, del cual se espera entre otras cosas una integración expedita y resiliente con entidades externos al FNA como alguno de los que integran su cadena de proveedores, este proyecto no sería posible: no es factible conseguir un nivel de despliegue SOA empresarial cuando el nivel de las capacidades de la arquitetura de la empresa, que es equivalente a hablar de madurez SOA, es bajo o básico. Simplemente es imposible.

![Gobierno SOA del FNA Sistema de medición gobierno arquitecturas FNA. Medidas de factibilidad de proyectos](images/factibilidad.png){#fig: width=}

_Fuente: elaboración propia._

<br>


<div style="page-break-before: always;"></div>
\newpage

# Referencias {.page_break_before}
<!-- Explicitly insert bibliography here -->
<div id="refs">@eservices1-22 @eservices3-22 @eservices4-22 @eservices5-23 @eservices6-12 @bptrends07
</div>


