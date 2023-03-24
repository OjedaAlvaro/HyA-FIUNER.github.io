# Hitología y Anatomía

Hola a todos, bienvenidos a la página de histología y Anatomía.

Este sitio web está construido usando [Docusaurus 2](https://docusaurus.io/), un moderno generador de sitios web estáticos

### Para realizar modificaciones en este proyecto, debe contar con algunos requerimientos previos
- [Node.js](https://nodejs.org/en/download/) version 16.14 o superior:
  - Al instalar Node.js, se recomienda marcar todas las casillas de verificación relacionadas con las dependencias.
- [Git](https://git-scm.com/downloads) en cualquier version, se recomienda siempre la ultima.

Ud puede verificar que version de Node.js posee usando:
```
$ node -v
```
Asi mismo la version de Git
```
$ git -v
```

### Modificaciones de forma local
Para comenzar con esto debemos clonar el repositorio a nuestra maquina, para esto usando la terminal o cmd, iremos a la carpeta donde deseamos descargarlo:
```
$ cd /rutaDeDescarga
```
Para clonarlo usaremos el comando:

```
$ git clone https://github.com/HyA-FIUNER/HyA-FIUNER.github.io.git
```
Una vez clonado, abra la carpeta con el editor de texto que sea de su preferencia, ud puede ver los cambios que va realizando de manera sincronica(aca se puede mejorar) para esto, debe poner el siguiente comando en la terminal:

```
$ npx docusaurus start
```

Este comando abrira la pagina web en su navegador predeterminado.

### Añadir las modificaciones al proyecto:

Para realizar cambios, ud debe "empujar" los cambios en git, para esto debemos agregar las modificaciones al sitio de trabajo

```
$ git add .
```
con el punto estamos queriendo decir que agregaremos toda la carpeta, luego de esto haremos un commit y luego "empujaremos"

```
$ git commit -m "Mensaje donde ponemos un resumen de los cambios realizados"
$ git push
```
Aca hay que ver que pasa cuando no tenes acceso y poner como hacerlo desde github
