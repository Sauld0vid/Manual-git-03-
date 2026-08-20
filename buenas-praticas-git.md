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

## Mantener una estructura clara del repositorio
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

La documentación de Git es una valiosa fuente de información que te ayudará a utilizar Git de manera efectiva, resolver problemas y mantener un flujo de trabajo eficiente. Leerla te permitirá aprovechar al máximo esta poderosa herramienta de control de versiones.

- La documentación oficial de Git: El sitio web oficial de Git proporciona documentación completa y detallada sobre todos los aspectos de Git. Aquí encontrarás información sobre comandos, conceptos, configuraciones, flujos de trabajo y mucho más. Se recomienda empezar por la sección "Git Basics" para obtener una base sólida sobre los conceptos y comandos fundamentales.

- Referencia de comandos: La documentación de Git incluye una referencia completa de todos los comandos disponibles en Git. Puedes consultar la descripción de cada comando, sus opciones y cómo utilizarlo correctamente. Esto es especialmente útil cuando encuentres un comando desconocido o necesites entender en detalle cómo funciona.

- Manuales de Git: La documentación de Git también incluye varios manuales específicos sobre temas particulares. Algunos ejemplos son: Pro Git, Git Glossary,Git Hooks,Git Attributes,etc.

- Ejemplos y tutoriales: Además de la documentación técnica, el sitio web de Git ofrece una sección de "Git Tutorials" con ejemplos prácticos y tutoriales paso a paso. Estos tutoriales cubren una amplia gama de temas, desde los conceptos básicos hasta flujos de trabajo avanzados, colaboración y más.

- Explorando Git en la línea de comandos: La documentación de Git te enseñará a utilizar los comandos, pero también es útil para explorar Git directamente desde la línea de comandos. Puedes utilizar la opción --help con cualquier comando para obtener información breve sobre su uso y opciones. Por ejemplo, puedes ejecutar git commit --help para obtener información sobre el comando commit.

