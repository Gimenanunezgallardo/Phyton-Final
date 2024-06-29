# Phyton-Final
Ejercicio clase 11

¿Por qué actualizar pip? Actualizar pip es importante por varias razones:

Mejoras de seguridad: Las versiones más recientes de pip suelen incluir correcciones de vulnerabilidades de seguridad, lo que ayuda a proteger tu entorno de desarrollo y producción.

Nuevas funcionalidades: Las actualizaciones pueden incluir nuevas características y mejoras que hacen que pip sea más fácil y eficiente de usar.

Corrección de errores: Las versiones más recientes pueden corregir errores y fallos presentes en versiones anteriores, mejorando la estabilidad de pip.

Compatibilidad: Actualizar pip asegura que tienes la mejor compatibilidad posible con las versiones más recientes de Python y los paquetes de la comunidad.

Cómo actualizar pip Para actualizar pip, puedes usar el siguiente comando en tu terminal o consola de comandos:

python -m pip install --upgrade pip

Este comando le dice a Python que use el módulo pip para instalar la última versión de sí mismo.

Ejemplo Completo Abrir la terminal o consola de comandos: En Windows, puedes usar Command Prompt, PowerShell o Git Bash. En macOS o Linux, usa la Terminal.

Ejecutar el comando de actualización:

python -m pip install --upgrade pip

Verificar la versión actualizada:

pip --version

Este comando te mostrará la versión de pip que tienes instalada actualmente, para que puedas confirmar que la actualización se ha realizado correctamente.

Actualizar pip regularmente te ayudará a mantener tu entorno de desarrollo seguro, compatible y eficiente.





gimen@DESKTOP-BDUBF8P MINGW64 /d
$ ls
'$RECYCLE.BIN'/      'PLOTTER MORITZU SERIE KSA 730'/
'Diseño Grafico'/    'PROGRAMAS PORTABLES'/
 Documents/          'Reset Epson L1300 ES.exe'*
 Downloads/          'System Volume Information'/
 FOTOS/              'TITULO DG.jpg'
 FUENTES/             TecnicaturaGit/
'Gimena PROGRAMAS'/   UCP/
'JH MUEBLES WEB'/     Windows10Upgrade/
 MUSICA/             'programas DE DISEÑO'/

gimen@DESKTOP-BDUBF8P MINGW64 /d
$ mkdir Python-Final

gimen@DESKTOP-BDUBF8P MINGW64 /d
$ cd python-Final

gimen@DESKTOP-BDUBF8P MINGW64 /d/python-Final
$ git init
Initialized empty Git repository in D:/Python-Final/.git/

gimen@DESKTOP-BDUBF8P MINGW64 /d/python-Final (master)
$ touch Finales.py

gimen@DESKTOP-BDUBF8P MINGW64 /d/python-Final (master)
$ code .

gimen@DESKTOP-BDUBF8P MINGW64 /d/python-Final (master)
$ python --version
Python 3.11.4

gimen@DESKTOP-BDUBF8P MINGW64 /d/python-Final (master)
$ python -m venv venv

gimen@DESKTOP-BDUBF8P MINGW64 /d/python-Final (master)
$ source venv/bin/activate
bash: venv/bin/activate: No such file or directory

gimen@DESKTOP-BDUBF8P MINGW64 /d/python-Final (master)
$ source venv/scripts/activate
(venv)
gimen@DESKTOP-BDUBF8P MINGW64 /d/python-Final (master)
$ pip list
Package    Version
---------- -------
pip        23.1.2
setuptools 65.5.0

[notice] A new release of pip is available: 23.1.2 -> 24.1.1
[notice] To update, run: python.exe -m pip install --upgrade pip
(venv)
gimen@DESKTOP-BDUBF8P MINGW64 /d/python-Final (master)
$ python.exe -m pip install --upgrade pip
Requirement already satisfied: pip in d:\python-final\venv\lib\site-packages (23.1.2)
Collecting pip
  Downloading pip-24.1.1-py3-none-any.whl (1.8 MB)
     ---------------------------------------- 1.8/1.8 MB 3.9 MB/s eta 0:00:00
Installing collected packages: pip
  Attempting uninstall: pip
    Found existing installation: pip 23.1.2
    Uninstalling pip-23.1.2:
    
gimen@DESKTOP-BDUBF8P MINGW64 /d/python-Final (master)
$ git add .

gimen@DESKTOP-BDUBF8P MINGW64 /d/python-Final (master)
$ git commit -m "Trabajo Final 11 - Python"


