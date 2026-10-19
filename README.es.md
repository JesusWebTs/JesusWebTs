<p align="right">
  <a href="https://github.com/JesusWebTs"><img src="https://img.shields.io/badge/EN-English-30363D?style=for-the-badge" /></a>
  <a href="https://github.com/JesusWebTs/JesusWebTs/blob/main/README.es.md"><img src="https://img.shields.io/badge/ES-Espa%C3%B1ol-38BDF8?style=for-the-badge" /></a>
</p>

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0f2027,50:203a43,100:2c5364&height=200&section=header&text=Richard%20Mart%C3%ADnez&fontSize=56&fontColor=ffffff&fontAlignY=38&desc=Full%20Stack%20Software%20Engineer%20Sr.&descAlignY=58&descSize=20" width="100%" />

<a href="https://jesusweb.vercel.app/">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=22&pause=1000&color=38BDF8&center=true&vCenter=true&width=640&lines=React+%C2%B7+Next.js+%C2%B7+React+Native;Node.js+%C2%B7+NestJS+%C2%B7+GraphQL;Productos+en+producci%C3%B3n%2C+web+%2B+m%C3%B3vil;AI-augmented+dev+con+Claude+Code" alt="Typing SVG" />
</a>

<p>
  <a href="https://www.linkedin.com/in/jesusweb/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" /></a>
  <a href="https://jesusweb.vercel.app/"><img src="https://img.shields.io/badge/Portfolio-jesusweb.vercel.app-111827?style=for-the-badge&logo=vercel&logoColor=white" /></a>
  <a href="mailto:jesus.jslink@gmail.com"><img src="https://img.shields.io/badge/Email-jesus.jslink%40gmail.com-EA4335?style=for-the-badge&logo=gmail&logoColor=white" /></a>
</p>

