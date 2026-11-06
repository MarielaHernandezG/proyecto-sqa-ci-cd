# Pipeline CI/CD con Aseguramiento de Calidad Integrado (SQA)

![Backend CI](https://img.shields.io/badge/Backend%20Tests-PASSED-brightgreen)
![Frontend CI](https://img.shields.io/badge/Frontend%20Tests-PASSED-brightgreen)
![Coverage](https://img.shields.io/badge/Backend%20Coverage-93.33%25-success)
![Quality Gate](https://img.shields.io/badge/SonarCloud-PASSED-blue)

## Descripción del Proyecto
Este proyecto implementa un entorno completo de Aseguramiento de la Calidad de Software (SQA) y un Pipeline de Integración Continua / Entrega Continua (CI/CD) automatizado para una aplicación full-stack.

## Stack Tecnológico
- **Backend**: Node.js, Express, Jest, Supertest
- **Frontend**: React, React Testing Library
- **CI/CD**: GitHub Actions
- **Análisis Estático**: SonarCloud

## Estructura del Repositorio
- `/.github/workflows/ci.yml`: Definición del pipeline CI/CD.
- `proyecto final.zip`: Código fuente comprimido del backend y frontend.
- `/docs`: Documentación formal de SQA Plan, Matriz de Pruebas, Métricas y Manual Técnico.

## Instrucciones de Instalación Local
```bash
# Clonar repositorio
git clone [https://github.com/MarielaHernandezG/proyecto-sqa-ci-cd.git](https://github.com/MarielaHernandezG/proyecto-sqa-ci-cd.git)

# Backend
cd backend && npm install && npm test

# Frontend
cd ../frontend && npm install && npm test
