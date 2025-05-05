# API Stand Tests

Este proyecto contiene un conjunto de pruebas automatizadas para la API de creación de usuarios, verificando la funcionalidad de la solicitud de nuevos usuarios. Utiliza `pytest` para la ejecución de pruebas y está diseñado para asegurar que la API maneje correctamente diferentes escenarios de entrada.

## Características

- Pruebas positivas para la creación de usuarios con nombres válidos.
- Pruebas negativas para manejar errores de entrada, como nombres demasiado cortos, largos o inválidos.
- Verificación de respuestas de la API, incluyendo códigos de estado y mensajes de error.

## Requisitos Previos

Antes de ejecutar las pruebas, asegúrate de tener instalados los siguientes paquetes:

- `pytest`
- `requests`

Puedes instalarlos utilizando pip:

```bash
pip install pytest requests

```

### Uso de Postman

Puedes utilizar Postman para probar manualmente los endpoints de la API. Asegúrate de configurar las rutas y los datos de acuerdo con los parámetros definidos en `configuracion.py` y `data.py`.

## Estructura del Código

El código está organizado en varios módulos:

- **`api_stand_tests.py`**: Contiene las pruebas automatizadas para la API de creación de usuarios.
- **`data.py`**: Proporciona datos de prueba y configuraciones necesarias para las pruebas, incluyendo encabezados y el cuerpo de la solicitud para crear usuarios.
- **`sender_stand_request.py`**: Maneja las solicitudes a la API, incluyendo la creación de usuarios y la gestión de productos.
- **`configuracion.py`**: Contiene configuraciones necesarias para la ejecución del proyecto, como rutas de servicio y archivos.
- **`main.py`**: Punto de entrada principal del proyecto, que incluye funciones de prueba simples.

## Programas Recomendados

Para ejecutar el código de manera adecuada, se recomienda tener instalados los siguientes programas:

- **Python**: Asegúrate de tener Python 3.x instalado en tu máquina.
- **Postman**: Para realizar pruebas manuales de la API.
- **Visual Studio Code** o cualquier otro editor de código: Para editar y gestionar el código fuente.
- **Git**: Para clonar el repositorio y gestionar el control de versiones.

## Información del Autor

Nombre: Eduardo Reyna Hernández  
Cohorte: 19
