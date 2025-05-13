# Ejemplos de programacion orientada a obejetos

## 1. Crear el archivo **.gitignore**

Se crea el achivo **.gitignore** para configurar los archivos que no se sincronizan con el repositorio

````shell
*.pyc
__pycache__/
.venv/
````

## 2. Crear el **virtual environment**

se crea el ambiente virtual de trabajo de python

````shell
python3 -m venv .venv (en lo ultimo es el nombre de tu repositorio)
````

## 3. Iniciar el **virtual environment**

Se inicia el **virtual environment** para instalar las librerias necesarias para el proyecto

````shell
source .venv/bin/activate
````

## 4. Actualizar **pip** dentro del **virtual environment**

Se actualiza la version instalada de **pip** para poder descargar las ultimas versiones de las librerias

````shell
pip install --upgrade pip
````

## 5. Verificar las librerias instaladas

Se verifica las librerias y versiones se tienen instaladas

````shell
pip freeze
````

## 6. Instalar librerias

Se instalan las librerias que se van a ocupar en el proyecto

````shell
pip install web.py
````

## 7. Crear el archivo **requirements.txt**

Se crea el archivo **requirements.txt** con las librerias y el numero de version utilizadas

````shell
pip freeze > requirements.txt
````

## 8. Crear el archivo **runtime.txt**

Se crea el archivo **runtime.txt** con la version de Python3 que se esta utilizando en el proyecto

````shell
python3 -V >runtime.txt
````

## 9. Indexar los archivos creados con **git**

Se

````shell
git add .
````

## 10. Generemos un **commit**

Se realiza un **commint** con un texto que describa los cambios realizados en el proyecto

````shell
git commint -m "CREATED configuracion basica"
````

## 11. Realizar un **push**

Se realiza un **push** para subir los cambios realizados al repositorio de **GitHub**

````shell
git push -u origin main
````