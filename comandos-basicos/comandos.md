# Comandos basicos de Git
Los pasos basicos del git normalmente son crear un repositorio, copiar uno existente, editar el codigo y subirlo. Y aunque hay cientos de comandos, es importante conocer los mas básicos y los más usados.

## `Git init`:
Este comando crea un nuevo repositorio Git o reinicia uno existente. 
Cuando ejecutas el comando, tu directorio actual se convierte en un repositorio Git, lo que te permite seguir sus cambios. Añade una carpeta oculta `.git` en el directorio, donde Git almacena todos los metadatos, el historial de versiones y los registros relacionados con el proyecto.

### Ejemplo:
* Primero abre tu terminal y crea una nueva carpeta para tu proyecto:
```
mkdir mi-proyecto-web
cd mi-proyecto-web
```
* Luego inicializa Git en esa carpeta:
Ejecuta el comando git init
```
git init
```

El resultado en la terminal será: `Initialized empty Git repository in /ruta/a/tu/carpeta/mi-proyecto-web/.git/`

## `git mmmmmmmm`:
Este comando sirve para configurar y personalizar el comportamiento del repositorio o el usuario. Puedes configurar tu nombre de uduario, direccion de correo electrónico, color de interfaz

### Ejemplo:
```
$ git config --global user.name "Tu Nombre"
$ git config --global user.email "tu@email.com"
```

## `git ssssss`:
Este se utiliza para clonar repositorios existente en un nuevo directorio y de paso, descarga todo lo que esta en el.

### Ejemplo:
```
$ git clone <URL_del_repositorio>
```
