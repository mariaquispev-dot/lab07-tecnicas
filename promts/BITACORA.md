# Bitacora de tecnicas avanzadas

Laboratorio 07: Tecnicas Avanzadas de Prompting. Herramienta de IA usada: (ChatGPT)

## EJERCICIO 2: ZERO-SHOT, ONE-SHOT Y FEW-SHOT

| Tipo | Aciertos (de 5) | Formato de la respuesta | Todas con el mismo formato (Si/No) |
|--------|-----|-----|--------|
| Zero-shot | 2|COMENTARIO |SI |
| One-shot | 2|COMENTARIO |SI |
| Few-shot | 2|COMENTARIO |SI |

## EJERCICIO 3: Chain of thought

| Pedido | Respuesta de la IA | Muestra los pasos (Si/No) | Correcta (Si/No) |
|-----|------|-------|-------|
| Directo | 90|NO |SI |
| Paso a paso |90 |SI |SI |

## EJERCICIO 4: Role prompting

| Version | Vocabulario (sencillo/tecnico) | Usa ejemplos o codigo | A quien le sirve mas |
|-----|-------|-----|----------|
| A. Sin rol | SENCILLO| NO| |
| B. Rol docente | TECNICO|SI | |
| C. Rol senior | TECNICO|SI | |

## EJERCICIO 5: Descomposicion
## EJERCICIO 6: Promt estructurado y autocritica

| Que revisar| Cumple (SI/NO)| 
|-----|-------|
|¿Tiene las 4 columnas pedidas?| SI|
|¿Incluye el bloqueo después de 3 intentos? | SI|
|¿Incluye casos con campos vacíos?| SI|
|¿Indica qué casos agregó en la autocrítica?| SI|
|¿Hay algún caso repetido o que no tenga sentido?| NO|

```text
(<rol>Actua como analista de pruebas de software.</rol>
<contexto>Login web con correo y contrasena. La cuenta se bloquea despues de 3 intentos fallidos.</contexto>
<tarea>Piensa paso a paso que puede fallar y escribe 6 casos de prueba.</tarea>
<formato>Tabla con las columnas: ID, escenario, datos de entrada, resultado esperado.</formato> )
```





