# CLAUDE.md

## Proyecto
**Trackeador de Postulaciones** — Aplicación web para rastrear búsqueda de empleo diaria con meta de 20 CVs por día.

## Contexto
- Usuario está aplicando a trabajos y necesita llevar cuenta de postulaciones diarias
- Meta: 20 CVs por día
- Requiere: contador, listado, calendario visual, almacenamiento local
- Tech stack: HTML vanilla + CSS + JavaScript (sin dependencias externas)

## Convenciones

### Commits
- Usar conventional commits: `feat:`, `fix:`, `docs:`, `refactor:`, `test:`
- NO agregar "Co-Authored-By" ni atribuciones AI en commits
- Ejemplo: `feat: agregar filtro por mes en calendario`

### Código
- JavaScript vanilla, sin frameworks
- localStorage para persistencia de datos
- Responsive design (mobile-first)
- Soportar light/dark mode
- Español en UI, inglés en código/comentarios

### Cambios
- Mantener estructura simple: index.html + README.md
- No agregar dependencias externas a menos que sea absolutamente necesario
- Testear en navegador antes de considerar terminado
- Si hay cambios grandes, avisar antes de implementar

## Preferencias
- Respuestas cortas y al punto
- Código limpio, sin over-engineering
- Documentar solo si hay lógica no obvia
- Si hay dudas sobre scope, preguntar primero
- El usuario puede pedir cambios en cualquier momento

## Próximos pasos posibles
- Exportar datos a CSV
- Sincronizar entre dispositivos (backend simple)
- Notificaciones de meta diaria
- Estadísticas avanzadas (tasa de respuesta, etc)
