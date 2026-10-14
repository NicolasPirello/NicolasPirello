<h1 align="center">Nicolás Pirello</h1>
<p align="center">
  <strong>AI Integration Engineer</strong><br>
  Buenos Aires, Argentina · Disponible para trabajo remoto
</p>

<p align="center">
  Diseño integraciones MCP y herramientas para agentes, y llevo sistemas a producción dirigiendo agentes de código con método.
</p>

<p align="center">
  <a href="https://nicolaspirello.com">nicolaspirello.com</a>
  ·
  <a href="https://www.linkedin.com/in/nicolas-pirello/">LinkedIn</a>
  ·
  <a href="mailto:dev@nicolaspirello.com">dev@nicolaspirello.com</a>
  ·
  <a href="https://nicolaspirello.com/cv-nicolas-pirello.pdf">CV</a>
</p>

Trabajo en integración de IA y sistemas agénticos. Diseño servidores MCP que conectan asistentes con servicios reales y dirijo agentes de código para desarrollar software que llega a producción.

Antes de programar trabajé años en análisis de datos y gestión dentro de una institución pública. Hoy desarrollo sistemas internos en esa misma área y soy el programador de [Forxite](https://forxite.com).

## Cómo trabajo

Uso IA en todos mis proyectos, con Cursor, agentes de código, MCPs, Skills y `AGENTS.md`. El problema, las decisiones, la revisión y lo que llega a producción quedan a mi cargo.

1. Especificar el problema y los límites
2. Dirigir agentes de código
3. Revisar cada cambio
4. Probar con tests y casos reales
5. Desplegar (Docker, IIS, Cloudflare)

## Integraciones de IA

Herramientas que los modelos pueden usar. El detalle de cada caso está en el sitio.

**[Balanz MCP](https://nicolaspirello.com/ia/balanz-mcp/)** · propio  
Servidor MCP de solo lectura que conecta una cuenta de Balanz con ChatGPT. No había un conector para eso: definí 18 herramientas tipadas, guié la identificación de los endpoints y lo dejé corriendo en Docker sobre un Mac mini. Python y FastMCP. No puede crear órdenes ni mover fondos.

**[YouTube Tools](https://nicolaspirello.com/ia/youtube-tools/)** · extendido  
Partí de [yt-dlp-mcp](https://github.com/kevinwatt/yt-dlp-mcp) y le sumé lo que le faltaba para que un modelo vea un video: miniaturas, cuadrículas cronológicas, fotogramas y transcripción local con Whisper large-v3 sobre MLX.

**[Reddit Trends MCP](https://nicolaspirello.com/ia/reddit-trends-mcp/)** · adaptado  
Partí de [reddit-mcp-server](https://github.com/eliasbiondo/reddit-mcp-server), que fallaba en mi entorno. Le agregué un transporte con navegador y proxies, lo validé en local y después lo dejé en Docker. Seis herramientas de lectura.

**[WebMCP](https://nicolaspirello.com/ia/webmcp/)** · propio  
Este portafolio expone herramientas para que los agentes de IA del navegador lo consulten sin leer el HTML.

## Software en producción

**[Sistema de Notificaciones Electrónicas](https://nicolaspirello.com/proyectos/notificaciones-electronicas/)** · solo  
Reemplazó un sistema anterior que fallaba y tenía menos funciones. Lo diseñé y construí solo, arquitectura incluida, y hoy lo usan unas 30.000 personas. React, ASP.NET Core y SQL Server, con un worker de correo desacoplado.

**[Ecosistema Forxite](https://nicolaspirello.com/proyectos/forxite/)** · solo y en equipo  
Ciberinteligencia y monitoreo de fraude. La plataforma interna nació de un scraper de Telegram (React, FastAPI, Telethon, PostgreSQL). Con el equipo Mynt hice el diseño, el frontend y la infraestructura de la plataforma para clientes. El sitio [forxite.com](https://forxite.com) lo desarrollé solo en Astro.

**[Sistema de Turnos y Visitas](https://nicolaspirello.com/proyectos/turnos-y-visitas/)** · solo  
Reemplazó la gestión de turnos que se hacía con Word y Gmail: agenda, asistente de programación, ingresos y egresos, y reportes. Lo hice solo y desde cero.

**[Sistema de Gestión de Salud Laboral](https://nicolaspirello.com/proyectos/gestion-salud-laboral/)** · equipo  
Diseñé la experiencia y la interfaz de un sistema de control médico del personal, la maqueté y la adapté a mobile. La lógica y el backend los hizo el resto del equipo.

Los sistemas institucionales usan nombres genéricos para proteger la privacidad.

## Stack

**IA y agentes**  
MCP (FastMCP, MCP SDK) · Cursor · Skills y AGENTS.md · RAG (FastAPI + Qdrant) · Whisper y MLX · OpenRouter, Ollama y LM Studio

**Frontend**  
React · TypeScript · Vite · TanStack Query · Zustand · Astro · CSS BEM

**Backend**  
Python · FastAPI · ASP.NET Core · Laravel · Node.js

**Datos**  
SQL Server · PostgreSQL · Redis · Qdrant

**Infraestructura**  
Docker · IIS · Cloudflare · GitLab CI

## Experiencia

**Programador — Forxite** · actualidad  
Convertí un scraper local de Telegram en la plataforma interna de monitoreo. Con el equipo Mynt hice el diseño, el frontend y la infraestructura de la plataforma para clientes, y desarrollé solo el sitio institucional.

**Desarrollador de software — Subsecretaría de Tecnología e Informática** · oct 2024 — actualidad  
Sistemas internos en producción con React, ASP.NET Core, Laravel y SQL Server: notificaciones electrónicas, turnos y visitas, y salud laboral. Prototipos de IA generativa (RAG) con FastAPI y Qdrant.

**Analista de datos y líder de equipo — Policía de la Ciudad** · 2020 — 2024  
Lideré equipos de análisis de datos en procesos masivos de más de 30.000 personas. Reportes institucionales y automatización con Excel y Power BI.

## Formación

- Desarrollador Web Full Stack · Digital House · 2022
- Desarrollo Web I y II · Google Actívate · 2023
- Introducción a Bases de Datos y SQL · EducaciónIT · 2022
- Español nativo · Inglés básico

## GitHub

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=NicolasPirello&show_icons=true&hide_border=true&title_color=111111&text_color=444444&icon_color=111111" alt="Estadísticas de GitHub de Nicolás Pirello" />
</p>

Más casos, con arquitectura y decisiones, en [nicolaspirello.com/proyectos](https://nicolaspirello.com/proyectos/).
