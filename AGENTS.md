# AGENTS.md

Este archivo define instrucciones permanentes para trabajar sobre este repositorio cuando el usuario entregue un pedido funcional en un archivo Markdown generado por Claude.

## Flujo obligatorio de trabajo

Cada vez que el usuario entregue un pedido funcional `.md`, seguir este proceso en este orden:

1. Leer completo el pedido funcional `.md`.
2. Revisar la estructura actual del repo.
3. Identificar el objetivo funcional.
4. Identificar pantallas, componentes, rutas, estilos, datos y archivos afectados.
5. Detectar riesgos técnicos, riesgos de UI/UX y riesgos de despliegue.
6. Revisar impacto en Firebase, build, rutas, autenticación, variables de entorno o dependencias.
7. Proponer un plan técnico antes de programar.
8. Hacer máximo 3 preguntas solo si son realmente bloqueantes.
9. Esperar la aprobación del usuario antes de ejecutar.
10. Implementar en pasos pequeños.
11. No romper funcionalidades existentes.
12. No instalar dependencias nuevas salvo que sean estrictamente necesarias.
13. Ejecutar validaciones disponibles antes de cerrar:
   - `npm run lint` si existe
   - `npm run build` si existe
   - `npm test` si existe
14. Corregir errores encontrados.
15. Entregar resumen final.

## Criterios permanentes

- Priorizar simplicidad.
- Mantener código limpio y mantenible.
- Mantener consistencia visual.
- Usar diseño moderno tipo SaaS.
- Hacer interfaces visuales, claras y profesionales.
- Cuidar responsive desktop y móvil.
- Mantener compatibilidad con Firebase.
- No exponer secretos, claves ni credenciales.
- No sobreingenierizar.

## Restricciones

- No modificar pantallas, componentes, lógica, configuración ni funcionalidad existente antes de presentar el análisis y el plan técnico.
- No ejecutar implementación hasta contar con aprobación explícita del usuario.
- Si existen dudas no bloqueantes, asumir la alternativa más simple y consistente con el proyecto actual.

## Formato obligatorio de cierre

```md
## Resumen

## Archivos modificados

## Pruebas ejecutadas

## Decisiones tomadas

## Pendientes o riesgos

## Próximo paso recomendado
```
