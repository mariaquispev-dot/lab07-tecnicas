# Tarea: Mi prompt avanzado 
## Tarea elegida

Diseñar y estructurar las clases para un sistema de gestion escolar.

## Version 1: prompt basico
Crea las clases necesarias para un ssitema de notas.

​Tecnica agregada: Ninguna.
​Por que: Sirve como punto de partida para evaluar que tan generica o incompleta es la respuesta de la IA sin directrices.
​Que mejoro en la respuesta: Establece una linea base, aunque genera resultados muy vagos y poco estructurados.

## Version 2
Actúa como un arquitecto de software experto en Java. Diseña las clases necesarias para un sistema de notas dividiendo la tarea en pasos: 
1. Indica los atributos y tipos de dato.
2. Escribe el código Java con constructor y métodos get/set.

Tecnica agregada: Role prompting (Rol de experto) y Descomposición (Dividir en pasos).  
​Por que: Ayuda a que la IA no entregue todo en un bloque masivo y desorganizado, enfocándose en la estructura paso a paso.
​Que mejoro en la respuesta: Organizo claramente los atributos por clases y separó la logica del codigo de los requerimientos.

## Version 3: prompt final

Actúa como un desarrollador Java Senior experto en buenas prácticas y arquitectura limpia. Diseña e implementa la clase Producto de un sistema de gestión escolar aplicando las siguientes técnicas:
- Rol específico: Desarrollador Java Senior.
- Few-shot / Contexto: Sigue un formato estructurado con atributos, constructor, métodos get/set y validaciones.
- Chain of Thought: Razona paso a paso las mejoras concretas que se le pueden aplicar al código (como validaciones y encapsulamiento).
Formato de respuesta deseado:
1. Listado de atributos con sus tipos de datos.
2. Bloque de código Java limpio y comentado.
3. Tabla de evaluación de calidad del código.

Tecnica agregada: Chain of Thought (Razonamiento paso a paso), Few-shot / Prompt estructurado y Autocrítica/Mejoras.  
​Por que: Combina multiples tecnicas para asegurar que el resultado sea robusto, profesional y directamente aplicable a nivel tecnico.
​Qué mejoró en la respuesta: Genero un codigo profesional con manejo de tipos correctos, estructuración limpia y sugerencias de mejora tecnica avanzadas.

## Tecnicas usadas en el prompt final
| PARTE DEL PROMT FINAL | TECNICA APLICADA | 
|------------|--------------------|
| "Actua como un desarrollador.." | Rol especifico | 
| "diseñando e implementando.." | Promt estructurado| 
| "razona paso a paso.." | Chain of  thought| 
| "Formato de respuestas.."|Desconposicion y formato definido| 

 ## Evaluacion del resultado

| CRITERIO DE EVALUACION |CUMPLE (SI/NO)| 
|------------|--------------------|
| ¿Incluye atributos con tipos de datos definidos?| Si | 
| ¿Contiene codigo java ejecutable y estructurado? | Si| 
| ¿Aplica al menos tres tecnicas de prompting evanzadas?| Si| 
| ¿Propone mejoras concretas o validaciones de codigo?|Si| 

## Por que elegi estas tecnicas

Elegi estas tecnicas porque permiten transformar una consigna ambigua en un requerimiento de software.Al asignar un rol de experto, la IA toma criterios de calidad de un profesional, lo cual ayuda a resolver mejor lo que le pedimos.