<!-- github-banner.svg -->
<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 1280 640" width="1280" height="640">
  <!-- Fondo con gradiente industrial-tecnológico -->
  <defs>
    <linearGradient id="bgGradient" x1="0%" y1="0%" x2="100%" y2="100%">
      <stop offset="0%" style="stop-color:#0f172a;stop-opacity:1" />
      <stop offset="50%" style="stop-color:#1e293b;stop-opacity:1" />
      <stop offset="100%" style="stop-color:#0f172a;stop-opacity:1" />
    </linearGradient>
    
    <linearGradient id="accentGradient" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%" style="stop-color:#3b82f6;stop-opacity:1" />
      <stop offset="100%" style="stop-color:#8b5cf6;stop-opacity:1" />
    </linearGradient>
    
    <filter id="glow">
      <feGaussianBlur stdDeviation="3" result="coloredBlur"/>
      <feMerge>
        <feMergeNode in="coloredBlur"/>
        <feMergeNode in="SourceGraphic"/>
      </feMerge>
    </filter>
  </defs>
  
  <!-- Fondo -->
  <rect width="100%" height="100%" fill="url(#bgGradient)"/>
  
  <!-- Patrón de circuitos/red industrial -->
  <g opacity="0.1" stroke="#60a5fa" stroke-width="1">
    <path d="M0,320 L1280,320" />
    <path d="M640,0 L640,640" />
    <circle cx="320" cy="160" r="40" fill="none"/>
    <circle cx="960" cy="480" r="40" fill="none"/>
    <path d="M200,200 Q320,160 440,200" fill="none"/>
    <path d="M840,440 Q960,480 1080,440" fill="none"/>
  </g>
  
  <!-- Engranaje izquierdo (representando industria) -->
  <g transform="translate(200,320)">
    <circle cx="0" cy="0" r="60" fill="#1e293b" stroke="url(#accentGradient)" stroke-width="3"/>
    <circle cx="0" cy="0" r="20" fill="#3b82f6"/>
    <!-- Dientes del engranaje -->
    <g fill="#60a5fa">
      <rect x="-55" y="-8" width="30" height="16" transform="rotate(0)"/>
      <rect x="-55" y="-8" width="30" height="16" transform="rotate(45)"/>
      <rect x="-55" y="-8" width="30" height="16" transform="rotate(90)"/>
      <rect x="-55" y="-8" width="30" height="16" transform="rotate(135)"/>
    </g>
  </g>
  
  <!-- Chip/IA centro (transición) -->
  <g transform="translate(640,320)" filter="url(#glow)">
    <rect x="-50" y="-50" width="100" height="100" rx="15" fill="#1e293b" stroke="url(#accentGradient)" stroke-width="3"/>
    <!-- Circuitos internos -->
    <g stroke="#8b5cf6" stroke-width="2">
      <path d="M-30,-30 L30,30" />
      <path d="M-30,30 L30,-30" />
      <circle cx="-20" cy="0" r="5" fill="#8b5cf6"/>
      <circle cx="20" cy="0" r="5" fill="#8b5cf6"/>
      <circle cx="0" cy="-20" r="5" fill="#8b5cf6"/>
      <circle cx="0" cy="20" r="5" fill="#8b5cf6"/>
    </g>
    <text x="0" y="85" text-anchor="middle" fill="#60a5fa" font-family="Arial" font-size="14">RAG/CAG</text>
  </g>
  
  <!-- Cerebro/derecha (representando IA) -->
  <g transform="translate(1080,320)">
    <path d="M-60,-40 C-30,-60 30,-60 60,-40 C80,-20 80,20 60,40 C30,60 -30,60 -60,40 C-80,20 -80,-20 -60,-40" 
          fill="none" stroke="url(#accentGradient)" stroke-width="3"/>
    <!-- Red neuronal interna -->
    <g stroke="#60a5fa" stroke-width="1" opacity="0.7">
      <circle cx="0" cy="0" r="30" fill="none"/>
      <circle cx="0" cy="0" r="15" fill="none"/>
      <line x1="-20" y1="-15" x2="20" y2="15"/>
      <line x1="-20" y1="15" x2="20" y2="-15"/>
    </g>
  </g>
  
  <!-- Flechas de conexión -->
  <g stroke="#60a5fa" stroke-width="2" stroke-dasharray="5,5">
    <path d="M280,320 L590,320" />
    <path d="M690,320 L1030,320" />
  </g>
  
  <!-- Texto principal -->
  <g text-anchor="middle" fill="white" font-family="Arial, sans-serif">
    <text x="640" y="180" font-size="48" font-weight="bold" fill="url(#accentGradient)">
      Industrial AI Developer
    </text>
    
    <text x="640" y="240" font-size="24" opacity="0.9">
      From Factory Floors to AI Models
    </text>
    
    <!-- Tech stack -->
    <g transform="translate(640, 520)" font-size="16" fill="#cbd5e1">
      <text x="-300" y="0">Python</text>
      <text x="-200" y="0">FastAPI</text>
      <text x="-100" y="0">React</text>
      <text x="0" y="0">Ollama</text>
      <text x="100" y="0">Vector Search</text>
      <text x="200" y="0">Kotlin</text>
      <text x="300" y="0">Firebase</text>
    </g>
    
    <!-- Tagline -->
    <text x="640" y="580" font-size="18" fill="#94a3b8">
      15 Years Industrial Exp • RAG/CAG Systems • Local AI • Edge Computing
    </text>
  </g>
  
  <!-- Elementos decorativos (partículas de datos) -->
  <g fill="#60a5fa" opacity="0.6">
    <circle cx="100" cy="100" r="2"/>
    <circle cx="400" cy="80" r="2"/>
    <circle cx="150" cy="500" r="2"/>
    <circle cx="800" cy="150" r="2"/>
    <circle cx="1100" cy="400" r="2"/>
    <circle cx="1200" cy="100" r="2"/>
    <circle cx="900" cy="550" r="2"/>
  </g>
