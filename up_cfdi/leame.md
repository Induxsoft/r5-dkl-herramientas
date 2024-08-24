# r5.up_cfdi.dkl
<p>Permite insertar un XML de cfdi a base de datos R5.</p><br>

## Sintaxis:
<p>
  <b>r5.up_cfdi.dkl db=</b>miconexion <b>cfdi=</b>ruta_archivo_xml <b>ref=</b>referencia_factura_o_recibo_cxc<br>
</p>

## Parámetros.
<p>
<b>db=</b> Conexión a la base de datos R5.<br>
<b>cfdi=</b> Ruta y archivo XML de CFDi.<br>
<b>ref=</b> Referencia del documento de venta, nota de crédito o pago.<br> 


## Ejemplo:
<p>
  ./dkl <b>r5.up_cfdi.dkl db=</b>pruebaxmlfallo@MaxiComercio.R5 <b>cfdi=</b>C:\dklprod\mifactura.XML<b> ref=</b>F00000001</b><br>
</p>
