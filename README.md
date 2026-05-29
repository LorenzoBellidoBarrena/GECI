# GECI

GECI es una aplicación Angular que maqueta un flujo de gestión de solicitudes con acceso mediante certificado electrónico o SSOweb. El proyecto usa Angular Material, rutas, modales, tablas, filtros y datos mock para representar una interfaz administrativa.

## 🚀 Demo

> Actualmente no hay una demo pública disponible. El proyecto puede ejecutarse en local siguiendo las instrucciones de instalación.

## 📸 Capturas

> Pendiente de añadir capturas de pantalla de la aplicación.

El repositorio contiene imágenes corporativas en `GECI/src/assets/images/`, pero no capturas finales de la interfaz.

## 🧩 Funcionalidades

* Página de bienvenida con información de acceso.
* Acceso mediante modales de certificado electrónico y SSOweb.
* Modal de bienvenida tras el login simulado.
* Pantalla de gestión de solicitudes.
* Listado de solicitudes con Angular Material Table.
* Filtros por estado desde sidebar: todas, pendientes, en proceso, atendidas y archivadas.
* Búsqueda por ID de solicitud.
* Filtro por rango de fechas con datepickers.
* Campo de comentario editable en la tabla.
* Pantalla de detalle de solicitud con tabla de documentos, CSV, errores y acciones.
* Uso de header, footer, sidebar y varios modales como componentes standalone.
* Configuración SSR con Angular y Express.

Los datos de solicitudes y detalles están definidos en los componentes; no se ha detectado integración con una API real.

## 🛠️ Tecnologías utilizadas

**Frontend**

* Angular 18
* TypeScript
* Angular Material
* Angular CDK
* Angular Forms
* CSS

**SSR**

* Angular SSR
* Express
* Node.js

**Testing**

* Karma
* Jasmine

## 🏗️ Arquitectura y estructura

```text
GECI/
├── GECI/
│   ├── src/
│   │   ├── app/
│   │   │   ├── components/
│   │   │   ├── pages/
│   │   │   ├── app.config.ts
│   │   │   └── app.routes.ts
│   │   ├── assets/
│   │   │   └── images/
│   │   ├── main.ts
│   │   └── main.server.ts
│   ├── package.json
│   └── angular.json
└── README.md
```

La aplicación usa componentes standalone y rutas lazy para la página de detalle.

## ⚙️ Instalación y ejecución

```bash
cd GECI
npm install
npm start
```

La app se sirve normalmente en `http://localhost:4200/`.

## 🧪 Tests

```bash
cd GECI
npm test
```

## 📦 Build o despliegue

```bash
cd GECI
npm run build
```

Para servir el bundle SSR tras compilar:

```bash
npm run serve:ssr:GECI
```

## 📌 Estado del proyecto

Demo técnica/proyecto académico en desarrollo.

Posibles mejoras futuras:

* Conectar el listado y el detalle con una API real.
* Añadir autenticación real para certificado/SSO si el proyecto lo requiere.
* Corregir textos con problemas de codificación en algunas plantillas.
* Añadir capturas de pantalla y flujo de uso.
* Ampliar tests para filtros, modales y navegación.

## 👨‍💻 Autor

Lorenzo Bellido Barrena

* Portfolio: https://lorenzo-bellido.vercel.app/
* LinkedIn: https://www.linkedin.com/in/lorenzo-bellido-barrena/
* GitHub: https://github.com/LorenzoBellidoBarrena
* Email: [lorenzobeba2@gmail.com](mailto:lorenzobeba2@gmail.com)
