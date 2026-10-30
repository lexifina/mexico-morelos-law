# Morelos: law history in git

The law of the State of Morelos (Estado Libre y Soberano de Morelos, Mexico) as a git history: one file per article, one commit per publication that changed it, dated the day it took effect, with the decree as the commit's author. `git blame` names the decree behind every paragraph; `git log` lists every change to an article; checking out a date gives the text in force that day.

It follows the shared design of [lexifina/global-law](https://github.com/lexifina/global-law), which places it at `mx-mor/`. Mexico's federal law is in [lexifina/mexico-law](https://github.com/lexifina/mexico-law).

The text is in Spanish, exactly as the source prints it.

## What this repository holds

123 ordenamientos with 1580 versions so far: the constitution first, then the codes and laws in force, added in parts. Regulations, decrees and repealed laws are not included yet.

| Folder | Ordenamiento | Versions | History |
| --- | --- | ---: | --- |
| `constitucion-politica/` | CONSTITUCION POLITICA DEL ESTADO LIBRE Y SOBERANO DE MORELOS | 180 | as first published, then each reform: 19 November 1930 to 30 January 2026 |
| `codigo-civil/` | CODIGO CIVIL PARA EL ESTADO LIBRE Y SOBERANO DE MORELOS | 22 | as first published, then each reform: 16 October 1993 to 14 May 2026 |
| `codigo-de-instituciones-y-procedimientos-electorales/` | CODIGO DE INSTITUCIONES Y PROCEDIMIENTOS ELECTORALES PARA EL ESTADO DE MORELOS | 15 | as first published, then each reform: 30 June 2014 to 25 December 2025 |
| `codigo-etico-para-el-instituto-de-capacitacion-para-el-traba/` | CODIGO ETICO PARA EL INSTITUTO DE CAPACITACION PARA EL TRABAJO DEL ESTADO DE MORELOS | 1 | as first published: 20 November 2010 |
| `codigo-familiar/` | CODIGO FAMILIAR PARA EL ESTADO LIBRE Y SOBERANO DE MORELOS | 89 | as first published, then each reform: 9 September 2006 to 8 October 2026 |
| `codigo-fiscal/` | CODIGO FISCAL PARA EL ESTADO DE MORELOS | 9 | as first published, then each reform: 12 December 2015 to 3 March 2026 |
| `codigo-penal/` | CODIGO PENAL PARA EL ESTADO DE MORELOS | 159 | as first published, then each reform: 7 November 1996 to 8 October 2026 |
| `codigo-procesal-civil/` | CODIGO PROCESAL CIVIL PARA EL ESTADO LIBRE Y SOBERANO DE MORELOS | 12 | as first published, then each reform: 16 October 1993 to 5 September 2024 |
| `codigo-procesal-familiar/` | CODIGO PROCESAL FAMILIAR PARA EL ESTADO LIBRE Y SOBERANO DE MORELOS | 29 | as first published, then each reform: 9 September 2006 to 29 August 2019 |
| `ley-de-acceso-de-las-mujeres-a-una-vida-libre-de-violencia/` | LEY DE ACCESO DE LAS MUJERES A UNA VIDA LIBRE DE VIOLENCIA PARA EL ESTADO DE MORELOS | 38 | as first published, then each reform: 6 December 2007 to 14 May 2026 |
| `ley-de-agricultura-familiar/` | LEY DE AGRICULTURA FAMILIAR DEL ESTADO DE MORELOS | 4 | as first published, then each reform: 14 February 2023 to 25 September 2025 |
| `ley-de-amnistia/` | LEY DE AMNISTIA PARA EL ESTADO LIBRE Y SOBERANO DE MORELOS | 2 | as first published, then each reform: 20 July 2023 to 25 September 2025 |
| `ley-de-apoyo-alimentario-para-personas-con-discapacidad-perm/` | LEY DE APOYO ALIMENTARIO PARA PERSONAS CON DISCAPACIDAD PERMANENTE TOTAL Y EN POBREZA EXTREMA DEL ESTADO DE MORELOS | 4 | as first published, then each reform: 10 March 2016 to 25 September 2025 |
| `ley-de-asistencia-social-y-corresponsabilidad-ciudadana/` | LEY DE ASISTENCIA SOCIAL Y CORRESPONSABILIDAD CIUDADANA PARA EL ESTADO DE MORELOS | 16 | as first published, then each reform: 22 November 2007 to 8 October 2026 |
| `ley-de-asociaciones-publico-privadas-para/` | LEY DE ASOCIACIONES PUBLICO PRIVADAS PARA DEL ESTADO DE MORELOS Y SUS MUNICIPIOS | 1 | as first published: 10 March 2021 |
| `ley-de-beneficios-estimulos-y-recompensas-a-las-personas-vet/` | LEY DE BENEFICIOS, ESTIMULOS Y RECOMPENSAS A LAS PERSONAS VETERANAS DE LA REVOLUCION EN EL ESTADO DE MORELOS -- ANTES LEY DE BENEFICIOS, ESTIMULOS Y RECOMPENSAS A LOS VETERANOS DE LA REVOLUCION EN EL ESTADO DE MORELOS -- | 4 | as first published, then each reform: 6 November 1974 to 25 September 2025 |
| `ley-de-bioaditivo-y-fomento-para-el-reciclaje-de-aceites-veg/` | LEY DE BIOADITIVO Y FOMENTO PARA EL RECICLAJE DE ACEITES VEGETALES Y GRASAS ANIMALES RESIDUALES PARA EL ESTADO DE MORELOS | 3 | as first published, then each reform: 2 September 2011 to 6 March 2014 |
| `ley-de-busqueda-de-personas/` | LEY DE BUSQUEDA DE PERSONAS PARA EL ESTADO DE MORELOS | 2 | as first published, then each reform: 13 July 2023 to 1 January 2026 |
| `ley-de-catastro-municipal/` | LEY DE CATASTRO MUNICIPAL PARA EL ESTADO DE MORELOS | 5 | as first published, then each reform: 31 July 2003 to 2 March 2017 |
| `ley-de-contratos-de-colaboracion-publico-privada/` | LEY DE CONTRATOS DE COLABORACION PUBLICO PRIVADA PARA EL ESTADO DE MORELOS | 6 | as first published, then each reform: 15 August 2008 to 8 October 2026 |
| `ley-de-coordinacion-hacendaria/` | LEY DE COORDINACION HACENDARIA DEL ESTADO DE MORELOS | 22 | as first published, then each reform: 8 April 2004 to 3 March 2026 |
| `ley-de-coordinacion-para-el-desarrollo-metropolitano/` | LEY DE COORDINACION PARA EL DESARROLLO METROPOLITANO DEL ESTADO DE MORELOS | 6 | as first published, then each reform: 20 January 2011 to 30 July 2015 |
| `ley-de-cultura-civica/` | LEY DE CULTURA CIVICA DEL ESTADO DE MORELOS | 13 | as first published, then each reform: 31 March 2011 to 2 May 2024 |
| `ley-de-cultura-y-derechos-culturales/` | LEY DE CULTURA Y DERECHOS CULTURALES PARA EL ESTADO DE MORELOS | 1 | as first published: 15 February 2024 |
| `ley-de-desarrollo-economico-sustentable/` | LEY DE DESARROLLO ECONOMICO SUSTENTABLE DEL ESTADO LIBRE Y SOBERANO DE MORELOS | 12 | as first published, then each reform: 5 June 2008 to 21 May 2026 |
| `ley-de-desarrollo-forestal-sustentable/` | LEY DE DESARROLLO FORESTAL SUSTENTABLE DEL ESTADO DE MORELOS | 6 | as first published, then each reform: 6 December 2007 to 16 May 2024 |
| `ley-de-desarrollo-rural-sustentable/` | LEY DE DESARROLLO RURAL SUSTENTABLE DEL ESTADO DE MORELOS | 17 | as first published, then each reform: 5 March 2009 to 25 December 2025 |
| `ley-de-desarrollo-social/` | LEY DE DESARROLLO SOCIAL PARA EL ESTADO DE MORELOS | 5 | as first published, then each reform: 7 November 2013 to 21 December 2023 |
| `ley-de-desarrollo-proteccion-e-integracion-de-las-personas-a/` | LEY DE DESARROLLO, PROTECCION E INTEGRACION DE LAS PERSONAS ADULTAS MAYORES PARA EL ESTADO LIBRE Y SOBERANO DE MORELOS | 17 | as first published, then each reform: 8 August 2010 to 8 October 2026 |
| `ley-de-deuda-publica/` | LEY DE DEUDA PUBLICA PARA EL ESTADO DE MORELOS | 2 | as first published, then each reform: 23 December 2016 to 13 July 2023 |
| `ley-de-educacion/` | LEY DE EDUCACION DEL ESTADO DE MORELOS | 12 | as first published, then each reform: 18 March 2021 to 3 September 2026 |
| `ley-de-entrega-recepcion-de-la-administracion-publica/` | LEY DE ENTREGA RECEPCION DE LA ADMINISTRACION PUBLICA PARA EL ESTADO DE MORELOS Y SUS MUNICIPIOS | 9 | as first published, then each reform: 17 December 2011 to 19 February 2026 |
| `ley-de-espacios-cardioprotegidos/` | LEY DE ESPACIOS CARDIOPROTEGIDOS PARA EL ESTADO DE MORELOS | 2 | as first published, then each reform: 22 June 2023 to 2 October 2025 |
| `ley-de-expropiacion-por-causas-de-utilidad-publica/` | LEY DE EXPROPIACION POR CAUSAS DE UTILIDAD PUBLICA | 2 | as first published, then each reform: 25 August 1994 to 2 April 2015 |
| `ley-de-filmaciones/` | LEY DE FILMACIONES PARA EL ESTADO DE MORELOS | 3 | as first published, then each reform: 26 March 2026 to 12 September 2026 |
| `ley-de-fiscalizacion-y-rendicion-de-cuentas/` | LEY DE FISCALIZACION Y RENDICION DE CUENTAS DEL ESTADO DE MORELOS | 5 | as first published, then each reform: 22 July 2017 to 5 September 2024 |
| `ley-de-fomento-a-las-actividades-de-las-organizaciones-de-la/` | LEY DE FOMENTO A LAS ACTIVIDADES DE LAS ORGANIZACIONES DE LA SOCIEDAD CIVIL DEL ESTADO DE MORELOS | 8 | as first published, then each reform: 13 December 2007 to 25 September 2025 |
| `ley-de-fomento-apicola-y-proteccion-del-proceso-de-polinizac/` | LEY DE FOMENTO APICOLA Y PROTECCION DEL PROCESO DE POLINIZACION PARA EL ESTADO DE MORELOS | 1 | as first published: 1 June 2023 |
| `ley-de-fomento-de-la-cultura-del-cuidado-del-agua-en-el-esta/` | LEY DE FOMENTO DE LA CULTURA DEL CUIDADO DEL AGUA EN EL ESTADO DE MORELOS | 4 | as first published, then each reform: 23 August 2012 to 25 September 2025 |
| `ley-de-fomento-y-desarrollo-de-los-derechos-y-cultura-de-las/` | LEY DE FOMENTO Y DESARROLLO DE LOS DERECHOS Y CULTURA DE LAS COMUNIDADES Y PUEBLOS INDIGENAS DEL ESTADO DE MORELOS | 4 | as first published, then each reform: 18 March 2012 to 13 November 2014 |
| `ley-de-fomento-y-proteccion-pecuaria/` | LEY DE FOMENTO Y PROTECCION PECUARIA DEL ESTADO DE MORELOS | 8 | as first published, then each reform: 16 August 2012 to 10 April 2025 |
| `ley-de-igualdad-de-derechos-y-oportunidades-entre-mujeres-y/` | LEY DE IGUALDAD DE DERECHOS Y OPORTUNIDADES ENTRE MUJERES Y HOMBRES PARA EL ESTADO DE MORELOS -- ANTES LEY DE IGUALDAD DE DERECHOS Y OPORTUNIDADES ENTRE HOMBRES Y MUJERES EN EL ESTADO DE MORELOS -- | 7 | as first published, then each reform: 17 January 2013 to 29 October 2025 |
| `ley-de-ingresos-del-gobierno/` | LEY DE INGRESOS DEL GOBIERNO DEL ESTADO DE MORELOS PARA EL EJERCICIO FISCAL DEL 1 DE ENERO AL 31 DE DICIEMBRE DE 2026 | 1 | as first published: 1 January 2026 |
| `ley-de-innovacion-ciencia-y-tecnologia/` | LEY DE INNOVACION, CIENCIA Y TECNOLOGIA PARA EL ESTADO DE MORELOS | 6 | as first published, then each reform: 4 August 2005 to 17 June 2021 |
| `ley-de-jovenes-emprendedores/` | LEY DE JOVENES EMPRENDEDORES DEL ESTADO DE MORELOS | 3 | as first published, then each reform: 30 September 2012 to 1 August 2024 |
| `ley-de-justicia-administrativa/` | LEY DE JUSTICIA ADMINISTRATIVA PARA EL ESTADO DE MORELOS | 6 | as first published, then each reform: 22 July 2017 to 14 May 2026 |
| `ley-de-justicia-alternativa-en-materia-penal/` | LEY DE JUSTICIA ALTERNATIVA EN MATERIA PENAL PARA EL ESTADO DE MORELOS | 4 | as first published, then each reform: 21 August 2008 to 11 December 2014 |
| `ley-de-la-comision-de-derechos-humanos/` | LEY DE LA COMISION DE DERECHOS HUMANOS DEL ESTADO DE MORELOS | 8 | as first published, then each reform: 9 June 2007 to 8 October 2026 |
| `ley-de-la-defensoria-publica/` | LEY DE LA DEFENSORIA PUBLICA DEL ESTADO DE MORELOS | 7 | as first published, then each reform: 4 April 2013 to 5 September 2024 |
| `ley-de-la-division-territorial/` | LEY DE LA DIVISION TERRITORIAL DEL ESTADO DE MORELOS | 28 | as first published, then each reform: 19 December 1932 to 17 September 2026 |
| `ley-de-las-personas-adolescentes-y-jovenes-en-el-estado-de-m/` | LEY DE LAS PERSONAS ADOLESCENTES Y JOVENES EN EL ESTADO DE MORELOS | 7 | as first published, then each reform: 4 April 2015 to 30 September 2024 |
| `ley-de-los-derechos-de-las-ninas-ninos-y-adolescentes/` | LEY DE LOS DERECHOS DE LAS NIÑAS, NIÑOS Y ADOLESCENTES DEL ESTADO DE MORELOS | 36 | as first published, then each reform: 14 October 2015 to 8 October 2026 |
| `ley-de-mercados/` | LEY DE MERCADOS DEL ESTADO DE MORELOS | 7 | as first published, then each reform: 28 October 1965 to 2 March 2017 |
| `ley-de-movilidad-transporte-y-seguridad-vial/` | LEY DE MOVILIDAD, TRANSPORTE Y SEGURIDAD VIAL DEL ESTADO DE MORELOS | 2 | as first published, then each reform: 26 November 2025 to 24 April 2026 |
| `ley-de-nomenclatura-de-los-bienes/` | LEY DE NOMENCLATURA DE LOS BIENES DEL ESTADO DE MORELOS Y DE SUS MUNICIPIOS | 3 | as first published, then each reform: 18 August 2012 to 25 September 2025 |
| `ley-de-obra-publica-y-servicios-relacionados-con-la-misma/` | LEY DE OBRA PUBLICA Y SERVICIOS RELACIONADOS CON LA MISMA DEL ESTADO DE MORELOS | 18 | as first published, then each reform: 28 December 2000 to 1 August 2024 |
| `ley-de-ordenamiento-territorial-y-desarrollo-urbano-sustenta/` | LEY DE ORDENAMIENTO TERRITORIAL Y DESARROLLO URBANO SUSTENTABLE DEL ESTADO DE MORELOS | 15 | as first published, then each reform: 27 August 2009 to 14 May 2026 |
| `ley-de-participacion-ciudadana/` | LEY DE PARTICIPACION CIUDADANA PARA EL ESTADO DE MORELOS | 1 | oldest version available: 13 November 2025 |
| `ley-de-planeacion/` | LEY DE PLANEACION PARA EL ESTADO DE MORELOS | 2 | as first published, then each reform: 1 October 2024 to 1 October 2024 |
| `ley-de-predios-baldios/` | LEY DE PREDIOS BALDIOS DEL ESTADO DE MORELOS | 2 | as first published, then each reform: 8 May 1979 to 25 September 2025 |
| `ley-de-prestacion-de-servicios-de-atencion-cuidado-y-desarro/` | LEY DE PRESTACION DE SERVICIOS DE ATENCION, CUIDADO Y DESARROLLO INTEGRAL INFANTIL DEL ESTADO DE MORELOS | 1 | as first published: 5 September 2024 |
| `ley-de-prestaciones-de-seguridad-social-de-las-instituciones/` | LEY DE PRESTACIONES DE SEGURIDAD SOCIAL DE LAS INSTITUCIONES POLICIALES Y DE PROCURACION DE JUSTICIA DEL SISTEMA ESTATAL DE SEGURIDAD PUBLICA | 2 | as first published, then each reform: 23 January 2014 to 5 March 2015 |
| `ley-de-presupuesto-participativo/` | LEY DE PRESUPUESTO PARTICIPATIVO DEL ESTADO DE MORELOS | 1 | as first published: 29 February 2020 |
| `ley-de-presupuesto-contabilidad-y-gasto-publico/` | LEY DE PRESUPUESTO, CONTABILIDAD Y GASTO PUBLICO DEL ESTADO DE MORELOS | 17 | as first published, then each reform: 9 February 1995 to 3 March 2026 |
| `ley-de-procedimiento-administrativo/` | LEY DE PROCEDIMIENTO ADMINISTRATIVO PARA EL ESTADO DE MORELOS | 5 | as first published, then each reform: 9 September 2000 to 9 February 2023 |
| `ley-de-proteccion-a-periodistas-y-defensores-de-derechos-hum/` | LEY DE PROTECCION A PERIODISTAS Y DEFENSORES DE DERECHOS HUMANOS DEL ESTADO DE MORELOS | 1 | as first published: 21 August 2018 |
| `ley-de-proteccion-de-datos-personales-en-posesion-de-sujetos/` | LEY DE PROTECCION DE DATOS PERSONALES EN POSESION DE SUJETOS OBLIGADOS DEL ESTADO DE MORELOS | 2 | as first published, then each reform: 27 July 2017 to 24 March 2018 |
| `ley-de-proteccion-y-conservacion-del-maiz-criollo-en-su-esta/` | LEY DE PROTECCION Y CONSERVACION DEL MAIZ CRIOLLO EN SU ESTADO GENETICO PARA EL ESTADO DE MORELOS | 4 | as first published, then each reform: 26 June 2014 to 25 December 2025 |
| `ley-de-proteccion-apoyo-y-promocion-de-la-lactancia-materna/` | LEY DE PROTECCION, APOYO Y PROMOCION DE LA LACTANCIA MATERNA PARA EL ESTADO DE MORELOS | 2 | as first published, then each reform: 1 August 2024 to 2 October 2026 |
| `ley-de-reinsercion-social-y-seguimiento-de-medidas-cautelare/` | LEY DE REINSERCION SOCIAL Y SEGUIMIENTO DE MEDIDAS CAUTELARES | 5 | as first published, then each reform: 25 August 2009 to 4 June 2016 |
| `ley-de-residuos-solidos-y-de-economia-circular-antes-ley-de/` | LEY DE RESIDUOS SOLIDOS Y DE ECONOMIA CIRCULAR -- ANTES LEY DE RESIDUOS SOLIDOS -- PARA EL ESTADO DE MORELOS | 11 | as first published, then each reform: 18 October 2007 to 28 May 2026 |
| `ley-de-responsabilidad-patrimonial/` | LEY DE RESPONSABILIDAD PATRIMONIAL DEL ESTADO DE MORELOS | 3 | as first published, then each reform: 1 January 2012 to 2 March 2017 |
| `ley-de-responsabilidades-administrativas/` | LEY DE RESPONSABILIDADES ADMINISTRATIVAS PARA EL ESTADO DE MORELOS | 3 | as first published, then each reform: 22 July 2017 to 29 February 2024 |
| `ley-de-salud/` | LEY DE SALUD DEL ESTADO DE MORELOS | 81 | as first published, then each reform: 30 June 2005 to 8 October 2026 |
| `ley-de-salud-mental/` | LEY DE SALUD MENTAL DEL ESTADO DE MORELOS | 20 | as first published, then each reform: 1 January 2012 to 8 October 2026 |
| `ley-de-seguridad-privada/` | LEY DE SEGURIDAD PRIVADA PARA EL ESTADO DE MORELOS | 1 | as first published: 11 March 2020 |
| `ley-de-sujetos-protegidos/` | LEY DE SUJETOS PROTEGIDOS PARA EL ESTADO DE MORELOS | 1 | as first published: 13 December 2014 |
| `ley-de-transformacion-digital/` | LEY DE TRANSFORMACION DIGITAL DEL ESTADO DE MORELOS | 1 | as first published: 4 October 2025 |
| `ley-de-transito/` | LEY DE TRANSITO DEL ESTADO DE MORELOS -ANTES TRANSITO Y TRANSPORTE- | 5 | as first published, then each reform: 9 February 1989 to 2 March 2017 |
| `ley-de-transparencia-y-acceso-a-la-informacion-publica/` | LEY DE TRANSPARENCIA Y ACCESO A LA INFORMACION PUBLICA DEL ESTADO DE MORELOS | 8 | as first published, then each reform: 28 April 2016 to 16 October 2025 |
| `ley-de-turismo/` | LEY DE TURISMO PARA EL ESTADO DE MORELOS | 1 | as first published: 26 November 2025 |
| `ley-de-uniformes-gratuitos-para-los-estudiantes-de-educacion/` | LEY DE UNIFORMES GRATUITOS PARA LOS ESTUDIANTES DE EDUCACION BASICA DEL ESTADO DE MORELOS | 2 | as first published, then each reform: 20 April 2017 to 17 July 2017 |
| `ley-de-victimas/` | LEY DE VICTIMAS DEL ESTADO DE MORELOS -- ANTES LEY DE ATENCION Y REPARACION A VICTIMAS DEL DELITO Y DE VIOLACIONES A LOS DERECHOS HUMANOS PARA EL ESTADO DE MORELOS -- | 17 | as first published, then each reform: 18 July 2013 to 6 February 2026 |
| `ley-de-vivienda/` | LEY DE VIVIENDA DEL ESTADO LIBRE Y SOBERANO DE MORELOS | 6 | as first published, then each reform: 22 December 2011 to 30 July 2015 |
| `ley-de-voluntad-anticipada-en-materia-de-salud-para-las-pers/` | LEY DE VOLUNTAD ANTICIPADA EN MATERIA DE SALUD PARA LAS PERSONAS EN SITUACION TERMINAL EN EL ESTADO DE MORELOS | 1 | oldest version available: 29 May 2025 |
| `ley-del-deporte-y-cultura-fisica/` | LEY DEL DEPORTE Y CULTURA FISICA DEL ESTADO DE MORELOS | 18 | as first published, then each reform: 5 July 2007 to 16 May 2024 |
| `ley-del-equilibrio-ecologico-y-la-proteccion-al-ambiente/` | LEY DEL EQUILIBRIO ECOLOGICO Y LA PROTECCION AL AMBIENTE DEL ESTADO DE MORELOS | 3 | as first published, then each reform: 2 September 2022 to 8 October 2026 |
| `ley-del-fondo-morelos-antes-ley-del-instituto-morelense-para/` | LEY DEL FONDO MORELOS - ANTES LEY DEL INSTITUTO MORELENSE PARA EL FINANCIAMIENTO DEL SECTOR PRODUCTIVO- | 6 | as first published, then each reform: 13 August 2009 to 27 September 2019 |
| `ley-del-instituto-de-capacitacion-para-el-trabajo/` | LEY DEL INSTITUTO DE CAPACITACION PARA EL TRABAJO DEL ESTADO DE MORELOS | 3 | as first published, then each reform: 9 July 1992 to 2 April 2015 |
| `ley-del-instituto-de-credito-para-los-trabajadores-al-servic/` | LEY DEL INSTITUTO DE CREDITO PARA LOS TRABAJADORES AL SERVICIO DEL GOBIERNO DEL ESTADO DE MORELOS | 9 | as first published, then each reform: 5 January 1984 to 19 October 2023 |
| `ley-del-notariado/` | LEY DEL NOTARIADO DEL ESTADO DE MORELOS | 2 | as first published, then each reform: 31 August 2018 to 5 September 2024 |
| `ley-del-registro-publico-de-la-propiedad-y-del-comercio/` | LEY DEL REGISTRO PUBLICO DE LA PROPIEDAD Y DEL COMERCIO DEL ESTADO DE MORELOS | 5 | as first published, then each reform: 1 December 2007 to 19 March 2015 |
| `ley-del-servicio-civil/` | LEY DEL SERVICIO CIVIL DEL ESTADO DE MORELOS | 30 | as first published, then each reform: 7 September 2000 to 3 March 2026 |
| `ley-del-sistema-anticorrupcion/` | LEY DEL SISTEMA ANTICORRUPCION DEL ESTADO DE MORELOS | 3 | as first published, then each reform: 20 April 2017 to 12 December 2025 |
| `ley-del-sistema-de-seguridad-publica/` | LEY DEL SISTEMA DE SEGURIDAD PUBLICA DEL ESTADO DE MORELOS | 1 | as first published: 1 January 2026 |
| `ley-estatal-contra-la-delincuencia-organizada/` | LEY ESTATAL CONTRA LA DELINCUENCIA ORGANIZADA | 3 | as first published, then each reform: 21 July 2005 to 2 March 2017 |
| `ley-estatal-de-agua-potable-morelos/` | LEY ESTATAL DE AGUA POTABLE, MORELOS | 11 | as first published, then each reform: 27 July 1995 to 25 December 2025 |
| `ley-estatal-de-apoyo-a-jefas-de-familia/` | LEY ESTATAL DE APOYO A JEFAS DE FAMILIA DEL ESTADO DE MORELOS | 2 | as first published, then each reform: 24 January 2013 to 11 April 2019 |
| `ley-estatal-de-documentacion-y-archivos-de-morelos/` | LEY ESTATAL DE DOCUMENTACION Y ARCHIVOS DE MORELOS | 4 | as first published, then each reform: 17 September 2009 to 2 March 2017 |
| `ley-estatal-de-fauna/` | LEY ESTATAL DE FAUNA DEL ESTADO DE MORELOS | 11 | as first published, then each reform: 3 May 1997 to 15 February 2024 |
| `ley-estatal-de-proteccion-civil-de-morelos/` | LEY ESTATAL DE PROTECCION CIVIL DE MORELOS | 2 | as first published, then each reform: 17 January 2018 to 25 April 2020 |
| `ley-estatal-de-responsabilidades-de-los-servidores-publicos/` | LEY ESTATAL DE RESPONSABILIDADES DE LOS SERVIDORES PUBLICOS | 18 | as first published, then each reform: 25 October 2007 to 29 August 2019 |
| `ley-estatal-para-la-asuncion-del-gobierno-de-la-funcion-de-s/` | LEY ESTATAL PARA LA ASUNCION DEL GOBIERNO DE LA FUNCION DE SEGURIDAD PUBLICA DE LOS MUNICIPIOS Y LAS POLICIAS PREVENTIVAS MUNICIPALES Y DE TRANSITO MUNICIPAL DEL ESTADO DE MORELOS | 3 | as first published, then each reform: 30 August 2012 to 2 October 2025 |
| `ley-estatal-para-la-convivencia-y-seguridad-de-la-comunidad/` | LEY ESTATAL PARA LA CONVIVENCIA Y SEGURIDAD DE LA COMUNIDAD ESCOLAR, MORELOS | 6 | as first published, then each reform: 24 July 2014 to 1 January 2025 |
| `ley-general-de-bienes/` | LEY GENERAL DE BIENES DEL ESTADO DE MORELOS | 10 | as first published, then each reform: 6 July 1989 to 3 March 2026 |
| `ley-general-de-hacienda/` | LEY GENERAL DE HACIENDA DEL ESTADO DE MORELOS | 46 | as first published, then each reform: 6 July 2006 to 3 March 2026 |
| `ley-general-de-hacienda-municipal/` | LEY GENERAL DE HACIENDA MUNICIPAL DEL ESTADO DE MORELOS | 27 | as first published, then each reform: 5 January 1984 to 6 February 2026 |
| `ley-organica-de-el-colegio-de-morelos/` | LEY ORGANICA DE EL COLEGIO DE MORELOS | 3 | as first published, then each reform: 27 August 2015 to 5 September 2024 |
| `ley-organica-de-la-administracion-publica/` | LEY ORGANICA DE LA ADMINISTRACION PUBLICA PARA EL ESTADO LIBRE Y SOBERANO DE MORELOS | 5 | as first published, then each reform: 30 September 2024 to 26 March 2026 |
| `ley-organica-de-la-fiscalia-general/` | LEY ORGANICA DE LA FISCALIA GENERAL DEL ESTADO DE MORELOS | 5 | as first published, then each reform: 12 July 2018 to 26 January 2024 |
| `ley-organica-de-la-universidad-autonoma/` | LEY ORGANICA DE LA UNIVERSIDAD AUTONOMA DEL ESTADO DE MORELOS | 1 | as first published: 21 May 2008 |
| `ley-organica-del-centro-de-conciliacion-laboral/` | LEY ORGANICA DEL CENTRO DE CONCILIACION LABORAL DEL ESTADO DE MORELOS | 1 | as first published: 1 October 2021 |
| `ley-organica-del-instituto-de-desarrollo-y-fortalecimiento-m/` | LEY ORGANICA DEL INSTITUTO DE DESARROLLO Y FORTALECIMIENTO MUNICIPAL DEL ESTADO DE MORELOS | 7 | as first published, then each reform: 21 July 2001 to 2 October 2025 |
| `ley-organica-del-poder-judicial-morelos/` | LEY ORGANICA DEL PODER JUDICIAL, MORELOS | 19 | as first published, then each reform: 13 April 1995 to 5 September 2024 |
| `ley-organica-del-tribunal-de-justicia-administrativa/` | LEY ORGANICA DEL TRIBUNAL DE JUSTICIA ADMINISTRATIVA DEL ESTADO DE MORELOS | 10 | as first published, then each reform: 22 July 2017 to 17 June 2024 |
| `ley-organica-del-tribunal-unitario-de-justicia-penal-para-ad/` | LEY ORGANICA DEL TRIBUNAL UNITARIO DE JUSTICIA PENAL PARA ADOLESCENTES DEL ESTADO DE MORELOS | 1 | as first published: 22 April 2021 |
| `ley-organica-municipal/` | LEY ORGANICA MUNICIPAL DEL ESTADO DE MORELOS | 103 | as first published, then each reform: 14 August 2003 to 3 September 2026 |
| `ley-organica-para-el-congreso/` | LEY ORGANICA PARA EL CONGRESO DEL ESTADO DE MORELOS | 71 | as first published, then each reform: 12 May 2007 to 11 October 2026 |
| `ley-para-el-impulso-de-la-cultura-de-la-legalidad/` | LEY PARA EL IMPULSO DE LA CULTURA DE LA LEGALIDAD DEL ESTADO DE MORELOS | 1 | as first published: 9 October 2014 |
| `ley-para-la-administracion-de-bienes-asegurados-de-la-fiscal/` | LEY PARA LA ADMINISTRACION DE BIENES ASEGURADOS DE LA FISCALIA GENERAL DEL ESTADO DE MORELOS | 2 | as first published, then each reform: 11 December 2014 to 2 October 2025 |
| `ley-para-la-atencion-y-proteccion-de-las-personas-con-la-con/` | LEY PARA LA ATENCION Y PROTECCION DE LAS PERSONAS CON LA CONDICION DEL ESPECTRO AUTISTA DEL ESTADO DE MORELOS | 1 | as first published: 28 May 2025 |
| `ley-para-la-conservacion-y-proteccion-del-arbolado-urbano/` | LEY PARA LA CONSERVACION Y PROTECCION DEL ARBOLADO URBANO PARA EL ESTADO LIBRE Y SOBERANO DE MORELOS | 2 | as first published, then each reform: 20 July 2023 to 25 September 2025 |
| `ley-para-la-declaracion-especial-de-ausencia-de-personas-des/` | LEY PARA LA DECLARACION ESPECIAL DE AUSENCIA DE PERSONAS DESAPARECIDAS EN EL ESTADO DE MORELOS | 1 | as first published: 7 July 2022 |

## Source

The legislation compilation of Mexico's Supreme Court, the Suprema Corte de Justicia de la Nación (SCJN), at <https://legislacion.scjn.gob.mx/>. For each ordenamiento it lists every publication in the state's official gazette (Periódico Oficial) that changed it (decree, erratum, ruling), with the date of publication, the decree's extract and the whole consolidated text as it stood after that publication. Each version here is one of those texts.

## Dates

- Each commit is dated at **noon, America/Mexico_City, on the day the publication took effect**: the day its own transitorios name, as SCJN's extract quotes them (most often the day after publication). When a decree names none, 3 days after publication.
- A consolidated text holds every change published before it, so it is never dated before the latest of their in-force days. Different in-force days for parts of one decree are not split.
- An act's first commit is its first publication when SCJN holds the original text; otherwise it is the oldest version SCJN holds.
- Versions that take effect after the retrieval day are on the `futuro` branch, never merged into `main`.

## Files

`<act>/art-005.md` is Artículo 5, `art-005-bis.md` Artículo 5 Bis; `encabezado.md` holds the title, the promulgation and preamble; `transitorios-original.md` the original transitory articles and `transitorios-<date>.md` those of the reform published that day. Section headings and editor's notes such as "(REFORMADO, P.O. ...)" stay in the file of the article they stand before. One paragraph per line.

## How it is checked

- Every version of every act is read back from git on the day it took effect and on the day before (`tools/check_repo.py`); both must match `corpus.json`.
- The letters and digits of every version equal those of SCJN's own text of that version (read independently of the parser), and every unit's text appears in it in order.
- Health checks: no merge commits, commit dates never go backwards, nothing dated in the future, and every commit's trailers parse.

## What "author" means

The author of a commit is the publication that changed the text (a decree, an erratum or a ruling), named by its category, gazette date and issue, with an e-mail address that cannot exist (`<key>@legislacion.scjn.gob.mx.invalid`). The committer is always Lexifina.

## Limits

This is not an official publication. The binding text is the one published in the state's official gazette (Periódico Oficial). The history starts with the oldest text SCJN holds for each ordenamiento, which for many is later than its enactment. Only the ordenamientos listed above are included.
