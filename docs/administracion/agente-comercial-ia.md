---
sidebar_position: 6
title: "Agentes IA de Eclipta: Agente comercial"
description: Un asistente virtual de IA que escribe por WhatsApp a cada lead de tus anuncios, averigua qué necesita y lo pasa a tu equipo listo para una demo.
---

# Agentes IA de Eclipta: Agente comercial

**Agentes IA de Eclipta** es la familia de asistentes de inteligencia artificial de la plataforma; cada uno lleva el nombre de lo que hace. El **Agente comercial** atiende a las personas que dejan sus datos en un anuncio: les escribe por WhatsApp apenas llegan, conversa con ellas, les hace seguimiento si no contestan y, cuando están listas, se las pasa a tu equipo con un resumen para que agende la demo y cierre.

Se presenta siempre como **asistente virtual de IA de tu empresa**, nunca con nombre de persona, y **nunca da precios ni mínimos de usuarios**: eso se habla en la demo.

## Antes de encenderlo

Necesitas:

1. El servicio **Chatbot con IA** contratado y su permiso encendido (**Configuración → IA**). Si no lo tienes, pídelo a Axiona 360.
2. Una **base de conocimiento** con lo que el agente puede afirmar de tu empresa (**Configuración → IA**). Es lo único que dice; lo que no esté ahí lo deja para el especialista.
3. Una **plantilla de WhatsApp aprobada por Meta** para abrir la conversación. En la plantilla, `{{1}}` es el primer nombre del lead y `{{2}}` lo que le interesa. Para el seguimiento, hasta tres plantillas más.
4. Una **campaña** que reciba al lead listo (la del equipo que cierra las ventas).
5. Una fuente de leads de anuncios en tu caja **Leads** (Meta, Google Ads, TikTok, LinkedIn o webhook).

## Configurarlo

1. Abre tu flujo de trabajo y entra a la caja **Leads**.
2. Ve a la pestaña **Agente IA**. Arriba verás **Agentes IA de Eclipta · Agente comercial** y un semáforo **Para que funcione** que te dice qué te falta.
3. Escribe **Cómo habla**: las instrucciones (quién es tu cliente ideal, qué hay que averiguar, qué no se debe prometer), el tono, la base de conocimiento, cuántas respuestas da antes de pasarlo a una persona y el largo de cada respuesta.
4. En **Mensajes con plantilla** elige la plantilla de apertura y los seguimientos (por ejemplo a 1, 3 y 7 días).
5. En **Cuando el lead está listo** elige la campaña que lo recibe y los correos a los que llega el resumen (separados por coma).
6. En **Horario de los seguimientos** deja los días y horas en que pueden salir. Por defecto: lunes a viernes de 8:00 a 17:00 y sábados de 9:00 a 14:00. Nunca salen en festivos.
7. Prueba el agente en **Probar el agente**: escribe como si fueras el lead. No le escribe a nadie ni guarda nada.
8. Pulsa **Guardar y comprobar** y revisa que el semáforo quede en verde.
9. Enciende el interruptor **Encendido** y pulsa **Guardar cambios**.

El agente viene **apagado**. Mientras lo está, tus leads siguen su camino de siempre.

## Cómo trabaja con cada lead

- **Al llegar el lead**, recibe la plantilla de apertura en menos de un minuto, a cualquier hora.
- **Si contesta**, el asistente conversa con él: responde lo que pregunta con tu base de conocimiento y averigua, de a una pregunta, qué necesita, cuántas personas atienden hoy, por qué canales y qué usan ahora.
- **Si no contesta**, salen los seguimientos que configuraste, solo en horario. Si no hay respuesta a ninguno, el lead queda como **Sin respuesta**.
- **Si pide una demo o cotización**, pide hablar con una persona, ya dio lo básico, o el agente llega a su límite de respuestas, se lo **pasa a tu equipo**.
- **Si deja de contestar** en plena conversación, a las 20 horas se pasa a tu equipo con lo que alcanzó a decir.
- **Si escribe «no me escriban más»** (o «baja», «stop»), el agente se despide, lo marca como **no molestar** y no vuelve a escribirle nunca.

## Cuando el lead está listo

Tu equipo recibe, a la vez:

- Una notificación en la **campanita** del panel con el nombre, la empresa, el teléfono, lo que necesita y el resumen.
- Un **correo** con el mismo resumen, si configuraste correos de aviso.
- La **conversación completa** en la cola de la campaña elegida, si hay alguien conectado; si no hay nadie, queda guardada y el resumen te dice a quién contactar.

La persona que atiende ve todo lo que se dijeron y sigue desde ahí, en horario de atención.

## Ver cómo le va

En **Publicidad**, al final de la pantalla, el bloque **Agente comercial IA** muestra, para el periodo que elijas: leads atendidos, los que contestaron, los calificados (tres o más respuestas), los que piden demo, los pasados a una persona, las bajas, los que no respondieron y cuánto tarda en escribirles. Todo por anuncio y por día.

Debajo están sus **conversaciones**. Pulsa **Ver** para leer una. Si quieres seguirla tú, pulsa **Tomar la conversación**: el agente se retira y el chat pasa a la cola de la campaña.

Las demos hechas y las ventas son gestiones de tu equipo: las ves arriba, en **Efectivos**.

## Qué tener en cuenta

- WhatsApp solo deja escribir primero con **plantillas aprobadas por Meta**. Si una plantilla deja de estar aprobada, el semáforo lo avisa y esa plantilla no sale.
- Un lead con celular fijo o sin teléfono no recibe mensajes del agente: sigue el camino de siempre.
- A quien ya se le escribió en los últimos 30 días no se le abre otra conversación.
- Si el servicio de IA no está disponible, el lead no se pierde: sigue por tu campaña o pasa a tu equipo.
