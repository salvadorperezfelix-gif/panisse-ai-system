# SISTEMA COMPLETO — PANISSE ÓPTICA
## Versión 2.0 — Stack profesional omnicanal

---

## VISIÓN GENERAL

```
LEAD ENTRA (WhatsApp / Instagram DM / Facebook Messenger)
              ↓
     RESPOND.IO — hub central
              ↓
     CLARA responde automáticamente 24/7
     (Claude API conectado a Respond.io)
              ↓
     Clasifica perfil → gestiona objeciones → agenda cita
              ↓
     Lead registrado automáticamente en Airtable
              ↓
     Confirmación de cita → Google Calendar
     Recordatorio automático 24h antes
              ↓
     VIENE A LA ÓPTICA
              ↓
     MAKE.COM activa secuencia postventa automática
              ↓
     Fidelización → Reseña Google → Reactivación
```

---

## STACK TÉCNICO

| Herramienta | Función | Coste/mes |
|---|---|---|
| Respond.io | Hub central — WhatsApp API + Instagram + Facebook + CRM | ~79€ |
| Claude API | Motor de Clara — IA conversacional | ~15€ |
| Make.com | Automatizaciones avanzadas y secuencias | ~10€ |
| Airtable | CRM extendido y base de datos clientes | 0€ |
| Buffer | Programación de contenido en redes | ~15€ |
| Google Calendar | Gestión de citas | 0€ |
| Google Business | SEO local y reseñas | 0€ |
| Meta Ads | Captación de leads (Instagram + Facebook) | Presupuesto aparte |
| **TOTAL INFRAESTRUCTURA** | | **~119€/mes** |

---

## FLUJO DETALLADO

### 1. CAPTACIÓN DE LEADS

**Meta Ads (Instagram + Facebook):**
- Target: 42-65 años, Lugo y radio 30km
- Intereses: salud, bienestar, calidad de vida, óptica, visión
- Creatividades: vídeo corto de Félix en la óptica (natural, 30-45 segundos)
- CTA único: "Enviar mensaje" → WhatsApp o DM directo
- Presupuesto mínimo viable: 5-10€/día

**Google Ads (búsqueda local):**
- Keywords: "óptica Lugo", "progresivos Lugo", "revisión visual Lugo", "gafas progresivas Lugo"
- CTA: llamada directa o WhatsApp
- Presupuesto mínimo viable: 5€/día

**Google Business (orgánico):**
- Post semanal con contenido educativo
- Respuesta a todas las reseñas en menos de 24h
- Fotos actualizadas del equipo y la óptica
- Servicios bien detallados con palabras clave locales

**Instagram orgánico:**
- 3 posts semanales (educativo, proceso, diferenciación)
- Reels de biselado, montaje, ASMR, adaptación progresivos
- Stories con llamadas a la acción hacia DM

---

### 2. RESPOND.IO — HUB CENTRAL

**Canales conectados:**
- WhatsApp Business API
- Instagram Direct Messages
- Facebook Messenger

**Todo en una bandeja de entrada unificada.**

**Flujo automático:**
1. Lead entra por cualquier canal
2. Respond.io detecta el mensaje
3. Activa a Clara (Claude API)
4. Clara responde en segundos
5. Conversa, clasifica, gestiona objeciones
6. Si hay interés → agenda cita
7. Lead pasa a Airtable automáticamente con su perfil

**Flujo manual (cuando Clara escala):**
- Quejas graves → Félix contacta personalmente
- Preguntas clínicas complejas → equipo responde
- Respond.io notifica al equipo cuando hay que intervenir

---

### 3. CLARA — COMPORTAMIENTO AUTOMÁTICO

**Al primer mensaje:**
- Saluda, se presenta como Clara
- Detecta necesidad
- Hace preguntas de clasificación
- Nunca da precios sin contexto

**Clasificación automática:**
- Perfil A (Premium): énfasis en experiencia, Zeiss, monturas italianas
- Perfil B (Sensible precio): claridad, honestidad, financiación
- Perfil C (Miedo progresivos): calma, adaptación, garantía de seguimiento

**Cierre:**
- Ofrece cita de revisión gratuita
- Propone horario concreto
- Registra nombre y confirma

**Escalada:**
- Queja grave → recoge datos → informa a Félix
- Tras 2-3 negativas seguidas → cierra con elegancia
- Fuera de horario → mensaje de ausencia + responde en cuanto abre

---

### 4. CRM — AIRTABLE

**Pipeline de estados:**
```
Nuevo → Conversando → Cita agendada → Vino → 
Presupuesto → Compró → Perdido → Seguimiento
```

**Campos por lead:**
- Nombre completo
- Canal de entrada (WhatsApp / Instagram / Facebook / Google)
- Fecha primer contacto
- Necesidad detectada
- Perfil (A / B / C)
- Estado actual
- Teléfono
- Fecha de cita
- Ticket (si compró)
- Fecha último contacto
- Notas clínicas
- Fecha próximo seguimiento

**Make.com registra automáticamente cada lead nuevo desde Respond.io.**

---

### 5. GESTIÓN DE CITAS

- Clara ofrece hueco disponible en conversación
- Make.com crea el evento en Google Calendar automáticamente
- Respond.io envía confirmación automática al cliente
- Respond.io envía recordatorio 24h antes

---

### 6. SECUENCIAS POSTVENTA (Make.com)

