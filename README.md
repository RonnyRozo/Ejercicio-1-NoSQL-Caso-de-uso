# Ejercicio-1-NoSQL-Caso-de-uso


A continuación, se presentan los requisitos funcionales y no funcionales del sistema, así como algunas posibles mejoras y características futuras:

Requisitos Funcionales:
Gestión de Usuarios:

Los usuarios deben poder registrarse, iniciar sesión y gestionar sus cuentas.
Gestión de Roles:

Deben existir tres roles de usuario: Administradores, Empleados y Clientes, cada uno con permisos específicos.
Gestión de Artículos:

Los usuarios con el rol de Administrador deben poder agregar, actualizar, eliminar y ver información detallada de los artículos en el sistema.
Los usuarios con el rol de Empleado y Cliente solo deben poder ver información de los artículos.
Gestión de Tickets:

Los usuarios con el rol de Empleado deben poder crear, actualizar y eliminar tickets.
Los usuarios con el rol de Cliente deben poder ver sus tickets pasados.
Operaciones CRUD en Tickets:

Los usuarios deben poder crear, leer, actualizar y eliminar tickets.
Cada ticket debe contener una lista de artículos comprados con cantidades y precios.
Cálculo del Subtotal, IVA y Total:

Al crear o actualizar un ticket, el sistema debe calcular automáticamente el subtotal, el IVA y el total, aplicando las tasas de impuestos correspondientes.
Actualización de Existencias de Artículos:

Al crear o actualizar un ticket, el sistema debe actualizar automáticamente las existencias de los artículos en función de las cantidades vendidas.
Seguridad y Autenticación:

Los datos del sistema deben estar protegidos mediante autenticación y autorización.
Registro de Actividades:

El sistema debe llevar un registro de actividades importantes, como cambios en los artículos, creación o actualización de tickets, etc.
Requisitos No Funcionales:
Rendimiento:

El sistema debe ser eficiente y responder rápidamente, incluso con un gran número de usuarios y registros.
Escalabilidad:

Debe ser fácil de escalar para manejar el crecimiento de datos y usuarios.
Seguridad:

Deben implementarse prácticas de seguridad para proteger los datos y prevenir accesos no autorizados.
Usabilidad:

La interfaz de usuario debe ser intuitiva y fácil de usar para los usuarios finales.
Disponibilidad:

El sistema debe estar disponible la mayor parte del tiempo, con una planificación adecuada para mantenimiento y actualizaciones.
Posibles Mejoras y Características Futuras:
Historial de Tickets:

Agregar un historial completo de tickets para que los clientes puedan ver sus compras pasadas.
Notificaciones:

Implementar notificaciones por correo electrónico o mensajes de texto para confirmar compras y cambios en el estado de los tickets.
Reportes y Análisis:

Agregar funcionalidades de generación de informes y análisis de ventas para ayudar a tomar decisiones comerciales.
Múltiples Monedas:

Permitir transacciones en diferentes monedas con tasas de cambio actualizadas.
Integración de Pagos:

Integrar pasarelas de pago para realizar transacciones en línea.
Aplicación Móvil:

Desarrollar una aplicación móvil para facilitar las compras y seguimiento de tickets.
Pruebas Automatizadas:

Implementar pruebas unitarias y de integración automatizadas para garantizar la calidad del código y la funcionalidad.
Optimización de la Base de Datos:

Realizar ajustes de rendimiento en la base de datos a medida que el sistema crece.
Soporte Multilingüe:

Agregar soporte para múltiples idiomas para llegar a una audiencia más amplia.
Integración con Redes Sociales:

Permitir a los usuarios compartir sus compras y experiencias en redes sociales.
Sistema de Puntuación y Comentarios:

Implementar un sistema de calificación y comentarios para productos y servicios.
