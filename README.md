# 🤖 RecepBot – Sistema de Automatización para Clínicas y Negocios con Citas

> Automatización completa del ciclo de vida de una cita: desde la confirmación hasta la reactivación del cliente. Construido con **Make (Integromat)**, **Google Calendar**, **Gmail**, **Google Sheets** y **ChatGPT**.
>
> ---
>
> ## 📋 Descripción
>
> RecepBot es un sistema de automatización diseñado para clínicas, consultas y cualquier negocio que trabaje con citas. Elimina tareas manuales repetitivas, reduce las ausencias y mejora la experiencia del cliente sin intervención humana.
>
> El proyecto está compuesto por **4 escenarios de Make** totalmente conectados entre sí.
>
> ---
>
> ## ⚙️ Escenarios
>
> ### 1️⃣ RecepBot 1 – Confirmación instantánea de citas
> Cuando se crea una nueva cita en Google Calendar, se dispara automáticamente un email de confirmación al paciente/cliente con todos los detalles de la cita.
>
> **Herramientas:** Make · Google Calendar · Gmail · ChatGPT
>
> ---
>
> ### 2️⃣ RecepBot 2 – Recordatorio 24h antes (anti no-show)
> 24 horas antes de la cita, el sistema envía un recordatorio automático por email. Reduce drásticamente las ausencias y cancelaciones de última hora.
>
> **Herramientas:** Make · Google Calendar · Gmail
>
> ---
>
> ### 3️⃣ RecepBot 3 – Solicitud de reseña en Google tras la cita
> Una vez finalizada la cita, el sistema detecta que ha pasado la hora de la cita y envía un email personalizado solicitando una valoración en Google My Business. Mejora la reputación online del negocio en piloto automático.
>
> **Herramientas:** Make · Google Calendar · Gmail · ChatGPT
>
> ---
>
> ### 4️⃣ RecepBot 4 – Reactivación de clientes dormidos (60 días sin visita)
> El sistema analiza el histórico de citas en Google Sheets y detecta clientes que llevan más de 60 días sin visitar el negocio. Les envía automáticamente un email de recuperación personalizado.
>
> **Herramientas:** Make · Google Sheets · Gmail · ChatGPT
>
> ---
>
> ## 🛠️ Stack tecnológico
>
> | Herramienta | Uso |
> |---|---|
> | Make (Integromat) | Orquestación de todos los escenarios |
> | Google Calendar | Trigger de citas y detección de eventos |
> | Gmail | Envío de emails automáticos |
> | Google Sheets | Base de datos de clientes e histórico |
> | ChatGPT (OpenAI) | Generación de mensajes personalizados con IA |
>
> ---
>
> ## 👤 Autor
>
> **Juan José Lopez Vello**
> Especialista en Hiperautomatización e IA | n8n · Make · UiPath · Power Platform
> [LinkedIn](https://www.linkedin.com/in/jjlopezvello-ia/)
>
> ---
>
> *Proyecto desarrollado en junio 2026 como parte del portfolio de automatización.*
