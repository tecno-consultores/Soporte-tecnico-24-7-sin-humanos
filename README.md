# Soporte Técnico 24/7 sin humanos: Revolucionando el Helpdesk del ISP con N8N y LLMs 🚀

Video de la presentacion en Youtube: https://www.youtube.com/watch?v=BHKMhNaxniM

Este repositorio contiene las diapositivas y el material de apoyo de la presentación técnica **"Soporte técnico 24/7 sin humanos"**, orientada a transformar radicalmente las operaciones de Nivel 1 (L1) en Proveedores de Servicios de Internet (ISPs) mediante la adopción de una cultura NetDevOps.

---

## 🔗 Enlace al Proyecto Principal: ISP-Copilot

Esta presentación es el marco teórico y arquitectónico del proyecto de código abierto **ISP-Copilot**. 

Si estás buscando el código fuente, los flujos de n8n, la configuración de contenedores Docker y la documentación técnica para implementar este sistema en tu propia red, dirígete al repositorio oficial principal:

👉 **[github.com/tecno-consultores/ISP-Copilot](https://github.com/tecno-consultores/ISP-Copilot)**

ISP-Copilot es 100% *self-hosted*, diseñado para garantizar la privacidad de los datos sin depender de nubes de terceros, utilizando herramientas como MikroTik, Zabbix, Qdrant y modelos de lenguaje (LLMs) locales.

---

## 📖 Contenido de la Presentación

La presentación está estructurada para guiar a los ingenieros, líderes de NOC y dueños de ISPs a través del problema de la saturación del soporte tradicional, hacia una solución orquestada e inteligente. 

Los temas abordados en este material incluyen:

*   **El Cuello de Botella del Nivel 1:** Análisis de los problemas de escalabilidad humana frente a fallas masivas, tareas repetitivas (desbloqueos PPPoE) y diagnósticos a ciegas.
*   **Orquestación Cognitiva:** Diagrama detallado de la arquitectura. Cómo **n8n** actúa como el núcleo orquestador conectando los sentidos (Zabbix/Graylog), el cerebro (LLM local + Qdrant RAG) y los brazos ejecutores (MikroTik/Ansible).
*   **Los 4 Pilares Operativos:**
    1.  **Bot de Atención (Nivel 0):** Respuestas instantáneas y mitigación de avalanchas vía WhatsApp.
    2.  **Copiloto NOC (L1/L2):** Ejecución guiada de diagnósticos complejos sin terminales abiertas.
    3.  **Triage Autónomo:** Reacción inmediata a eventos de red en madrugadas y feriados.
    4.  **Automatización Programada:** Auditorías y respaldos de infraestructura silenciosos.
*   **Ejecución Segura (Allowlist):** Cómo el sistema utiliza el *Function Calling* para auditar BGP, revisar PPPoE y diagnosticar cortes de fibra ópticos desde la OLT sin inventar comandos.
*   **Políticas de Seguridad y Gobernanza:** Explicación del mecanismo **Human-in-the-loop** (validación vía Telegram/Slack) y el **Safe Mode automatizado** en MikroTik para evitar aislamientos catastróficos.
*   **Democratización del NOC:** El enfoque 100% de código abierto para devolver el control operativo al ISP.

---

## 📥 Cómo ver el material

Puedes visualizar la presentación directamente desde GitHub abriendo el archivo PDF incluido en la raíz de este repositorio:

*   [📄 Ver Presentación: Soporte-tecnico-24-7-sin-humanos.pdf](./Soporte-tecnico-24-7-sin-humanos.pdf)

*(Si descargas o clonas el repositorio, puedes abrir el PDF con cualquier visor estándar o navegador web).*

---

## 👨‍💻 Ponente y Autor

**Jesús Palencia**
*SRE (Site Reliability Engineer) en Tecno Consultores.*
Fiel defensor del Software Libre, desarrollador comunitario y especialista en infraestructura de redes y ciberseguridad. 

*   **Contacto Comercial/Soporte:** ventas@tecnoconsultores.net
*   **Teléfono:** +58-412-488-85-08

---

*Desarrollado por y para la comunidad de telecomunicaciones. Transformando la "fuerza bruta" en inteligencia automatizada.*
