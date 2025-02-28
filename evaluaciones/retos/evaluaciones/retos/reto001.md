# Reto 001 - Legibilidad
Teniendo en cuenta los códigos generados en asignaturas de programación anteriores además de proyectos personales se deben identificar los errores que se cometían y exponerlos para saber cómo han evolucionado tus habilidades. El objetivo es analizar los errores más comunes, como malas prácticas, falta de optimización, problemas de seguridad o dificultades en la mantenibilidad del código.

## Nombrado

| *Principio* | *Código*|
|-|-|
| **Elige nombres descriptivos** | `String colado = Scanner.nextInt ("Elija un agujero: ");`|
| **Elige nombres al nivel de abstracción apropiado** |  |
| **Usa nomenclatura estándar donde sea posible** |  |
| **Nombres no ambiguos** |  |
| **Usa nombres largos para ámbitos largos** |  |
| **Evita codificaciones** |  |
| **Los nombres deberían describir los efectos laterales** |  |
| **Los nombres deben revelar su intención** |  |
| **La elección de buenos nombres lleva tiempo, pero ahorra más de lo que toma** |  |
| **Nombres pronunciables que permitan mantener una conversación** |  |
| **Mayúsculas en los caracteres inicio de palabra (CamelCase)** |  |
| **Nombres del dominio del problema y de la solución** |  |
| **Elige una palabra para un concepto abstracto y aferrarte a él** |  |
| **Nombres de paquetes deben ser sustantivos y comenzar en minúsculas** |  |
| **Nombres de clases deben ser sustantivos y comenzar en mayúsculas** |  |
| **Nombres de métodos deben ser verbos o una frase con verbo y comenzar en minúsculas** |  |
| **Nombres de métodos de acceso deben anteponer get(is para lógicos) y /set o put** |  |
| **Si un nombre requiere un comentario, el nombre no revela su intención** |  |
| **Nombres de una letra y muy en particular, 'O' y 'l' que se confunden con 0 y 1** |  |

## Comentarios

- Nada puede ser tan perjudicial como un enrevesado comentario desactualizado que propaga mentiras y desinformación 
    - [Comentario Malo I](https://github.com/oscarsantasanchez/prg1-22-23/blob/4196931d185cf2e8dd7905c184f07f0ae189244e/retos/entregas/oscarSantamaria/evaContinua/RetoDiecinueve.java#L3)
    - [Comentario Malo II](https://github.com/oscarsantasanchez/prg1-22-23/blob/4196931d185cf2e8dd7905c184f07f0ae189244e/retos/entregas/oscarSantamaria/evaContinua/RetoDiecisiete.java#L68)

- Nada puede estorbar más encima de un módulo que frívolos comentarios dogmáticos.
- Es simplemente una tontería tener una regla que dice que cada variable debe tener un comentario o que cada función debe tener un javadoc a a no ser que sea publicado como biblioteca
- No comentes código malo, re-escríbelo — Kernighan & Plaugher