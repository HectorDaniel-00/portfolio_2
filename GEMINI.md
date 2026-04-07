# Mi Portafolio - Instrucciones para Claude Code

## Contexto del proyecto

- Portfolio personal con Angular standalone v21 y Tailwind.
- Es informacion sobre mi, para que las empresas o los reclutadores puedan ver mi informacion y todo lo que hago,

## Skills activas

@.claude/skills/contenido/SKILL.md
@.claude/skills/estilos/SKILL.md
@.claude/skills/buenas-practicas/SKILL.md

## Reglas generales

- Responde siempre en español
- No generes código comentado innecesario
- Antes de crear un componente nuevo, revisa si ya existe uno similar en src/app/shared/components/
- Usa el archivo src/app/data/portfolio.data.ts para todo el contenido estático

## Estructura del proyecto

src/
app/
core/ → servicios globales, guards
shared/ → componentes reutilizables, modelos reutilizables
features/ → secciones del portafolio (hero, about, projects...)
data/ → contenido estático en TypeScript

## Mision

- Hacer solo UI bonita, responsiva, profesional y con buena vista al ojo del usuario.
- Animaciones basicas con TailwindCSS.
- No hacer logica compleja o logica de negocio.

## Comandos útiles

- `ng serve` → desarrollo local
- `ng generate component` → crear componente
