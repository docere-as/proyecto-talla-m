# Manual de Estilo

Para que el repositorio del proyecto no sea un caos, acordamos estas
normas:


## 🛠 Desarrollo y Código

- Lenguaje: Usamos Elixir. Aprovechad sus fortalezas: GenServer,
  Supervisors, Agents.

- Limpieza: El comando mix format es nuestro mejor amigo. Usadlo
  siempre antes de subir código.
  
- Documentación: No solo digáis qué hace la función, usad ExDoc y
  typespecs para que el código se autodocumente.

> [!TIP] Las acciones de tipo _precommit_ y de integración continua
> pueden automatiza el uso de mix format.

> [!TIP] El formato se describe en docuementos como este: [The Elixir
> Style
> Guide](https://github.com/christopheradams/elixir_style_guide).

  
## 🌿 Control de Versiones (Git)

- Commits: Pequeños y frecuentes. Usad el formato: emoji + tipo:
  descripción (Ej: 🚀 feat: añadir sistema de mensajería).

- Ramas: No trabajéis todos sobre main. Usad ramas y luego
  integradlas.

- Higiene: No incluir en el repositorio ficheros de configuración de
  ningún IDE particular y evitar los commits desde la interfaz web de
  github siempre que sea posible.

> [!TIP] Los siguientes documentos os ayudarán a establecer unas
> normas comunes:
>
> [Conventional Commits](https://www.conventionalcommits.org/en/v1.0.0/)
>
> [How to Write Better Git Commit Messages](https://www.freecodecamp.org/news/how-to-write-better-git-commit-messages/)
> 
> 
> [gitmoji](https://gitmoji.dev/)

> [!TIP] Este documento compara las estrategias más habituales para el
> uso de ramas: [What Are the Best Git Branching
> Strategies](https://www.abtasty.com/blog/git-branching-strategies/)


## 📐 Arquitectura

- Modelo C4: Documentad los 4 niveles (Contexto, Contenedores,
  Componentes y Código).

- Decisiones (ADR): Si decidís cambiar el diseño, escribid un pequeño
  documento explicando el motivo.

  [Architectural Decision Records](https://adr.github.io/).

- Documentación complementaria: diagrama e instrucciones de despliegue.

- Higiene: dividid los diagramas muy complejos en partes.
  
  Además de las fuentes de los diagramas, añadir al repositorio su
  versión en formato _PDF_ o _PNG_.


## Calidad

- Pruebas: No hay código sin test. Usad `mix test`. Si hacéis pruebas
  manuales, documentad los pasos para que caulquiera pueda repetirlas.
	
> [!NOTE]
> Preferimos las pruebas automatizadas.
