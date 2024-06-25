# Python Final

Este proyecto contiene la configuración inicial y el entorno virtual de un proyecto en Python. A continuación, se detallan los pasos seguidos y la investigación sobre `pip`.

## Pasos Seguidos

1. Crear una carpeta:
   ```bash
   mkdir python-final
   ```
2. Entrar en la carpeta:
   ```bash
   cd python-final
   ```
3. Iniciar el repositorio:
   ```bash
   git init
   ```
4. Crear un archivo Python:
   ```bash
   touch finales.py
   ```
5. Abrir Visual Studio Code:
   ```bash
   code .
   ```
6. Verificar la versión de Python:
   ```bash
   python -V
   python3 -V
   ```
7. Crear el entorno virtual:
   ```bash
   python3 -m venv venv
   ```
8. Activar el entorno virtual:
   - En Linux:
     ```bash
     source venv/bin/activate
     ```
   - En Windows:
     ```bash
     venv\Scripts\activate
     ```
9. Actualizar pip:
   ```bash
   python3 -m pip install --upgrade pip
   ```

## Investigación sobre pip

`pip` es el gestor de paquetes oficial de Python. Permite instalar y gestionar bibliotecas y dependencias de Python. Actualizamos `pip` para asegurarnos de que tenemos la última versión, con todas las mejoras y correcciones de seguridad más recientes.
