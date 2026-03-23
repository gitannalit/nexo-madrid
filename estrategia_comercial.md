# Estrategia Comercial — Nexo Dubái · Madrid
## Documento de Comprensión del Proyecto y Plan de Marketing y Ventas

---

## 1. COMPRENSIÓN DEL PROYECTO

### El Evento
**Nexo Dubái - Madrid** es un evento presencial de 2 días (sábado 26 y domingo 27 de abril de 2026) que se celebra en un venue exclusivo en Madrid. El evento está dirigido a empresarios y emprendedores españoles que quieren resolver tres problemas concretos:

1. **Optimización fiscal**: Aprender a reducir su carga impositiva entre un 40% y un 50% de forma legal, mediante estructuras empresariales internacionales.
2. **Inversión en Dubái**: Conocer el mercado inmobiliario de Dubái de primera mano, con rentabilidades del 8-20% anual, y entender cómo invertir desde España.
3. **Networking de alto nivel**: Conectar con más de 200 empresarios en un entorno exclusivo, generando sinergias y oportunidades de negocio reales.

### El Precio
- **Precio online (landing page)**: 197€
- **Precio general en sala**: 297€ (tachado en la landing para generar urgencia)
- **Pasarela de pago**: Stripe — `https://buy.stripe.com/9B63cw84D5HQ4BQ4UdfIs02`

### La Comunidad Existente
El proyecto tiene una comunidad previa: el evento de Dubái (28 de febrero al 2 de marzo de 2026) ya se celebró con éxito, generando vínculos fuertes entre los participantes. Esta comunidad es un activo de social proof muy potente para la venta del evento de Madrid.

### La Landing Page
La landing page está construida con identidad visual negro profundo + dorado (idéntica a evento-nexodubai.com), tipografía Geist, y contiene:
- Ticker animado con mensajes clave
- Hero asimétrico con carrusel de 4 imágenes
- Cuenta atrás en tiempo real hasta el 26 de abril
- Sección de beneficios con tabs (Lo que conseguirás / Qué incluye)
- Testimonios escritos + vídeo de la comunidad Nexo
- Métricas de impacto (40-50% ahorro, 8-20% ROI, +200 empresarios)
- Agenda de 2 días (Sábado y Domingo)
- Proceso de admisión simplificado (3 pasos)
- Sección "¿Este evento es para ti?"
- FAQ con 8 preguntas
- Formulario de contacto (nombre, email, teléfono)
- Todos los CTAs apuntan directamente a Stripe
- Google Tag Manager (GTM-K77K3V7D) instalado

---

## 2. ESTRATEGIA DE MARKETING Y VENTAS

### Dos Canales Principales

| Canal | Objetivo | Inversión recomendada | Destino del tráfico |
|---|---|---|---|
| **Canal A — Webinar** | Captar leads cualificados, educar y convertir en caliente | 70% del presupuesto | Formulario de Meta → Grupo WhatsApp → Webinar → Venta |
| **Canal B — Compra directa** | Captar compradores impulsivos o ya convencidos | 30% del presupuesto | Landing page → Stripe (compra inmediata) |

La lógica del 70/30 es sólida: el webinar permite educar al prospecto, generar confianza y cerrar en caliente a personas que necesitan más información antes de comprar. El canal directo captura a quienes ya tienen la intención de compra clara.

---

### CANAL A — Flujo Webinar (70%)

**Paso 1 — Anuncio en Meta (Facebook/Instagram)**
El anuncio lleva a un **formulario nativo de Meta Leads** (no a una web externa), lo que maximiza la tasa de conversión porque el usuario no abandona la plataforma.

**Paso 2 — Formulario de Meta Leads**
Campos recomendados (mínimos para no generar fricción):
- Nombre completo
- Email
- Teléfono (WhatsApp)
- Pregunta de cualificación: *"¿Cuánto pagas aproximadamente en impuestos al año?"* (opciones: Menos de 10.000€ / 10.000-30.000€ / 30.000-60.000€ / Más de 60.000€)

**Paso 3 — Automatización post-formulario**
Inmediatamente después de completar el formulario:
- Email automático de bienvenida con el enlace al grupo de WhatsApp
- Mensaje de WhatsApp automático (si se usa herramienta como ManyChat o similar) con el mismo enlace

**Paso 4 — Grupo de WhatsApp**
El grupo de WhatsApp actúa como sala de espera del webinar. Durante los días previos se publican:
- Contenido de valor (datos fiscales, casos de éxito)
- Recordatorios del webinar
- Testimonios del evento de Dubái

**Paso 5 — Webinar en directo**
Duración recomendada: 60-90 minutos. Estructura:
1. Presentación del problema (impuestos en España)
2. La solución (estructuras internacionales + Dubái)
3. Casos de éxito reales de la comunidad Nexo
4. Presentación del evento de Madrid (26-27 abril)
5. Oferta especial para asistentes al webinar
6. Cierre con urgencia (plazas limitadas, precio especial)

**Paso 6 — Seguimiento post-webinar**
- Email de replay + oferta con límite de tiempo (24-48h)
- Mensajes de seguimiento en WhatsApp

---

### CANAL B — Flujo Compra Directa (30%)

**Paso 1 — Anuncio en Meta**
Anuncio directo a la landing page `nexomadrid-lx9svcg6.manus.space`

**Paso 2 — Landing Page**
El usuario llega a la landing, lee el contenido y hace clic en cualquier CTA → Stripe

**Paso 3 — Pago en Stripe**
El usuario completa el pago de 197€ directamente

**Paso 4 — Confirmación**
Email automático de Stripe con la confirmación de compra y los detalles del evento

---

## 3. SEGMENTACIÓN DE AUDIENCIA PARA META ADS

### Audiencia Principal
- **Edad**: 30-55 años
- **Género**: Principalmente masculino (aunque no exclusivo)
- **Ubicación**: España (especialmente Madrid, Barcelona, Valencia, Sevilla, Bilbao)
- **Intereses**: Emprendimiento, inversión inmobiliaria, fiscalidad, Dubai, negocios internacionales, libertad financiera
- **Comportamiento**: Propietarios de negocios, tomadores de decisiones, viajeros frecuentes

### Audiencias Personalizadas (Retargeting)
- Visitantes de la landing page (pixel de Meta)
- Leads del formulario que no compraron
- Audiencia similar (Lookalike) a los compradores existentes

---

## 4. KPIs Y MÉTRICAS OBJETIVO

| Métrica | Canal Webinar | Canal Directo |
|---|---|---|
| CPL (Coste por lead) | 3-8€ | — |
| Tasa de conversión formulario → asistente webinar | 30-50% | — |
| Tasa de conversión webinar → venta | 5-15% | — |
| CTR del anuncio | 1-3% | 0.5-2% |
| Tasa de conversión landing → compra | — | 1-3% |
| CPA (Coste por adquisición) | 30-80€ | 50-120€ |

---

## 5. PRESUPUESTO RECOMENDADO (PRUEBA INICIAL)

Para validar ambos canales antes de escalar:

| Concepto | Importe |
|---|---|
| Meta Ads Canal A (Webinar) | 700€ |
| Meta Ads Canal B (Directo) | 300€ |
| **Total prueba inicial** | **1.000€** |

Con un CPA medio de 50-80€ y un ticket de 197€, el ROAS mínimo para ser rentable es de **1.5x** — muy alcanzable con una audiencia bien segmentada y el social proof existente de la comunidad Nexo.

---

*Documento elaborado por Manus AI — Marzo 2026*
