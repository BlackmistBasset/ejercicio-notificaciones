# Ejercicio notificaciones

La idea es realizar la funcionalidad del sistema de notificaciones de una app tipo red social. Pueden trabajar sobre el clon instagram, pero sepan que se complejiza el ejercicio por el tamaño de la app. Si no se sienten seguras aún con React, recomiendo crearlo de 0 y luego de última se replica en la app ya existente.

Debe existir un disparador de la creación de la notificación (por ejemplo, un botón "enviar notificación"). El mensaje que llega a la notificación debe poder ser dinámico y que existan diferentes tipos de notificaciones (o sea, que el cuerpo de la notificación pueda variar eventualmente).

Debe existir un componente "Notificaciones" que agrupe todas las notificaciones que le lleguen al usuario. Si el botón se aprieta varias veces, debe llegarle una notificación por click. Cada notificación es independiente de las demás. Las notificaciones deben poder marcarse como leídas y deben poder eliminarse (notificación por notificación y también mediante la opción "borrar todas").

Las notificaciones deben persistir de alguna manera -por ejemplo, con las herramientas que tenemos actualmente, guardandose en el localStorage-.

Debe haber un contador de notificaciones. El contador solo debe contar las notificaciones no leidas, no todas.
