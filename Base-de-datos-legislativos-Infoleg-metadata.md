Base de Datos Legislativos Infoleg
===========================================================

Este recurso contiene las leyes, decisiones administrativas, decretos, resoluciones, disposiciones, acordadas y todo acto administrativo publicado en la primera sección del Boletín Oficial de la República Argentina desde mayo 1997 más la normativa referenciada. La información se actualiza diariamente y las consultas actualizadas están disponibles en [Infoleg](http://www.infoleg.gob.ar/).

http://datos.jus.gob.ar/dataset/base-de-datos-legislativos-infoleg

Características
---------------

- **Fecha de Primera Publicación:** 05/09/2016

- **Tags o Etiquetas:** leyes, decisiones administrativas, decretos, resoluciones, disposiciones, acordadas, boletín oficial

- **Organización:** Ministerio de Justicia y Derechos Humanos. Secretaría de Planificación Estratégica. Dirección Nacional del Sistema Argentino de Información Jurídica

- **Autor:** Ministerio de Justicia y Derechos Humanos. Secretaría de Planificación Estratégica. Dirección Nacional del Sistema Argentino de Información Jurídica

- **Responsable:** Ministerio de Justicia y Derechos Humanos. Secretaría de Planificación Estratégica. Dirección Nacional del Sistema Argentino de Información Jurídica

- **Grupo:** Información Jurídica

- **Frecuencia de Actualización:** Mensualmente

Recursos disponibles
--------------------

### Base Infoleg de Normativa Nacional

- **Nombre del archivo:** base-infoleg-normativa-nacional.csv

- **Descripción del contenido:** base de documentos digitales normativos nacionales: leyes, decisiones administrativas, decretos, resoluciones, disposiciones, acordadas y todo acto administrativo publicado en la primera sección del Boletín Oficial de la República Argentina desde mayo 1997 más la normativa referenciada. La información se actualiza diariamente y las consultas actualizadas están disponibles en Infoleg <http://www.infoleg.gob.ar/> . 
Los DNU que figuran en este registro son todos los que fueron publicados en el Boletín Oficial y que fueron dictados conforme el artículo 99 inc. 3 de la Constitución Nacional, en acuerdo general de ministros.


- **Formato:** CSV delimitado por comas, codificado en UTF-8

- **Rango temporal:** base Infoleg de Normativa Nacional desde mayo de 1997 hasta la fecha consignada como "Datos actualizados al"

### Campos del recurso

- **id_norma (entero):** identificador de la Norma

- **tipo_norma (string):** clasificación de la norma de acuerdo a la jerarquía normativa (ej. leyes, decisiones administrativas, decretos, etc.)

- **numero_norma (string):** número de la norma o S/N (sin número)

- **clase_norma (string):** atributo complementario del tipo de norma (ej. Comunicaciones A B C, Resoluciones Conjuntas, etc.)

- **organismo_origen (string):** organismo emisor de la norma

- **fecha_sancion (fecha):** fecha que se sancionó la ley o se emitió el acto administrativo

- **numero_boletin (entero):** número de boletín donde se publicó la norma

- **fecha_boletin (fecha):** fecha del Boletín Oficial (BO) donde se publicó la norma

- **pagina_boletin (entero):** número de página del boletín

- **titulo_resumido (string):** tema específico que trata la norma

- **titulo_sumario (string):** tema genérico que trata la norma

- **texto_resumido (string):** sintesis de la norma (se reproduce el copete o el art. 1)

- **observaciones (string):** anotaciones complementarias a la norma (ej. fe de erratas, aclaraciones, abrogación, etc.)

- **texto_original (string):** link al texto original de la norma tal como fue publicado

- **texto_actualizado (string):** link al texto actual vigente de la norma

- **modificada_por (entero):** cantidad de normas que modifican/complementan a la presente

- **modifica_a (entero):** cantidad de normas a las que modifica/complementa la presente

### Base Complementaria Infoleg de Normas Modificadas

- **Nombre:** base-complementaria-infoleg-normas-modificadas.csv

- **Descripción:** base complementaria Infoleg con normas nacionales modificadas: leyes, decisiones administrativas, decretos, resoluciones, disposiciones, acordadas y todo acto administrativo publicado en la primera sección del Boletín Oficial de la República Argentina desde mayo 1997 más la normativa referenciada

- **Formato:** CSV delimitado por comas, codificado en UTF-8

- **Rango temporal:** listado actualizado a la fecha consignada como "Datos actualizados al"

### Campos del recurso

- **id_norma_modificada (entero):** identificador de la Norma modificada

- **id_norma_modificatoria (entero):** identificador de la Norma modificante

- **tipo_norma (string):** clasificación de la norma de acuerdo a la jerarquía normativa (ej. leyes, decisiones administrativas, decretos, etc.)

- **numero_norma (string):** número de la norma o S/N (sin número)

- **clase_norma (string):** atributo complementario del tipo de norma (ej. Comunicaciones A B C, Resoluciones Conjuntas, etc.)

- **organismo_origen (string):** organismo emisor de la norma

- **fecha_boletin (fecha):** fecha del Boletín Oficial (BO) donde se publicó la norma

- **titulo_sumario (string):** tema genérico que trata la norma

- **titulo_resumido (string):** tema específico que trata la norma

### Base Complementaria Infoleg de Normas Modificatorias

- **Nombre:** base-complementaria-infoleg-normas-modificatorias.csv

- **Descripción:** base complementaria Infoleg con normas nacionales modificatorias: leyes, decisiones administrativas, decretos, resoluciones, disposiciones, acordadas y todo acto administrativo publicado en la primera sección del Boletín Oficial de la República Argentina desde mayo 1997 más la normativa referenciada

- **Formato:** CSV delimitado por comas, codificado en UTF-8

- **Rango temporal:** Listado actualizado a la fecha consignada como "Datos actualizados al"

### Campos del recurso

- **id_norma_modificatoria (entero):** identificador de la norma modificatoria

- **id_norma_modificada (entero):** identificador de la norma modificada

- **tipo_norma (string):** clasificación de la norma de acuerdo a la jerarquía normativa (ej. leyes, decisiones administrativas, decretos, etc.)

- **numero_norma (string):** número de la norma o S/N (sin número)

- **clase_norma (string):** atributo complementario del tipo de norma (ej. Comunicaciones A B C, Resoluciones Conjuntas, etc.)

- **organismo_origen (string):** organismo emisor de la norma

- **fecha_boletin (fecha):** fecha del Boletín Oficial (BO) donde se publicó la norma

- **titulo_sumario (string):** tema genérico que trata la norma

- **titulo_resumido (string):** tema específico que trata la norma

Notas:
------
Este Conjunto de datos es publicado en el Portal de Datos Abiertos de la Justicia Argentina mediante [Resolución Nº 986 del Ministerio de Justicia y Derechos Humanos](http://datos.jus.gob.ar/resoluciones/RESOL-2016-986-E-APN-MJ.pdf), del 26 de Octubre de 2016.

