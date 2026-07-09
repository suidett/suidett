<!-- HEADER BANNER -->
<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:092E20,50:1a6d3c,100:4169E1&height=200&section=header&text=Danilo%20Palavecino&fontSize=44&fontColor=ffffff&fontAlignY=35&desc=Full-Stack%20Developer%20%7C%20Python%20%C2%B7%20Django%20%C2%B7%20React&descSize=18&descAlignY=58" width="100%" />
</p>

<!-- ANIMATED TAGLINE -->
<p align="center">
  <a href="mailto:danilopalavecino.fuentealba01@gmail.com">
    <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=22&duration=3200&pause=900&color=1A6D3C&center=true&vCenter=true&width=680&lines=I+build+real+business+software;Multi-tenant+SaaS+%C2%B7+Billing+%C2%B7+APIs+%C2%B7+Automation;Construyo+software+de+negocio+que+sale+a+producci%C3%B3n" alt="typing" />
  </a>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/Django-092E20?style=for-the-badge&logo=django&logoColor=white" />
  <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white" />
  <img src="https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB" />
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white" />
  <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white" />
</p>

<p align="center">
  <img src="https://img.shields.io/badge/📍_Chile-333?style=flat-square" />
  <img src="https://img.shields.io/badge/💼_Available_for_freelance-1a6d3c?style=flat-square" />
  <img src="https://img.shields.io/badge/🌐_Fluent_written_English-4169E1?style=flat-square" />
</p>

---

## 👋 About me · Sobre mí

**EN** — Full-stack developer focused on **backend and business systems**. I design and ship
production software: multi-tenant SaaS, invoicing with PDF generation, inventory & management
systems, REST APIs, web scraping and automations. Clean architecture, data isolation, and things
that **actually work**.

**ES** — Desarrollador full-stack enfocado en **backend y sistemas de negocio**. Diseño y llevo a
producción software real: SaaS multi-tenant, facturación con PDF, gestión e inventario, APIs REST,
scraping y automatizaciones. Arquitectura limpia, aislamiento de datos y cosas que **funcionan de verdad**.

---

## 🚀 Featured — SaaS platform · Plataforma SaaS

### 🌐 Higestio — Multi-tenant SaaS · [higestio.com](https://higestio.com) &nbsp;✅ **live**

**EN** — A **live multi-tenant SaaS**: any business signs up and gets its own workspace
(subdomain + isolated database) for **electronic invoicing (Chile · SII)**, inventory, POS,
treasury and sales — all in one place.<br>
**ES** — **SaaS multi-tenant en vivo**: cada negocio se registra y obtiene su propio espacio
(subdominio + base aislada) para **boletas/facturas electrónicas (SII)**, inventario, caja y
ventas — todo en un solo lugar.

> 🚀 **10+ businesses onboarded in its first phase** · **+10 clientes reales en su primera fase.**

<p align="center">
  <a href="https://higestio.com"><img src="assets/higestio-hero.png" width="90%" /></a>
</p>
<p align="center"><a href="https://higestio.com"><b>🔗 higestio.com — probar en vivo</b></a></p>

---

### 🏢 Gestio — the system in production (a real tenant of Higestio)

**EN** — A full management & invoicing platform for distribution businesses: invoicing
(facturas & boletas), delivery notes (remitos), credit/debit notes, accounts receivable,
treasury with daily cash-close, expenses and analytics. **Running in production** for a real
business — and also built as a **multi-tenant SaaS** (a PostgreSQL schema per company with
subdomain routing).

**ES** — Plataforma completa de gestión y facturación para negocios de distribución: facturación,
remitos, notas de crédito/débito, cuenta corriente, tesorería con cierre de caja, gastos y
reportes. **En producción** para un negocio real — y construida además como **SaaS multi-tenant**
(un schema de PostgreSQL por empresa, con ruteo por subdominio).

**Highlights**
- 🧾 Invoicing, delivery notes & credit/debit notes · 💰 accounts receivable
- 🏦 Treasury + daily cash-close · 📊 real-time dashboards & reports
- 🔒 Multi-tenant — a PostgreSQL **schema per company** (`django-tenants`) + subdomain routing
- ⚙️ Production-ready: Docker · Gunicorn · WeasyPrint (PDF) · Sentry

<p align="center">
  <code>Python</code> · <code>Django</code> · <code>django-tenants</code> · <code>PostgreSQL</code> · <code>WeasyPrint</code> · <code>Docker</code>
</p>

<p align="center">
  <img src="assets/gestio-dashboard.png" width="49%" />
  <img src="assets/gestio-facturas.png" width="49%" />
</p>
<p align="center">
  <img src="assets/gestio-cuenta-corriente.png" width="49%" />
  <img src="assets/gestio-reportes.png" width="49%" />
</p>

> Real production system — **client names blurred for privacy**; real amounts and charts kept.<br>
> *Sistema real en producción — nombres de clientes difuminados por privacidad.*

<details>
<summary><b>📸 More modules · Más módulos</b></summary>
<br>
<p align="center">
  <img src="assets/gestio-remitos.png" width="49%" />
  <img src="assets/gestio-tesoreria.png" width="49%" />
</p>
<sub>Delivery notes (remitos) · treasury with bank balances & cash-close.</sub>
</details>

> <sub>🔒 Deployed as several instances (single-business & multi-tenant SaaS). Source is private —
> happy to walk through the code & architecture. · Desplegado en varias instancias; código privado,
> con gusto muestro el código y la arquitectura.</sub>

---

### ☕ Vittorio Coffee — Coffee-shop e-commerce

**EN** — E-commerce storefront for a specialty coffee roaster (*since 2017*): landing, product
catalog, cart & checkout.<br>
**ES** — Tienda online (e-commerce) para una cafetería de especialidad: landing, catálogo de
productos, carrito y checkout.

<p align="center"><img src="assets/vittorio-landing.png" width="82%" /></p>

<p align="center"><code>React</code> · <code>TypeScript</code></p>

---

## 🛠️ What I can help you with · En qué te puedo ayudar

| Area · Área | Tech |
|---|---|
| Backend & REST APIs | Django · FastAPI · Node/Express |
| Web apps & dashboards | React + Django/Python |
| Web scraping & data | Python · Playwright · BeautifulSoup |
| Automation & bots · Automatización | API integrations · Telegram/Discord bots |
| Databases · Bases de datos | PostgreSQL · MongoDB · MySQL |

---

<p align="center">
  <a href="mailto:danilopalavecino.fuentealba01@gmail.com">
    <img src="https://img.shields.io/badge/✉️_danilopalavecino.fuentealba01@gmail.com-1a6d3c?style=for-the-badge" />
  </a>
</p>

<p align="center"><i>Let's build something that ships. · Construyamos algo que salga a producción.</i></p>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:4169E1,50:1a6d3c,100:092E20&height=120&section=footer" width="100%" />
