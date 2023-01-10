# Herramienta r5.limpiar.inventario.dkl

Esta herramienta permite optimizar información del módulo de inventarios en una base de datos R5; utilice esta herramienta cuando tenga  mucha información de inventarios de años atrás y que no utiliza el sistema para las transacciones actuales.

La herramienta recopila  todas las existencias por productos y por almacén guardando la información para un historial, después procede a eliminar todos los movimientos de inventarios desde el origen de los tiempos a una fecha indicada como parámetro.


Parámetros de línea de comando:
```
-bd: miConexion@Maxicomercio.R5   //conexion a la base de datos
-f= 2021-12-28   //fecha de final(Desde el origen de los tiempos a la fecha final).
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
