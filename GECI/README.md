# GECI App

Aplicación Angular que maqueta la gestión de solicitudes con Angular Material, rutas, tablas, filtros y modales de acceso. Este README documenta la app interna; el README raíz del repositorio incluye una visión más completa.

## 🚀 Demo

> Actualmente no hay una demo pública disponible. El proyecto puede ejecutarse en local siguiendo las instrucciones de instalación.

## 📸 Capturas

> Pendiente de añadir capturas de pantalla de la aplicación.

## 🧩 Funcionalidades

* Página de inicio con acceso por certificado o SSOweb.
* Modales de acceso y bienvenida.
* Listado de solicitudes con filtros por estado.
* Búsqueda por ID y rango de fechas.
* Detalle de solicitud con documentos, CSV, errores y acciones.
* Componentes standalone para header, footer, sidebar y modales.
* Configuración SSR.

## 🛠️ Tecnologías utilizadas

* Angular 18
* Angular Material
* Angular CDK
* TypeScript
* Angular SSR
* Express
* Karma/Jasmine

## 🏗️ Arquitectura y estructura

```text
GECI/
├── src/app/
│   ├── components/
│   ├── pages/
│   └── app.routes.ts
├── src/assets/images/
├── package.json
└── angular.json
```

## ⚙️ Instalación y ejecución

```bash
npm install
npm start
```

## 🧪 Tests

```bash
npm test
```

## 📦 Build o despliegue

```bash
npm run build
npm run serve:ssr:GECI
```

## 📌 Estado del proyecto

Demo técnica con datos mock. Pendiente de integración con backend real, capturas y corrección de textos con problemas de codificación.

## 👨‍💻 Autor

Lorenzo Bellido Barrena

* Portfolio: https://lorenzo-bellido.vercel.app/
* LinkedIn: https://www.linkedin.com/in/lorenzo-bellido-barrena/
* GitHub: https://github.com/LorenzoBellidoBarrena
* Email: [lorenzobeba2@gmail.com](mailto:lorenzobeba2@gmail.com)
