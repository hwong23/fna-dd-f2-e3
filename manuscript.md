---
title: Etapa 2. Ejecución Gobierno. Incremento 1
keywords:
- SOA
- madurez
- gobierno
- FNA
lang: en-US
date-meta: '2023-07-06'
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
  <meta name="dc.date" content="2023-07-06" />
  <meta name="citation_publication_date" content="2023-07-06" />
  <meta property="article:published_time" content="2023-07-06" />
  <meta name="dc.modified" content="2023-07-06T18:13:43+00:00" />
  <meta property="article:modified_time" content="2023-07-06T18:13:43+00:00" />
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
  <link rel="alternate" type="text/html" href="https://hwong23.github.io/fna-dd-f2-e3/v/1202fa45bb205a7f099dead46f7c3134e7afcebd/" />
  <meta name="manubot_html_url_versioned" content="https://hwong23.github.io/fna-dd-f2-e3/v/1202fa45bb205a7f099dead46f7c3134e7afcebd/" />
  <meta name="manubot_pdf_url_versioned" content="https://hwong23.github.io/fna-dd-f2-e3/v/1202fa45bb205a7f099dead46f7c3134e7afcebd/manuscript.pdf" />
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




<small><em>Los productos contractuales (PR0n) de esta etapa([Web](https://hwong23.github.io/fna-dd-f2-e3/v/1202fa45bb205a7f099dead46f7c3134e7afcebd/))
están basados en el resultado de la consultoría "Arquitectura E-Service",
[Sharepoint STEF@1202fa4](https://stefaninilatam.sharepoint.com/:f:/r/sites/PROYECTOARQUITECTURAE-SERVICEFNA/Documentos%20compartidos/General/Repositorio%20SOA/Procesos%20Fase%20II/181-2020.%20E-SERV.%20Fase%202-ETAPA%200.%20docx?csf=1&web=1&e=BiNcBP)
del July 6, 2023.
</em></small>

|    **Versión** del producto 1.1202fa4 de 06 Jul 2023



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
| Versión        | 1.1202fa4 del 06 Jul 2023 |
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
>    06 Jul 2023
>
>    **Versión** 1.1202fa4

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
Uno de los objetivos nominales del Gobierno SOA del FNA, objeto de este proyecto, es _aumentar la relevancia de los de modelos de arquitectura: instrumentos de encuentro para el entendimiento, análisis, y comunicación entre actores_. Los modelos son por tanto el sujeto y principal la evidencia de la existencia del gobierno. De ahí que los modelos de arquitectura del FNA modificados a razón de este proyecto han sido modificados, tengan la importancia de un entregable.

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


<div style="page-break-before: always;"></div>
\newpage

# Referencias {.page_break_before}
<!-- Explicitly insert bibliography here -->
<div id="refs">@eservices1-22 @eservices2-22 @eservices3-22 @eservices4-22 @eservices5-23
* TOGAF 9.1. Risk Management (2023). 
     En https://pubs.opengroup.org/architecture/togaf9-doc/arch/chap27.html
* Software Architecture Evaluation Methods – A survey. P. Shanmugapriya, Research Scholar, Department of CSE, SCSVMV University, Enathur, Tamilnadu,INDIA
</div>



