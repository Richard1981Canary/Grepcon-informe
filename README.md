# Informe de Visita GREPCON

Formulario de visita a técnicos en campo (7 pasos → resumen → PDF).
Es una PWA con su propio icono: se instala gratis en Android e iPhone desde el navegador,
sin tiendas de apps.

## Publicar (una vez)

En GitHub: *Settings → Pages → Source: Deploy from a branch*, rama `main`, carpeta `/ (root)` → *Save*.

## Usar

- **Enlace para compartir:** https://richard1981canary.github.io/Grepcon-informe/
- **Android (Chrome):** abrir el enlace → menú ⋮ → *Instalar app*.
- **iPhone / iPad (Safari):** abrir el enlace → Compartir → *Añadir a pantalla de inicio*.
- En el visor del PDF, **📤 Compartir** abre la hoja del móvil (WhatsApp, correo, Teams…).
- Funciona sin conexión una vez abierta por primera vez.

## Historial

Cada vez que se genera el PDF, el informe se guarda automáticamente en la pestaña
**📁 Historial**, dentro del propio dispositivo. Desde ahí se puede:

- **Ver** el informe de nuevo.
- **Compartir** el PDF más tarde (útil si en la visita no había conexión). Al compartirlo
  queda marcado como *Enviado*; los que faltan aparecen como *Pendiente de enviar* y se
  cuentan en el número naranja de la pestaña.
- **Buscar** por técnico, cliente o lugar, y **borrar** informes (pide confirmación).

Los informes se guardan solo en ese teléfono o tableta: no se comparten entre dispositivos
y se pierden si se desinstala la app o se borran los datos del navegador.

Al publicar cambios, sube `VERSION` en `sw.js` para que las apps instaladas se actualicen.
