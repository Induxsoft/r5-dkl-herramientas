# r5.up_cfdi.dkl
<p>Permite insertar un XML de cfdi a base de datos R5.</p><br>

## Sintaxis:
<p>
  <b>r5.up_cfdi.dkl db=</b>miconexion <b>cfdi=</b>ruta_archivo_xml <b>ref=</b>referencia_factura_o_recibo_cxc<br>
</p>

## Parámetros.
<p>
<b>db=<b/> Conexión a la base de datos R5.<br>
<b>cfdi</b>b> Ruta y archivo XML de CFDi.<br>
<b>ref</b> Ruta y archivo XML de CFDi.<br> 
</p>
  
## Ejemplo:
<p>
  <b>./dkl r5.up_cfdi.dkl db=pruebaxmlfallo@MaxiComercio.R5 cfdi=C:\dklprod\mifactura.XML ref=F00000001</b><br>
</p>
