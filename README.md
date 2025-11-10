# Llanos Auditores - Website Template

Una plantilla web profesional basada en el diseño de Contawork Consultores, adaptada para "Llanos Auditores". Incluye diseño responsivo moderno, animaciones interactivas y funcionalidades completas para un sitio web de servicios contables y tributarios.

## 🚀 Características Principales

### ✨ Diseño y Experiencia de Usuario
- **Diseño Responsivo**: Adaptación perfecta a dispositivos móviles, tablets y desktop
- **Animaciones Suaves**: Efectos de desplazamiento y transiciones elegantes
- **Tipografía Moderna**: Fuente Montserrat para una apariencia profesional
- **Navegación Intuitiva**: Menú fijo con efectos de scroll y navegación suave
- **Colores Profesionales**: Paleta de colores azul profesional con acentos dorados

### 📋 Secciones Incluidas
1. **Header/Navegación**: Menú fijo con logo y navegación responsiva
2. **Hero Section**: Sección principal con animación de texto dinámico
3. **Servicios**: Tarjetas interactivas con efecto flip 3D
4. **Sobre Nosotros**: Información de la empresa con imágenes y badges
5. **Planes**: Cuatro opciones de planes con precios y características
6. **Beneficios**: Lista de ventajas con iconos y descripciones
7. **Contacto**: Formulario funcional con validación
8. **Testimonios**: Carrusel de testimonios de clientes
9. **FAQ**: Preguntas frecuentes con acordeón
10. **Footer**: Enlaces sociales y información de contacto

### 🛠️ Funcionalidades Técnicas
- **Formulario de Contacto**: Validación completa y notificaciones
- **Animación de Texto**: Efecto de escritura automática en el hero
- **Carrusel de Testimonios**: Navegación automática y manual
- **Scroll Animations**: Elementos aparecen al hacer scroll
- **Validación de Formularios**: Verificación en tiempo real
- **Navegación Suave**: Scroll suave entre secciones
- **Optimización de Performance**: Carga lazy de imágenes

## 📁 Estructura de Archivos

```
llanosauditores/
├── index.html          # Archivo principal HTML
├── styles.css          # Estilos CSS personalizados
├── script.js           # JavaScript interactivo
├── README.md           # Este archivo
└── assets/             # Carpeta de recursos (crear)
    ├── logo-llanos-auditores.png
    ├── logo-llanos-auditores-white.png
    ├── hero-auditores.png
    ├── hero-background.jpg
    ├── about-team.png
    ├── badge-quality.png
    ├── icon-contable.png
    ├── icon-tributaria.png
    ├── icon-remuneraciones.png
    ├── icon-auditoria.png
    ├── testimonial-1.png
    └── testimonial-2.png
```

## 🎨 Personalización

### Colores Principales
```css
:root {
    --primary-color: #1e40af;      /* Azul principal */
    --secondary-color: #3b82f6;    /* Azul secundario */
    --accent-color: #f59e0b;       /* Dorado de acento */
    --success-color: #10b981;      /* Verde de éxito */
    --dark-color: #1f2937;         /* Gris oscuro */
}
```

### Tipografía
- **Fuente Principal**: Montserrat (Google Fonts)
- **Pesos disponibles**: 300, 400, 500, 600, 700

### Modificar Contenido

#### 1. Cambiar Información de Contacto
En `index.html`, busca la sección de contacto:
```html
<h5>contacto@llanosauditores.cl</h5>
<h5>+569 1234 5678</h5>
<h5>Av. Providencia 123, Of. 456, Santiago - Chile</h5>
```

#### 2. Personalizar Planes
Modifica los precios y características en la sección `#planes`:
```html
<div class="plan-price">$30.000<span>/mes</span></div>
```

#### 3. Actualizar Servicios
Cambia los iconos y descripciones en la sección de servicios.

#### 4. Modificar Testimonios
Actualiza los testimonios de clientes en la sección correspondiente.

## 🔧 Instalación y Uso

### Requisitos
- Navegador web moderno
- Editor de código (VS Code recomendado)
- Servidor web local (opcional para desarrollo)

### Pasos de Instalación

1. **Crear carpeta de proyecto**
   ```bash
   mkdir llanos-auditores
   cd llanos-auditores
   ```

2. **Crear estructura de archivos**
   - Copia los archivos HTML, CSS y JS
   - Crea la carpeta `assets/`

3. **Añadir imágenes**
   - Añade todas las imágenes listadas en la estructura
   - Asegúrate de que coincidan con las rutas en el código

