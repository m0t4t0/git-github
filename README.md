# Git y GitHub

Deja de versionar tus proyectos usando tu propio sistema de control de versiones. Mejor usa Git, el sistema de control de versiones por excelencia que utiliza la industria tecnológica. Aprende a trabajar con git, conceptos básicos, clonar un repositorio y gestionar tus proyectos alojándolos en tu repositorio local y en GitHub.

:sunny::sunny::sunny::sunny::sunny: BÁSICO :suspect:

* Llevar un Control de Versiones en tus Proyectos con Git
* Trabajar en Equipos de Forma Colaborativa
* Utilizar Dominios Personalizados con GitHub Pages
* Instalar Git en tu sistema operativo

## Configuración Básica :hatching_chick:

* Identidad
Lo primero que deberás hacer cuando instales Git es establecer tu nombre de usuario y dirección de correo electrónico. Esto es importante porque los "commits" de Git usan esta información, y es introducida de manera inmutable en los commits que envías:
```bash
    $ git config --global user.name "nombres apellidos"
    $ git config --global user.email "correo@proveedor.com"
```

* Editor
Puedes elegir el editor de texto por defecto que se utilizará cuando Git necesite que introduzcas un mensaje. Si no indicas nada, Git usará el editor por defecto de tu sistema, que generalmente es Vim. Si quieres usar otro editor de texto como Nano, puedes hacer lo siguiente:
```bash
    $ git config --global core.editor nano
```

* Comprobar configuración
Si quieres comprobar tu configuración, puedes usar el comando git config --list para mostrar todas las propiedades que Git ha configurado:
```bash
    $ git config --list
```