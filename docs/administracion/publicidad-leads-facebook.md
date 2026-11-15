---
sidebar_position: 5
title: "Publicidad: leads de Facebook y su seguimiento"
description: Recibe en Eclipta los leads de tus anuncios de Facebook e Instagram, mira de qué anuncio vino cada uno y cuáles nadie ha atendido.
---

# Publicidad: leads de Facebook y su seguimiento

Cuando alguien llena el formulario de uno de tus anuncios de Facebook o Instagram, Eclipta lo recibe solo, lo guarda en tu base de datos y lo lleva a la campaña que elijas. Además te dice **de qué anuncio vino**, te avisa si **nadie lo ha atendido** y, si lo quieres, te muestra **cuánto te cuesta** cada lead.

Todo se configura en un solo sitio: la caja **Leads** de tu flujo de trabajo. La pantalla **Publicidad** solo sirve para mirar.

## Conectar tu página de Facebook

1. Entra a **Flujos de Trabajo** y abre tu flujo. Haz doble clic en la caja **Leads** (si no la tienes, arrástrala desde la lista de cajas).
2. Abre la pestaña **Meta** y pulsa **Activar Meta**.
3. Escribe el **ID de la página**, el **Token de acceso** y el **App Secret de la app de Meta**, y pulsa **Conectar la página**. Eclipta lo comprueba con Meta y suscribe la página a tus leads.
4. Solo la primera vez, en tu app de Meta (**Webhooks → Page → leadgen**) pega la **URL de devolución de llamada** y el **Token de verificación** que ves en la sección **En la app de Meta (una sola vez)**.
5. Si solo quieres algunos formularios, en **Qué formularios** escribe sus números separados por coma. Vacío significa todos.
6. Pulsa **Guardar cambios**.

Para llevar los leads a una campaña, saca una flecha desde la caja **Leads** hasta la caja de la campaña y publica el flujo.

:::tip Pruébalo sin gastar anuncios
En la pestaña **Probar** hay un lead de ejemplo de Meta con anuncio, campaña y plataforma. Pulsa **Probar** y verás qué se leería, a qué campaña iría y de qué anuncio saldría. No se guarda ni se envía nada. También puedes usar la herramienta de prueba de anuncios de clientes potenciales de Meta: el lead aparece en la pestaña **Registro**.
:::

## De qué anuncio viene cada lead

Eclipta guarda, para cada lead, la campaña, el conjunto de anuncios, el anuncio, el formulario, si vino de Facebook o de Instagram y la hora en que se llenó. En la pestaña **Meta**, sección **De qué anuncio viene cada lead**, eliges en qué campos de tu base se escribe el **origen** («Facebook» o «Instagram») y la **campaña / anuncio**, para que el agente lo vea al abrir la ficha. Si no eliges ninguno, Eclipta usa los campos que se llamen **Origen del lead** y **Anuncio o formulario de origen**. Si el formulario ya traía ese dato, no se cambia.

## Confirmar al interesado por WhatsApp

Para que cada lead reciba un mensaje apenas llega, saca una flecha desde la caja **Leads** hasta una caja **Plantilla de WhatsApp** y publica el flujo. Si la pestaña **Meta** no encuentra esa flecha, te lo avisa en la sección **Confirmación automática al interesado**.

## Avisos de leads sin atender

Un lead vale más mientras está fresco. En la pestaña **Alertas** eliges cuántos minutos puede esperar sin ninguna gestión (30 por defecto, o **No avisar**) y a quién se avisa: **Supervisores y administradores** o **Solo administradores**.

- El aviso sale en la **campanita** del panel, uno por caja, con cuántos leads esperan.
- Los minutos se cuentan solo mientras la campaña está abierta, según su horario: un lead que llega de noche se avisa cuando la campaña abre.
- Cuando alguien gestiona los leads, el aviso queda como **Resuelta**.

## La pantalla Publicidad

Entra por **Publicidad** en el menú. Elige las fechas y mira por **Campaña**, **Conjunto de anuncios** o **Anuncio** (toca una fila para bajar un nivel). Verás:

- **Leads recibidos**, **Sin atender**, **Contactados** y **Efectivos**.
- El **tiempo a la primera gestión**.
- **Del lead a la venta**: cuántos pasan de un paso al siguiente.
- La lista de **Leads sin atender**, los más viejos primero, marcando los que ya se avisaron.
- **Descargar Excel** con lo mismo que ves.
- **Configurar**, que abre directo la caja con sus ajustes.

Un lead cuenta como **Contactado** o **Efectivo** según la clasificación de la tipificación con la que lo cerró el agente (se cambia en la campaña).

## Cuánto cuesta cada lead

En la pestaña **Meta**, sección **Gasto de la publicidad**, escribe el **ID de la cuenta publicitaria** y el token de lectura de Meta y pulsa **Conectar la cuenta**. Eclipta trae lo gastado por anuncio cada día; también puedes pulsar **Sincronizar ahora**. Solo lee: no toca tus anuncios. Con la cuenta conectada, la pantalla **Publicidad** añade **Gasto**, **Costo por lead**, **Costo por contactado** y **Costo por efectivo**. Sin ella, cuenta los leads y no muestra costos. Si Meta rechaza el token, la caja te dice el motivo.
