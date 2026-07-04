# Protocolo de verificación de ayudas

Este protocolo existe para que cualquier persona — un vecino, un periodista, un fiscal, un escéptico — pueda comprobar que cada ayuda registrada ocurrió de verdad, **sin que ninguna persona vulnerable pague el costo de esa comprobación.**

Dos reglas madre:

1. **La carga de la prueba es nuestra, nunca de quien recibe ayuda.** Verificar es trabajo de quien ayuda y de quien registra. A la persona que recibió no se le pide papel, foto ni testimonio.
2. **Si no se puede verificar, no se registra.** Preferimos un registro corto y verdadero a uno largo e inflado. Un número exagerado destruye en un día la credibilidad que cuesta años construir.

---

## Evidencia mínima según el tamaño de la ayuda

| Tamaño | Registro básico | Verificadores | Evidencia adicional |
|---|---|---|---|
| Pequeña (1-10 personas) | fecha, lugar, qué se dio | 1, además de quien entregó | — |
| Mediana (11-99) | fecha, lugar, qué se dio | 2 | 1+ foto sin rostros de quien recibe |
| Masiva (100+) | fecha, lugar, qué se dio | 2, al menos 1 externo a la célula | fotos del evento sin rostros identificables + método de conteo declarado (raciones preparadas, porciones servidas, etc.) + origen de recursos detallado |

## Quién puede verificar

- Una persona con nombre completo y forma de contacto, que estuvo presente en la entrega.
- **Nadie se verifica solo:** quien entregó la ayuda no puede ser su propio verificador.
- En ayudas masivas, al menos un verificador externo a la célula: un donante, un líder comunitario, un pastor local.
- El verificador consiente dos cosas: que su nombre sea público y que cualquiera pueda contactarlo para preguntar. Se le explica esto antes, con cariño y claridad — es un servicio, no un trámite.

## La cadena de registro

- Cada ayuda entra a este repositorio **por commit dentro de las 72 horas** siguientes a la entrega.
- El historial de Git es la cadena de custodia: cada cambio queda firmado con fecha y autor, y nada se puede alterar sin dejar huella pública.
- Las correcciones se hacen con un commit nuevo que explica el error. **Jamás se reescribe la historia.**
- Cada ayuda tiene su expediente (fotos, verificadores, notas de conteo) en una carpeta `registro/evidencia/ayuda-NNN/`.

## Línea roja: privacidad de quien recibe

- **Nunca se publica:** nombre, rostro, dirección de casa ni historia personal de quien recibe ayuda.
- La ubicación se registra a nivel de caserío, aldea o zona — nunca la casa de nadie.
- En las fotos puede verse la comida, la fila de espaldas, los verificadores (si consienten). Rostros de quien recibe, no.
- Si una persona quiere contar su propia historia públicamente, es su derecho: con consentimiento escrito y al menos 30 días después de recibida la ayuda, para que nunca sienta que la ayuda estaba condicionada a contar.

## Cuando alguien viene a escudriñar

Si un periodista, un fiscal o un escéptico pregunta, esto es lo que se hace — y se hace con gusto, porque para esto existe el registro:

1. Se le comparte el enlace al registro público completo, sin pedirle nada a cambio.
2. Se le facilita el contacto de los verificadores que consintieron.
3. **No se le da acceso a identidades de quienes recibieron ayuda**, y se le explica por qué: la transparencia aplica al dinero y al poder, nunca al vulnerable (innegociable #4).
4. Si encuentra un error real, se le agradece, se corrige con commit público y se registra como incidente (métrica de fruto #4). Un error corregido a la vista de todos vale más que diez ayudas: es la prueba de que el sistema funciona.

## Origen de los recursos

- **Dinero:** entra primero al [registro de finanzas](finanzas.md) el mismo día, con doble firma. La ayuda referencia ese movimiento. Ayuda registrada sin movimiento correspondiente = incidente de opacidad.
- **Especie:** se registra qué se donó, quién lo donó (con su consentimiento) y a qué ayuda se destinó.
- **Se rechaza** toda donación que exija secreto, protagonismo del donante frente a quienes reciben, o condiciones político-partidistas.

## Aplicación retroactiva: ayuda #001

La ayuda #001 (~1,000 platos servidos, Fraijanes, 4-abr-2026) se registró antes de que existiera este protocolo. Estado del expediente al 4 de julio de 2026:

- [x] Método de conteo: ~1,000 platos, **estimación en sitio** de Delia Genoveva Civas Flores la mañana del evento (sin conteo formal; así se declara)
- [x] Origen de los recursos: pizza pagada de su bolsillo por el fundador, directo al proveedor — corregido públicamente el 4-jul-2026 (antes decía "donante con reserva"; la reserva no aplica al fundador)
- [x] Evidencia documental: [transcripción del chat de coordinación](evidencia/ayuda-001/chat-2026-04-04.md), con consentimiento de ambos participantes
- [x] Primera verificadora: Delia Genoveva Civas Flores, presente en la entrega (no puede contar dos veces: registró Y verifica una sola vez)
- [ ] Segundo verificador **externo a la célula** (alguien de la escuela, un repartidor, un líder comunitario presente) — Esteban no puede verificar su propia entrega
- [ ] Recibo o monto de la compra de pizza, para completar el valor en finanzas.md
- [ ] Fotos de la jornada sin rostros identificables de quienes recibieron — **no se han encontrado**

**Fecha límite: 18 de julio de 2026.** Si no se completa, la ayuda se re-etiqueta como "registro histórico — verificación incompleta". Decir la verdad sobre nuestro propio registro, incluso cuando duele, es el testimonio.
