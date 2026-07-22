# Brief de prototipo — Marketplace de ebooks (Fase 1: Asistente de lectura IA)

> Disclaimer: el perfil de cliente detrás de este mapa proviene de un ejercicio de curso
> ("Clase 3"). Si los datos de research son simulados, este brief entrena el método,
> no decide un roadmap real.

## 1. Producto y segmento
Marketplace/suscripción de ebooks para lectores hispanohablantes de LatAm. Este brief
cubre la **primera fase del roadmap**: el quick win, antes de encarar los big bets de
pricing y catálogo.

## 2. Perfil del cliente (resumen)

**Top 3 jobs**
- [Funcional] Comprar y empezar a leer al instante, para aprovechar tiempos muertos de trabajo.
- [Emocional] Desconectarse de pantallas de trabajo antes de dormir.
- [Funcional] Resaltar/exportar notas y buscar citas exactas para reuniones y presentaciones.

**Top 3 dolores**
- Recargo en dólares + impuestos de tarjeta internacional.
- Catálogo en español limitado / novedades demoradas / títulos no disponibles por país.
- No existe una suscripción tipo Spotify que funcione bien en la región.

**Top 3 beneficios**
- [Emocional] No sentir que pagar libro por libro es "un lujo".
- [Social] Ser referente de lecturas para el equipo/pareja — recomendar y regalar.
- Deseado: IA que resuma lo leído y ayude a retener + búsqueda de citas exactas en segundos.

## 3. Propuesta de valor — roadmap por fases

Priorización según la matriz de impacto/complejidad
([matriz-impacto-complejidad.svg](../matriz-impacto-complejidad.svg)) y la decisión de
secuencia dada por el equipo (quick win → incremental → big bets).

**Fase 1 — Quick win (a prototipar ahora)**
- Asistente de lectura IA: resume, busca citas exactas, exporta notas → crea el beneficio
  deseado "IA que resuma y ayude a retener" + "búsqueda de citas exactas en segundos" y
  atiende el job funcional de uso profesional.

**Fase 2 — Incremental**
- Sistema de regalo (gift link universal) + club de lectura social → crea "ser referente
  de lecturas" y alivia lo difícil/raro de regalar un ebook entre países.
- "Modo antes de dormir" (tema cálido + retoma automática) → crea el momento de
  desconexión de pantallas de trabajo.

**Fase 3 — Big bets (al final)**
- Precio en pesos vía PPA + plan compartido → alivia el recargo en dólares y "pagar es un lujo".
- Traducción IA día 1 + simultaneidad negociada con editoriales → alivia catálogo
  limitado/demorado y títulos no disponibles por país.

## 4. Flujo clave a prototipar
**Asistente de lectura IA**: desde que el usuario está leyendo hasta que resume, busca y
exporta. Es el flujo de esta fase por ser el quick win: bajo esfuerzo, impacto medio,
sin dependencias externas (a diferencia de los big bets de pricing/partnerships editoriales).

## 5. Pantallas sugeridas
1. **Biblioteca**: libro en lectura destacado, continuidad multi-dispositivo visible.
2. **Lector**: texto + botón "resumir este capítulo" y opción de resaltar.
3. **Resumen ejecutivo IA**: resumen generado del capítulo/libro leído hasta el momento.
4. **Buscador de citas**: búsqueda de frase exacta (texto o por voz) dentro del libro.
5. **Notas exportadas**: lista de resaltados/citas guardadas, exportar a PDF/doc para reuniones.

## 6. Qué queremos validar
- Creemos que los lectores con el job "buscar citas exactas para reuniones y
  presentaciones" van a usar el buscador semanalmente, porque ese uso profesional está
  declarado explícitamente en el perfil.
- Creemos que el resumen IA + exportación de notas aumenta la sensación de "retener lo
  leído" lo suficiente como para diferenciarnos de un lector de ebooks genérico.
- Creemos que este quick win por sí solo **no** va a mover el dolor dominante (pricing
  en dólares) — es intencional: valida la feature de IA antes de invertir en los big
  bets de Fase 3.

## Cierre anti-complacencia
- **Secuencia por decisión humana, no de la IA**: el orden quick win → incremental →
  big bets lo definió el equipo; la IA solo lo documentó.
- **Riesgo de la secuencia**: como el prototipo de esta fase no toca el dolor más
  cargado emocionalmente (precio en dólares/"lujo"), no usar estos resultados para
  concluir "product-market fit" general — solo valida la feature de IA.
