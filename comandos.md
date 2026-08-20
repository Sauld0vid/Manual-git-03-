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

## `git config`:
Este comando sirve para configurar y personalizar el comportamiento del repositorio o el usuario. Puedes configurar tu nombre de usuario, direccion de correo electrónico, color de interfaz

### Sintaxis:
```
$ git config --global user.name "Tu Nombre"
$ git config --global user.email "tu@email.com"
```

## `git clone`:
Este se utiliza para clonar repositorios existente en un nuevo directorio y de paso, descarga todo lo que esta en el.

### Sintaxis:
```
$ git clone <URL_del_repositorio>
```

## `git status`:
Este comando nos muestra todos los cambios realizados en el repositorio. Te dice que archivos han cambiado, están pendientes de ser confirmados o no están siendo rastreados por Git.

### Sintaxis:
```
$ git status
```


## `git add`:
El comando git add añade tus cambios al área de preparación. Para este hay dos sintaxis, ya sea para subir unos o todos los archivos.

### Sintaxis 1: (añade todos los archivos)
```
$ git add .
```

### Sintaxis 2: 
```
$ git add <nombre_archivo>
```

## `git commit`:
Registra los cambios confirmados en el repositorio. Crea un punto de control con un mensaje que describe los cambios realizados.

### Sintaxis: 
```
$ git commit -m "Mensaje descriptivo"

```

## `git remote add`:
crea una conexión entre tu repositorio Git local y el repositorio Git remoto, permitiéndote introducir y extraer cambios entre ellos:

### Sintaxis: 
```
$ git remote add <repo_name> <remote_url>
```

## `git push`:
Sincroniza tu repositorio remoto con el repositorio local.
Una vez que ejecutes este comando, el repositorio remoto reflejará todos los cambios que hayas confirmado localmente.

### Sintaxis: 
```
$ git push <remote> <branch>
```

