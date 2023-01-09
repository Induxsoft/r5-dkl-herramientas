# r5.limpiar.inventario.dkl

El r5.limpiar.inventario es una herramienta para la aplicación maxiComercio
Que nos da la funcionalidad de eliminar los datos de las tablas de inventarios 
De la base de datos del cliente, de acuerdo a una fecha dada como parámetro e inserta datos 
después de haber eliminado los datos de las tablas inventarios de  acuerdo al producto y almacén que corresponden al producto.

Parámetros de línea de comando:
```
-bd: miConexion@Maxicomercio.R5   //referencia a la base de datos
-f=20211228   o 2021-12-28   //fecha de corte
```

## Ejecutar la herramienta
1. abrimos la consola de devkron
2. escribimos devkron seguido de la ubicación de la herramienta
	 ```devkron c:/Users/user/desktop/r5.limpiar.inventario.dkl```
3. en seguida colocamos los parámetros
```devkron c:/Users/user/desktop/r5.limpiar.inventario.dkl -bd:miConexion@Maxicomercio.R5 -f=2021-12-28```
4. si todo sale bien mandara un mensaje


## Ejecutarlo desde la consola de Windows (cmd)
1. abrir cmd 
2. escribir ```cd C:\ProgramData\Induxsoft\machine\winShell\v10```
3. continuar con el paso 2 de las instrucciones anteriores
