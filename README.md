 # **Sistema de Ventas ¨Updates¨**

Sistema de punto de venta pensado para negocios pequeños — cafeterías, quioscos, tiendas de barrio — que necesitan controlar ventas, stock y turnos de trabajo de forma simple, rápida y sin depender de una conexión a internet constante.

Desarrollado por [Julio_GE](https://github.com/JulioC9808-ops).

## Plataformas disponibles

- 🖥️ **Windows** — aplicación de escritorio con instalador en español.
- 📱 **Android** — aplicación nativa con escáner de código QR integrado.

Descarga la última versión de cada plataforma desde la sección [Releases](../../releases) de este repositorio.

## Características principales

### Cierre de turno guiado
El empleado registra lo que le queda de cada producto al final de su turno; el sistema calcula automáticamente cuánto se vendió y desglosa el dinero recibido por tipo de pago:
- Efectivo, contado billete por billete según su denominación.
- Transferencias, con su ID de referencia.
- Ventas VIP, con concepto y monto.

Antes de poder cerrar el turno, el sistema verifica que el total declarado cuadre exactamente con lo vendido — evitando descuadres de caja.

### Sincronización sin internet
Todo el negocio puede operar completamente offline. Cuando hace falta compartir información entre dispositivos —productos, precios, stock actualizado, o el cierre de turno de un empleado— la app usa un código QR sobre la misma red Wi-Fi local para transferir los datos directamente entre el celular del empleado y el del administrador, sin pasar por ningún servidor externo.

### Activación de empleados por QR
El administrador genera un único código QR por empleado que contiene su usuario, contraseña y todos los datos del negocio (productos, precios, stock, movimientos). El empleado lo escanea una vez para activarse, y puede volver a escanearlo cuando necesite traer información actualizada.

### Panel de administración
- Resumen general del negocio.
- Reportes de ventas y cierres de turno.
- Historial de movimientos de stock.
- Historial de salarios por empleado (con cálculo automático por porcentaje de ventas, si se activa).
- Gestión completa de productos y precios.
- Gestión de usuarios y empleados.
- Vista dedicada de ventas VIP.
- Ajustes generales: nombre del negocio, logo, tema visual.

### Panel de empleado
- Vista de stock disponible en tiempo real.
- Entrada de productos desde almacén al punto de venta.
- Cierre de turno guiado paso a paso.
- Actualización de datos del negocio vía QR (solo en la versión Android).

### Roles diferenciados
Cada usuario —administrador o empleado— ve únicamente las herramientas que le corresponden, con su propia interfaz adaptada.

### Tutorial y ayuda integrada
Guía paso a paso para nuevos usuarios, y sugerencias contextuales (`?`) en las secciones que lo requieren.

### Actualizaciones automáticas
La aplicación revisa por sí sola si existe una versión más reciente disponible y guía al usuario para instalarla, sin pasos manuales complicados.

### Protección de licencia
Cada instalación de escritorio queda vinculada a una huella única del equipo, como medida de protección contra copias no autorizadas.

## Soporte

Para reportar un problema o sugerir una mejora, puedes escribirme a **[Julio](wa.me+5351616816)**

