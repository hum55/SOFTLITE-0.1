<p align="center">
  <img src="https://img.shields.io/badge/⚡_SOFTLITE-Sistema_POS-1a2f5a?style=for-the-badge&labelColor=1a2f5a" alt="SOFTLITE"/>
</p>

<h1 align="center">⚡ SOFTLITE</h1>
<h3 align="center">Sistema de Punto de Venta & Aplicación de Inventario</h3>

<p align="center">
  <img src="https://img.shields.io/badge/Estado-En%20Desarrollo-yellow?style=flat-square" alt="Estado"/>
  <img src="https://img.shields.io/badge/Licencia-MIT-blue?style=flat-square" alt="Licencia"/>
  <img src="https://img.shields.io/badge/Java_17-Spring_Boot_3-ED8B00?style=flat-square&logo=openjdk&logoColor=white" alt="Java"/>
  <img src="https://img.shields.io/badge/React_18-Vite-61DAFB?style=flat-square&logo=react&logoColor=white" alt="React"/>
  <img src="https://img.shields.io/badge/MySQL_8-4479A1?style=flat-square&logo=mysql&logoColor=white" alt="MySQL"/>
  <img src="https://img.shields.io/badge/Metodología-Scrum-6DB33F?style=flat-square" alt="Scrum"/>
</p>

<p align="center">
  <b>SOFTLITE</b> es un sistema de punto de venta (POS) integral diseñado para el sector minorista,<br/>
  que combina un programa de cobro rápido e intuitivo con una aplicación de inventario en tiempo real.<br/>
  Pensado para funcionar en hardware accesible, sin complicaciones y con una interfaz amigable.
</p>

<p align="center">
  <a href="#-características">Características</a> •
  <a href="#-arquitectura">Arquitectura</a> •
  <a href="#-instalación">Instalación</a> •
  <a href="#-colaboradores">Equipo</a> •
  <a href="#-estimación-de-costos">Costos</a>
</p>

---

## 📋 Tabla de Contenidos

