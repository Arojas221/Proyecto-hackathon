# 1. URL del programa:
	a.(en el programa):* Running on http://127.0.0.1:8080
 	    		   * Running on http://192.168.249.19:8080
	b.(Máquina virtual): *


# 2. Resumen de la funcionalidad
###### Una página para la gestión PQRS (Peticiones, Quejas, Reclamos, Sugerencias y Denuncias) hecho en python para tanto entidades públicas o privadas fundamental para evaluar la calidad del servicio a cliente. Se pueden crear, editar y borrar peticiones; consultar, responder y editar peticiones enviadas y consultar las métricas y reportes globales de todas las peticiones existentes.
	
## librerías utilizadas (Para reportes y visualizaciones avanzadas):
* Pandas. 
* OpenPyXL.
* ReportLab.
* Matplotlib. 
## Técnologías usadas:
* HTML5
* Bootstrap
* CSS Personalizado
* MySQL
* Flask

# 3. y 4. Jerarquía del proyecto
```.
├── static
│   ├── \ css
│   │   ├── style.css 
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
├── .env 
├── app.py // lógica del entorno virtual.
├── config.py // funcionalidades para el backend.
├── models.py // configura la lógica para la base de datos
├── readme.md
├── setup.py
└──sql.txt
```
###### \ css
	Contiene los diseños hechos en css para las ventanas
###### templates	
	Contiene cada una de las ventanas con su estructura y lógica definida usando html.
###### .env
	 configura el entorno hecho en flask.
###### models.py
	Contiene la lógica de la base de datos que se encuentra conectada.
###### confi.py
	configura la lógica para conectarse a la base de datos
###### sql
	contiene la información para poder crear la base de datos en sql

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
	
	b).en la máquina virtual y base de datos
		1.Tener instalada una distribución de Linux (ubuntu)
		2. Entrar a la distribución con wsl.
		3. Instalar Azure desde la distribución y crear una cuenta.
		4. Crear la base de datos para el programa y desplegarlo.
		5. entrar al programa y Configurar el entorno virtual, ingrsando 
			- pip install build
			- python -m build --Wheel (genera el archivo.wlm)
	4. Entrar a la máquina virtual:
		-ssh usernam@ipdelavm
	3. transferir la carpeta build al entorno virtual
	-scp -r Hackaton\ PQRS/ jd@68.155.148.163:/home/jd/
	4. 
		-./venv/Scripts/actívate
		- pip install flask
		-pip install -r requirements.txt
	5. desplegar la base de datos en azure
	6. Comprobar que al correr el archivo, funcione la base de datos del azure
	7. correr la máquina virtual

# 7.Peticiones
<img width="1054" height="433" alt="image" src="https://github.com/user-attachments/assets/66dbc73e-2d92-468d-8388-d04d306382c6" />

# 8.Base de datos

![Imagen de WhatsApp 2025-09-11 a las 11 10 10_091baf6b](https://github.com/user-attachments/assets/631189ad-cf13-413e-ae97-f08cf410e79f)


# Integrante
* Juan David samaca Rojas 












