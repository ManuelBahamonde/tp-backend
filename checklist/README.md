# Checklist

## Backend

|Requerimiento funcional|cant. mín.<br>1 o 2 integ|cant. máx.<br>3 o 4 integ|Detalle/Listado de casos|Cumple|
|:-|-:|-:|:-|-|
|ABMC simple|1 x integ|1 x integ|1- Locatario (Usuario con rol de Locatario) <br>2- Inmobiliarias <br>3- TipoInmueble
|ABMC dependiente|1|2|1- Localidad (depende de Provincia) <br> 2- Inmuebles (depende de TipoInmueble, Usuario, Localidad)
|Listado simple|1|1|1- Listado de Inmobiliarias
|Listado complejo obligatorio|1|2|1- Listado de Inmuebles (se relaciona con inmobiliaria) <br>2- Listado de Localidades (se relaciona con Provincia)
|Listado adicional con filtro|0|0|
|Detalle básico|1(*)|2(*)|1- Inmueble <br> 2- Inmobiliaria
|Detalle parametrizable|0|0|
|Otros|0|0| 1- Localización usando API Google. En el alta/modificacion de un inmueble, se setea la ubicación con un mapa de Google. En el detalle de un inmueble, mostramos su ubicación tambien en un mapa de Google. En el mismo detalle, tambien mostraríamos en el footer una sección de "Inmuebles cercanos" con inmuebles del mismo tipo que el del detalle y que se encuentren en el radio del inmueble actual.

(\*) Los detalles básicos pueden ser reemplazado por un detalle parametrizados en los

## Frontend

|Requerimiento|Cumple|
|:-|-|
|Invocar API listado||
|Invocar API detalle||
|Mostrar detalle al hacer click <br>en elemento del listado||

## Requerimientos Técnicos

|Requerimiento técnico|Cumple|
|:-|-|
|Framework frontend||
|Framework CSS o preprocesador CSS||
|Framework backend||
|Uso de API REST o GraphQL||
|ORM/ODM||
|Base de datos persistente||
