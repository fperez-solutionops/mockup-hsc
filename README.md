# 🏥 Hospital San Camilo - Sitio Web Institucional

Una página web moderna y accesible para el Hospital San Camilo de San Felipe, diseñada con enfoque en la experiencia del usuario, accesibilidad y profesionalismo médico.

![Hospital San Camilo](https://images.unsplash.com/photo-1519494080410-f9aa76cb4283?ixlib=rb-4.0.3&auto=format&fit=crop&w=1200&h=400&q=80)

## 🌟 Características Principales

### 🎨 Diseño Moderno y Profesional
- **Interfaz Limpia**: Diseño minimalista y profesional apropiado para una institución de salud
- **Paleta de Colores Institucional**: Azules confiables que transmiten seguridad y profesionalismo
- **Tipografía Legible**: Fuente Inter optimizada para lectura en pantalla
- **Diseño Responsive**: Adaptable a dispositivos móviles, tablets y escritorio

### ♿ Accesibilidad Web (WCAG AA)
- **Alto Contraste**: Cumple estándares WCAG AA para texto y elementos interactivos
- **Navegación por Teclado**: Totalmente accesible via teclado
- **Textos Alternativos**: Imágenes con descripciones para lectores de pantalla
- **Estructura Semántica**: HTML semánticamente correcto

### 🚨 Banner de Emergencias
- **Información 24/7**: Datos de contacto de urgencias siempre visibles
- **Animaciones Sutiles**: Efectos de shimmer y pulse para llamar la atención
- **Indicadores de Estado**: Señalización clara del servicio activo

### 🧭 Navegación Inteligente
- **Header Sticky**: Navegación siempre accesible durante el scroll
- **Enlaces Activos**: Resaltado automático de la sección actual
- **Smooth Scrolling**: Desplazamiento suave entre secciones
- **Búsqueda Integrada**: Barra de búsqueda para especialidades y servicios

### 📅 Sistema de Agendamiento
- **Formulario Intuitivo**: Selección de especialidad, profesional y horarios
- **Información de Horarios**: Disponibilidad claramente mostrada
- **Protocolos COVID-19**: Información de seguridad sanitaria
- **Documentos Requeridos**: Lista clara de requisitos

### 🏥 Servicios Clínicos
- **Indicadores de Disponibilidad**: Estado en tiempo real de cada servicio
- **Información Detallada**: Horarios, profesionales y contacto por especialidad
- **Iconografía Profesional**: Íconos Font Awesome para cada especialidad
- **Cards Interactivas**: Hover effects y transiciones suaves

### 📰 Sección de Noticias
- **Actualizaciones Regulares**: Noticias y novedades del hospital
- **Categorización**: Organización por tipo de noticia
- **Imágenes Optimizadas**: Carga rápida y calidad apropiada

### 🔗 Accesos Rápidos
- **Servicios Frecuentes**: Enlaces directos a servicios más solicitados
- **Información del Paciente**: Derechos, deberes y guías
- **Contacto Directo**: Múltiples canales de comunicación

## 🛠️ Tecnologías Utilizadas

- **HTML5**: Estructura semántica y moderna
- **CSS3**: Estilos avanzados con variables CSS y flexbox/grid
- **TailwindCSS**: Framework de utilidades para diseño rápido
- **JavaScript Vanilla**: Funcionalidad interactiva sin dependencias
- **Font Awesome**: Iconografía profesional
- **Google Fonts**: Tipografía Inter para mejor legibilidad

## 🚀 Demo en Vivo

👉 **[Ver Sitio en GitHub Pages](https://tu-usuario.github.io/hospital-san-camilo)**

## 📂 Estructura del Proyecto

```
hospital-san-camilo/
├── index.html (renombrado de hospitalsancamilo.html)
├── README.md
├── assets/
│   ├── images/
│   ├── css/
│   └── js/
└── docs/ (opcional para documentación adicional)
```

## 🏃‍♂️ Cómo Ejecutar Localmente

1. **Clonar el repositorio**:
   ```bash
   git clone https://github.com/tu-usuario/hospital-san-camilo.git
   cd hospital-san-camilo
   ```

2. **Abrir en el navegador**:
   - Simplemente abre `index.html` en tu navegador preferido
   - O usa un servidor local:
   ```bash
   # Con Python 3
   python -m http.server 8000
   
   # Con Node.js (npx)
   npx serve .
   
   # Con PHP
   php -S localhost:8000
   ```

3. **Visitar**: `http://localhost:8000`

## 📱 Características Responsive

- **Mobile First**: Diseño optimizado para móviles primero
- **Breakpoints**: 
  - Mobile: < 640px
  - Tablet: 640px - 1024px
  - Desktop: > 1024px
- **Touch Friendly**: Botones y enlaces optimizados para touch

## ♿ Características de Accesibilidad

- ✅ **Contraste WCAG AA**: Todos los textos cumplen estándares de contraste
- ✅ **Navegación por Teclado**: Tab, Enter, Espacio funcional
- ✅ **Screen Readers**: Estructura semántica y alt tags
- ✅ **Focus Visible**: Indicadores claros de foco
- ✅ **Zoom**: Funcional hasta 200% sin pérdida de funcionalidad

## 🔧 Personalización

### Colores
Las variables CSS están definidas en `:root` para fácil personalización:

```css
:root {
    --hospital-primary: #1e40af;
    --hospital-secondary: #2563eb;
    --hospital-accent: #1d4ed8;
    /* ... más variables */
}
```

### Contenido
- Edita `index.html` para cambiar contenido
- Reemplaza imágenes en las URLs correspondientes
- Modifica información de contacto y servicios

## 🌐 Deploy en GitHub Pages

1. **Fork o clonar** este repositorio
2. **Renombrar** `hospitalsancamilo.html` a `index.html`
3. **Commit y push** los cambios
4. **Configurar GitHub Pages**:
   - Ve a Settings > Pages
   - Source: Deploy from a branch
   - Branch: main
   - Folder: / (root)
5. **¡Listo!** Tu sitio estará disponible en `https://tu-usuario.github.io/hospital-san-camilo`

## 📋 Lista de Verificación para Deploy

- [ ] Renombrar archivo principal a `index.html`
- [ ] Verificar que todas las imágenes cargan correctamente
- [ ] Probar en dispositivos móviles
- [ ] Validar HTML y CSS
- [ ] Verificar accesibilidad
- [ ] Configurar dominio personalizado (opcional)

## 🤝 Contribuciones

Las contribuciones son bienvenidas. Para cambios importantes:

1. Fork el proyecto
2. Crea una rama para tu feature (`git checkout -b feature/AmazingFeature`)
3. Commit tus cambios (`git commit -m 'Add some AmazingFeature'`)
4. Push a la rama (`git push origin feature/AmazingFeature`)
5. Abre un Pull Request

## 📝 Mejoras Futuras

- [ ] Sistema de agendamiento funcional con backend
- [ ] Integración con APIs de salud
- [ ] Chat en línea para consultas
- [ ] Portal del paciente
- [ ] Traducción a múltiples idiomas
- [ ] PWA (Progressive Web App)
- [ ] Integración con calendario
- [ ] Sistema de notificaciones

## 📄 Licencia

Este proyecto está bajo la Licencia MIT. Ver `LICENSE` para más detalles.

## 👥 Créditos

- **Diseño y Desarrollo**: [Tu Nombre]
- **Imágenes**: Unsplash.com
- **Iconos**: Font Awesome
- **Tipografía**: Google Fonts (Inter)
- **Framework CSS**: TailwindCSS

## 📞 Contacto

**Hospital San Camilo** (Ejemplo)
- 📧 Email: contacto@hospitalsancamilo.cl
- 📱 Teléfono: (+56) 34 259-1234
- 🏥 Dirección: Av. Miraflores 2085, San Felipe
- 🌐 Web: [GitHub Pages URL]

---

**⭐ Si este proyecto te fue útil, considera darle una estrella en GitHub ⭐**

---

### 🏥 Acreditaciones

<img src="https://upload.wikimedia.org/wikipedia/commons/2/2d/Logo_del_MINSAL_Chile.png" alt="MINSAL Chile" height="40">

*Sitio web desarrollado siguiendo las mejores prácticas de accesibilidad web y estándares de calidad para instituciones de salud.* 