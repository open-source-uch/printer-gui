# Printer GUI

Interfaz gráfica para imprimir en el servidor Anakena del DCC.

## Objetivos

Proveer una interfaz estandarizada para imprimir en el DCC sin utilizar una terminal.

## Devel Environment

### IDE

A continuación las opciones recomendadas para OSUCH:

1. PyCharm Professional

> Enlace: https://www.jetbrains.com/pycharm/

El curso Metodologías de Diseño y Programación requiere obtener un licencia
educacional (sin costo) de JetBrains para utilizar el IDE [IntelliJ](https://www.jetbrains.com/idea/).

Esta licencia de JetBrains también habilita su producto PyCharm Professional;
se recomienda su uso porque la interfaz es idéntica.

2. Visual Studio Code

> Enlace: https://code.visualstudio.com/

Este es un programa utilizado en la industria y fuera del ámbito académico,
provee extensiones que lo vuelven apto para trabajar con diferentes lenguajes de programación.

Está vinculado a Microsoft, pero puede utilizarse sin costo.

3. VSCodium

> Enlace: https://vscodium.com/

El código fuente de Visual Studio Code es Open Source, este es un *fork*.

No incluye telemetría de Microsoft y puede utilizarse en reemplazo de VSCode;
importante destacar que no todas las extensiones son compatibles.

### Source File Structure

A continuación el orden de archivos dentro del repositorio:

```
printer-gui
├── .env
├── .git
├── .gitignore
├── .idea
├── README.md
├── resources
└── src

```

* **.env**: Contiene la versión estática de Python y las bibliotecas utilizadas.
  * *VSCode/VSCodium*: Lo captura de forma automática.
  * *PyCharm*: Click derecho
* **.git**: Contiene el repositorio de Git (no tocar).
* **.gitignore**: Listado de archivos/directorios ignorados por git (no tocar).
* **.idea**: Contiene configuraciones de PyCharm.
* **README.md**: Pantalla principal que aparece en GitHub.
* **resources**: Contiene todo lo que no sea código.
* **src**: Contiene todo el código que conforma la lógica del programa.

## Good practices

Se intenta seguir lo siguente:

* https://docs.python-guide.org/writing/structure/
