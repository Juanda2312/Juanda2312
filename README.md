<div align="center">

# Hi, I'm Juan David Tapiero Montoya 👋
### Systems and Computer Engineering Student · Junior Full Stack & Mobile Developer

Studying Systems and Computer Engineering at **Universidad del Quindío** · Armenia, Colombia 🇨🇴

I build web backends with **Spring Boot**, frontends with **Angular** and **React**, and mobile apps with **Flutter**.
I enjoy turning data-structure theory into real, working products.

[![Portfolio](https://img.shields.io/badge/Portfolio-3FB950?style=for-the-badge&logo=githubpages&logoColor=white)](https://juanda2312.github.io/portafolio/)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/juan-david-tapiero-montoya-4834b02b3)
[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:juandavidtapiero8@gmail.com)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Juanda2312)

</div>

<details>
<summary><b>🇨🇴 Leer en español</b></summary>

<br>

### Hola, soy Juan David 👋
Estudiante de **Ingeniería de Sistemas y Computación** en la **Universidad del Quindío** (Armenia, Colombia) y desarrollador junior full stack y móvil. Construyo backends con **Spring Boot**, frontends con **Angular** y **React**, y apps móviles con **Flutter**. Me gusta convertir la teoría de estructuras de datos en productos reales que funcionan.

🌐 **Mira mi portafolio:** [juanda2312.github.io/portafolio](https://juanda2312.github.io/portafolio/)

#### 🏢 [PropTech](https://github.com/Juanda2312/PropTech) — Plataforma Inteligente de Gestión Inmobiliaria
Un sistema full stack que va más allá del CRUD: gestiona inmuebles, clientes, asesores, visitas y operaciones, y analiza el comportamiento comercial. Sus colecciones principales (tabla hash, árbol AVL, grafo, pila, colas y lista enlazada) son **implementaciones propias, sin `java.util`**.

- **Arquitectura en capas:** frontend en Angular 17 + API REST con Spring Boot 3 (Java 21), documentada con Swagger UI
- **Estructuras de datos con propósito:** AVL para precios y rankings, grafo + BFS para relaciones cliente–inmueble, pila para deshacer, colas FIFO y de prioridad para visitas y alertas
- **Motor de recomendaciones** con puntaje de 0 a 100, alertas automáticas y detección de comportamientos inusuales
- **PropBot:** asistente con IA (LLM vía OpenRouter) con datos en vivo de la plataforma
- **Dos roles:** panel de administración y portal del cliente, con persistencia en JSON

#### 🎮 [E-Commerce Marketplace Gamer](https://github.com/ShanT237/EcommerceProductosGamer) — Backend de Marketplace Multi-Vendedor
Un marketplace multi-vendedor de productos gaming (periféricos, mobiliario de setup, juegos físicos, licencias digitales y combos), desarrollado para *Programación Avanzada / Ingeniería de Software* en la Universidad del Quindío con **Domain-Driven Design** y **Clean Architecture**. Proyecto en equipo con [Santiago Torres](https://github.com/ShanT237) y [José Bedoya](https://github.com/thelegendsxv); el frontend en Angular está planeado.

- **Modelo de dominio rico:** raíces de agregado (`Producto`, `Compra`), objetos de valor como `record` de Java y constructores privados con métodos de fábrica que protegen las invariantes (stock nunca negativo, reembolso dentro de 48 h, una reseña por compra, productos exclusivos, preventas)
- **37 casos de uso** de compras, catálogo, combos, reseñas y puntos, wishlist y notificaciones, cuentas y reportes
- **Seguridad:** Spring Security con JWT (roles `COMPRADOR` / `VENDEDOR`), contraseñas con BCrypt y la identidad del usuario siempre tomada del token
- **API REST** documentada con Swagger, con búsqueda paginada de catálogo y reportes de ventas y más vendidos resueltos en la base de datos (H2 por defecto, perfil MariaDB)
- **Pruebas:** repositorios con `@DataJpaTest`, endpoints con seguridad (401 / 403 / 201) y una prueba de integración de punta a punta con `MockMvc`

#### 🛒 [ListaMercado](https://github.com/Juanda2312/ListaMercado) — App Offline para Organizar el Mercado
Una app Android 100% offline para organizar las compras: gestiona productos y supermercados, arma la lista con totales por supermercado y controla un presupuesto con el saldo restante.

- Búsqueda inteligente (sin distinguir mayúsculas ni tildes) y filtro por supermercado
- Dos vistas: **plana** y **por supermercado**, con tachado sincronizado
- Deslizar para quitar ítems con opción de deshacer, y presupuesto opcional (saldo en verde/rojo)
- APK de release firmado, sin permiso de internet y con datos guardados localmente

#### 📦 [Sistema de Gestión de Proveedores y Productos](https://github.com/ShanT237/relational-inventory-db) — Proyecto de Bases de Datos
Proyecto final de *Bases de Datos I* en la Universidad del Quindío: una aplicación de escritorio que registra qué proveedores pueden suministrar qué productos, hecha **sin frameworks** (biblioteca estándar de Python y librerías puntuales) sobre una base de datos normalizada en SQL Server. Proyecto en equipo con [Santiago Torres](https://github.com/ShanT237) y [José Bedoya](https://github.com/thelegendsxv).

- **Diseño relacional:** 9 tablas normalizadas, diagrama entidad-relación, diagrama relacional y diccionario de datos; la relación muchos a muchos proveedor–producto se resuelve con una tabla intermedia (precio y días de entrega)
- **SQL avanzado:** consultas `JOIN` de varias tablas y subconsultas, todas parametrizadas para evitar inyección SQL
- **Acceso por roles:** un administrador, usuarios tradicionales (CRUD completo) y esporádicos (solo consulta), con contraseñas cifradas con PBKDF2 y bitácora de entradas y salidas
- **Reportes en PDF** con filtros elegidos por el usuario, generados con `reportlab`
- **Arquitectura en tres capas** (presentación, lógica y datos) y despliegue de SQL Server con Docker

*Más abajo encuentras el stack tecnológico, certificaciones y estadísticas.*

</details>

---

## 🌐 Portfolio

My personal portfolio (bilingual ES/EN, plain HTML, CSS and JavaScript): **[juanda2312.github.io/portafolio](https://juanda2312.github.io/portafolio/)**

---

## 🚀 Featured Projects

### 🏢 [PropTech](https://github.com/Juanda2312/PropTech) — Smart Real Estate Management Platform
A full stack real estate system that goes beyond CRUD: it manages properties, clients, advisors, visits and deals, and analyzes commercial behavior. Its core collections (hash table, AVL tree, graph, stack, queues, linked list) are **custom implementations, without `java.util`**.

- **Layered architecture:** Angular 17 frontend + Spring Boot 3 REST API (Java 21), documented with Swagger UI
- **Data structures with a purpose:** AVL tree for price/ranking queries, graph + BFS for client–property relations, stack for undo, FIFO and priority queues for visits and alerts
- **Recommendation engine** that scores properties from 0 to 100 against each client's profile, plus automatic alerts and unusual-behavior detection
- **PropBot:** AI assistant (LLM via OpenRouter) that answers with live platform data, with different context for admins and clients
- **Two roles:** admin dashboard and client portal (favorites, history, interactions, recommendations), with JSON persistence between runs

![Java](https://img.shields.io/badge/Java_21-ED8B00?style=flat&logo=openjdk&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=flat&logo=spring-boot&logoColor=white)
![Angular](https://img.shields.io/badge/Angular_17-DD0031?style=flat&logo=angular&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat&logo=typescript&logoColor=white)
![Maven](https://img.shields.io/badge/Maven-C71A36?style=flat&logo=apachemaven&logoColor=white)
![Swagger](https://img.shields.io/badge/Swagger-85EA2D?style=flat&logo=swagger&logoColor=black)

---

### 🎮 [E-Commerce Marketplace Gamer](https://github.com/ShanT237/EcommerceProductosGamer) — Multi-Vendor Marketplace Backend
A multi-vendor marketplace for gaming products (peripherals, setup furniture, physical games, digital licenses and combos), built for *Advanced Programming / Software Engineering* at Universidad del Quindío with **Domain-Driven Design** and **Clean Architecture**. Team project with [Santiago Torres](https://github.com/ShanT237) and [José Bedoya](https://github.com/thelegendsxv); Angular frontend planned.

- **Rich domain model:** aggregate roots (`Producto`, `Compra`), value objects as Java records, private constructors with factory methods that enforce business invariants (stock never negative, refunds within 48 h, one review per purchase, exclusive products, pre-sales)
- **37 use cases** across purchases, catalog, combos, reviews and loyalty points, wishlists and notifications, accounts, and reports
- **Security:** Spring Security with JWT (role-based `COMPRADOR` / `VENDEDOR`), BCrypt-hashed passwords, and user identity always taken from the token
- **REST API** documented with Swagger, with paginated catalog search and sales / best-seller reports resolved in the database (H2 by default, MariaDB profile)
- **Testing:** `@DataJpaTest` repository tests, secured endpoint tests (401 / 403 / 201), and an end-to-end integration test with `MockMvc`

![Java](https://img.shields.io/badge/Java_21-ED8B00?style=flat&logo=openjdk&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=flat&logo=spring-boot&logoColor=white)
![Gradle](https://img.shields.io/badge/Gradle-02303A?style=flat&logo=gradle&logoColor=white)
![MariaDB](https://img.shields.io/badge/MariaDB-003545?style=flat&logo=mariadb&logoColor=white)
![JWT](https://img.shields.io/badge/JWT-000000?style=flat&logo=jsonwebtokens&logoColor=white)
![DDD](https://img.shields.io/badge/DDD_+_Clean_Architecture-7B2CBF?style=flat)

---

### 🛒 [ListaMercado](https://github.com/Juanda2312/ListaMercado) — Offline Grocery Shopping App
A 100% offline Android app to organize grocery shopping: manage products and supermarkets, build a shopping list with totals per supermarket, and track a budget with the remaining balance.

- Smart search (case and accent insensitive) and filtering by supermarket
- Two list views: **flat list** and **by supermarket**, with strike-through sync between them
- Swipe to remove items with undo, and an optional budget (remaining shown in green/red)
- Signed release APK, no internet permission, all data stored locally

![Flutter](https://img.shields.io/badge/Flutter-02569B?style=flat&logo=flutter&logoColor=white)
![Dart](https://img.shields.io/badge/Dart-0175C2?style=flat&logo=dart&logoColor=white)
![Android](https://img.shields.io/badge/Android-3DDC84?style=flat&logo=android&logoColor=white)
![Provider](https://img.shields.io/badge/State-Provider-5C2D91?style=flat)

---

### 📦 [Suppliers & Products Management System](https://github.com/ShanT237/relational-inventory-db) — Relational Database Project
Final project for *Databases I* at Universidad del Quindío: a desktop application that tracks which suppliers can provide which products, built **without frameworks** (Python standard library plus targeted libraries) on top of a normalized SQL Server database. Team project with [Santiago Torres](https://github.com/ShanT237) and [José Bedoya](https://github.com/thelegendsxv).

- **Relational design:** 9 normalized tables, ER diagram, relational diagram and data dictionary; the many-to-many supplier–product relation is resolved with a junction table (price and delivery days)
- **Advanced SQL:** multi-table `JOIN` queries and subqueries (e.g. suppliers priced above average, products with no supplier), all parameterized to prevent SQL injection
- **Role-based access:** one administrator, traditional users (full CRUD) and occasional users (read-only), with PBKDF2-hashed passwords and a login/logout audit log
- **PDF reports** with user-selected filters, generated with `reportlab`
- **Three-layer architecture** (presentation, business logic, data access) and a Docker-based setup for SQL Server

![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![Tkinter](https://img.shields.io/badge/Tkinter-GUI-3776AB?style=flat)
![SQL Server](https://img.shields.io/badge/SQL_Server-CC2927?style=flat&logo=microsoftsqlserver&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white)

---

## 🛠️ Tech Stack

**Languages**
![Java](https://img.shields.io/badge/Java-ED8B00?style=flat&logo=openjdk&logoColor=white)
![Dart](https://img.shields.io/badge/Dart-0175C2?style=flat&logo=dart&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat&logo=typescript&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=flat&logo=c%2B%2B&logoColor=white)
![Elixir](https://img.shields.io/badge/Elixir-4B275F?style=flat&logo=elixir&logoColor=white)

**Backend**
![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=flat&logo=spring-boot&logoColor=white)
![Maven](https://img.shields.io/badge/Maven-C71A36?style=flat&logo=apachemaven&logoColor=white)
![Gradle](https://img.shields.io/badge/Gradle-02303A?style=flat&logo=gradle&logoColor=white)
![REST API](https://img.shields.io/badge/REST_API-009688?style=flat)

**Frontend & Mobile**
![Angular](https://img.shields.io/badge/Angular-DD0031?style=flat&logo=angular&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=flat&logo=react&logoColor=61DAFB)
![Flutter](https://img.shields.io/badge/Flutter-02569B?style=flat&logo=flutter&logoColor=white)

**Databases**
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat&logo=mysql&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-336791?style=flat&logo=postgresql&logoColor=white)
![SQL Server](https://img.shields.io/badge/SQL_Server-CC2927?style=flat&logo=microsoftsqlserver&logoColor=white)
![MariaDB](https://img.shields.io/badge/MariaDB-003545?style=flat&logo=mariadb&logoColor=white)

**DevOps & Tools**
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat&logo=git&logoColor=white)
![Android Studio](https://img.shields.io/badge/Android_Studio-3DDC84?style=flat&logo=androidstudio&logoColor=white)

**Concepts**
Data Structures & Algorithms · REST API Design · DDD & Clean Architecture · JWT Security · Unit & Integration Testing · OOP · Relational Databases

---

## 📚 Certifications

- 🏆 **Full Stack Empresarial con Spring Boot y Angular** — Dev Senior Code (2025)
- 🏆 **SQL: Curso completo de Bases de Datos** — Udemy (2025)

---

## 📈 GitHub Stats

<div align="center">

[![](https://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=Juanda2312&theme=tokyonight)](https://github.com/Juanda2312)

[![](https://github-profile-summary-cards.vercel.app/api/cards/repos-per-language?username=Juanda2312&theme=tokyonight)](https://github.com/Juanda2312)
[![](https://github-profile-summary-cards.vercel.app/api/cards/most-commit-language?username=Juanda2312&theme=tokyonight)](https://github.com/Juanda2312)

[![](https://github-profile-summary-cards.vercel.app/api/cards/stats?username=Juanda2312&theme=tokyonight)](https://github.com/Juanda2312)
[![](https://github-profile-summary-cards.vercel.app/api/cards/productive-time?username=Juanda2312&theme=tokyonight&utcOffset=-5)](https://github.com/Juanda2312)

![GitHub Streak](https://streak-stats.demolab.com?user=Juanda2312&theme=tokyonight&hide_border=true)

</div>

---

## 🌐 Languages

- 🇨🇴 Spanish — Native
- 🇺🇸 English — B2

---

<div align="center">

⭐ Thanks for stopping by! Feel free to check my repos or reach out.

</div>
