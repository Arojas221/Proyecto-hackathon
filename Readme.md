# 1. URL del programa:
	a.(en el programa):* Running on http://127.0.0.1:8080
 	    		   * Running on http://192.168.249.19:8080
	b.(Máquina virtual): *

# 2. Una página web que registra peticiones de tipo PQRS de diversos usuarios.
	*librerías utilizadas (Para reportes y visualizaciones avanzadas):
	- Pandas. 
	- OpenPyXL. 
	- ReportLab.
	- Matplotlib. 
	*Técnologías usadas:
	- HTML5
	- Bootstrap
	- CSS Personalizado
	- MySQL
	- Flask

# 3. y 4. Jerarquía del proyecto
```.
├── static
│   ├── \ css
│   │   ├── style.css // carpeta con los diseños en css
├── templates // diseño de cada ventana
│   ├── base.html
│   ├── dashboard.html
│   ├── editar_pqrsd.html
│   ├── gestion.html
│   ├── index.html
│   ├── login.html
│   ├── nueva_pqrsd.html
│   ├── politica_privacidad.html
│   ├── registro_usuario.html
│   ├── reportes.html
│   ├── responder_pqrs.html
│   ├── tabla_usuarios_registro.html
│   ├── terminos_servicio.html
│   ├── ver_pqrsd.html
├── .deployment
├── .env //para configurar la base de datos.
├── app.py // lógica del entorno virtual.
├── config.py // funcionalidades para el backend.
├── models.py // configura la lógica para la base de datos
├── readme.md
├── setup.py
└── sql Informacion pruebas.txt//archivo para crear la base de datos por separado
```
# 5. configuraciones declaradas en el config.py

    DB_HOST = os.getenv("MYSQL_HOST", "localhost") // Define la red a la que se va a conectar
    DB_USER = os.getenv("MYSQL_USER", "pqrsd_user") //Define el nombre de usuario
    DB_PASSWORD = os.getenv("MYSQL_PASSWORD", "pqrsd_password_2023") // Define la contraseña del usuario
    DB_NAME = os.getenv("MYSQL_DB", "sistema_pqrsd") // Define el nombre de la BD
    DB_PORT = os.getenv("MYSQL_PORT", "3306")// define el puerto 

# 6. Paso a paso para ejecutar el proyecto.
	a).En el programa
		1. Instalar el lenguaje python en el computador.
		2. Instalar xampo y tener encendida las opciones de apache y MySQL.
		3. Abrir el proyecto en un editor de código como VSC.
		4. Abri SQL e ingresar los scripts del archivo sql.txt para crear la base de datos.
		5. ejecutar en la terminal el comando python app.py.
	
	b).en la máquina virtual

# 7.Peticiones
<img width="1054" height="433" alt="image" src="https://github.com/user-attachments/assets/66dbc73e-2d92-468d-8388-d04d306382c6" />
# 8. Base de datos
![Imagen de WhatsApp 2025-09-11 a las 11 10 10_091baf6b](https://github.com/user-attachments/assets/631189ad-cf13-413e-ae97-f08cf410e79f)











