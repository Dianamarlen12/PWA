# PWA
Actividad 2.2 - PWA (Creación de una PWA)

# ¿Qué es un Service Worker?

Ten en cuenta que las PWA se ejecutan solo en https porque el service workers puede acceder a la solicitud y manejarla. Por lo tanto, se requiere seguridad.

Un service worker es un script que tu navegador ejecuta en segundo plano en un hilo separado. Eso significa que se ejecuta en un lugar diferente y está completamente separado de tu página web. Esa es la razón por la que no puede manipular elementos en el DOM.

Sin embargo, es superpoderoso. El service worker puede interceptar y manejar solicitudes de red, administrar el caché para habilitar el soporte fuera de línea o enviar notificaciones push a tus usuarios.
