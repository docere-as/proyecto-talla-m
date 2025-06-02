# Styleguide


## El código fuente

- Documentar el código con _ExDoc_.

- Se recomienda usar anotaciones de tipos con `typespec` y demás.

- El formato para el código viene dado por la configuración por
  defecto de `mix format`.

- Todo el código incluido en el repositorio debe haber sido formateado
  usando `mix format`. Se recomienda forzar este aspecto con acciones
  _precommit_ y/o de integración continua.

- El estilo de codificación está descrito en esta documento: [The
  Elixir Style
  Guide](https://github.com/christopheradams/elixir_style_guide).
  
- La estructura del proyecto parte de la estructura creada por `mix
  new`.

  
## Los mensajes de commit

Usar _Conventional commits_, con el siguiente cambio: complementar el
_type_ indicado en la especificación con el _gitmoji_ correspondiente.

Referencias útiles:

  - [Conventional
    Commits](https://www.conventionalcommits.org/en/v1.0.0/)

  - [How to Write Better Git Commit
    Messages](https://www.freecodecamp.org/news/how-to-write-better-git-commit-messages/)
  
  
  - [gitmoji](https://gitmoji.dev/)


## El control de versiones

- Realizar commits pequeños y frecuentes.

- Evitar los commits desde la interfaz web de github siempre que sea posible.

- No incluir en el repositorio ficheros de configuración de ningún
  IDE particular.
  
- Se recomienda el uso de ramas. En caso de usarlas se debe establecer
  una estrategia para su gestión, p.e.: [What Are the Best Git
  Branching
  Strategies](https://www.abtasty.com/blog/git-branching-strategies/)


## El diseño de la arquitectura

- Documentar el diseño con los cuatro niveles del modelo C4.

- Salvo que sea trivial, añadir un diagrama de despliegue.

- En los casos en que los diagramas sean muy complejos, es preferible
  dividirlos en varios diagramas.
  
- Además de las fuentes de los diagramas, añadir al repositorio su
  versión en formato _PDF_ o _PNG_.

- Todos los cambios y decisiones adoptadas en el diseño se documentan
  siguiendo el formato [Architectural Decision
  Records](https://adr.github.io/).


## Las pruebas

- El esfuerzo principal se dedica a las pruebas software
  automatizadas.
  
- Las pruebas automatizadas se ejecutan con `mix test`.

- Opcionalmente, se realizarán pruebas exploratorias.

- En caso de realizar pruebas exploratorias, es primordial que sean
  reproducibles y documentar los pasos necesarios para reproducirlas.
  
- Documentar los tipos de pruebas realizadas, los escenarios cubiertos,
  y los escenarios no cubiertos.
  

## La documentación

La documentación del proyecto incluye:

  - Breve descripción del sistema desarrollado, y cualquier otra
    información que contribuya a una mejor comprensión del mismo.
  
  - Requisitos funcionales.
  
  - Requisitios no funcionales del mismo.

  - Diseño de la arquitectura. Tal y como se describe en el apartado
    correspondiente.

  - Instrucciones para compilar, desplegar y  utilizar la aplicación.
  
  - Documentación de los tests. Tal y como se describe en el apartado
    correspondiente.

  - El material audiovisual empleado en la presentación.
