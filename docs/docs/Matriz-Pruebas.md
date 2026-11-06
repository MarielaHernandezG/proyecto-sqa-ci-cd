# Matriz de Pruebas Automatizadas

| ID Caso | Módulo | Tipo | Entrada / Acción | Resultado Esperado | Resultado Obtenido | Estado |
| :--- | :--- | :--- | :--- | :--- | :--- | :--- |
| **TC-01** | Backend | Integración | `GET /api/health` | HTTP 200 `{ status: "UP" }` | HTTP 200 `{ status: "UP" }` | **PASS** |
| **TC-02** | Backend | API CRUD | `GET /api/tasks` | HTTP 200 con lista de tareas | HTTP 200 con array JSON | **PASS** |
| **TC-03** | Frontend | Componente | Renderizado de `App.js` | Título "Proyecto SQA - CI/CD Pipeline" | En el DOM y visible | **PASS** |
