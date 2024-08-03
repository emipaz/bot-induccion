# Proyecto de Chat Bot Induccion para empresas

## Descripción

Es un bot que basado en la documentacion interna de una empresa induce al nuevo empleado en sus tareas, pero se puede adaptar a cualquier empresa o proyecto.

## Requisitos

1. Python 3.8 o superior globalmente

### Crear un entorno virtual

1. Crear una carpeta en el directorio de trabajo
2. Crear un entorno virtual con el comando 

```bash
python -m venv <nombre de la carpeta del entorno virtual>
```

3. Actualizar pip con el comando

```bash
python -m pip install --upgrade pip
```

O ejecutando el script get_pip.py

```bash
python get-pip.py
```

4. Instalar las dependencias con el comando

```bash
pip install -r requirements.txt
```

> El archivo requirements.txt contiene las dependencias que se van a instalar en el entorno virtual, hay mas de las necesarias para este proyecto, pero se recomienda tenerlas para proyectos que requieran otros recursos.

5. Guardar la api_key de open ai en el archivo .env

```bash
OPENAI_API_KEY = <api_key>
```

6. Crear un kernel global para jupyter (Opcional)

```bash
python -m ipykernel install --user --name <nombre del kernel> --display-name <nombre del kernel>
```

7. Iniciar jupyter O Visual Studio Code