🌐 **[jesusweb.vercel.app](https://jesusweb.vercel.app/)** · 📧 **[jesus.jslink@gmail.com](mailto:jesus.jslink@gmail.com)**


</div>

## 👋 Sobre mí

Ingeniero de software **Full Stack Sr.** con más de 5 años construyendo sistemas escalables, modulares y enfocados en seguridad en **web, móvil y cloud**. He llevado a producción plataformas CMS, soluciones B2B y apps móviles en Android e iOS.

Fuera del código: modelo bases de datos, levanto requerimientos con clientes, estimo tiempos y presupuestos, lidero equipos y hago pruebas en campo para entender el producto desde el usuario.

- 🚗 **La Wawa** — Full Stack Sr. (2022 – hoy): CMS, B2B, Driver App y Rider App
- 🎨 **UXVerse Studio** — Full Stack (2023 – 2026): arquitectura, estimación y entrega para clientes
- 🧭 **Kromatics Design** — Líder de equipo (2023 – 2025): retos técnicos, interlocución con C-level, kit UI propio
- 🤖 Trabajo con **agentes de IA** (Claude Code, skills y orquestación) como parte del flujo de desarrollo

## 🏗️ Arquitectura que diseñé

<table>
<tr>
<td width="33%" valign="top">

### ⚙️ Generador de interfaces
Un contrato de tipos que se **genera leyendo el código de la API** (AST de los resolvers) y se distribuye a **3 webapps y 2 apps móviles** a la vez. El front nunca escribe tipos de la API a mano, y un cambio en el back llega tipado a todos los proyectos con un comando.

</td>
<td width="33%" valign="top">

### 🎨 UI v2 / design system
Creé la **UI v2 de La Wawa**: una librería de componentes abstractos con temas, skeletons y error boundaries por defecto, compartida por CMS, B2B y el portal de partners. Lo que aprendí diseñándola me sirvió para construir desde cero las interfaces de **DaCapo** y **Rewrite AI**.

</td>
<td width="33%" valign="top">

### 🤖 Arquitectura de agentes de IA
**AIDevCell**: un modelo de trabajo donde un gestor divide el requerimiento, un agente escribe, otro distinto revisa, se corren gates de lint/TS y cada commit queda atribuido a su agente. Skills para relevo entre sesiones, PRs, ClickUp y Slack.

</td>
</tr>
</table>

## 🛠️ Stack

<p align="center">
  <img src="https://skillicons.dev/icons?i=ts,js,react,nextjs,redux,nodejs,nestjs,express,graphql,mongodb,postgres,firebase,aws,docker,kubernetes,jest,html,css,git,vercel,redis,prisma,materialui,cypress,tailwind,vite,python,opencv,unity,cs,blender&perline=11" />
</p>

<p align="center">
  <img src="https://img.shields.io/badge/React_Native-20232A?style=flat-square&logo=react&logoColor=61DAFB" />
  <img src="https://img.shields.io/badge/Expo-000020?style=flat-square&logo=expo&logoColor=white" />
  <img src="https://img.shields.io/badge/Zustand-443E38?style=flat-square&logo=react&logoColor=white" />
  <img src="https://img.shields.io/badge/Prisma-2D3748?style=flat-square&logo=prisma&logoColor=white" />
  <img src="https://img.shields.io/badge/Stripe-635BFF?style=flat-square&logo=stripe&logoColor=white" />
  <img src="https://img.shields.io/badge/Claude_Code-D97757?style=flat-square&logo=anthropic&logoColor=white" />
</p>

## 🤝 Más allá del código

<table>
<tr>
<td width="50%" valign="top">

### 🌿 Versionado y flujo con GitHub
- Flujo de ramas `develop` → `staging` → `main` con PRs por feature y PRs hermanos para hotfixes
- Code review en cada PR (humano + CodeRabbit) y resolución de conflictos entre equipos
- Versionado semántico de paquetes npm (changesets / semantic-release) y changelogs por release
- Commits atribuibles: cada cambio dice quién lo hizo, persona o agente
- CI con lint y type-check como condición para mergear

</td>
<td width="50%" valign="top">

### 🧭 Gestión y negocio
- Levantamiento y validación de requerimientos directamente con clientes
- Estimación de presupuestos y tiempos de entrega
- Liderazgo de equipo y acompañamiento a otros desarrolladores
- Interlocución con C-level y comunicación del estado del proyecto
- Modelado de bases de datos, aportes en UI/UX y pruebas en campo con usuarios reales

</td>
</tr>
</table>

## 🚀 Productos que he construido

> El código es privado (son productos comerciales), pero están en producción:

| Producto | Qué es | Stack |
| --- | --- | --- |
| 🚗 **[La Wawa](https://cms.enwawa.com/es)** | Transporte corporativo: CMS de flota, rutas e incidencias, portal [B2B](https://b2b.enwawa.com/es), portal de partners, [Driver App](https://play.google.com/store/apps/details?id=com.la_wawa.wawadriverapp) con validación por QR y [Rider App](https://play.google.com/store/apps/details?id=com.wawainc.lawawa). Tiempo real, geolocalización en segundo plano y dos UI kits como paquetes npm | **Back:** NestJS · GraphQL (Apollo) · Prisma · MongoDB · Socket.IO · Redis · Firebase · Stripe · Twilio<br>**Web:** Next.js · Apollo Client · next-intl · Ant Design · Tailwind · Radix · Storybook · Cypress<br>**Mobile:** Expo · React Native · Expo Router · Maps · NativeWind · TanStack Query |
| 🏠 **[PartaRentals](https://partarentals.com/)** | Marketplace de alquiler mensual multi-rol (propietarios, inquilinos, agentes) y multipaís, con servidores y bases separados por país, pagos recurrentes, comisiones y [backoffice](https://backoffice.partarentals.com/login) | **Back:** NestJS · GraphQL (Apollo) · Mongoose · MongoDB · S3 · Google OAuth · Puppeteer<br>**Web:** Next.js · Tailwind · Radix · Redux Toolkit · next-intl · Leaflet<br>**Backoffice:** React · Redux Toolkit · Bootstrap · ECharts · FullCalendar |
| ✍️ **Rewrite AI** | Extensión de Chrome con IA que reescribe el texto seleccionado en distintos estilos: traducción, humanización y planes por suscripción. Backend propio y portal de administración | **IA:** Claude · OpenRouter · Groq · OpenAI<br>**Back:** NestJS · TypeORM · PostgreSQL · BullMQ · Redis · Socket.IO · Stripe · S3<br>**Front:** React · MUI · Zustand · Chrome MV3 · Next.js · HeroUI · Tailwind<br>**Infra:** Docker |
| 🎹 **DaCapo** | Aprende piano desde videos tipo Synthesia: un **pipeline de visión por computadora** (detección de manos y teclas) transcribe el video a notas, con **98,85 % de acierto** en Für Elise. El motor de práctica dibuja la cascada, la hace sonar, la pasa a pentagrama y **verifica por MIDI** lo que tocas. Incluye API, worker, panel de auditoría del pipeline, SDK compartido y extensión de Chrome para la ingesta de videos | **Back:** NestJS · TypeORM · PostgreSQL · Socket.IO · S3 · JWT<br>**Visión:** Python · OpenCV · MediaPipe · NumPy<br>**Front:** React · Vite · Tailwind · Zustand · Tone.js MIDI<br>**Infra:** Docker · Chrome MV3 |
| 🎟️ **[Comercio B2B](https://comerciob2b.onrender.com/)** | Fidelización white-label con puntos, sellos y rifas, y tarjetas en **Google y Apple Wallet** que se actualizan solas. Tres apps: comercio, cliente con lector QR y admin interno | **Back:** NestJS · TypeORM · PostgreSQL · BullMQ · Redis · Socket.IO · S3 · Twilio · firma de pases Wallet<br>**Front:** React · Vite · Tailwind · Radix/shadcn · MUI · Zustand · Recharts |
| 🅿️ **[Estacionate](https://estacionate.io/)** | Valet gratuito para comercios y [Estacionate+](https://play.google.com/store/apps/details?id=com.estacionateplus.records), parquímetros con pago por tiempo: app de usuario, app del personal de campo y panel administrativo con mapas | **Back:** NestJS · TypeORM · PostgreSQL · BullMQ · Redis · Socket.IO · S3 · Twilio · Docker<br>**Web:** Next.js · HeroUI · React · Vite · MUI · TanStack Query · Mapbox<br>**Mobile:** Expo · React Native · Redux Toolkit · Vision Camera · OneSignal |
| 📊 **RG Asesores** · **StarStats** | Plataformas a medida para clientes | React · Node |

### 🤖 Productos propios con IA

| Proyecto | Qué es | Stack |
| --- | --- | --- |
| 🧠 **AIDevCell** | Plataforma multi-agente organizada por departamentos: convierte un requerimiento en trabajo ejecutable, analiza un repositorio y produce hallazgos y un plan de mantenimiento, y ejecuta tareas de código en un entorno aislado, generando parches que ningún proceso automático aplica sin revisión | NestJS · React · Vite · Tailwind · Socket.IO · Claude (Anthropic SDK) · monorepo pnpm · contratos JSON Schema · Vitest |
| 📝 **Sistema de agentes en Markdown** | Un equipo de agentes sobre **Claude Code** construido solo con archivos `.md` (skills, routers de contexto y `CLAUDE.md`), sin código de orquestación. Un gestor trocea el requerimiento, un agente escribe y otro revisa. Toma tareas de ClickUp, refina, deja relevos entre sesiones, sincroniza ramas, corre los gates de lint y TS, abre PRs, atiende a CodeRabbit, entrega en ClickUp y reporta en Slack | Claude Code · Skills · Markdown · GitHub CLI · ClickUp · Slack |
| 🔎 **AiBusinessExplorer** | Embudo de prospección: barre negocios por zona, detecta los que no tienen web o la tienen caída o insegura, los enriquece con redes e imágenes, los califica con IA solo cuando hace falta y entrega el pedido a **AIDevCell**, que construye el sitio | NestJS · MongoDB · Claude · React · Vite · Tailwind · Overture Maps |

### 🎮 Juegos

| Juego | Qué es | Stack |
| --- | --- | --- |
| 🎨 **Splash Tag: The Paint Terror** | Party game multijugador asimétrico: un cazador casi ciego persigue a 4 corredores que solo se ven cuando alguien los mancha de pintura, y los corredores se delatan entre ellos. Partidas de 90 s, modo local y online con salas de Steam, bots de 4 niveles y mapas generados | Unity 6 · C# · URP · Mirror · Steamworks · Blender |

## 📈 Actividad

<p align="center">
  <img src="https://streak-stats.demolab.com?user=JesusWebTs&mode=weekly&theme=tokyonight&hide_border=true&date_format=j%20M%5B%20Y%5D" />
</p>

<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/JesusWebTs/JesusWebTs/output/github-snake-dark.svg" />
    <img src="https://raw.githubusercontent.com/JesusWebTs/JesusWebTs/output/github-snake.svg" />
  </picture>
</p>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:2c5364,50:203a43,100:0f2027&height=100&section=footer" width="100%" />
