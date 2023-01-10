# Herramienta r5.limpiar.inventario.dkl

Esta herramienta permite optimizar información del módulo de inventarios en una base de datos R5; utilice esta herramienta cuando tenga  mucha información de inventarios de años atrás y que no utiliza el sistema para las transacciones actuales.

La herramienta recopila  todas las existencias por productos y por almacén guardando la información para un historial, después procede a eliminar todos los movimientos de inventarios desde el origen de los tiempos a una fecha indicada como parámetro.


Parámetros de línea de comando:
```
-bd: miConexion@Maxicomercio.R5   //conexion a la base de datos
-f= 2021-12-28   //fecha final(Desde el origen de los tiempos a la fecha final).
```

## Para ejecutar la herramienta realice lo siguiente:
1. Descargue la herramienta y coloquela en una ubicacion.
2. Instalar el interprete de Lenguaje DKL de induxsoft de distribucion gratuita Devkron Language.
3. Ejecute la herramienta desde el CMD de windows con el interprete de Lenguaje Devkron.exe de la siguiente forma:
	- Acceda a la ubicacion del interprete ubicado en: C:\ProgramData\induxsoft\machine\winShell\v10
	- Ejecute la herramienta .DKL con el interprete indicando su ubicacion como se indica en el ejemplo.
	 ```devkron \miubicacion\r5.limpiar.inventario.dkl -bd:miConexion@Maxicomercio.R5 -f=2021-12-28```
4. si todo es correcto mandara un mensaje
 ```Nota: Cuando el proceso inicie espere a que finalice, no cierre ni cancele, ya que puede causar daños irreversibles en la Base de datos. ```
