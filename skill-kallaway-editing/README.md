# Skill de edición · Kallaway

Edita reels en el estilo de Kallaway: pantalla dividida (prueba arriba, cara abajo), subtítulo pequeño en el centro, franja del gancho,
cortes secos en la palabra y palabra gigante con la cara completa. Entrenada con los 20 videos de este repositorio (830 escenas medidas).

## Instalar
1. Descarga `kallaway-editing.zip` (botón **Download raw file**).
2. **Claude (claude.ai o app):** Ajustes → Capacidades → Skills → *Subir skill* → elige el zip.
   **Claude Code:** descomprime en `~/.claude/skills/kallaway-editing/`.
   **ChatGPT / Gemini:** sube el zip al chat (o a un Proyecto/Gem) y escribe: «Lee EMPIEZA_AQUI.md y sigue SKILL.md».
3. Sube tu clip y escribe: «Edita este video con la skill kallaway-editing».

## Qué trae
- `SKILL.md`, `REGLAS_GENERALES.md`, `docs/` (RULEBOOK, EDIT_LOGIC, FORMATOS, Katana, Edit Studio)
- `library/` — 399 ejemplos reales con hoja de fotogramas y ficha (qué, diseño, animación, por qué)
- `references/` — desglose toma por toma, lógica y energía de cada video
- `system/` — el motor: transcripción, corte, subtítulos, render (Remotion), sonido, panel A/B/C, capturas web (`evidence.py`)
- `plugins/edit-studio/` — plugin de edición de Higgsfield

## Ejemplo (`ejemplo/`)
Borrador del clip de prueba, su plan (`beats.json`, `edit_plan.json`) y los prompts del material que faltaba (`ASSETS_kal-prueba.md`).
