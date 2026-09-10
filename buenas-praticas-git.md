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