</svg>
<div align="center">
  <img src="banner.png" alt="Demo" width="full">
  <h1>👋 ¡Hola, soy Pedro Mencías!</h1>
  <p>Desarrollador apasionado con un enfoque en el aprendizaje continuo y la colaboración.</p>
</div>

---

### 🚀 Sobre Mí

Soy un entusiasta de la programación siempre buscando nuevas formas de aprender y construir. Mi pasión radica en la resolución de problemas a través del código y en la constante exploración de nuevas tecnologías.

### 📚 Formación Continua

Saqué mi Titulación de Técnico Superior en Sistemas de Telecomunicaciones e Informática hace ya muchos años, pero nunca dejo de aprender cosas nuevas. No hay mejor aptitud que mantenerse actualizado... nuestro campo cambia constantemente. En la actualidad estoy aplicándome en las certificaciones de Oracle, y me alegra compartir que he logrado:

<div align="center">

| | | |
|:---:|:---:|:---:|
| <img src="OCI25FA.png" alt="OCI Foundations AI" width="200"> | <img src="GENAIPRO.png" alt="OCI Generative AI Professional" width="200"> | <img src="proxtit.png" alt="Descripción 3" width="200"> |
| **OCI Foundations AI** | **OCI Generative AI Professional** | **Título 3** |
| <img src="proxtit.png" alt="Descripción 4" width="200"> | <img src="proxtit.png" alt="Descripción 5" width="200"> | <img src="proxtit.png" alt="Descripción 6" width="200"> |
| **Título 4** | **Título 5** | **Título 6** |

</div>

En cuanto a lenguajes de programación, estoy inmerso en el aprendizaje y la profundización de:

-   **Kotlin**: Explorando el desarrollo moderno de aplicaciones.
-   **React**: Construyendo interfaces de usuario dinámicas y reactivas.
-   **Python**: Utilizándolo para scripting, desarrollo backend y análisis de datos.

### 🌱 Mis Intereses

Me interesa todo lo relacionado con el desarrollo de software, desde la concepción de una idea hasta la implementación y optimización. Siempre estoy abierto a nuevos desafíos y a expandir mi conjunto de habilidades.

### ✨ Busco Colaborar

Me encantaría colaborar en proyectos que permitan **ayudar a otros** y en los que pueda aplicar mis conocimientos mientras sigo aprendiendo. Si tienes una idea o un proyecto en el que crees que puedo aportar, ¡no dudes en contactarme!

### 📬 ¿Cómo Contactarme?

La mejor forma de contactarme es a través de **email**. Puedes enviarme un correo electrónico y con gusto responderé.

[📧 Mi Correo](mailto:beyond.digital.web@gmail.com)

### 📊 Mis Estadísticas en GitHub

Aquí puedes ver un resumen de mi actividad:

<div align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=Charran78&show_icons=true&theme=radical&hide_border=false" alt="Estadísticas de GitHub de Charran78"/>
  
</div>

---

### ⚡ Dato Curioso

A pesar de mi experiencia, me considero un "newbie" eterno, siempre con ganas de aprender como si fuera el primer día. ¡Esa es la chispa que me mantiene motivado!

---

[📋 Visita mi Portafolio](https://pedromencias.netlify.app/)
[😏 Pásate por mi LinkedIn](https://www.linkedin.com/in/pedro-menc%C3%ADas-68223336b/)
[☕ Invitame aun Café](https://buymeacoffee.com/beyonddigiv)
[🐉 Blogs](https://androidalonia.wordpress.com/)
---

<div align="center">
  <p>¡Gracias por visitar mi perfil! 😊</p>
</div>
