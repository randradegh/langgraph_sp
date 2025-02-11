# Proyecto de Integración de Herramientas con LangChain y LangGraph

[![Python](https://img.shields.io/badge/Python-3.13.1-blue)](https://www.python.org/)
[![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange)](https://jupyter.org/)
[![LangChain](https://img.shields.io/badge/LangChain-v0.0.1-green)](https://github.com/hwchase17/langchain)
[![LangGraph](https://img.shields.io/badge/LangGraph-v1.0.0-brightgreen)](https://github.com/microsoft/langgraph)
[![Requests](https://img.shields.io/badge/Requests-2.x-blue)](https://docs.python-requests.org/)
[![python-dotenv](https://img.shields.io/badge/python--dotenv-v0.21.0-blue)](https://github.com/theskumar/python-dotenv)

## Descripción

Este proyecto es un ejemplo completo de integración de herramientas en un entorno interactivo de Jupyter Notebook con Python. Se utilizan las librerías **LangChain** y **LangGraph** para definir y ejecutar flujos de trabajo que permiten:

- La ejecución condicional de acciones.
- La integración de herramientas externas, como la API Weatherbit para consultar el clima.
- La gestión y procesamiento de mensajes en un agente conversacional.

Además, el archivo `.cursorrules` permite personalizar mensajes y comportamientos en la interfaz, proporcionando un feedback continuo al usuario durante la ejecución.

## Requisitos

- **Python 3.13.1** (o superior)
- **Jupyter Notebook** o **JupyterLab**

Se requiere la instalación de las siguientes dependencias:

- `python-dotenv`
- `requests`
- `langchain_core` (o paquete equivalente)
- `langgraph`

## Instalación

1. Clona el repositorio:

   ```bash
   git clone https://github.com/tu_usuario/tu_repositorio.git
   ```

2. Accede al directorio del proyecto:

   ```bash
   cd tu_repositorio
   ```

3. Instala las dependencias:

   ```bash
   pip install -r requirements.txt
   ```

   *Asegúrate de configurar el archivo `.env` con las claves de API necesarias (por ejemplo, `WEATHERBIT_API_KEY`).*

## Uso

Abre el Notebook principal:

```bash
jupyter notebook langgraph_sp.ipynb
```

El proyecto ejecuta un flujo de trabajo interactivo que utiliza herramientas externas para responder a consultas, como la información del clima.

## Estructura del Proyecto

- **langgraph_sp.ipynb**: Notebook principal con la lógica de ejecución y definición de flujos.
- **.cursorrules**: Archivo de configuración para personalizar los mensajes y comportamientos durante la ejecución.
- **README.md**: Este archivo.
- Otros archivos y carpetas de soporte.

## Contribuciones

¡Las contribuciones son bienvenidas! Si deseas mejorar el proyecto o reportar algún error, por favor, abre un *issue* o envía un *pull request*.

## Licencia

Este proyecto se distribuye bajo la Licencia MIT. Consulta el archivo `LICENSE` para más detalles.
