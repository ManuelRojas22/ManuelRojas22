<h1 align="center">Hola, soy Manuel Rojas 👋</h1>
<h3 align="center">Desarrollador Web Full Stack · Django · Python · MySQL · Medellín, Colombia</h3>

<br>

<p align="center">
  <img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&size=22&duration=3500&pause=1000&center=true&vCenter=true&width=750&lines=Django+%26+Python+Developer;Full+Stack+Web+Developer;MySQL+%26+Database+Design;CSS+%26+Responsive+UI+Enthusiast;Siempre+aprendiendo+nuevas+tecnologías" />
</p>

---

## Sobre mí

Soy Manuel Rojas, desarrollador web Full Stack con sede en **Medellín, Colombia**. Me apasiona construir aplicaciones que resuelvan problemas reales: desde sistemas de autenticación robustos hasta dashboards de datos urbanos en tiempo real para mi ciudad.

Mi enfoque está en el backend con **Python y Django**, pero disfruto igual el lado del frontend: construyo interfaces limpias, responsivas y bien animadas con **CSS puro**, sin depender innecesariamente de librerías. Creo que entender los fundamentos hace mejores desarrolladores.

- 🛠️ Construyo aplicaciones completas con **Django 6**, **Flask** y **MySQL 8**.
- 🎨 Interfaces responsivas en **CSS3** puro — Flexbox, custom properties, animaciones sin JS.
- 🔐 Implementé autenticación completa desde cero: login, registro, cambio y recuperación de contraseña con tokens UUID.
- 🌆 Trabajo en proyectos con impacto real para Medellín: movilidad urbana, salud digital, educación.
- 📡 Integro APIs externas: TomTom Traffic, Google Gemini, OpenStreetMap/Nominatim, ArcGIS.
- 📚 Actualmente profundizando en **React** y arquitecturas modernas de frontend.

---

## Tecnologías

<p align="center">
  <img src="https://skillicons.dev/icons?i=html,css,js,python,django,flask,mysql,git,github,vscode" />
</p>

---

## Stack que domino

| Capa           | Tecnologías                                              |
|----------------|----------------------------------------------------------|
| Frontend       | HTML5, CSS3 (Flexbox, custom properties, animaciones), JavaScript |
| Backend        | Python 3.14, Django 6, Flask                             |
| Base de datos  | MySQL 8+ (vistas, triggers, esquemas SQL manuales)       |
| Autenticación  | Django Auth, tokens UUID, formularios personalizados     |
| APIs externas  | TomTom Traffic v5, Google Gemini, Nominatim, ArcGIS      |
| Herramientas   | Git, GitHub, VS Code, mysqlclient, python-dotenv         |

---

## Proyectos destacados

### 🔐 [Auth — Sistema de autenticación Django](https://github.com/ManuelRojas22/auth)

Sistema completo de autenticación con **Django 6 + MySQL**. Diseño SAAS responsivo en modo claro, **sin ninguna dependencia de JavaScript**. Incluye login, registro, cambio de contraseña y recuperación por email con tokens UUID seguros.

**Características principales:**
- 6 vistas · 5 formularios personalizados · 7 rutas
- Recuperación de contraseña con tokens UUID + expiración automática
- Triggers MySQL para normalización de datos al insertar usuarios
- Vistas SQL reutilizables: `vw_active_users`, `vw_valid_reset_tokens`
- 20 objetos flotantes animados en CSS puro, con trayectorias y duraciones independientes
- Stack: `Python 3.14 · Django 6.0.5 · MySQL 8 · CSS3 · mysqlclient`

