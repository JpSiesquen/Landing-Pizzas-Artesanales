# Roadmap de Pizzería Artesanal - Landing Page

Este documento detalla el plan de acción para el desarrollo de una landing page de alta calidad, optimizada para rendimiento y experiencia de usuario, enfocada en una pizzería artesanal.

## Stack Tecnológico Propuesto

*   **Framework**: [Astro](https://astro.build/) - Ideal para sitios enfocados en contenido, con carga ultra rápida y excelente SEO.
*   **Estilos**: **Vanilla CSS / CSS Modules** - Para un control total sobre la estética "premium" y rústica solicitada, sin dependencias innecesarias.
*   **Imágenes**: **Astro Image Optimization** - Para compresión automática y lazy loading nativo.
*   **Despliegue**: **GitHub Pages** - Hosting estático gratuito y confiable.
*   **Fuentes**: Google Fonts (Anton y Montserrat).

---

## Roadmap de Desarrollo

### Fase 1: Cimientos y Diseño (Día 1)
- [ ] **Inicialización**: Configurar proyecto Astro en el directorio actual.
- [ ] **Design System**: Definir variables de CSS para la paleta rústica:
    - `rojo-ladrillo`: #A63D2D
    - `beige-arena`: #F2E8CF
    - `verde-oliva`: #6A7045
    - `carbon-suave`: #2D2D2A
- [ ] **Tipografía**: Importar Anton (títulos) y Montserrat (cuerpo).
- [ ] **Favicon**: Crear e integrar ícono de pizza artesanal.

### Fase 2: Desarrollo de Componentes Core (Día 1-2)
- [ ] **Navbar**: Navegación fluida y responsive.
- [ ] **Hero Section**: Imagen de impacto (unsplash/pexels), slogan y botón "Haz tu pedido" hacia WhatsApp.
- [ ] **Menú Interactivo**: Listado con precios, ingredientes e imágenes de alta calidad con efecto hover.
- [ ] **WhatsApp CTA**: Botón flotante persistente para pedidos rápidos.

### Fase 3: Secciones de Contenido y Experiencia (Día 2-3)
- [ ] **Historia (Nosotros)**: Layout con tipografía cuidada y narrativa cercana.
- [ ] **Testimonios**: Slider o grid de clientes satisfechos.
- [ ] **Contacto**: Formulario básico (estético) e información de contacto.
- [ ] **Google Maps**: Integración de mapa embebido arriba del footer y en contacto.

### Fase 4: Optimización y Pulido (Día 3)
- [ ] **Animaciones**: Implementar `Intersection Observer` para revelaciones suaves de secciones y hover dinámico en botones.
- [ ] **Accesibilidad**: Etiquetas ARIA, navegación por teclado y contraste verificado.
- [ ] **SEO Local**: Metadatos OpenGraph, Schema.org (LocalBusiness) con dirección y horarios.
- [ ] **Performance**: Verificación de carga en móviles y optimización de imágenes.

### Fase 5: Lanzamiento (Día 3)
- [ ] **Configuración CI/CD**: Setup de GitHub Actions para desplegar en GitHub Pages.
- [ ] **Pruebas finales**: Verificación de enlaces de WhatsApp y visualización en diferentes dispositivos.

---

## Requisitos Técnicos Específicos

### Diseño Visual (Aesthetics)
- **Rústico & Moderno**: Uso de texturas sutiles (fondo tipo papel artesanal), bordes redondeados suaves y sombras orgánicas.
- **Micro-interacciones**: Feedback visual inmediato al pasar el mouse por los items del menú.

### Integraciones
- **WhatsApp**: Enlace directo `https://wa.me/XXXXXXXXXXX?text=Hola!%20Quiero%20hacer%20un%20pedido`.
- **Google Maps**: Iframe optimizado para no bloquear la carga inicial.

## Preguntas Abiertas para el Usuario

> [!IMPORTANT]
> 1. **Número de WhatsApp**: ¿Cuál es el número de teléfono para el botón de pedidos?
> 2. **Ubicación**: ¿Cuál es la dirección exacta para el mapa de Google?
> 3. **Contenido del Menú**: ¿Tienes una lista inicial de pizzas y precios, o prefieres que use datos de ejemplo realistas?
> 4. **Redes Sociales**: ¿Qué enlaces de Instagram/Facebook/TikTok debemos incluir en el footer?
