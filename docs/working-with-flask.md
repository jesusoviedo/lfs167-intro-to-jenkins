# 🚀 Levantar la Aplicación Flask

## En un entorno de Desarrollo
Para iniciar la aplicación Flask en modo desarrollo, sigue estos pasos:

### 1. Activar entorno

Asegúrate de activar tu entorno virtual:

```bash
# En Windows:
.venv\Scripts\activate
# En MacOS/Linux:
source .venv/bin/activate
```

### 2. Configurar el archivo .flaskenv
Crea un archivo .flaskenv en el directorio raíz del proyecto y agrega las siguientes líneas para especificar el nombre de la aplicación y el entorno:

```bash
FLASK_APP=app
FLASK_ENV=development
FLASK_RUN_PORT=8080
FLASK_DEBUG=1
```

### 3. Levantar la aplicación
Con todo configurado, ejecuta el siguiente comando para levantar la aplicación:

```bash
python -m flask run
```

Esto iniciará el servidor en `http://127.0.0.1:8080/`, donde podrás ver tu aplicación Flask en acción (en modo debug activado).

## En un entorno de Producción