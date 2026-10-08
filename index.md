---
layout: default
title: Política de privacidad
---
# Política de privacidad — Asistente de WhatsApp en pruebas

**Última actualización:** 8 de octubre de 2026.

**Responsable:** Sergio González, Bogotá, Colombia.  
**Contacto:** sagonzal@outlook.com.

## Alcance y finalidad

Esta aplicación es un prototipo para probar la recepción de mensajes de WhatsApp, las respuestas automáticas y la intervención manual del responsable. Su uso está limitado a participantes autorizados para las pruebas.

Los datos se utilizan para ejecutar las pruebas, diagnosticar errores, mantener el contexto de las conversaciones y revisar la calidad de las respuestas.

## Datos tratados

La aplicación puede recibir y almacenar el número de teléfono del remitente, el texto de sus mensajes, los identificadores y fechas de los mensajes, las respuestas generadas y las notas del responsable sobre la conversación.

No se deben enviar contraseñas, datos de tarjetas, documentos de identidad ni información sensible. Se recomienda utilizar mensajes y datos ficticios.

## Procesamiento y servicios utilizados

Los mensajes se reciben mediante WhatsApp Business Platform de Meta y un túnel HTTPS de ngrok. Estos proveedores procesan información de acuerdo con sus propias condiciones y políticas.

El prototipo almacena el historial en una base de datos local del equipo utilizado por el responsable.

Cuando se activa el modo de inteligencia artificial, se envía a la API de OpenAI el texto y el contexto necesario de la conversación para generar respuestas. El programa no incluye el número telefónico en esa solicitud, aunque los mensajes escritos por el participante pueden contener información personal.

Cuando el modo de inteligencia artificial está desactivado, el programa no envía las conversaciones a OpenAI. Los proveedores pueden procesar información fuera de Colombia.

## Conservación y eliminación

El prototipo no tiene eliminación automática del historial. El responsable realizará su eliminación manual al finalizar las pruebas, salvo que exista una obligación legal de conservación.

Puede solicitarse la eliminación anticipada escribiendo al correo de contacto. La eliminación del historial local no elimina automáticamente las copias que puedan existir en WhatsApp o en los sistemas de los proveedores, sujetos a sus respectivas políticas.

## Derechos y contacto

Los participantes pueden solicitar información sobre sus datos, su actualización, rectificación o eliminación y, cuando corresponda, revocar la autorización para su tratamiento.

Para presentar una solicitud, escriba a **sagonzal@outlook.com** indicando el asunto «Datos personales — prueba WhatsApp» y el número utilizado en la prueba. Se verificará la identidad del solicitante sin pedir contraseñas ni códigos de acceso.

La participación es voluntaria. Antes de incorporar participantes, el responsable les informará sobre esta política y solicitará la autorización que corresponda.

## Cambios

Esta política se actualizará si cambian las funciones, los proveedores o las finalidades del prototipo. La versión vigente se publicará en esta misma página.
