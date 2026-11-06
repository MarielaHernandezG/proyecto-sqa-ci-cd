# Manual Técnico y Arquitectura del Pipeline

## 1. Arquitectura del Pipeline CI/CD
El flujo automatizado se ejecuta en GitHub Actions (`.github/workflows/ci.yml`) en cada evento de `push` o `pull_request` sobre la rama `main`[cite: 26].

### Etapas (Jobs):
1. **test-backend**: Configura Node.js 18, instala dependencias (`npm ci`) y ejecuta los tests de Jest (`npm test`).
2. **test-frontend**: Instala dependencias, ejecuta pruebas unitarias de React y realiza la compilación (`npm run build`).
3. **sonarcloud**: Analiza la calidad estática del código mediante SonarCloud Action.

## 2. Guía de Mantenimiento Local
Para ejecutar y probar la suite de calidad localmente:

```bash
# Backend
cd backend
npm install
npm test

# Frontend
cd frontend
npm install
npm test
