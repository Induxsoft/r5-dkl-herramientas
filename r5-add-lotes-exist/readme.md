# La herramienta ADD_Lotes_A_Existencias.dkl realiza las siguientes transacciones:

- Activa en todos los articulos el requerimiento de Lotes.
- Elimina registros del historial de requisiciones, tablas: docf_ddocumento,docf_historialstatus,docf_documento.
- Elimina los registros de Movimientos(Entradas/Salidas) en las tablas: Cardex,DCardex,DCapa.
  -Al ejecutar esta herramienta ya NO tendra disponible el historial de movimientos(entradas/salidas) y de requisiciones desde la  fecha de ejecucion de la herramienta hacia atras.
- Agrega Lotes a los Articulos que tengan existencias.

Para ejecutar la herramienta realice lo siguiente:
1. Descargue la herramienta y coloquela en una ubicacion.
2. Instalar el interprete de Lenguaje DKL de induxsoft de distribucion gratuita: Devkron Language.
3. Establecer el nombre de nuestra conexion a la base de datos R5 en la herramienta:
	a). Abrir el archivo ADD_Lotes_A_Existencias.dkl con un editor de texto (Visual Code,NotePad++ etc.)
	b). Modificar en "MiConexion@MaxiComercio.R5" por el nombre de nuestra conexion a la BD.
           	ejemplo: dbr.open("ferretera2000@MaxiComercio.R5") 
	c). Guarde y cierre.
4. Ejecute la herramienta desde el CMD de windows con el interprete de Lenguaje: Devkron.exe
	a). Acceda a la ubicacion del interprete ubicado en: C:\ProgramData\induxsoft\machine\winShell\v10
        b). Ejecute la herramienta .DKL con el interprete indicando su ubicacion.
		Ejemplo: C:\ProgramData\induxsoft\machine\winShell\v10\Devkron.exe c:\Micarpeta\ADD_Lotes_A_Existencias.dkl	
	c). El proceso iniciara y espere a que finalice, no cierre ni cancele, ya que puede causar daños irreversibles en la Base de datos.

Una vez finalizada todos los articulos con existencias tendran un Lote con fecha de caducidad 6 Meses despues de la ejecucion de la herramienta.