**Estructura del proyecto:**
```
auth/
├── auth_project/           # Configuración principal Django
│   ├── settings.py         # Config DB, email, apps instaladas
│   ├── urls.py             # Enrutamiento raíz
│   └── wsgi.py
├── accounts/               # App principal de autenticación
│   ├── models.py           # Modelo de token de recuperación (UUID)
│   ├── forms.py            # LoginForm, RegisterForm, PasswordForms...
│   ├── views.py            # login, register, change_password, reset_password...
│   ├── urls.py             # 7 rutas de autenticación
│   └── templates/
│       └── accounts/
│           ├── login.html
│           ├── register.html
│           ├── change_password.html
│           ├── reset_password.html
│           └── reset_password_confirm.html
├── static/
│   └── css/
│       └── auth.css        # Animaciones CSS puras, diseño SAAS
├── sql/
│   ├── triggers.sql        # Triggers de normalización MySQL
│   └── views.sql           # vw_active_users, vw_valid_reset_tokens
├── requirements.txt
└── manage.py
```

---

### 🧠 [PsyAI Connect](https://github.com/ArleyRojo/PsyAI-Connect) *(colaboración)*

Plataforma de chatbot de psicología impulsada por **Google Gemini**, con backend MySQL/XAMPP. Desarrollada como colaboración con foco en backend, integración de IA y resiliencia de API keys.

**Características principales:**
- Chat conversacional con contexto psicológico usando `gemini-2.5-flash-lite`
- Rotación automática de API keys para evitar agotamiento de cuota gratuita
- Variable de entorno `GEMINI_API_KEYS` con múltiples claves separadas por coma
- Script `setup_install.py` para instalación automatizada con credenciales pre-llenadas
- Backend MySQL con sesiones de usuario y historial de conversaciones
- Stack: `Flask · Python · MySQL · Google Gemini API · XAMPP`

**Estructura del proyecto:**
```
PsyAI-Connect/
├── app/
│   ├── __init__.py
│   ├── routes.py               # Rutas Flask: chat, login, registro
│   ├── models.py               # Modelos de usuario y sesión MySQL
│   └── services/
│       └── chatbot_service.py  # Lógica Gemini + rotación de API keys
├── templates/
│   ├── index.html              # Interfaz del chat
│   ├── login.html
│   └── register.html
├── static/
│   ├── css/
│   └── js/
├── config.py                   # Variables de entorno, config DB
├── setup_install.py            # Instalación automatizada
├── requirements.txt
└── run.py
```

---

## Estadísticas de GitHub

<p align="center">
  <img height="180em" src="https://github-readme-stats.vercel.app/api?username=ManuelRojas22&show_icons=true&theme=tokyonight&hide_border=true"/>
  <img height="180em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=ManuelRojas22&layout=compact&theme=tokyonight&hide_border=true"/>
</p>

<p align="center">
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=ManuelRojas22&theme=tokyonight&hide_border=true"/>
</p>

<p align="center">
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=ManuelRojas22&theme=tokyo-night&hide_border=true" />
</p>

---

## Actualmente aprendiendo

```text
⚛️  React — componentes, hooks, estado global
🎨  Diseño UI/UX — sistemas de diseño, accesibilidad
⚡  Optimización Web — performance, lazy loading, Core Web Vitals
🏗️  Buenas prácticas Full Stack — arquitectura limpia, escalabilidad
🚀  Despliegue — Railway, Render, configuración de producción Django
```

---

## Objetivos

- Desplegar aplicaciones Django en producción (Railway, Render, VPS).
- Construir un dashboard con React + Django REST Framework.
- Contribuir a proyectos open source relacionados con educación y ciudades inteligentes.
- Crear proyectos escalables y mantenibles con código limpio.

---

## Contacto

<p align="center">
  <a href="mailto:manuelalejandro.rojasquintero@gmail.com">
    <img src="https://img.shields.io/badge/Gmail-manuelalejandro.rojasquintero-red?style=for-the-badge&logo=gmail&logoColor=white">
  </a>
  &nbsp;
  <a href="https://github.com/ManuelRojas22">
    <img src="https://img.shields.io/badge/GitHub-ManuelRojas22-181717?style=for-the-badge&logo=github&logoColor=white">
  </a>
</p>

---

<p align="center">
  <i>"El aprendizaje constante es la mejor herramienta de un desarrollador."</i>
</p>
