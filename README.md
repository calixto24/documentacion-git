
# Documentación Git

Todo lo que estoy aprendiendo de Git.

## Indice
- [1. Introducción](#introduccion)
    - [¿Que es git?](#que-es-git)
    - [¿Como maneja y almacena sus datos?](#como-maneja-y-almacena-sus-datos)
    - [¿Porque es rapido?](#porque-es-rapido)
    - [Los tres estados](#los-tres-estados)

## Introducción

### ¿Que es Git?

Git es una herramienta de control de versiones. Es decir, es un sistema que registra los cambios realizados por una o mas personas y nos permite recuperar versiones especificas.

### ¿Como maneja y almacena sus datos?

Git a diferencia de los demas sistemas de almacenamiento de informacion, crea una copia instantanea del proyecto. En cambio, los otros crean una version diferente por cada modificacion que se realice.

![imagen](md/img1.png)

```bash
  Nota: Cada version es un documento diferente
```

Por su parte git, maneja sus datos como un conjunto de copias instantaneas, cuando creas un proyecto, guarda una referencia y si no haces alguna modificacion, git no almacena de nuevo la informacion, sino, guarda la referencia anterior del archivo.

![imagen](md/img2.png)

## ¿Porque es rapido?

Para navegar por la historia del proyecto, Git no necesita conectarse al servidor para obtener la historia y mostrartela, ya que lo lee directamente de tu base de datos local. De esta manera ves la informacion de manera inmediata.

## Los tres estados

Git tiene tres estados fundamentales:

- **Confirmado**: Los datos estan almacenados en la base de datos local.

- **Modificado**: Has hecho alguna modificacion, no confirmado en la base de datos local.

- **Preparado**: Has marcado el archivo modificado que pronto estará confirmado.

Las tres secciones importantes de un poryecto Git:

- **Directorio Git**: En el se encuentran los metadatos del proyecto, eso es lo que se copia cuando clonas un proyecto.

- **Directorio de trabajo**: Es una copia de una version del proyecto.

- **Area de preparación**: Es un archivo que almacena información que irá en tu proxima confirmación.

Flujo de trabajo de Git:

- Modificas unos archivos del directorio de trabajo. 

- Preparas los archivos añadiendolos al area de preparación.

- Confirmas los cambios del area de preparación y se almacena al directorio git.