4. **Abrir en navegador**
   - Abre `index.html` directamente en el navegador
   - O usa un servidor local como Live Server

### Servidor Local (Recomendado)
```bash
# Con Python 3
python -m http.server 8000

# Con Node.js (si tienes live-server instalado)
npx live-server

# Con PHP
php -S localhost:8000
```

## 📱 Responsividad

### Breakpoints
- **Mobile**: < 576px
- **Tablet**: 576px - 768px
- **Desktop**: > 768px

### Características Responsivas
- Navegación móvil con hamburger menu
- Reorganización de contenido en tablets
- Optimización de imágenes para móviles
- Formularios adaptados a pantallas táctiles

## ⚡ Optimización y Performance

### Técnicas Implementadas
- **Lazy Loading**: Carga diferida de imágenes
- **CSS Minificación**: Estilos optimizados
- **JavaScript Eficiente**: Código optimizado y sin dependencias pesadas
- **Imágenes Optimizadas**: Uso de formatos modernos recomendado
- **Caching**: Headers de cache recomendados

### Recomendaciones Adicionales
```html
<!-- Preload critical resources -->
<link rel="preload" href="assets/logo.png" as="image">
<link rel="preload" href="https://fonts.googleapis.com/css2?family=Montserrat" as="style">

<!-- Enable compression -->
<meta http-equiv="Content-Encoding" content="gzip">
```

## 🌐 SEO y Accesibilidad

### SEO Implementado
- Meta tags optimizados
- Estructura semántica HTML5
- URLs amigables con anclas
- Heading hierarchy correcta
- Alt text en imágenes

### Accesibilidad
- Contraste adecuado de colores
- Navegación por teclado
- ARIA labels donde necesario
- Formularios accesibles
- Texto alternativo en imágenes

### Meta Tags Recomendados
```html
<meta name="description" content="Llanos Auditores - Expertos en servicios contables y tributarios en Chile">
<meta name="keywords" content="contabilidad, tributaria, auditoria, chile, servicios contables">
<meta property="og:title" content="Llanos Auditores - Expertos Contables & Tributarios">
<meta property="og:description" content="Servicios profesionales de contabilidad y asesoría tributaria">
<meta property="og:image" content="assets/og-image.jpg">
```

## 🚦 Testing y Validación

### Lista de Verificación
- [ ] Todas las imágenes cargan correctamente
- [ ] Formulario de contacto funciona
- [ ] Navegación responsive funciona
- [ ] Animaciones se ejecutan suavemente
- [ ] Enlaces internos funcionan
- [ ] Velocidad de carga < 3 segundos
- [ ] Compatible con Chrome, Firefox, Safari, Edge

### Herramientas de Testing
- **Google PageSpeed Insights**: Performance
- **GTmetrix**: Optimización
- **W3C Validator**: HTML válido
- **WAVE**: Accesibilidad

## 🔄 Mantenimiento

### Actualizaciones Regulares
1. **Contenido**: Actualizar testimonios y casos de éxito
2. **Imágenes**: Renovar fotos del equipo y oficinas
3. **Precios**: Mantener planes actualizados
4. **SEO**: Revisar y optimizar contenido

### Backup y Versionado
- Usar Git para control de versiones
- Backup regular de archivos
- Documentar cambios importantes

## 🤝 Soporte y Contribuciones

### Reportar Problemas
Si encuentras algún error o tienes sugerencias:
1. Documenta el problema detalladamente
2. Incluye capturas de pantalla si es necesario
3. Especifica navegador y sistema operativo

### Mejoras Futuras
- [ ] Integración con CRM
- [ ] Blog/Noticias section
- [ ] Chat en vivo
- [ ] Calculadora de impuestos
- [ ] Portal de clientes
- [ ] Sistema de citas online

## 📄 Licencia

Este template está basado en el diseño de Contawork Consultores y está adaptado para uso educativo y comercial. Asegúrate de:

- Reemplazar todas las imágenes con contenido propio
- Actualizar toda la información de contacto
- Personalizar el contenido según tu empresa
- Verificar compatibilidad con regulaciones locales

## 📞 Contacto de Desarrollo

Para soporte técnico o modificaciones adicionales del template, puedes contactar al desarrollador.

---

**Versión**: 1.0.0  
**Última actualización**: Noviembre 2024  
**Compatible con**: HTML5, CSS3, ES6+  
**Dependencias**: Bootstrap 5.3.2, Font Awesome 6.4.0