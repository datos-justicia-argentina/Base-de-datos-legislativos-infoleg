#Base de datos legislativos Infoleg
Este recurso contiene las leyes, decisiones administrativas, decretos, resoluciones, disposiciones, acordadas y todo acto administrativo publicado en la primera sección del Boletín Oficial de la República Argentina desde mayo 1997 más la normativa referenciada.

##Características
- **Fecha de Publicación:** dd/mm/aaaa
- **Recurso:** base de datos legislativos Infoleg
- **Tags o Etiquetas:** leyes, decisiones administrativas, decretos, resoluciones, disposiciones, acordadas, boletín oficial
- **Organización:** Ministerio de Justicia y Derechos Humanos. Subsecretaría de Asuntos Registrales. Registro Nacional de Reincidencia.
- **Autor:** Ministerio de Justicia y Derechos Humanos. Secretaría de Planificación Estratégica. Dirección Nacional del Sistema Argentino de Información Jurídica.
- **Responsable:** Ministerio de Justicia y Derechos Humanos. Secretaría de Planificación Estratégica. Dirección Nacional del Sistema Argentino de Información Jurídica.
- **Frecuencia de Actualización:** Mensual

##Recursos
###Base de datos legislativos Infoleg
- **Nombre:** base_de_datos_legislativos_infoleg
- **Descripción:** Base de documentos digitales legislativos: leyes, decisiones administrativas, decretos, resoluciones, disposiciones, acordadas y todo acto administrativo publicado en la primera sección del Boletín Oficial de la República Argentina desde mayo 1997 más la normativa referenciada.
- **Formato:** TXT delimitado por tabulaciones
- **Rango temporal:** 05/1997 a la fecha

###Campos del recurso
-	**id_norma (entero):** Identificador de la Norma
-	**tipo_norma (string):** Listado predeterminado (leyes, decisiones administrativas, decretos, etc.)
-	**numero_norma (string):** Número de la norma o S/N (sin número)
-	**clase_norma (string):** Agregado de la norma (ej. Comunicaciones A B C, Resoluciones Conjuntas, etc.)
-	**dependencia (string):** Organismo emisor
-	**fecha_sancion (fecha):** Fecha que se sancionó definitivamente la ley o se emitió el acto administrativo
-	**numero_boletin (entero):** Número de boletín donde se publicó la norma
-	**fecha_boletin (fecha):** Fecha de boletín donde se publicó la norma
-	**pagina_boletin (entero):** Número de página del boletín
-	**titulo_resumido (string):** Referencia específica del tema que trata la norma 
-	**titulo_sumario (string):** Referencia genérica al tema que trata la norma 
-	**texto_resumido (string):** Breve resumen de la norma (se reproduce el copete o el artículo 1)
-	**observaciones (string):** Registra anotaciones (fe de erratas, aclaraciones, abrogación)
-	**texto_original (string):** Link al texto original de las normas
-	**texto_actualizado (string):** Link a los textos vigentes de las normas. Supone la existencia de un antecedente - “norma modificada”-  reformado por  una o más normas posteriores – “norma/s modificatoria/s”-
