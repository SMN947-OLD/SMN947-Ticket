# SMN947-Ticket
Open source PHP &amp; MySQLi based ticket system.

Este es un proyecto que busca crear un sistema de tickets para manejo de centros de soporte y atención al cliente, la idea surge luego de probar varios aplicativos con algunas cosas muy buenas pero con la sensación de que les faltaba algo.

## Características del proyecto
- Basado en PHP y MySQLi
- Inicialmente solo en español


  ### Parte administrativa
  - Niveles de acceso por departamentos o secciones.
  - Enrutamiento interno.
  - Niveles de urgencia.
  - Filtros por palabras clave.
  - Respuestas guardadas.
  - Seccion de FAQ´s como recursos internos de ayuda.

  ### Parte del usuario
  - Seleccion de departamento al que desea escribir.
  - Capacidad de calificar el servicio.
  - Revisión de históricos.
  - Seccion de FAQ´s como recursos publicos de ayuda.

Inicialmente no se hace mucho énfasis en la vinculación con servicios SMTP o la función PHPMail, solo se usarán mensajes **in-app** con facil vinculacion para notificaciones.
