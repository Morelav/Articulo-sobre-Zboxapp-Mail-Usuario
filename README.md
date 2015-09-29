# Configuracion-de-un-reenvio-interno-con-Outlook
Correcciones para el articulo

Debido que se han presentado problemas con la sincronización de correos en Outlook 2013, como se muestra en este hilo oficial de Microsoft:

Problems with Outlook 2013 and IMAP synchronization

Ante esta situación, existen algunas alternativas para no usar Outlook 2013 con IMAP.

Por ejemplo:

- Usuarios de tipo Professional y Premium: pueden perfectamente utilizar el Connector, o utilizar la conexión de forma nativa desde Outlook con el servidor usando EAS (Exchange Active Sync)

- Usuarios de tipo Basic: sólo pueden conectarse mediante POP o IMAP, pero dado que es la sincronización IMAP la que posee problemas con Outlook 2013, es que recomendamos realizar la conexión por POP, dejando una copia de los correos en el servidor, para poderlos revisar con el celular o vía webmail.

Esto último nos trae otro inconveniente, es que al enviar un correo desde Outlook 2013 conectado por POP, el mensaje no se muestra en la carpeta Enviados, a pesar que el mismo haya llegado al destinatario.

Para solucionarlo se necesita crear una regla tanto por el lado del software de correo como en ZBox Webmail y asi lograr tener una copia de lo enviado en la carpeta Enviados desde Outlook 2013


Pasos para crear la regla desde el Outlook 2013
1. Ir a Archivo -> Informacion -> Administrar reglas y alertas



2.  Seleccionar Nueva regla

 
3. Seleccionar la opcion que dice Aplicar regla a los mensajes que envie y luego Click en siguiente
 
4. Debe seleccionar siguientes opciones y luego Click en siguiente


 
 Haz click a través de la cuenta, se abrirá una venta como la siguiente



5. Seleccionar: Enviar una copia del mensaje a persona. 

 

Escribir dirección de correo actual del usuario . ¡Importante!



Click en Aceptar

 

6. Finalizar creación de regla

 



Dar en Finalizar

 

Qué obtendremos con esto? con esto haremos en Outlook 2013 que cada correo que se envíe, se reenvíe una copia a sí mismo.

Sí, esto quedará en la bandeja de entrada, pero puede crear un filtro en el ZBox Webmail para que esos correos queden en la carpeta de Enviados del Webmail. Esta parte la puede solicitar al área de soporte a traves del correo soporte@zboxapp.com o realizarla usted mismo de la siguiente manera.

Pasos para crear el filtro en ZBox Webmail
1. Ingrese al webmail
2. Vaya a Preferencias -> Filtros

3. Coloque los siguientes datos en el filtro

Ojo: en el correo debe colocar su propia dirección de correo electrónico

4. Presione Aceptar y luego Guardar

 
