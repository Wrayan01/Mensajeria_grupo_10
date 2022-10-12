# Mensajeria_grupo_10 - V1.0
Proyecto desarrollo Web - Universidad del Norte

Frontend: HTML, CSS, Bootstrap
Backend: Flask.
Base de datos: Sqlite3

App minimalista para el envio y recepción de mensajes entre usuarios, el cual contiene:

- Login: el cual enviará un correo verificacion con llave única para confirmación de su correo.
- Activación de cuenta.
- Restablecimiento de contraseña en caso de perdida u olvido.
- Vista de aréa de mensajeria, en donde podrá ver los usuarios registrados a los cuales podrá enviar mensajes.

Los mensajes constan de:
- Asunto: Breve descripción del motivo del mensaje:
- Remitente: el cual será el usuario que ha autenticado e iniciado sesion.
- Destinatario: persona quien recibirá el mensaje, solo podrá visualizar usuarios registrados en la app.

Tendrá una tabla en donde podrá visualizar el listado de mensaje(enviados y recibidos) el cual contiene:
- Nombre del destinatario.
- Correo de destinatario.
- Asunto del mensaje.
- Descripción del mensaje.
- Hora de envio o recepción
- Etiqueta de identificación de "ENVIADO" o "RECIBIDO"

Menu lateral de navegación, donde podrá realizar cambios de contraseña, visualizar vista de mensajeria y Logout.




