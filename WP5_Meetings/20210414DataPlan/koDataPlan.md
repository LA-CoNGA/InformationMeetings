---
title: "(re) Kick off Data Plan"
author: "WP5"
date: \today
#https://stackoverflow.com/questions/25654845/how-can-i-create-a-text-box-for-a-note-in-markdown
header-includes:
    - \usepackage[most]{tcolorbox}
    - \definecolor{light-yellow}{rgb}{1, 0.95, 0.7}
    - \newtcolorbox{myquote}{colback=light-yellow,grow to right by=-10mm,grow to left by=-10mm, boxrule=0pt,boxsep=0pt,breakable}
    - \newcommand{\cuadro}[2]{\begin{myquote} \textbf{#1:} \emph{#2} \end{myquote}}
---

# Objetivo

* Ponernos al día.
* Llevar el data plan a la mesa de discusión del consorcio lo más pronto posible

# ¿Qué hay?

* Borrador data plan TUD (Joany) <- desarrollo más adelante.
* Trabajo en licencias y metadatos (Alex +  Reina)

# Propuesta (para organizar una conversación general dentro del consorcio)
## El objetivo principal de un data plan para LA-CoNGA en lenguaje entendible por humanos:
* Preservar (repositorios, formatos, respaldos, plataforma)
* Proveer (volver accesible, metadatos)
* Proteger (clasificar contenido, autoría, autorización de uso, información sensible, privacidad)

\cuadro{Proveer + proteger}{= balance \bf{openness and protection}}

### Objetivo indirecto:
Promover la discusión de buenas prácticas compartidas en un contexto internacional-interinstitucional, donde el tema no se ha tratado de forma nada homogénea

# Documento TUD
## FAIR
Los datos deben ser FAIR (importancia de estar en línea y de los metadatos: preservar y proveer)

* Buscable (F)
* Accesible (A)
* Interoperable (I)
* Reutilizable (R)

# Algunas tareas pendientes
## Reconocer y clasificar contenidos:
* Académicos
	* Planes de estudio: carga horaria, competencias y/o temas, bibliografia
	* Planificaciones: plan de clases pormenorizado, distribución semanal
	* Apuntes
	* Láminas
	* Videos de apoyo
	* Videos de clase
	* Listas de Staff: quienes han participado, cuando, función desempeñada
	* Material de práctica: guias, proyectos, datasets, jupyter notebooks*
	* Tareas: Ejercicios de desarrollo, datasets (experimentales o sintéticos), propuestas de proyectos, códigos (procesamiento, simulación), láminas de exposición

# Algunas tareas pendientes
## Reconocer y clasificar contenidos:
* Especial: 
	* datos Ciencia Ciudadana, data sheets, firmwares, proyectos específicos,
	* hackatons: propuestas, productos.. (?) listas de participación, staff, etc
* Evaluación: 
	* Plan de calidad
	* Calificaciones estudiantes
	* Otras evaluaciones de cumplimiento del proyecto (ej. timesheets, diversity, etc)

# Algunas tareas pendientes
## Reconocer y clasificar contenidos:
* Historia:
	* Minutas.
	* Láminas de discusión en reuniones (como estas)
* Documentos: 
	* Convenios
	* MVV
	* CoC
	* Proyecto aprobado
	* Manual de imagen
	* Plantillas varias
	* Piezas publicitarias
	* Publicaciones RRSS


# Pregunta
* Datos que consume el proyecto(?)
	* Plan de trazabilidad (citar las cosas)

# Documento TUD y Algunas tareas pendientes
## Más plataforma

* Definir repositorios compartidos, institucionales, tiempo de compromiso, embargos, etc

## Instituciones

* Armonizar instituciones. 
	* Es muy necesario dinamizar la discusión interna. En particular la apertura aún genera muchas dudas.

* Data protection officer. ¿Es necesario? JAL cree que sí 
	* DO: debe empaparse en este tema, ayuda a desarrollar el plan y advierte posibles puntos problemáticos. ¿Puede ser un grupito?

# Referencias

## Políticas europeas:

* https://ec.europa.eu/research/participants/docs/h2020-funding-guide/cross-cutting-issues/open-access-dissemination_en.htm
* https://www.dfg.de/en/research_funding/proposal_review_decision/applicants/research_data/index.html

## Recomendaciones de socios RedCLARA(?) políticas de las instituciones académicas (generan una gran parte de los productos)

* UCV
	* Promueve la difusión de sus productos y su repositorio saber.ucv.ve
	* Se adhiere a la declaración de Berlín de 2003
	* Openaccess UCV: http://fisica.ciens.ucv.ve/direccion/documentos/2016/20161130_DeclaracionBerlinOpenAccess.pdf (Artículo 1)
	* Medios digitales: http://fisica.ciens.ucv.ve/direccion/documentos/2016/20161130_ReglamentoMediosDigitales.pdf (artículo 4)

# 

* USB: JAL no consigue info
* Colombia: JAL no consigue info
* Ecuador: hay visibilidad de sus repositorios
* Perú: 
	* UNI: JAL no consigue info. 
	* San Marcos: referencia a politicas establecidas en Budapest 2002 (documento que seguiría en Berlin 2003)

* \cuadro{Declaración de Berlín}{Está borrada del mapa. ¿Por qué?}

# Declaración de Berlín (extracto)

De: https://openaccess.mpg.de/Berlin-Declaration

Nuestra  misión  de  diseminar  el  conocimiento  será  incompleta  si  la  información  no  es  puesta a disposición de la sociedad de manera expedita y amplia. Es necesario apoyar  nuevas posibilidades de diseminación del conocimiento, no solo a través de la manera clásica, sino  también  utilizando  el  paradigma  del  acceso  abierto por medio de la Internet.  Definimos el acceso abierto como una amplia fuente de conocimiento humano y patrimonio cultural aprobada por la comunidad científica. 

Para  que  se  pueda  alcanzar  la  visión  de  una  representación  del  conocimiento  global  y  accesible, la Web del futuro tiene que ser sustentable, interactiva y transparente. El contenido y las herramientas de software deben ser libremente accesibles y compatibles. 
