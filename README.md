# marginalizacion_mexico
Tabla de indicadores socioeconómicos e índice y grado de marginación por entidad federativa y lugar que ocupa en el contexto nacional 1990-2015, estimados a partir de información registrada en los censos de población y vivienda 1990, 2000 y 2010. así como de los conteos de población y vivienda de 1995 y 2005 y la encuesta Intercensal 2015. Fuente: CONAPO, 2024.

Se describen a continuación los pasos para poder visualizar el documento, de primera instancia se pide descargar los datos correspondientes a la base datos el archivo:
Base_Indice_de_marginacion_estatal_90_15.csv

Se creará la base de datos utilizando MYSQL WORKBENCH con las siguientes indicaciones para importar los datos del csv:
  CREATE TABLE base_indice_de_marginacion_estatal_90_15 (
    CVE_ENT int 
    NOM_ENT text 
    POB_TOT int 
    ANALF double 
    SPRIM double 
    OVSDE double 
    OVSEE double 
    OVSAE double 
    VHAC double 
    OVPT double 
    PLmenor5000 double 
    PO2SM double 
    OVSDSE text 
    IM double 
    GM text 
    IND0A100 text 
    LUGAR int 
    AÑO int);

Una vez se haya creado la base de datos en MYSQL se procede a abrir el archivo marginacion_mexico.ipynb y se ejecuta para poder observar los datos que se analizaron.
