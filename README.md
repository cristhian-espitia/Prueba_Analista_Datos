# Prueba_Analista_Datos
Prueba Analista Calidad de Datos BI
La siguiente prueba se debe desarrollar en el programa funciones y paquetes de su preferencia (No existe ningún tipo de restricción para desarrollar el objetivo y demostrar sus conocimientos en R, Python, SQL, Excel, etc. También está permitido todo tipo de consultas, repositorios o demás recursos que considere necesarios). Presentar un informe conciso con los resultados, análisis y el proceso desarrollado (enviar en un archivo plano txt los scripts realizados)
Descripción de los datos.
La Caja Colombiana de Subsidio Familiar – Colsubsidio, es una compañía que pertenece al Sistema del Subsidio Familiar y al Sistema de Protección y Seguridad Social colombiano, que en sus más de 60 años se ha consolidado como la caja de compensación familiar de mayor cobertura del país. Su gestión, la desarrolla a través de la administración de recursos provenientes de las empresas aportantes y la prestación de servicios sociales para los trabajadores afiliados, sus familias y la población en general.
Colsubsidio ha dividido la prestación de sus servicios en once diferentes unidades especializadas de servicio (UES) que ofrecen diferentes productos.
En este caso, se requiere un perfilamiento de los datos, la programación de reglas de calidad y negocio que se puedan ejecutar diariamente para conocer el nivel de calidad de la información y posteriormente lograr generar diferentes tipos de reportes gerenciales. Para tal fin se le dispone la siguiente base de datos:

Persona: Datos de las personas con afiliación vigente a la caja  :

Data
---
https://colsubsidio365-my.sharepoint.com/personal/nydibosm_colsubsidio_com/_layouts/15/onedrive.aspx?id=%2Fpersonal%2Fnydibosm%5Fcolsubsidio%5Fcom%2FDocuments%2FPRUEBA%20DE%20CONOCIMIENTO%20ANALISTA%20CALIDAD%20DE%20%20DATOS&ga=1

Reto de análisis de calidad

Realice un informe que dé respuesta a las siguientes preguntas de negocio e identifique la cantidad de fallas presentadas por variable y el indicador de calidad general y por variable (registros sin errores / cantidad de registros).

1.	¿Como está perfilada las bases de datos (Tipo de datos, mayor y mínimo valor, longitud del campo)?

2.	Programe y genere los indicadores de calidad de las siguientes reglas: 
	
Reglas de calidad: 

•	El campo “NumIdPersona” no admite campos vacíos

•	En el campo “Genero” solo se admite como valido los valores “F” Y “M”

•	En el campo “Segmento” solo se permiten las siguientes opciones: Alto, Básico, Joven y Medio

•	En el campo edad no se admite el valor 0 y tampoco puede tener más de 2 caracteres

Regla de negocio: 

De acuerdo con el campo “Categoria” solo se permiten las siguientes opciones en el campo “Segmento_poblacional”
 

[![111.png](https://i.postimg.cc/fR3Pd2Tw/111.png)](https://postimg.cc/G4CzwjyN)
