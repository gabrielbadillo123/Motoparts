# 9. Decisiones de Arquitectura

Este capítulo documenta las decisiones de arquitectura más relevantes del ERP Motoparts.

## Decisión 1: Arquitectura monolítica inicial
- **Alternativas:** Microservicios desde el inicio.  
- **Justificación:** El alcance del proyecto es acotado y el equipo es reducido. Un monolito es más fácil de desarrollar y desplegar.  
- **Consecuencias:** Migración futura a microservicios si el sistema escala.

## Decisión 2: Backend en Java Spring Boot
- **Alternativas:** Node.js con Express, Python con Django.  
- **Justificación:** Spring Boot ofrece robustez, amplia comunidad, integración con JPA y seguridad.  
- **Consecuencias:** Mayor curva de aprendizaje, pero estabilidad a largo plazo.

## Decisión 3: Base de Datos Relacional (PostgreSQL)
- **Alternativas:** MySQL, MongoDB (NoSQL).  
- **Justificación:** Se requiere integridad referencial, consultas SQL complejas y soporte a transacciones.  
- **Consecuencias:** Escalabilidad principalmente vertical, pero alta confiabilidad.

## Decisión 4: Frontend con React (SPA)
- **Alternativas:** Angular, Vue.js.  
- **Justificación:** React permite desarrollo modular, rápido y con amplia comunidad.  
- **Consecuencias:** Necesidad de capacitar al equipo en React.

## Decisión 5: Integración con sistemas externos
- **Ejemplo:** Facturación electrónica y sistema contable.  
- **Justificación:** Requisito legal y contable en Colombia.  
- **Consecuencias:** Dependencia de servicios externos, posibles caídas fuera de nuestro control.
