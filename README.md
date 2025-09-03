# fastapi_INNER_LIGTH-katerin_moya-3147253
# INNER_LIGHT 🌟

Proyecto desarrollado en **FastAPI** con base de datos **MongoDB**, como parte del proceso formativo en el SENA (ADSO).

---

## 🚀 Requisitos previos

- Python 3.8 o superior
- MongoDB instalado y corriendo en `mongodb://localhost:27017`
- Git (opcional, si deseas clonar desde un repositorio)

---

## ⚙️ Instalación
 
   git clone https://github.com/tu-usuario/INNER_LIGHT.git
   cd INNER_LIGHT
Crea y activa un entorno virtual:

python -m venv venv
source venv/bin/activate   # En Linux/Mac
venv\Scripts\activate      # En Windows
Instala las dependencias:

bash
Copiar código
pip install -r requirements.txt
▶ Ejecución
Levanta el servidor con Uvicorn:

uvicorn app:app --reload
La API estará disponible en:
 http://127.0.0.1:8000

Y la documentación interactiva en Swagger:
 http://127.0.0.1:8000/docs

 Estructura del proyecto

INNER_LIGHT/
│── app.py            # Punto de entrada de la aplicación
│── database.py       # Configuración de la base de datos
│── models/           # Modelos (Pydantic)
│── routers/          # Rutas de la API
│── seed.py           # Datos iniciales
│── requirements.txt  # Dependencias
✅ Funcionalidades principales
Gestión de usuarios (CRUD completo)

Validación de datos con Pydantic

Documentación automática con Swagger


Desarrollado por katerin moya
Programa: ADSO – SENA

yaml
Copiar código

---

👉 Este `README.md` ya te cubre la parte de **documentación y despliegue local**.  
Si luego lo subes a GitHub, quedará aún más completo para tu lista de chequeo.  

¿Quieres que te arme también los **comandos paso a paso para subir tu proyecto a GitHub** por primera vez?







Preguntar a ChatGPT
