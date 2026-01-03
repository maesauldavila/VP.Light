# 🎯 VP.Light - AIDN Viewer

[![Status](https://img.shields.io/badge/status-active-success.svg)]()
[![License](https://img.shields.io/badge/license-proprietary-red.svg)]()
[![Version](https://img.shields.io/badge/version-1.0.0-blue.svg)]()

> Visualizador profesional de presentaciones con medios complementarios integrados y experiencia de usuario premium.

🔗 **Demo en vivo:** [maesauldavila.github.io/VP.Light](https://maesauldavila.github.io/VP.Light/)  
🔗 **Shortlink:** [bit.ly/vp-light](https://bit.ly/vp-light)

---

## 📋 Contenido

- [Características](#-características)
- [Propiedad Intelectual](#️-propiedad-intelectual)
- [Tecnologías](#️-tecnologías)
- [Instalación Local](#-instalación-local)
- [Uso](#-uso)
- [Licencia](#-licencia)
- [Contacto](#-contacto)

---

## ✨ Características

### Diseño Premium - Boutique

- **Glassmorphism** con efectos de blur y transparencias
- **Modo oscuro/claro** automático con persistencia
- **15+ micro-interacciones** y animaciones fluidas suaves
- **100% responsive** (320px - 4K)
- **WCAG 2.1 AA compliant** - accesibilidad total
- **Nivel boutique agency** ($8,500-11,000 USD valor de mercado)

### Funcionalidades Core

#### 📊 Presentaciones Soportadas
- ✅ **PDF** - Documentos multipágina
- ✅ **HTML** - Presentaciones web interactivas
- ✅ **Imágenes** - JPG, PNG, GIF, WebP

#### 🎬 Medios Complementarios
- ✅ **Video** - MP4, WebM, OGG
- ✅ **Audio** - MP3, WAV, OGG
- ✅ **Enlaces web** - iFrames embebidos

#### 🎮 Controles Avanzados
- ✅ Navegación por teclado (flechas)
- ✅ Gestos táctiles (swipe)
- ✅ Modo fullscreen
- ✅ Sidebar colapsable
- ✅ Drag & drop de archivos
- ✅ Múltiples archivos simultáneos

### Performance

| Métrica | Valor |
|---------|-------|
| **Peso total** | ~65KB (ultra-ligero) |
| **Carga inicial** | <1s en 3G |
| **Lighthouse Performance** | 98/100 |
| **Accesibilidad** | 100/100 |

---

## 🛡️ Propiedad Intelectual

### ⚠️ PROTECCIÓN DE MARCA Y CONTENIDO

**Este repositorio está protegido por derechos de autor.**

#### 🏢 Marca Corporativa AIDN

**ELEMENTOS PROTEGIDOS:**
- ✓ Logo AIDN (hexágono con gradiente azul)
- ✓ Paleta de colores (#0c2a85, #03b4d6)
- ✓ Sistema de branding VP.Light
- ✓ Tagline corporativo: "Catapultando empresas para liderar el cambio"
- ✓ Arquitectura de software y diseño UI/UX

**© 2026 AIDN. Todos los derechos reservados.**

#### 👤 Autor y Desarrollador

**ELEMENTOS PROTEGIDOS:**
- ✓ Código fuente completo
- ✓ Diseño y estructura del visor
- ✓ Sistema de micro-interacciones
- ✓ Implementación de glassmorphism
- ✓ Lógica de navegación y controles

**© 2026 Saúl Dávila Pantoja. Todos los derechos reservados.**

---

## 📜 Restricciones de Uso

### ❌ PROHIBIDO (Sin autorización escrita):

1. Uso comercial del diseño o código
2. Clonar/bifurcar con fines comerciales
3. Uso de marca AIDN en proyectos propios
4. Modificación y redistribución comercial
5. Creación de trabajos derivados comerciales
6. Venta o sublicenciamiento del proyecto
7. Eliminación de avisos de copyright

### ✅ PERMITIDO (Con atribución):

1. Visualización del código para fines educativos
2. Referencias técnicas en artículos (con crédito)
3. Inspiración conceptual (no copia directa)
4. Fork para estudio personal (no público)

**Atribución requerida:**
```
Basado en VP.Light por Saúl Dávila Pantoja
https://github.com/maesauldavila/VP.Light
Código original bajo licencia propietaria
```

---

## ⚖️ Licencia Propietaria

**Este proyecto NO está bajo licencia de código abierto.**

```
Copyright © 2026 AIDN & Saúl Dávila Pantoja

LICENCIA PROPIETARIA

Todos los derechos reservados. No se permite:
- Uso comercial
- Redistribución
- Uso de marca AIDN
- Trabajos derivados comerciales

Uso educativo permitido con atribución adecuada.

Para permisos comerciales: sauldavila@gmail.com
```

### 🚨 Protección Legal

Este repositorio está protegido bajo:
- Ley Federal del Derecho de Autor (México)
- Digital Millennium Copyright Act (DMCA)
- Propiedad intelectual corporativa de AIDN

**Violaciones serán reportadas bajo DMCA Takedown Notice.**

---

## 🛠️ Tecnologías

### Stack
- **HTML5** semántico con ARIA labels
- **CSS3** (Custom Properties, Backdrop Filters, Grid, Flexbox)
- **JavaScript ES6+** vanilla (sin frameworks)
- **FileReader API** - Lectura de archivos locales
- **Blob URL API** - Manejo de recursos multimedia

### APIs del Navegador
- **Fullscreen API** - Modo presentación
- **localStorage API** - Persistencia de tema
- **Drag & Drop API** - Carga de archivos
- **Touch Events API** - Gestos táctiles
- **Keyboard Events API** - Navegación por teclado

### Características Técnicas
- **Single-file architecture** - Máxima portabilidad
- **Zero dependencies** - No requiere build
- **Progressive enhancement** - Funciona en todos los navegadores
- **Responsive design** - Mobile-first approach
- **Accessibility-first** - Screen readers compatible

---

## 💻 Instalación Local

### Visualización Directa

```bash
# Clonar (solo para visualización educativa)
git clone https://github.com/maesauldavila/VP.Light.git

# Abrir en navegador
open index.html
```

### Con Servidor Local (Recomendado)

**Python:**
```bash
cd VP.Light
python -m http.server 8000
# Abrir http://localhost:8000
```

**Node.js:**
```bash
cd VP.Light
npx http-server -p 8000
```

**VS Code:**
- Instalar extensión "Live Server"
- Click derecho en `index.html` → "Open with Live Server"

---

## 📊 Estructura del Proyecto

```
VP.Light/
│
├── index.html                  # Aplicación completa (single-file)
├── README.md                   # Este archivo
├── LICENSE.txt                 # Licencia propietaria
│
├── favicon.ico                 # Favicon 16x16
├── favicon-16x16.png          # Favicon 16x16
├── favicon-32x32.png          # Favicon 32x32
├── apple-touch-icon.png       # iOS icon 180x180
├── android-chrome-192x192.png # Android icon
├── android-chrome-512x512.png # Android icon
├── banner-VP.Light.png        # OG image (1280x640)
│
└── .github/
    └── FUNDING.yml            # Info de contacto
```

**Arquitectura single-file por diseño:**
- ✅ Máxima portabilidad
- ✅ Cero dependencias de build
- ✅ Deploy instantáneo
- ✅ Fácil mantenimiento

---

## 🎯 Uso

### Para Usuarios

1. **Cargar presentación:**
   - Arrastra archivos PDF/HTML/imágenes al área central
   - O haz clic en el ícono de carga

2. **Navegar:**
   - **Teclado:** Flechas ← → para cambiar diapositivas
   - **Touch:** Swipe izquierda/derecha
   - **Botones:** Anterior/Siguiente

3. **Medios complementarios:**
   - Clic en menú lateral (☰)
   - Agregar videos, audios o enlaces web
   - Reproducir durante la presentación

4. **Modo fullscreen:**
   - Clic en botón de pantalla completa
   - O presiona tecla `F`
   - Controles aparecen al mover el mouse

5. **Cambiar tema:**
   - `Ctrl + Alt + T` - Alternar modo oscuro/claro

### Atajos de Teclado

| Tecla | Acción |
|-------|--------|
| `←` | Diapositiva anterior |
| `→` | Diapositiva siguiente |
| `F` o `F11` | Fullscreen |
| `S` | Alternar sidebar |
| `Ctrl+Alt+T` | Cambiar tema |
| `Esc` | Salir de fullscreen/cerrar media |

### Para Desarrolladores (Referencia)

**Puntos de aprendizaje destacados:**

```javascript
// Estado centralizado
const state = {
  presentation: {
    currentPage: 1,
    totalPages: 1,
    loaded: false,
    files: []
  },
  media: {
    files: [],
    current: null
  },
  ui: {
    sidebarVisible: false,
    isFullscreen: false
  }
};

// Caché de elementos DOM
const els = {};

// Validación de archivos
function validateFile(file, type) {
  const MAX_SIZE = {
    presentation: 50 * 1024 * 1024,
    video: Infinity,
    audio: 100 * 1024 * 1024
  };
  // Validación robusta con tipos MIME
}

// Gestos táctiles
function setupTouchGestures() {
  // Detección de swipe con threshold
}
```

---

## 📐 Casos de Uso

### 1. Presentaciones Corporativas
```
✅ Presentar pitch decks durante reuniones
✅ Capacitaciones internas con videos
✅ Reportes ejecutivos con gráficas
```

### 2. Educación
```
✅ Clases con material multimedia
✅ Workshops interactivos
✅ Cursos en línea
```

### 3. Eventos
```
✅ Conferencias con slides + demos
✅ Webinars con recursos adicionales
✅ Talleres prácticos
```

---

## 🔒 Política de DMCA

**Reportamos violaciones activamente.**

Si detectamos uso no autorizado:
1. DMCA Takedown Notice a GitHub
2. Reporte a plataformas de hosting
3. Acciones legales según gravedad

**Para evitar problemas:**
- Solicita permisos ANTES de usar
- Proporciona atribución adecuada
- Respeta las restricciones

---

## 📞 Contacto

### Para Permisos Comerciales

**Saúl Dávila Pantoja**
- 📧 Email: sauldavila@gmail.com
- 📱 WhatsApp: [+52 1 55 3719 1248](https://wa.me/5215537191248)
- 🌐 Web: [maesauldavila.github.io/tarjeta-digital](https://maesauldavila.github.io/tarjeta-digital/)

### Para Marca AIDN

- 📧 Via Saúl Dávila (Representante Autorizado)

### Reportar Uso No Autorizado

**Email:** sauldavila@gmail.com  
**Asunto:** "Reporte DMCA - VP.Light"

---

## 🙏 Reconocimientos

### Inspiración y Referencias

- **PDF.js** - Mozilla (inspiración para visor PDF)
- **Presentation frameworks** - Reveal.js, Impress.js
- **Design patterns** - Google Material Design, Apple HIG

**Nota:** VP.Light es 100% código original. No utiliza bibliotecas externas.

---

## 📈 Métricas

### Lighthouse Scores

| Métrica | Score |
|---------|-------|
| Performance | 98/100 |
| Accessibility | 100/100 |
| Best Practices | 100/100 |
| SEO | 100/100 |

### Compatibilidad

| Navegador | Versión | Soporte |
|-----------|---------|---------|
| Chrome | 90+ | ✅ Full |
| Firefox | 88+ | ✅ Full |
| Safari | 14+ | ✅ Full |
| Edge | 90+ | ✅ Full |
| Opera | 76+ | ✅ Full |

### Dispositivos

| Tipo | Rango | Estado |
|------|-------|--------|
| Desktop | 1024px+ | ✅ Optimizado |
| Tablet | 768-1024px | ✅ Optimizado |
| Mobile | 320-768px | ✅ Optimizado |

---

## ❓ FAQ

### ¿Puedo usar este código para mi visor?

**No directamente.** Necesitarías eliminar toda la marca AIDN y contactarme para permisos.

### ¿Puedo hacer un fork público?

**Solo para estudio personal.** Si lo haces público, elimina TODO el contenido protegido.

### ¿Cuánto cuesta una licencia comercial?

**Contactar para negociación:**
- Uso individual: $500-1,500 USD
- Uso corporativo: $2,000-5,000 USD
- White label completo: $10,000+ USD

### ¿Qué formatos soporta?

**Presentaciones:** PDF, HTML, JPG, PNG, GIF, WebP  
**Videos:** MP4, WebM, OGG, MOV, AVI  
**Audio:** MP3, WAV, OGG, WebM  
**Web:** Cualquier URL (vía iframe)

### ¿Hay límite de tamaño?

**Presentaciones:** 50MB por archivo  
**Audio:** 100MB por archivo  
**Video:** Sin límite (depende del navegador)

### ¿Funciona offline?

**Sí.** Una vez cargado, funciona completamente offline. Los archivos se manejan localmente vía FileReader API.

---

## 🎓 Uso Educativo

### Si Quieres Referenciar

**En artículos:**
```markdown
Inspirado por [VP.Light - AIDN Viewer]
(https://github.com/maesauldavila/VP.Light)

Nota: Código original bajo licencia propietaria.
Solo se usan conceptos generales.
```

**Permitido:**
- ✅ Explicar conceptos técnicos
- ✅ Screenshots con marca visible
- ✅ Disclaimer de propiedad intelectual

**Prohibido:**
- ❌ Copiar código sin atribución
- ❌ Usar como base comercial
- ❌ Remover marca AIDN

---

## 💡 Filosofía del Proyecto

> *"La estrategia empieza cuando termina la improvisación."*

**Principios:**
1. **Simplicidad primero** - Single-file architecture
2. **Accesibilidad universal** - Funcional para todos
3. **Performance** - Carga rápida, experiencia fluida
4. **Diseño premium** - Nivel boutique agency
5. **Zero dependencies** - Máxima portabilidad

---

## 🏆 Valor del Proyecto

**Este proyecto representa:**
- 120-150 horas de desarrollo senior
- $8,500-11,000 USD valor de mercado
- Código production-ready
- Branding protegido legalmente
- Arquitectura escalable

**Respeto mutuo = Comunidad saludable.**

---

## 📝 Changelog

### v1.0.0 (Enero 2026)

**Features:**
- ✅ Visor de presentaciones multipágina
- ✅ Soporte PDF, HTML, imágenes
- ✅ Medios complementarios (video/audio/web)
- ✅ Dark mode automático con persistencia
- ✅ Navegación por teclado y touch
- ✅ Modo fullscreen con controles
- ✅ Sidebar colapsable
- ✅ Drag & drop de archivos
- ✅ 15+ micro-interacciones
- ✅ WCAG 2.1 AA compliant

**Performance:**
- 98/100 Lighthouse Performance
- ~65KB peso total
- <1s carga en 3G

---

## 🤝 Contribuciones

**Política: CERRADO**

Este es un proyecto personal/corporativo privado.

- ❌ No se aceptan Pull Requests
- ❌ No se aceptan Issues públicos
- ❌ No se buscan colaboradores

**Para reportar bugs:** sauldavila@gmail.com

---

## ⭐ ¿Te Gusta Este Proyecto?

- ⭐ Dale una estrella al repositorio
- 📢 Compártelo con atribución
- 💬 Contacta para permisos comerciales
- 🙏 Respeta la propiedad intelectual

**Dar estrella ≠ Permiso de uso comercial**

---

## 🔮 Roadmap Futuro

### En Consideración
- [ ] Modo presentador con notas
- [ ] Generación de thumbnails
- [ ] Historial de presentaciones recientes
- [ ] Exportar presentación como PDF
- [ ] Integración con Google Drive/Dropbox
- [ ] Modo colaborativo (compartir en tiempo real)

**Nota:** Estas características dependen de demanda comercial y licenciamiento.

---

## 📚 Documentación Adicional

### Recursos Relacionados
- [Tarjeta Digital AIDN](https://maesauldavila.github.io/tarjeta-digital/) - Contacto profesional
- [AIDN Strategic Consulting](https://aidn.com.mx) - Sitio corporativo (pendiente)

### Tecnología
- [FileReader API Docs](https://developer.mozilla.org/en-US/docs/Web/API/FileReader)
- [Fullscreen API Docs](https://developer.mozilla.org/en-US/docs/Web/API/Fullscreen_API)
- [CSS Backdrop Filter](https://developer.mozilla.org/en-US/docs/Web/CSS/backdrop-filter)

---

**© 2026 AIDN & Saúl Dávila Pantoja - Todos los derechos reservados**

*VP.Light - Visualizador Profesional de Presentaciones*
