# Nombre del proyecto

## Descripción de la aplicación

Breve descripción del sistema desarrollado, así como los requisitos
funcionales y no funcionales del mismo, y cualquier otra información
que contribuya a una mejor comprensión del mismo.

## Requisitos funcionales

## Requisitos no funcionales

## Propuesta de arquitectura

Diseño de la arquitectura propuesta siguiendo el modelo C4, niveles 1
y 2.

```mermaid
C4Context
  title Diagrama de contexto de Nombre de la aplicación
  
  Enterprise_Boundary(b0, "AppBoundary") {
    Person(user, "User", "Una usuaria del sistema")
	
	System(system, "Nombre de la aplicación", "Permite a las usuarias hacer los casos de uso")
	
	Rel(user, system, "Usa")
}
``` 

```mermaid
C4Container
  title Diagrama de contenedores de Nombre de la aplicación
  
  Person(user, "User", "Una usuaria del sistema")
  
  Container_Boundary(c1, "Aplicación") {
    Container(container, "Contenedor", "Contender de la aplicación")
  }
  
  Rel(user, container, "Usa", "BEAM Messages")
```

