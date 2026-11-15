---
sidebar_position: 4
title: Verificación en dos pasos
description: Proteger tu cuenta con un código de tu teléfono, entrar con él y qué hacer si pierdes el teléfono.
---

# Verificación en dos pasos

Con la verificación en dos pasos, además de tu contraseña Eclipta te pide un **código de 6 dígitos** que cambia cada 30 segundos y que muestra una aplicación de tu teléfono. Así, aunque alguien descubra tu contraseña, no puede entrar a tu cuenta sin tu teléfono.

Es **opcional**: cada persona decide si la activa. Si no la activas, entras como siempre, solo con tu contraseña.

Necesitas una aplicación de verificación en tu teléfono, por ejemplo **Google Authenticator**, **Microsoft Authenticator** o **Authy**.

## Activarla

1. Abre tu menú de perfil y pulsa **Ver perfil**.
2. En **Verificación en dos pasos**, pulsa **Activar**.
3. En tu aplicación, agrega una cuenta nueva y **escanea el código QR** de la pantalla. Si no puedes escanearlo, escribe en la aplicación la clave que aparece debajo del código.
4. Escribe en **Código** los 6 dígitos que muestra la aplicación y pulsa **Confirmar y activar**.
5. Eclipta te muestra tus **códigos de recuperación**. Guárdalos con **Copiar** o **Descargar** y pulsa **Ya los guardé**.

:::warning
Los códigos de recuperación se muestran **una sola vez**. Guárdalos en un lugar seguro, distinto de tu teléfono (por ejemplo, impresos o en un administrador de contraseñas).
:::

La verificación solo queda activa cuando confirmas con un código. Si cierras la pantalla antes de ese paso, no pasa nada: tu cuenta sigue pidiendo solo la contraseña.

## Entrar con el código

1. Escribe tu usuario o correo y tu contraseña, y pulsa **Entrar**.
2. Eclipta te pide el **Código de verificación**. Escribe los 6 dígitos que muestra tu aplicación y pulsa **Verificar**.

Cada código sirve **una sola vez**. Si Eclipta dice que el código no es correcto o que ya se usó, espera a que la aplicación muestre el siguiente e inténtalo otra vez. Si tardas más de unos minutos, Eclipta te pide escribir de nuevo tu contraseña.

Si falla varias veces seguidas, tu cuenta se bloquea unos segundos antes de dejarte intentar de nuevo.

## Si perdiste tu teléfono

Usa uno de tus **códigos de recuperación**:

1. Escribe tu contraseña y pulsa **Entrar**.
2. En la pantalla del código, pulsa **Usar un código de recuperación**.
3. Escribe uno de tus códigos y pulsa **Verificar**.

Cada código de recuperación sirve **una sola vez**. Cuando entres, en **Ver perfil** puedes **Generar códigos nuevos** (los anteriores dejan de servir) o desactivar la verificación.

Si no tienes tampoco tus códigos de recuperación, pídele a un administrador de tu empresa que **quite la verificación en dos pasos** de tu usuario. Después entras solo con tu contraseña y puedes activarla de nuevo en tu teléfono nuevo.

## Generar códigos de recuperación nuevos

1. En **Ver perfil**, en **Verificación en dos pasos**, pulsa **Generar códigos nuevos**.
2. Escribe tu contraseña y un código (el de tu aplicación o uno de recuperación) y pulsa **Generar códigos nuevos**.
3. Guarda los códigos nuevos. Los anteriores ya no sirven.

## Desactivarla

1. En **Ver perfil**, en **Verificación en dos pasos**, pulsa **Desactivar**.
2. Escribe tu contraseña y un código (el de tu aplicación o uno de recuperación) y pulsa **Desactivar**.

Tu cuenta vuelve a pedir solo la contraseña.

{/* INTERNO, no se muestra al cliente. Hoy la activación vive en Ver perfil del panel (administradores y supervisores). Los agentes no tienen esa pantalla: la verificación en dos pasos para agentes llega cuando su espacio tenga perfil. */}
