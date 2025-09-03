# 2. Restricciones de Arquitectura

Las decisiones tecnológicas adoptadas para este ERP son:

- **Lenguaje Backend:** Java con Spring Boot.
- **Frontend:** Aplicación de una sola página (SPA) desarrollada con React.
- **Base de Datos:** PostgreSQL (relacional).
- **Interfaz con usuarios:** HTTPS/JSON a través de una API REST.
- **Arquitectura:** Cliente-Servidor monolítico (SPA + API + DB).

## Restricciones adicionales
- Cumplir con normativas de facturación electrónica en Colombia.
- Seguridad en accesos mediante autenticación y autorización.
- Compatibilidad con sistemas contables externos.
