# Investigación: buenas prácticas de GitHub
GitHub no debe entenderse únicamente como un sitio para almacenar código. Es una plataforma para control de versiones, colaboración, revisión de código, automatización, documentación y seguridad.

Aplicar buenas prácticas permite que un proyecto sea:
- Mas facil de mantener 
- Mas seguro 
- Mas conprensible para los nuevos desarrrolladores 
- Mas sencillo de revisar 
- Menos propenso a errores 
- Más organizado para el trabajo en equipo 

GitHub recomienda explícitamente utilizar documentación, ramas, revisiones mediante Pull Requests y mecanismos de seguridad para mantener repositorios saludables.

##Mantener una estructura clara del repositorio
Una de las primeras buenas prácticas es organizar correctamente los archivos del proyecto.

Una estructura habitual podría ser:
    * mi-proyecto
     * src/
      * tests/
       * docs/
        * .github/
            * workflows/
            * ISSUE_TEMPLATE/
            * PULL_REQUEST_TEMPLATE.md
            * CODEOWNERS
    * .gitignore
    * README.md
    * CONTRIBUTING.md
    * CODE_OF_CONDUCT.md
    * LICENSE
    * SECURITY.md


No todos los proyectos necesitan todos estos archivos, pero cada uno cumple una función específica.

## README.md
GitHub recomienda tener un README en cada repositorio porque permite explicar rápidamente qué es el proyecto y cómo utilizarlo.

Un buen README debería incluir, según el proyecto:

- Nombre y descripción.
- Objetivo.
- Tecnologías utilizadas.
- Requisitos.
- Instalación.
- Configuración.
- Ejemplos de uso.
- Cómo ejecutar las pruebas.
- Cómo contribuir.
- Licencia.
Buena práctica: mantener el README actualizado. Una documentación desactualizada puede ser incluso más perjudicial que no tener documentación.Buena práctica: mantener el README actualizado. Una documentación desactualizada puede ser incluso más perjudicial que no tener documentación.

## Crear commits descriptivos 
Los commits deben explicar claramente qué cambio se realizó.

Buenos ejemplos:

feat: agregar sistema de login
fix: corregir error de autenticación
docs: actualizar README

Se deben evitar mensajes poco claros como:

cambios
update
arreglos
final

## Utilizar pull requests 

Los Pull Requests permiten revisar los cambios antes de agregarlos a la rama principal. Cada Pull Request debería explicar qué cambios se realizaron y qué problema solucionan.

La revisión de código ayuda a encontrar errores, mejorar la calidad del programa y asegurar que los cambios cumplen con las reglas del proyecto.

## Seguridad 
Nunca se deben subir contraseñas, tokens, API Keys o información privada al repositorio. Para evitarlo se puede utilizar un archivo .gitignore y variables de entorno.

GitHub también proporciona herramientas como Dependabot, Secret Scanning y Code Scanning, que ayudan a detectar vulnerabilidades y problemas de seguridad.

## Automatizacióm
 GitHub Actions permite automatizar tareas como ejecutar pruebas, comprobar el código y realizar despliegues. Por ejemplo, cada vez que se realiza un Pull Request se pueden ejecutar automáticamente las pruebas del proyecto.

Esto ayuda a detectar errores antes de incorporar los cambios a main.

## Documentación y mantenimiento 
Un proyecto debe mantener su documentación actualizada. Si cambia la forma de instalar, ejecutar o utilizar el programa, también debe actualizarse el README.md.

Además, es importante mantener las dependencias actualizadas, corregir errores y revisar periódicamente la seguridad del proyecto.

## Conclucion
Las buenas prácticas en GitHub permiten trabajar de una manera más organizada, segura y profesional. Utilizar correctamente las ramas, commits, Pull Requests, documentación y herramientas de seguridad facilita el trabajo en equipo y ayuda a mantener la calidad del proyecto.

## Fuentes 
* Github Docs
* GitHub Actions
* GitHub Security
* GitHub Pull Requests
