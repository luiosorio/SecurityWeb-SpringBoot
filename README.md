# SecurityWeb-SpringBoot
Aprender a integrar Spring Security en una aplicación Spring Boot para proteger rutas específicas

Instrucciones:

Crear el proyecto con Spring Initializr
Dependencias: Spring Web, Spring Security, Thymeleaf (opcional).
Configurar usuarios en memoria
  - Usuario 1: admin / admin123 con rol ADMIN.
  - Usuario 2: user / user123 con rol USER.
Proteger rutas específicas
  - /admin: solo accesible para usuarios con rol ADMIN.
  - /user: accesible para usuarios con rol USER o ADMIN.
  - /public: accesible sin autenticación.
Probar la autenticación
