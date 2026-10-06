# lab-paseto-v1v2v3

Laboratorio de autenticación y autorización con **PASETO v4.public** — Seguridad en el Desarrollo de Software.

Contiene las tres versiones evolutivas del laboratorio:

| Carpeta | Descripción |
|---|---|
| [`lab-paseto`](./lab-paseto) | V1 — PASETO básico: login, generación/verificación de token, ruta protegida |
| [`lab-paseto-v2`](./lab-paseto-v2) | V2 — Suma roles de usuario, autorización y documentación Swagger |
| [`lab-paseto-v3`](./lab-paseto-v3) | V3 — Suma CRUD completo, validaciones con express-validator y Swagger ampliado |

Cada carpeta incluye su propio `README.md` con las instrucciones de instalación y la batería de pruebas documentada.

## Ejecutar cualquiera de las versiones

```bash
cd lab-paseto        # o lab-paseto-v2 / lab-paseto-v3
npm install
npm run dev
```

El servidor queda disponible en `http://localhost:3000` (V2 usa el puerto 3001 y V3 el 3002 para poder correr las tres a la vez).
