# Dashboard de Gestión de Citas Médicas

## Descripción
Este proyecto corresponde a la Actividad 3 del caso de estudio: Plataforma Inteligente de Gestión de Citas Médicas en un Hospital de Lima Norte.

El dashboard fue desarrollado con Streamlit y permite visualizar:
- Citas por especialidad.
- Estado de las citas.
- Citas por mes.

## Archivos del proyecto
- `app.py`: código principal del dashboard.
- `citas_medicas.csv`: dataset generado en la Actividad 1.
- `requirements.txt`: librerías necesarias para ejecutar el proyecto.
- `README.md`: descripción del proyecto.

## Ejecución en Visual Studio Code
1. Abrir la carpeta del proyecto en Visual Studio Code.
2. Abrir una terminal.
3. Instalar las librerías:
```bash
pip install -r requirements.txt
```
4. Ejecutar el dashboard:
```bash
streamlit run app.py
```

## Publicación en Streamlit Community Cloud
1. Crear un repositorio público en GitHub llamado `dashboard-citas-medicas`.
2. Subir los archivos `app.py`, `citas_medicas.csv`, `requirements.txt` y `README.md`.
3. Ingresar a Streamlit Community Cloud.
4. Seleccionar el repositorio.
5. Indicar como archivo principal `app.py`.
6. Presionar Deploy.
7. Copiar la URL pública generada.
