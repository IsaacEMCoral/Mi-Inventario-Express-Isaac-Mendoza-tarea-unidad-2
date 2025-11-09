# Mi Inventario Express Isaac Mendoza
Actividad Unidad 2 Aplicaciones WEB (UPS). Ejemplo de aplicación para gestion de inventario usando las herramientas Node.js, Express, MongoDB y Socket.io.
Después de descargar la carpeta "MiInventarioExpress":
1.	Se debe inicializar el servidor en MongoDB con el nombre “miinventario”.
2.	Inicializar la aplicación en Windows PowerShell con el comando “node server.js”
3.	Abrir en cualquier navegador el siguiente enlace: http://localhost:3000
Esto nos manda a la ventana principal donde se debe:
1.	Registrarse en la aplicación, esto manda al usuario la página principal.
2.	Una vez registrado se puede usar el mismo usuario y contraseña en Login sin necesidad de registrarse nuevamente en la aplicación.
3.	En “Productos” se puede eliminar o editar productos existentes e ingresar nuevos productos.
a.	“Crear producto” permite ingresar para cada producto: 
i.	Nombre
ii.	SKU o identificador individual del producto
iii.	precio
iv.	cantidad
v.	descripción
vi.	subir una imagen del producto
vii.	guardar
b.	En “Editar” se despliegan los mismos parámetros que en crear producto y permite la modificación de cada uno.
c.	Para eliminar un producto solo se aplasta el botón que dice “Eliminar”.
4.	En chat se puede enviar mensajes con los otros administradores.
Dependencias (npm install):
•	express
•	ejs
•	mongoose
•	dotenv
•	express-session
•	connect-mongo
•	express-ejs-layouts
•	nodemon
