# consultas_1_sql
introducción a las consultas de una base de datos usando el lenguaje SQL

## BASE DE DATOS:VENTAS 
## TABLA: CLIENTE 

![Tabla cliente](tabla_cliente.png"tabla cliente")


## Instruccion SELECT 
- permite seleccionar datos de una tabla.!
` SELECT campos_tabla FROM nombre_tabla`
### consulta NO. 1
1. para visualizar toda la informacion que contiene la tabla ciente se puede incluir con la intruccion SELEC el caracter **\*** o cada uno de los campos de la tabla.

- `SELEC + FROM Cliente`
- `SELEC identificacion, nombre, apellidos, dirrecion, telefono, ciudad_nac, fecha_nac FROM Cliente`

![consulta 1](consultas1.png"consultas 1")


### Consulta No. 2

2. para viasualizar solamente la identificacion del cliente: `SELEC identificacion FROM Cliente`

![consultas 2](consultas2.png"consultas 2")


### consulta No. 3 

3. Si se desea obtenerr los registros cuya identificacion sea mayor o igual a 150, se debe utlizar la clausula `where ` que escifica las conciones que deben reunir los registros que se van a seleccionar `SELEC * FROM cLIENTE WHERE identificacion>=150`

![consultas 3](consultas3.png"consultas 3")
