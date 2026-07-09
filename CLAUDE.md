# Guía para Claude — Red de Células

Sitio estático + registros públicos en markdown de la **Red de Células**: comunidades pequeñas que resuelven necesidades reales con transparencia radical. Sin dueño, sin secretos. Todo bajo CC BY-SA 4.0.

**Sitio en vivo:** https://red-de-celulas.onrender.com — Render lo redespliega **automáticamente con cada push a `main`** (Blueprint, `render.yaml`). No hay build: HTML puro.

## Estructura

- `index.html` — página principal (un solo archivo, CSS inline, móvil primero, sin dependencias externas; mantener liviano para datos limitados)
- `diario.html` — Diario de Los Hechos, misma regla de diseño
- `CONSTITUCION.md` — Constitución de Los Hechos v1.0, **ratificada por la célula**: no editar su contenido sin acuerdo explícito de la célula (solo el fundador no basta)
- `registro/ayudas.md`, `registro/finanzas.md`, `registro/celulas.md` — registros públicos
- `registro/verificacion.md` — protocolo de verificación (leerlo antes de tocar cualquier registro)
- `registro/evidencia/ayuda-NNN/` — expediente por ayuda
- `diario/DIARIO-DE-LOS-HECHOS.md` — diario perpetuo; entradas nuevas SIEMPRE al final, numeradas en orden
- `diario/como-escribir.md` — guía y checklist de privacidad del facilitador

## Reglas duras (violarlas rompe la constitución del proyecto)

1. **Nunca reescribir la historia**: no borrar registros ni entradas del diario, no hacer force-push, no enmendar commits ya publicados. Los errores se corrigen con un commit nuevo o una "fe de errata" al pie.
2. **Privacidad del vulnerable**: jamás publicar nombre, rostro, dirección o detalles identificables de quien recibe ayuda. Ubicaciones solo a nivel de zona/caserío. En la duda, anonimizar más.
3. **Verificación antes que volumen**: toda ayuda registrada cumple `registro/verificacion.md` (verificadores con nombre y consentimiento, nadie se verifica solo, registro en 72h). Números sin sustento no se publican; las estimaciones se declaran como estimaciones.
4. **Dinero siempre a la vista**: cualquier mención de dinero se asienta en `registro/finanzas.md` el mismo día, con responsable y comprobante. Al fundador no se le aplica reserva de nombre.
5. **Anti-espectáculo**: nada de likes, contadores, testimonios destacados, fotos de impacto ni lenguaje de marketing. Tono sobrio y humilde, como se habla en la mesa de una casa guatemalteca (voseo).
6. **Consentimiento antes de publicar**: nombres de personas solo con su "sí" registrado. Los registros que esperan un dato lo dicen explícitamente ("pendiente"), nunca se inventa.

## Contexto operativo

- Fundador y facilitador actual: Esteban Recinos Leonardo (período hasta enero 2027, sin reelección consecutiva — ver `registro/celulas.md`).
- Commits en español, mensaje descriptivo. El historial de Git es la cadena de custodia pública del proyecto.
- Si existe `PROMPT-EQUIPO.md` en el directorio, es el prompt de trabajo del equipo fundador: seguí su formato de respuesta (rendición de cuentas → diagnóstico → entrega → prueba de calidez → supuestos → 3 pasos).