| Momento | Canal | Mensaje |
|---|---|---|
| Día 3 | WhatsApp | Check adaptación gafas nuevas |
| Día 14 | WhatsApp | ¿Cómo vas? Revisión si hay molestias |
| Día 30 | WhatsApp | Solicitud reseña Google |
| Mes 11 | WhatsApp | Aviso caducidad garantía |
| Año 2 | WhatsApp | Recordatorio revisión visual |

**Recuperación de leads perdidos:**
- 48-72h sin respuesta → seguimiento elegante automático
- 30 días sin actividad → reactivación suave

---

### 7. MENSAJES PREDEFINIDOS

**Confirmación de cita:**
> "Hola [nombre], te confirmamos tu cita el [día] a las [hora] en Panisse Óptica. Estamos en Rúa do Teatro Baixo nº2, Lugo — tienes parking gratuito en el Parking Anxel Fole, en la misma calle. Hasta pronto."

**Recordatorio 24h:**
> "Hola [nombre], te recordamos tu cita mañana a las [hora]. Si necesitas cambiar algo, escríbenos sin problema."

**Check adaptación día 3:**
> "Hola [nombre], ¿qué tal vas con las gafas nuevas? Es normal que los primeros días notes algo diferente. Si tienes cualquier duda, aquí estamos."

**Día 14:**
> "Hola [nombre], ¿cómo llevas las gafas? Si todo va bien, perfecto. Si hay algo que no termina de encajar, pásate y lo revisamos sin problema."

**Solicitud reseña:**
> "Hola [nombre], esperamos que estés contento con tus gafas. Si te ha gustado la experiencia, nos ayudaría mucho que nos dejaras una reseña en Google — solo lleva un minuto. Gracias."

**Aviso garantía:**
> "Hola [nombre], tu garantía de un año está próxima a vencer. Si quieres que revisemos las gafas antes de que caduque, escríbenos y te buscamos un hueco."

**Reactivación 2 años:**
> "Hola [nombre], han pasado dos años desde tu última revisión visual. La vista cambia con el tiempo y merece la pena revisarla. La visita es gratuita — ¿cuándo te vendría bien?"

**Seguimiento lead perdido 48h:**
> "Hola [nombre], te escribo por si quedó algo en el aire. Si tienes alguna duda o quieres que te orientemos, aquí estamos sin compromiso."

---

### 8. CONTENIDO SEMANAL (Buffer)

**Estructura:**
- Lunes: Post educativo (salud visual, progresivos, pantallas, cataratas...)
- Miércoles: Proceso o artesanía (biselado, montaje, ASMR, detrás de cámaras)
- Viernes: Diferenciación, testimonio o equipo

**Google Business:**
- 1 post semanal con palabra clave local
- Respuesta a todas las reseñas en menos de 24h

**Pilares de contenido:**
1. Autoridad clínica
2. Artesanía óptica
3. Diferenciación frente a cadenas
4. Educación visual
5. Equipo y confianza

---

### 9. RESEÑAS GOOGLE

- Make.com envía solicitud automática a los 30 días de la compra
- Google Business notifica cada reseña nueva
- Respond.io o Clara genera respuesta personalizada
- Objetivo: llegar a 100 reseñas de 5 estrellas en 12 meses

---

## ORDEN DE IMPLEMENTACIÓN

### Semana 1
- [ ] Crear cuenta Respond.io
- [ ] Solicitar WhatsApp Business API (requiere verificación de empresa en Meta)
- [ ] Conectar Instagram y Facebook a Respond.io
- [ ] Integrar Claude API con prompt completo de Clara
- [ ] Testear flujo básico de conversación

### Semana 2
- [ ] Configurar pipeline en Airtable
- [ ] Conectar Make.com a Respond.io y Airtable
- [ ] Automatizar registro de leads
- [ ] Configurar confirmaciones y recordatorios de cita
- [ ] Integrar Google Calendar

### Semana 3
- [ ] Montar secuencias postventa en Make.com
- [ ] Configurar seguimiento de leads perdidos
- [ ] Testear flujo completo end-to-end
- [ ] Lanzar primeros anuncios con el sistema activo

### Mes 2
- [ ] Optimizar anuncios según datos reales
- [ ] Activar Buffer con calendario de contenido
- [ ] Ajustar Clara según conversaciones reales
- [ ] Activar solicitud automática de reseñas

### Mes 3
- [ ] Revisar KPIs y ajustar
- [ ] Escalar presupuesto de anuncios si el sistema convierte bien
- [ ] Explorar Google Ads si Meta funciona

---

## KPIs SEMANALES

| Métrica | Objetivo mes 1 | Objetivo mes 3 |
|---|---|---|
| Leads entrantes | 10/semana | 25/semana |
| Tasa conversación → cita | 30% | 40% |
| Tasa cita → compra | 50% | 60% |
| Ticket medio | 350€+ | 450€+ |
| Reseñas Google nuevas | 2/mes | 5/mes |
| Leads recuperados | 10% | 20% |

---

## RESUMEN DE COSTES

| Concepto | Coste mensual |
|---|---|
| Respond.io | ~79€ |
| Claude API | ~15€ |
| Make.com | ~10€ |
| Buffer | ~15€ |
| Airtable | 0€ |
| **Infraestructura total** | **~119€/mes** |
| Meta Ads (mínimo viable) | ~150-300€/mes |
| Google Ads (opcional mes 2) | ~100-200€/mes |

**Con un ticket medio de 350€, necesitas 1 cliente nuevo al mes para cubrir la infraestructura. Todo lo demás es rentabilidad pura.**
