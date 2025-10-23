# Que es Conventional Commit?

**Conventional Commit** es una especificación para formatear mensajes de commit en Git de manera consitente y estandarizada. Establece un conjkunto de reglas simples para crear mensajes de commit comprensibles para humano y máquina.

### Tipos comunes
|  | |
|---|---|
| ```feat``` | Nueva funcionalidad |
| ```fix``` | Corrección de error |
| ```doc``` | Cambios solo en documentación |
| ```style``` | Formato, espacios, comas. Sin cambiar lógica |
| ```refactor``` | Reestructura del código sin cambiar comportamiento |
| ```test``` | Agregar o midificar test |
| ```chore``` | Cambios de mantenimiento |
| ```perf``` | Mejora de rendimiento |

### Por qué es importante?
- Da ***claridad y consitencia***, el equipo sabe de inmediato qué hace cada commit sin tener que leer el código.
- Permite ***generar automáticamente*** changelogs y versionado semántico.
- ***Historial limpio y navegable***, es mas fácil buscar commits relevantes, entender la evolución del proyecto y hacer revisiones.
- ***Integración con CI/CD***, algunos pipelines usan los tipos de commit para decidir acciones automáticas.
