# Cookiecutter - Mi Proyecto

Este repositorio es una plantilla de proyecto generada con Cookiecutter.

##  Uso rápido

Puedes clonar esta plantilla usando el siguiente comando:

```bash
cookiecutter https://github.com/AlejandroSegura24/cookiecutter-personal.git
```

Asegúrate de tener instalado cookiecutter:

```bash
pip install cookiecutter
```

## Pasos para subir el repositorio a GitHub

1. ### Entrar a la carpeta del proyecto generado

```bash
cd nombre-del-proyecto
```

2. ### Inicializa Git dentro de la carpeta
```bash
git init
```

3. ### Agrega todos los archivos a Git y luego haz tu primer commit
```bash
git add .
git commit -m "Primer commit: proyecto generado con Cookiecutter"
```

4. ### Ve a GitHub y crea un repositorio vacio

* Ve a https://github.com/new

* Asigna el mismo nombre o el que prefieras, por ejemplo: mi-proyecto-cool

* NO marques "Initialize with README"

* Crea el repositorio

5. ### Conecta tu proyecto local al repositorio remoto
```bash
git remote add origin https://github.com/tu-usuario/mi-proyecto-cool.git
```

6. ### Sube el repositorio a GitHub
```bash
git branch -M main
git push -u origin main
```