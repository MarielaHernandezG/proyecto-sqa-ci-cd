# Plan de Aseguramiento de la Calidad del Software (SQA Plan)

## 1. Propósito y Alcance
Este documento establece las actividades, herramientas y métricas para garantizar la calidad del software en la aplicación full-stack (Node.js/Express backend y React frontend).

## 2. Estándares y Herramientas
- **Control de Versiones**: GitHub
- **Integración Continua**: GitHub Actions
- **Pruebas Unitarias y de Integración**: Jest, Supertest (Backend), React Testing Library (Frontend)
- **Análisis Estático**: ESLint, Prettier, SonarCloud

## 3. Métricas y Umbrales
- **Cobertura de Pruebas**: Mínimo 60% requerido (Backend actual: 93.33%, Frontend: 100% en componentes clave).
- **Vulnerabilidades y Bugs**: 0 permitidos en producción.

## 4. Gestión de Riesgos
- **Riesgo**: Fallos de compilación por inconsistencia de dependencias.
- **Mitigación**: Uso estricto de `npm ci` en el pipeline CI/CD.
