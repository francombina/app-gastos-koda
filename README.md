# 🐶 KodaCoin — Seguimiento de gastos

Aplicación web para el control y análisis de gastos personales o en pareja, diseñada para eliminar la carga manual mediante automatización e integración de APIs.

🔗 **[Abrir Aplicación](https://francombina.github.io/KodaCoin/)**

## 🏗️ Arquitectura de Datos (ETL)
1. **Ingesta Automatizada:** Captura de movimientos y transacciones integrando la API de Mercado Pago y carga rápida desde el dispositivo.
2. **Backend Serverless & Validación:** Procesamiento, categorización y reglas de negocio ejecutadas mediante Google Apps Script.
3. **Almacenamiento en la Nube:** Consolidación estructurada en Google Sheets operando como base de datos relacional ligera en tiempo real.
4. **Privacidad y Seguridad:** Los endpoints del backend y las hojas de cálculo se encuentran desacoplados y protegidos fuera del código público del cliente.

## 🛠️ Stack Técnico
* **Frontend:** HTML5, CSS3, JavaScript (Diseño Mobile-First)
* **Backend & Automatización:** Google Apps Script, API REST de Mercado Pago
* **Base de Datos:** Google Sheets Cloud
