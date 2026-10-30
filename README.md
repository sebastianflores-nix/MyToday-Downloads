# MyToday para Mac

Seguimiento del tiempo, tareas y clientes en tu Mac.

## Descargar

[**Descargar MyToday — versión del 30 de octubre de 2026**](https://github.com/sebastianflores-nix/MyToday-Downloads/releases/tag/v0.1.0-preview-20261030)

| Tu Mac | Instalador |
|---|---|
| Apple Silicon o Intel con macOS 13.3 o posterior | [**MyToday Universal**](https://github.com/sebastianflores-nix/MyToday-Downloads/releases/download/v0.1.0-preview-20261030/MyToday-Mac-Universal-2026.10.30-preview.dmg) |
| Intel antigua con OS X El Capitan 10.11.6 o posterior | [MyToday Legacy — experimental](https://github.com/sebastianflores-nix/MyToday-Downloads/releases/download/v0.1.0-preview-20261030/MyToday-Legacy-Intel-2026.10.30-preview.dmg) |



## Instalar

1. Descarga el DMG correspondiente.
2. Ábrelo y arrastra MyToday a Aplicaciones.
3. Abre la app desde Aplicaciones.

**Estas versiones tienen firma local de pruebas y no están notarizadas por Apple.** GitHub no cambia esa condición: macOS puede bloquear la primera apertura. No se garantiza una instalación sin avisos. Consulta la guía oficial de Apple: https://support.apple.com/es-mx/102445

## Qué incluye

Seguimiento por cliente en pestañas, varios temporizadores simultáneos, tareas con tiempo estimado, mascotas y resumen semanal por cliente con desglose por día. Alcanzar el tiempo estimado no completa una tarea: la persona debe marcarla como terminada.

Los datos se guardan localmente en la Mac. El paquete no incluye el historial del creador ni sus credenciales de correo. El envío de informes requiere configurar la conexión de esa instalación; descargar la app no activa por sí solo el correo. Revisa el destinatario en Configuración antes de enviar.

**Limitación conocida:** la pausa automática por inactividad/reposo todavía está pendiente. Pausa o termina tus temporizadores antes de dejar de trabajar para evitar que se acumulen horas sin trabajar.

La edición Legacy usa un almacenamiento separado. No hay actualizador automático. Exporta un respaldo antes de cambiar de edición o probar una actualización.

## Validación de esta compilación

164 pruebas de interfaz/lógica y 24 pruebas nativas aprobadas. Los DMG se verifican con hdiutil y las firmas locales con codesign. Las pruebas automatizadas no sustituyen la validación en cada Mac, especialmente en El Capitan.

Este repositorio contiene únicamente instaladores y documentación. El código fuente se mantiene privado.
