# Sistema Educativo Distribuido
Este sistema implementa microservicios para la gestión de usuarios, asignaturas y matrículas. Incluye seguridad con JWT, monitoreo, pruebas, y despliegue automatizado con Docker y GitHub Actions.

## Microservicios
- **usuarios-servicio**: Gestión de usuarios y autenticación.
- **asignaturas-servicio**: Gestión de asignaturas.
- **matriculas-servicio**: Gestión de matrículas.
- **eureka-server**: Descubrimiento de servicios.
- **config-server**: Configuración centralizada.
- **gateway-servicio** (opcional): Enrutamiento y seguridad.

## Arquitectura
- Comunicación entre microservicios con Feign.
- Seguridad con JWT.
- Monitoreo con Spring Boot Actuator, Prometheus y Grafana.
- Despliegue con Docker Compose.