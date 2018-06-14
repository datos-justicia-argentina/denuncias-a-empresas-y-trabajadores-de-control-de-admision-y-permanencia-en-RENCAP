Denuncias a empresas y trabajadores de control de admisión y permanencia en RENCAP
==================================================================================

Este conjunto de datos corresponde a la información generada por las denuncias recibidas en el Registro Nacional de Empresas y Trabajadores de Control de Admisión y Permanencia (RENCAP), por vía telefónica o formulario web, sobre actos de discriminación, violencia o incumplimiento de las disposiciones vigentes en que incurren los Controladores de Admisión y Permanencia (CAP) y/o las empresas organizadoras de espectáculos públicos, radicadas por los damnificados, allegados y/o testigos. Las denuncias se reciben en la línea gratuita 0800-222-0080 o en la página http://www.jus.gob.ar/rencap.aspx/servicios/denuncias/dar-de-alta.aspx.

El RENCAP es un organismo de segundo orden, no realiza procedimientos de investigación ni aplica sanciones en relación a estas denuncias. Su función en relación a las mismas se limita a canalizarlas a las autoridades provinciales o de la Ciudad Autónoma de Buenos Aires -según corresponda su competencia- para que éstas le den el tratamiento que estimen corresponder en función de la legislación allí vigente.
La información aportada por el denunciante es confidencial y es tratada de acuerdo a la [Ley N° 25.326 de Protección de Datos Personales](http://servicios.infoleg.gob.ar/infolegInternet/anexos/60000-64999/64790/texact.htm). Al efectuar la denuncia, el denunciante declara conocer y aceptar el procedimiento y los alcances que tendrá la misma.

El Registro Nacional de Empresas y Trabajadores de Control de Admisión y Permanencia fue creado por [Decreto N° 1824/2009](http://servicios.infoleg.gob.ar/infolegInternet/anexos/160000-164999/160784/norma.htm). Su función principal es la de operar un banco informático o base de datos que permite recibir, clasificar, incorporar, transmitir y archivar toda la información suministrada por las jurisdicciones provinciales y por la Ciudad Autónoma de Buenos Aires, en la medida que adhieran a la [Ley N° 26.370](http://servicios.infoleg.gob.ar/infolegInternet/anexos/140000-144999/140950/norma.htm).
La Ley [Ley N° 26.370](http://servicios.infoleg.gob.ar/infolegInternet/anexos/140000-144999/140950/norma.htm) establece las reglas de habilitación del personal que realiza tareas de control de admisión y permanencia de público en general, y para empleadores cuya actividad consista en la organización y explotación de eventos y espectáculos públicos.

http://datos.jus.gob.ar/dataset/denuncias-a-empresas-y-trabajadores-de-control-de-admision-y-permanencia-en-rencap

Características
---------------

-	**Fecha de Primera Publicación:** 30/06/2018

-	**Tags o Etiquetas:** discriminación, violencias, registros, patovicas, espectáculos, admisiones, denuncias, esventos, permanencia

-	**Organización:** Ministerio de Justicia y Derechos Humanos. Subsecretaría de Asuntos Registrales. Dirección Nacional del Registro Nacional de Empresas y Trabajadores de Control de Admisión y Permanencia

-	**Autor:** Ministerio de Justicia y Derechos Humanos. Subsecretaría de Asuntos Registrales. Dirección Nacional del Registro Nacional de Empresas y Trabajadores de Control de Admisión y Permanencia

-	**Responsable:** Ministerio de Justicia y Derechos Humanos. Subsecretaría de Asuntos Registrales. Dirección Nacional del Registro Nacional de Empresas y Trabajadores de Control de Admisión y Permanencia

-	**Grupo:** Sistema Registral

-	**Frecuencia de Actualización:** Trimestralmente

Recursos disponibles
--------------------

### Denuncias a empresas y trabajadores de control de admisión y permanencia en RENCAP - actualizado al AAAA-MM-DD

-	**Nombre del archivo:** denuncias-rencap-AAAA-MM-DD.csv

-	**Descripción del contenido:** : información generada por las denuncias recibidas sobre actos de discriminación, violencia y/o incumplimiento de las disposiciones vigentes, en que incurran los Controladores de Admisión y Permanencia (CAP) y/o las empresas organizadoras de espectáculos públicos

-	**Formato:** CSV delimitado por comas, codificado en UTF-8

-	**Rango temporal:** detalle de las denuncias registradas desde agosto de 2010 hasta la fecha consignada como "Datos actualizados al"

### Campos del recurso

-	**denuncia_numero (entero):** número interno del registración de la denuncia, conforme al orden de ingreso

-	**hecho_fecha_hora (date):** fecha y hora en la que el denunciante indica que sucedió el incidente

-	**hecho_provincia (string):** provincia en la que el denunciante indica que sucedió el incidente

-	**hecho_municipio (string):** municipio, partido, departamento o barrio en el que ocurrió el incidente denunciado

-	**hecho_localidad (string):** localidad o ciudad en la que ocurrió el incidente denunciado

-	**hecho_discriminacion (string):** en caso de tratarse de un hecho de discriminación, identifica el tipo de discriminación que ocurrió. Si hay más de uno, están separados por guión medio. Puede tomar los valores:

    -   Por aspecto físico
    -   Por orientación sexual
    -   Por indumentaria
    -   Por religión
    -   Por ideología
    -   Racial
    -   Otros

-	**hecho_irregularidades (string):** indica la irregularidad denunciada. Si hay más de una, están separadas por guión medio. Puede tomar los valores:

    -   El personal de control no esta identificado
    -   No exhibe nomina de personal de control habilitado
    -   No exhibe condiciones de adminsión y permanencia
    -   Hay mas personas que las permitidas por la habilitación
    -   Presencia de menores
    
-	**hecho_lugar (string):** indica el lugar en el cual ocurren los incidentes. Si hay más de uno, están separados por guión medio. Puede tomar los valores:

    -   En el interior del local
    -   En el acceso local
    -   En las proximidades del local

-	**hecho_cometido_por (string):** indica quién cometió el hecho. Si hay más de uno, están separados por guión medio. Puede tomar los valores:

    -   Controladores
    -   Personal de empresas de seguridad
    -   Personas vinculadas a la empresa
    -   Policias

-	**hecho_tipo_violencia (string):** indica el tipo de violencia denunciada. Si hay más de una, están separadas por guión medio. Puede tomar los valores:

    -   Agresión verbal
    -   Agresión física
    -   Agresión sexual

-	**hecho_accion_realizada (string):** indica las acciones que llevó a cabo el denunciante ante el incidente. Si hay más de una, están separadas por guión medio. Puede tomar los valores:

    -   Se solicitó asistencia policial
    -   Se hizo denuncia policial
    -   Se hizo denuncia ante la fiscalia

-	**denuncia_estado (string):** indica si la denuncia fue derivada a la jurisdicción competente o si fue desestimada por no corresponder la derivación. Entre los posibles motivos de desestimación podemos encontrar:

    -	La denuncia pertenece a un ámbito ajeno a la competencia del RENCAP
    -	El denunciante solicita que la denuncia sea desestimada
    -	El hecho denunciado no implica infracción alguna a la normativa
    -	Hecho extemporáneo
    -	Inconsistencia en los datos brindados por el denunciante
    -	Errores de carga
    -	Generación de registro duplicado


-	**denuncia_fecha_cambio_estado (date):** indica la fecha en que la denuncia fue derivada o desestimada

-	**denuncia_via_ingresa (string):** indica la vía por la cual ingresó la denuncia. Puede tomar los valores:

    -   Call center
    -   Página web de RENCAP

-	**denuncia_fecha_hora_carga (date):** indica la fecha-hora en que la denuncia fue ingresada al sistema


### Notas

-	**[Ley Nacional de Espectáculos Públicos Nº 26.370](http://servicios.infoleg.gob.ar/infolegInternet/anexos/60000-64999/64790/texact.htm)**
    
##[Decreto Reglamentario Nº 1824/2009](http://servicios.infoleg.gob.ar/infolegInternet/anexos/160000-164999/160784/norma.htm)

##[Resolución MJyDH Nº 1024/2013](http://servicios.infoleg.gob.ar/infolegInternet/anexos/215000-219999/215997/norma.htm)

### Provincia de Buenos Aires

-	**[Ley de adhesión N° 13.964](http://www.saij.gob.ar/13964-local-buenos-aires-adhesion-provincia-ley-nacional-26370-reglas-habilitacion-personal-realiza-tareas-control-admision-permanencia-publico-eventos-espectaculos-publicos-lpb0013964-2008-12-23/123456789-0abc-defg-469-3100bvorpyel?q=%28numero-norma%3A13964%20%29&o=0&f=Total%7CTipo%20de%20Documento/Legislaci%F3n%7CFecha%7COrganismo%7CPublicaci%F3n%7CTema%7CEstado%20de%20Vigencia%7CAutor%7CJurisdicci%F3n/Local/Buenos%20Aires&t=1) (Publicada B.O. 10/02/2009)**
	
    -	Decreto reglamentario N° 1096/09

-	**Provincia de Catamarca**

    -	Ley de adhesión N° 5485 (Publicada B.O. 8/11/2016)

    -	Resolución que aprueba Convenio: En trámite

-	**Provincia de Chaco**

    -	[Ley de adhesión N° 6709](http://www.saij.gob.ar/6709-local-chaco-adhesion-ln-26370-control-admision-permanencia-mod-art-29-ley-134-lph0006709-2010-12-15/123456789-0abc-defg-907-6000hvorpyel?q=%28numero-norma%3A6709%20%29&o=0&f=Total%7CTipo%20de%20Documento/Legislaci%F3n/Ley%7CFecha%7COrganismo%7CPublicaci%F3n%7CTema%7CEstado%20de%20Vigencia%7CAutor%7CJurisdicci%F3n&t=7) (Publicada B.O. 12/01/2011)

    -	Decreto reglamentario N° 1676/2011
    
    -	Resolución que aprueba convenio: En trámite

-	**Provincia de Chubut**

    -	Ley de adhesión XIX N° 66 (Publicada B.O. 18/07/2014)
    
    -	Decreto reglamentario N° 260/2015

    -	Resolución MJyDH Nº 1826/2015 (Convenio)

-	**Provincia de Entre Ríos**

    -	[Ley de adhesión N° 10.517](http://www.saij.gob.ar/10517-local-entre-rios-adhesion-provincia-entre-rios-ley-nacional-26370-crea-registro-provincial-controladores-lpe0010517-2017-09-12/123456789-0abc-defg-715-0100evorpyel?q=%28numero-norma%3A10517%20%29&o=0&f=Total%7CTipo%20de%20Documento/Legislaci%F3n%7CFecha%7COrganismo%7CPublicaci%F3n%7CTema%7CEstado%20de%20Vigencia%7CAutor%7CJurisdicci%F3n/Local/Entre%20R%EDos&t=1) (Publicada B.O. 11/10/2017)

-	**Provincia de Río Negro**

    -	[Ley de adhesión N° 4351](http://www.saij.gob.ar/4351-local-rio-negro-adhiere-ley-nacional-26370-establece-reglas-habilitacion-personal-control-admision-permanencia-publico-eventos-espectaculos-publicos-lpr2004351-2009-05-15/123456789-0abc-defg-153-4002rvorpyel?q=%28numero-norma%3A4351%20%29&o=0&f=Total%7CTipo%20de%20Documento/Legislaci%F3n%7CFecha%7COrganismo%7CPublicaci%F3n%7CTema%7CEstado%20de%20Vigencia%7CAutor%7CJurisdicci%F3n/Local/R%EDo%20Negro&t=1) (Publicada B.O. 4/06/2009)
    
    -	Decreto reglamentario N° 696/2011

    -	Resolución MJyDH Nº 1121/2014 (Convenio)

-	**Provincia de Salta**

    -	[Ley de adhesión N° 7649](http://www.saij.gob.ar/7649-local-salta-adhesion-ley-nacional-26370-espectaculos-publicos-lpa0007649-2010-11-30/123456789-0abc-defg-946-7000avorpyel?q=%28numero-norma%3A7649%20%29&o=0&f=Total%7CTipo%20de%20Documento/Legislaci%F3n/Ley%7CFecha%7COrganismo%7CPublicaci%F3n%7CTema%7CEstado%20de%20Vigencia%7CAutor%7CJurisdicci%F3n/Local/Salta&t=1) (Publicada B.O. 28/12/2008)
    
    -	Decreto reglamentario N° 1921/2011

-	**Provincia de Santa Cruz**

[Ley de adhesión N° 3095](http://www.saij.gob.ar/3095-local-santa-cruz-adhesion-ley-nacional-26370-reglas-habilitacion-personal-realiza-tareas-control-admision-eventos-espectaculos-publicos-lpz0003095-2009-11-26/123456789-0abc-defg-590-3000zvorpyel?q=%28numero-norma%3A3095%20%29&o=0&f=Total%7CTipo%20de%20Documento/Legislaci%F3n/Ley%7CFecha%7COrganismo%7CPublicaci%F3n%7CTema%7CEstado%20de%20Vigencia%7CAutor%7CJurisdicci%F3n/Local/Santa%20Cruz&t=1) (Publicada B.O. 22/12/2009)

   -	Decreto reglamentario N° 3005/2009

-	**Provincia de Santa Fe**

    -	[Ley de adhesión N° 13205](http://www.saij.gob.ar/13205-local-santa-fe-adhesion-ley-nacional-26370-sobre-reglas-habilitacion-personal-realiza-tareas-control-admision-permanencia-espectaculos-publicos-lps0013205-2011-11-03/123456789-0abc-defg-502-3100svorpyel) (Publicado B.O. 20/12/2011)

    -	[Decreto reglamentario N° 2146/2015](http://www.saij.gob.ar/2146-local-santa-fe-reglamentacion-ley-13205-adhiere-ley-nacional-26370-s20150002146-2015-07-08/123456789-0abc-641-2000-5102svorpced)

    -	[Resolución MJyDH Nº 974/2017](http://servicios.infoleg.gob.ar/infolegInternet/verNorma.do?id=304616) (Convenio)


Constitución Nacional – Artículos relevantes en materia de espectáculos públicos
--------------------------------------------------------------------------------

Artículo 1.- La Nación Argentina adopta para su gobierno la forma representativa republicana federal, según la establece la presente Constitución.

Artículo 5.- Cada provincia dictará para sí una Constitución bajo el sistema representativo republicano, de acuerdo con los principios, declaraciones y garantías de la Constitución Nacional; y que asegure su administración de justicia, su régimen municipal, y la educación primaria. Bajo de estas condiciones el Gobierno federal, garante a cada provincia el goce y ejercicio de sus instituciones.

Artículo 16.- La Nación Argentina no admite prerrogativas de sangre, ni de nacimiento: no hay en ella fueros personales ni títulos de nobleza. Todos sus habitantes son iguales ante la ley, y admisibles en los empleos sin otra condición que la idoneidad. La igualdad es la base del impuesto y de las cargas públicas.

Artículo 31.- Esta Constitución, las leyes de la Nación que en su consecuencia se dicten por el Congreso y los tratados con las potencias extranjeras son la ley suprema de la Nación; y las autoridades de cada provincia están obligadas a conformarse a ella, no obstante cualquiera disposición en contrario que contengan las leyes o constituciones provinciales, salvo para la provincia de Buenos Aires, los tratados ratificados después del Pacto de 11 de noviembre de 1859.

Artículo 33.- Las declaraciones, derechos y garantías que enumera la Constitución no serán entendidos como negación de otros derechos y garantías no enumerados; pero que nacen del principio de la soberanía del pueblo y de la forma republicana de gobierno.

Artículo 121.- Las provincias conservan todo el poder no delegado por esta Constitución al Gobierno federal, y el que expresamente se hayan reservado por pactos especiales al tiempo de su incorporación.

Artículo 122.- Se dan sus propias instituciones locales y se rigen por ellas. Eligen sus gobernadores, sus legisladores y demás funcionarios de provincia, sin intervención del Gobierno federal.

Artículo 123.- Cada provincia dicta su propia constitución, conforme a lo dispuesto por el Artículo 5° asegurando la autonomía municipal y reglando su alcance y contenido en el orden institucional, político, administrativo, económico y financiero.

Artículo 124.- Las provincias podrán crear regiones para el desarrollo económico y social y establecer órganos con facultades para el cumplimiento de sus fines y podrán también celebrar convenios internacionales en tanto no sean incompatibles con la política exterior de la Nación y no afecten las facultades delegadas al Gobierno federal o el crédito público de la Nación; con conocimiento del Congreso Nacional. La ciudad de Buenos Aires tendrá el régimen que se establezca a tal efecto.

Artículo 128.- Los gobernadores de provincia son agentes naturales del Gobierno federal para hacer cumplir la Constitución y las leyes de la Nación.

[Ley 24.059 de seguridad interior](http://servicios.infoleg.gob.ar/infolegInternet/anexos/0-4999/458/texact.htm)