- [Descripción del Proyecto](#-descripción-del-proyecto)
- [Problema que Resuelve](#-problema-que-resuelve)
- [Características](#-características)
- [Módulos del Sistema](#-módulos-del-sistema)
- [Arquitectura](#-arquitectura)
- [Stack Tecnológico](#-stack-tecnológico)
- [Instalación](#-instalación)
- [Estructura del Proyecto](#-estructura-del-proyecto)
- [Mercado Objetivo](#-mercado-objetivo)
- [Estimación de Costos](#-estimación-de-costos)
- [Cronograma](#-cronograma)
- [Colaboradores](#-colaboradores)
- [Nombres Propuestos](#-nombres-propuestos)
- [Licencia](#-licencia)

---

## 🎯 Descripción del Proyecto

SOFTLITE nace como respuesta a una necesidad real en el comercio minorista: contar con un sistema de punto de venta que sea **potente pero simple**, que no exija hardware costoso y que cualquier persona pueda aprender a usar en poco tiempo.

El proyecto se divide en dos componentes principales:

### 💰 Programa de Punto de Venta

Un sistema de cobro diseñado para la velocidad y la simplicidad. Permite procesar ventas, aplicar descuentos, manejar múltiples métodos de pago y corregir errores de cobro sin necesidad de llamar a un supervisor para cada ajuste. Todo esto desde una interfaz limpia que funciona incluso en equipos con recursos limitados.

### 📦 Aplicación de Inventario

Una herramienta que transforma el tedioso proceso de conteo y control de mercancía en algo ágil y visual. Permite verificar existencias en tiempo real, recibir alertas de stock bajo, registrar entradas de mercancía y mantener un historial completo de movimientos, todo desde una interfaz intuitiva y accesible.

> [!NOTE]
> **Filosofía del proyecto:** Si un cajero necesita más de 30 segundos para completar una venta o si un inventarista necesita un manual para contar productos, algo estamos haciendo mal.

---

## 🔍 Problema que Resuelve

| Problema actual | Cómo lo resuelve SOFTLITE |
|:---|:---|
| Sistemas POS complejos que requieren semanas de capacitación | Interfaz intuitiva con máximo 3 clics para cualquier operación |
| Software que exige hardware costoso y moderno | Optimizado para equipos de gama baja con requisitos mínimos |
| Errores de cobro que no se pueden corregir fácilmente | Modificación de productos ya cobrados sin procesos engorrosos |
| Inventarios manuales lentos y propensos a error | App visual que verifica existencias en tiempo real |
| Desconexión entre ventas e inventario | Sincronización automática entre cobro e inventario |
| Caídas de internet que detienen las ventas | Modo offline con sincronización automática al reconectar |
| Sistemas cerrados que no se adaptan | Arquitectura open source, modular y personalizable |

---

## ✨ Características

### Punto de Venta

- ⚡ **Cobro rápido** con lectura de código de barras (escáner o cámara)
- 💳 **Múltiples métodos de pago** simultáneos (efectivo, tarjeta, transferencia)
- 🔄 **Corrección de errores** — modifica productos ya cobrados sin complicaciones
- 🧾 **Tickets automáticos** — generación de recibos con datos fiscales
- 📴 **Modo offline** completo con sincronización posterior
- 🏷️ **Descuentos flexibles** por porcentaje o monto fijo
- ↩️ **Devoluciones** parciales o totales con ajuste automático de inventario

### Inventario

- 📊 **Existencias en tiempo real** — conteo y verificación instantánea
- 🔔 **Alertas automáticas** de stock mínimo configurables por producto
- 📥 **Registro de entradas** de mercancía vinculadas a proveedor
- 📜 **Historial completo** de movimientos (ventas, entradas, ajustes, devoluciones)
- 🔍 **Búsqueda avanzada** y filtrado de productos

### General

- 👤 **Registro de empresa** y empleados con turnos laborales
- 🔐 **Control de acceso** por roles (Admin, Cajero, Inventarista, Supervisor)
- 📈 **Dashboard** con métricas en tiempo real y reportes exportables (PDF/Excel)
- 🌐 **SaaS** — accesible desde cualquier dispositivo con navegador
- 🎨 **Interfaz UX/UI** amigable, intuitiva y accesible
- 📱 **Multi-dispositivo** — optimizado para PC, tablet y móvil
- 🛡️ **Seguridad** — base de datos con backups automáticos y JWT
- 🚀 **Instalación sencilla** — Docker o manual en minutos

---

## 📦 Módulos del Sistema

```
┌──────────────────────────────────────────────────────┐
│                     SOFTLITE POS                     │
├───────────┬───────────┬───────────┬──────────────────┤
│  💰 Cobro │ 📦 Invent.│ 📊 Report.│ 👤 Usuarios/Roles│
├───────────┼───────────┼───────────┼──────────────────┤
│ 🤝 Client.│ 📋 Provee.│ 🧾 Factur.│ 🔔 Notificaciones│
├───────────┴───────────┴───────────┴──────────────────┤
│              ⚙️  Configuración del Sistema            │
└──────────────────────────────────────────────────────┘
```

| Módulo | Descripción |
|:---|:---|
| **💰 Cobro (POS)** | Escaneo, carrito, descuentos, pagos múltiples, tickets |
| **📦 Inventario** | CRUD de productos, alertas de stock, historial de movimientos |
| **📊 Reportes** | Ventas por período/empleado/categoría, dashboard, exportación PDF/Excel |
| **👤 Usuarios y Roles** | Registro de empleados, turnos, RBAC, log de actividad |
| **🤝 Clientes** | Registro, búsqueda e historial de compras |
| **📋 Proveedores** | Gestión con historial de órdenes de compra |
| **🧾 Facturación** | Recibos y comprobantes con datos fiscales |
| **🔔 Notificaciones** | Alertas de stock bajo, ventas inusuales, eventos del sistema |
| **⚙️ Configuración** | Datos del negocio, impresora, umbrales, backups |

---

## 🏗 Arquitectura

El proyecto contempla dos enfoques según la escala del negocio:

### Opción A — Monolítica `Recomendada para v1.0`

Para tiendas individuales o negocios pequeños. Todo en un solo despliegue.

```
┌───────────────────────────────┐
│         SOFTLITE v1.0         │
│                               │
│   ┌───────────────────────┐   │
│   │  Frontend             │   │
│   │  React 18 + Vite      │   │
│   ├───────────────────────┤   │
│   │  Backend              │   │
│   │  Spring Boot 3 (API)  │   │
│   ├───────────────────────┤   │
│   │  Base de Datos        │   │
│   │  MySQL / PostgreSQL   │   │
│   └───────────────────────┘   │
│                               │
└───────────────────────────────┘
```

### Opción B — Microservicios `Escalable para v2.0+`

Para negocios con planes de crecimiento o múltiples sucursales.

```
┌──────────────────────────────────────┐
│          FRONTEND (React SPA)        │
└─────────────────┬────────────────────┘
                  │ HTTPS / JWT
┌─────────────────▼────────────────────┐
│        API GATEWAY / BALANCER        │
├──────────┬───────────┬───────────────┤
│ Servicio │ Servicio  │  Servicio     │
│  Cobro   │ Inventario│  Reportes     │
├──────────┼───────────┼───────────────┤
│ Servicio │ Servicio  │  Servicio     │
│ Usuarios │ Clientes  │  Config       │
└────┬─────┴─────┬─────┴───────────────┘
     │           │
  ┌──▼──┐   ┌───▼─────────┐
  │ BD  │   │     BD      │
  │Prod.│   │ Financieros │
  └─────┘   └─────────────┘
```

> [!TIP]
> Se inicia con arquitectura monolítica por simplicidad. La estructura modular del código permite migrar a microservicios sin reescribir desde cero.

---

## 🛠 Stack Tecnológico

| Capa | Tecnología | Versión |
|:---|:---|:---|
| Backend | Java + Spring Boot | 17 / 3.x |
| Frontend | React + Vite | 18 / 5.x |
| Estilos | Tailwind CSS | 3.x |
| Base de Datos | MySQL / PostgreSQL | 8 / 15 |
| ORM | JPA / Hibernate | 6.x |
| Autenticación | Spring Security + JWT | — |
| Control de Versiones | Git + GitHub | — |
| CI/CD | GitHub Actions | — |
| Contenedores | Docker + Docker Compose | — |
| Pruebas Backend | JUnit 5 + Mockito | — |
| Pruebas Frontend | Jest + React Testing Library | — |
| Pruebas E2E | Cypress | — |
| Reportes | JasperReports / iText | — |

---

## 🚀 Instalación

### Requisitos previos

```
Java 17+  ·  Node.js 18+  ·  MySQL 8+  ·  Docker (opcional)  ·  Git
```

### Con Docker (recomendado)

```bash
# 1. Clonar el repositorio
git clone https://github.com/JorgeTSW/softlite.git
cd softlite

# 2. Configurar variables de entorno
cp .env.example .env
# Editar .env con los datos de tu base de datos

# 3. Levantar con Docker Compose
docker-compose up -d

# 4. Acceder al sistema
# Frontend → http://localhost:3000
# API      → http://localhost:8080/api
```

### Manual

```bash
# Backend
cd softlite-backend
./mvnw spring-boot:run

# Frontend (en otra terminal)
cd softlite-frontend
npm install
npm run dev
```

---

## 📁 Estructura del Proyecto

```
softlite/
│
├── 📂 softlite-backend/              ← API REST (Java + Spring Boot)
│   └── src/main/java/com.softlite/
│       ├── controllers/               # Endpoints REST
│       ├── services/                  # Lógica de negocio
│       ├── repositories/             # Acceso a datos (JPA)
│       ├── models/                   # Entidades de BD
│       ├── dto/                      # Objetos de transferencia
│       ├── security/                 # JWT + Spring Security
│       ├── exceptions/               # Manejo global de errores
│       └── config/                   # Configuración general
│
├── 📂 softlite-frontend/             ← SPA (React + Vite)
│   └── src/
│       ├── pages/                    # Rutas principales
│       ├── components/               # UI reutilizable
│       ├── services/                 # Llamadas a la API
│       ├── store/                    # Estado global (Zustand)
│       ├── hooks/                    # Custom hooks
│       ├── utils/                    # Utilidades
│       └── assets/                   # Imágenes, íconos
│
├── 📂 .github/workflows/             ← CI/CD con GitHub Actions
├── 📂 docs/                          ← Documentación del proyecto
├── 🐳 docker-compose.yml
└── 📄 README.md
```

---

## 🏪 Mercado Objetivo

SOFTLITE está diseñado para negocios minoristas que necesitan un sistema confiable sin la complejidad ni el precio de las soluciones empresariales:

| Segmento | Ejemplos | Prioridad |
|:---|:---|:---:|
| **Comercio pequeño** | Tiendas de abarrotes, misceláneas, papelerías | 🔴 Alta |
| **Comercio mediano** | Minisupers, ferreterías, tiendas de ropa, farmacias | 🔴 Alta |
| **Alimentos** | Panaderías, carnicerías, fruterías, tortillerías | 🟡 Media |
| **Servicios** | Estéticas, lavanderías, talleres con venta de refacciones | 🟡 Media |
| **Especializado** | Tiendas de electrónica, accesorios, vape shops | 🟢 Futuro |

> [!IMPORTANT]
> **¿Por qué estos mercados?** Son negocios que hoy operan con libretas, Excel o sistemas POS costosos que no aprovechan al 100%. SOFTLITE les da exactamente lo que necesitan: cobrar rápido, controlar su inventario y ver cuánto vendieron — sin pagar licencias de miles de pesos.

---

## 💰 Estimación de Costos

### Desarrollo — 5 desarrolladores × 24 meses

| Escenario | Tarifa/hora | Total estimado (USD) |
|:---|:---:|---:|
| 🟢 **Bajo** (juniors) | $8 – $15 | $108,000 – $202,500 |
| 🟡 **Medio** (mid-level) | $15 – $30 | $202,500 – $405,000 |
| 🔴 **Alto** (seniors) | $30 – $60 | $405,000 – $810,000 |

### Infraestructura — durante desarrollo

| Concepto | Costo |
|:---|---:|
| Servidor cloud (24 meses × $30–$80) | $720 – $1,920 |
| Dominio + SSL (2 años) | $40 |
| Herramientas de gestión (Jira, Figma, etc.) | $0 – $2,400 |
| Licencias de software | $0 (open source) |
| CI/CD (GitHub Actions) | $0 |

### Costos adicionales

| Concepto | Costo |
|:---|---:|
| Hardware (escáneres, impresoras, PCs) | $500 – $3,000 |
| Capacitación de usuarios finales | $500 – $2,000 |
| Migración de datos | $300 – $1,500 |
| Documentación y manuales | $200 – $800 |
| Pruebas de seguridad (OWASP) | $500 – $2,000 |
| Piloto en tienda | $300 – $1,000 |
| Contingencia (~15%) | $16,200 – $121,500 |

### Mantenimiento post-lanzamiento — anual

| Concepto | Costo/año |
|:---|---:|
| Servidor cloud | $360 – $960 |
| Dominio + SSL | $20 |
| Mantenimiento correctivo | $2,400 – $9,600 |
| Mantenimiento evolutivo | $3,600 – $14,400 |
| Soporte técnico (N1, N2, N3) | $3,600 – $18,000 |
| Backups y monitoreo | $240 – $600 |
| Actualizaciones de seguridad | $600 – $2,400 |
| **Total anual** | **$10,820 – $45,980** |

### 📊 Resumen total — escenario medio

| Concepto | Monto (USD) |
|:---|---:|
| Desarrollo + infraestructura | ~$306,000 |
| Costos adicionales | ~$20,000 – $50,000 |
| Primer año de mantenimiento | ~$25,000 |
| **🔵 Gran total estimado** | **$351,000 – $381,000** |

### Estimaciones individuales del equipo

| Integrante | Enfoque | Rango estimado |
|:---|:---|:---|
| **Humberto Ramírez** | Costo completo con mantenimiento | $351K – $381K USD |
| **Danna Albertos** | Desarrollo + operación anual | $40K – $360K MXN + $13K – $38K MXN/año |
| **Giovana Díaz** | Sistema avanzado completo | $500K – $2,000K MXN |
| **Dylan Vázquez** | Base + especificaciones | $40K – $90K MXN (base) / $50K – $800K MXN (completo) |

---

## 📅 Cronograma

| Fase | Duración | Entregable |
|:---|:---:|:---|
| 📋 Análisis de requisitos | Meses 1–2 | Documento SRS, historias de usuario |
| 🎯 Alcance y viabilidad | Mes 2–3 | Estudio técnico, económico y operativo |
| 🏗️ Diseño arquitectónico | Mes 3–4 | Documento de arquitectura, stack definido |
| 📐 Diseño detallado | Meses 4–6 | Diagramas UML, modelo ER, APIs REST |
| 🖼️ Prototipado y validación | Meses 6–8 | Mockups, prototipo funcional validado |
| 💻 Implementación (Sprints 0–5) | Meses 8–20 | Sistema funcional completo |
| 🧪 Pruebas y despliegue | Meses 20–24 | Sistema en producción + documentación |

> **Metodología:** Scrum con sprints de 2 semanas, dailys de 15 min, reviews y retrospectivas cada sprint.

---

## 👥 Colaboradores

| Avatar | Nombre | GitHub | Rol |
|:---:|:---|:---|:---|
| 🔵 | **Humberto Ramírez Gruintal** | [@JorgeTSW](https://github.com/JorgeTSW) | 💰 POS, Cobro y Costos |
| 🟢 | **Danna Pamela Albertos Sosa** | [@DannaAlbertos](https://github.com/DannaAlbertos) | 👤 Registro y Empleados |
| 🟡 | **Giovana Ruby Díaz Anduze** | [@GiovanaTSW](https://github.com/GiovanaTSW) | 🎨 UX/UI y Accesibilidad |
| 🔴 | **Dylan Vázquez Soriano** | [@dyvaso87-dot](https://github.com/dyvaso87-dot) | 📱 Optimización y Registros |

### Áreas de enfoque

- **Humberto Ramírez** — Programa de punto de venta: sistema amigable con bajo requerimiento de hardware, resolución de problemas simples, corrección de cobros erróneos y estimación completa de costos del proyecto.

- **Danna Pamela Albertos** — Registro de empresa y empleados con turnos laborales, facilidad de inicio del sistema, contabilización y verificación de existencia de productos.

- **Giovana Ruby Díaz** — Diseño UX/UI intuitivo y accesible, modelo SaaS, funcionalidad integral y diseño de base de datos.

- **Dylan Vázquez** — Optimización para múltiples dispositivos, registros de ventas y productos, interfaz amigable, facilidad de uso e instalación.

---

## 💡 Nombres Propuestos

| Nombre | Concepto | Estado |
|:---|:---|:---:|
| **SOFTLITE** | Software ligero y accesible | ✅ Seleccionado |
| SAILESAPP | Juego de palabras con "sales" + app | — |
| CLOUDSALES | Ventas en la nube | — |
| LOGICSOFT | Software con lógica sólida | — |
| AIRSELL | Vender con ligereza | — |
| SOFTFRIEND | Software amigable | — |

---

## 📄 Licencia

Este proyecto está bajo la licencia [MIT](LICENSE).

Eres libre de usar, modificar y distribuir este software.

---

<p align="center">
  <b>⚡ SOFTLITE</b> © 2025
  <br/>
  Hecho con ☕ y 💻 por el equipo de desarrollo
  <br/><br/>
  <i>Sistema pensado para que vender sea fácil y controlar tu inventario sea aún más fácil.</i>
</p>