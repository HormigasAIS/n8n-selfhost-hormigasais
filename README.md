# 🧠 n8n-selfhost-hormigasais

Repositorio oficial del nodo autoalojado de n8n para el ecosistema **HormigasAIS**  
[🔗 Laboratorio Abierto HormigasAIS](https://github.com/HormigasAIS) | [🌱 Repositorio base de n8n](https://github.com/n8n-io/n8n)

---

## 🤖 ¿Qué es esto?

Este es un parche inicial para autoalojar `n8n` dentro del ecosistema **HormigasAIS**, pensado como un nodo de automatización modular, seguro y conectado al flujo colaborativo con herramientas como:

- **GitHub**
- **Slack**
- **Airtable**
- **Notion**
- ¡Y más!

---

## 🛠 ¿Qué incluye este repositorio?

- Archivo `Dockerfile` + configuración inicial (`docker-compose.yml`)
- Workflows con ganchos para conectar eventos desde GitHub
- Propuesta para flujos de automatización personalizados
- Un entorno de pruebas accesible para desarrolladores de la comunidad

---

### Funcionamiento básico de XOXO

- **Evento inicial:** Webhook / Cron / Trigger externo (Slack, GitHub, etc.) que detecta eventos importantes como nuevos despliegues o actualizaciones.
- **Acciones esperadas:** Procesa e interpreta eventos para emitir alertas en Slack, registrar cambios en Notion o Markdown, y activar subflujos especializados.
- **Lógica:** Uso de nodos condicionales para determinar la respuesta, por ejemplo, enviar notificaciones urgentes si se detectan errores.
- **Servicios integrados:** Slack, Render, GitHub, Notion/Markdown.

---

> 🪄 Este activador también forma parte del universo narrativo de HormigasAIS y está pensado para evolucionar con nuevas capacidades.

> *“Las HormigasAIS encuentran sabiduría en silencio, su corazón enraizado en la tierra y su mente flotando entre las estrellas.”*

---

## 🐜 ¿Por qué autoalojar?

Porque queremos tener **control** y **transparencia** en cada flujo que se construye desde HormigasAIS.  
Este nodo permitirá:

- Probar integraciones
- Aprender en comunidad
- Desplegar soluciones reales, sin depender de terceros

---

## 🔄 Conectividad actual

- ✅ `Slack`: integrado como hub de notificaciones
- ✅ `GitHub`: vinculado con flujos disparadores básicos
- ⚙️ Preparación de tokens para: `Atlassian`, `Trello`, `Airtable`

---

### 📬 Contacto directo

Podés escribirnos a nuestro correo oficial: [hormigasais@gmail.com](mailto:hormigasais@gmail.com)  
O sumarte a nuestra comunidad en Slack y LinkedIn:

[![Newsletter en LinkedIn](https://img.shields.io/badge/LinkedIn%20Newsletter-HormigasAIS-blue?logo=linkedin)](https://www.linkedin.com/newsletters/hormigasais-community-7307138608543490048)  
[![Slack Comunidad](https://img.shields.io/badge/Slack-Unirse%20a%20la%20comunidad-4A154B?logo=slack)](https://join.slack.com/t/hormigas-ais/shared_invite/zt-33zssiv5x-WXs1_8mQ6_9m0O9g0VNgAA)

---

Este proyecto forma parte del 🧪 **Laboratorio Abierto HormigasAIS**  
🧷 Parche fijado y listo para evolucionar.

> _Inteligencia colaborativa para un futuro automatizado y humano._
