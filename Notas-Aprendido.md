# Introducción

La contracción de "Dev" y "Ops" hace referencia a la sustitución del desarrollo y las operaciones en silos. La idea es crear equipos multidisciplinares que ahora trabajen conjuntamente con herramientas y procedimientos compartidos y eficaces. Los procedimientos de DevOps esenciales son un planeamiento ágil, una integración y un ofrecimiento de valor continuos, así como la supervisión de las aplicaciones. DevOps es un recorrido constante.

## Comprender el tiempo de ciclo

Empecemos con una suposición básica sobre el desarrollo de software. Lo describiremos con el bucle OODA (observar, orientar, decidir, actuar). Diseñado originalmente para evitar que los pilotos de cazas salieran disparados, el bucle OODA es una excelente manera de pensar en cómo mantener la ventaja respecto a la competencia. Para empezar, observe el negocio, el mercado, las necesidades, el comportamiento actual del usuario y los datos de telemetría disponibles.

DevOps se centra en reducir el tiempo de ciclo del desarrollo de software, comenzando con la canalización de versiones. La integración continua ayuda a detectar defectos tempranamente y evita problemas de fusión, proporcionando retroalimentación rápida a los equipos. La entrega continua permite a las organizaciones corregir errores y adaptarse rápidamente a cambios empresariales. El control de versiones con Git facilita la comunicación global del equipo y la supervisión de actividades de desarrollo.

Las técnicas Agile y lean se usan para planificar y gestionar el trabajo en sprints, y adaptarse a necesidades cambiantes. En DevOps, el software debe recolectar telemetría para cumplir con objetivos empresariales.

La supervisión y registro de aplicaciones en ejecución ayudan a validar estrategias rápidamente. Las nubes públicas e híbridas eliminan cuellos de botella y proporcionan infraestructura flexible, ya sea como servicio (IaaS) o plataforma (PaaS).

La infraestructura como código (IaC) permite la automatización y validación de entornos. Los microservicios dividen los casos de uso en pequeños servicios reutilizables, mejorando la escalabilidad y eficacia. Los contenedores son una evolución ligera y rápida de la virtualización.

Adoptar DevOps puede ser difícil al principio, pero con práctica frecuente, como en el gimnasio, se vuelve más fácil y efectivo. Comienza con prácticas que tengan el mayor impacto y desarrolla sinergias.

## Reducir el tiempo de ciclo

Al adoptar prácticas de DevOps:
- El tiempo de ciclo se reduce trabajando en lotes más pequeños.
- Uso de más automatización.
- Reforzar la canalización de versión.
- Mejorar la telemetría.
- Implementar con más frecuencia.

<hr>

# ¿Qué es GitHub?

GitHub es una plataforma de Software como Servicio (SaaS) de Microsoft que proporciona repositorios basados en Git y herramientas de DevOps para desarrollar e implementar software. Tiene una amplia gama de integraciones con otras herramientas líderes.

## ¿Qué proporciona GitHub?
GitHub ofrece una variedad de servicios para el desarrollo y la implementación de software:

- **Codespaces**: Entorno de desarrollo en la nube basado en Visual Studio Code. Facilita el desarrollo multiplataforma, permitiendo que los desarrolladores trabajen desde cualquier lugar con un entorno de desarrollo consistente.
  - **Ejemplo**: Un desarrollador puede crear un Codespace para trabajar en un proyecto de Node.js sin necesidad de instalar Node.js localmente en su máquina.

- **Repos**: Repositorios públicos y privados basados en Git. Permiten el control de versiones y la colaboración en proyectos de software.
  - **Ejemplo**: Un equipo de desarrollo puede usar un repositorio privado para colaborar en el desarrollo de una aplicación interna.

- **Acciones**: Permite la creación de flujos de trabajo de automatización. Estos flujos pueden incluir tareas como la integración continua (CI) y la entrega continua (CD), utilizando scripts personalizados y variables de entorno.
  - **Ejemplo**: Un flujo de trabajo puede compilar automáticamente el código y ejecutar pruebas cada vez que se hace un commit en el repositorio.

- **Packages**: Administración de paquetes que permite integrar código de otros proyectos de código abierto y de terceros.
  - **Ejemplo**: Un proyecto puede usar GitHub Packages para gestionar dependencias como bibliotecas de terceros, asegurando que se usen versiones específicas de los paquetes.

- **Seguridad**: Características de seguridad como el escaneo de código para detectar vulnerabilidades y la revisión automatizada de código.
  - **Ejemplo**: GitHub puede escanear automáticamente el repositorio en busca de dependencias con vulnerabilidades conocidas y sugerir actualizaciones para mejorar la seguridad.

En resumen, GitHub es una herramienta integral para la colaboración y la gestión del ciclo de vida del desarrollo de software, facilitando desde la codificación hasta la implementación segura y eficiente del software.

<hr>

# ¿Qué es Azure DevOps?

Azure DevOps es una plataforma de Software como Servicio (SaaS) de Microsoft que proporciona una cadena de herramientas de DevOps de un extremo a otro para desarrollar e implementar software. Se integra con las herramientas más importantes del mercado, siendo una excelente opción para orquestar una cadena de herramientas de DevOps.

## ¿Qué proporciona Azure DevOps?

Azure DevOps incluye una gama de servicios que abarcan el ciclo de vida de desarrollo completo:

- **Azure Boards**: Herramienta para el seguimiento de elementos de trabajo, planeamiento ágil, visualizaciones e informes.
  - **Ejemplo**: Un equipo ágil puede usar Azure Boards para planificar sprints y rastrear el progreso de las tareas de desarrollo.

- **Azure Pipelines**: Plataforma CI/CD que soporta múltiples lenguajes, plataformas y contenedores.
  - **Ejemplo**: Una empresa puede usar Azure Pipelines para compilar, probar y desplegar automáticamente su aplicación en diferentes entornos.

- **Azure Repos**: Repositorios de Git privados hospedados en la nube.
  - **Ejemplo**: Un equipo de desarrollo puede almacenar y gestionar su código fuente en Azure Repos, aprovechando las capacidades de control de versiones de Git.

- **Azure Artifacts**: Administración de paquetes compatible con Maven, npm, Python y NuGet.
  - **Ejemplo**: Un proyecto puede utilizar Azure Artifacts para gestionar y compartir bibliotecas internas de código entre diferentes equipos.

- **Azure Test Plans**: Solución para pruebas planeadas y exploratorias.
  - **Ejemplo**: Un equipo de QA puede crear y ejecutar planes de prueba detallados para asegurar la calidad del software antes de su lanzamiento.

Además, Azure DevOps puede orquestar herramientas de terceros, permitiendo una integración fluida con otras plataformas y servicios utilizados por el equipo de desarrollo.

En resumen, Azure DevOps es una solución completa para la gestión del ciclo de vida del desarrollo de software, proporcionando herramientas esenciales para cada etapa, desde la planificación hasta la entrega y pruebas.
