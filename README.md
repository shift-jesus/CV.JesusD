# Portafolio de Desarrollador - JDCY.dev

Este es el código fuente de mi portafolio personal, una página web estática diseñada para mostrar mis habilidades, proyectos y experiencia como desarrollador Full Stack. El diseño está inspirado en una estética "hacker" moderna, con un tema oscuro, animaciones y elementos interactivos.

## 🚀 Características Principales

- **Diseño Moderno y Responsivo:** Totalmente adaptable a dispositivos móviles, tabletas y computadoras de escritorio.
- **Tema Oscuro "Hacker":** Una interfaz con estética de terminal, colores neón y efectos visuales como `scanlines` y `grid-overlays`.
- **Animaciones Dinámicas:**
  - Efecto de escritura en el título principal.
  - Animaciones de aparición (`fade-in`) al hacer scroll, implementadas eficientemente con `IntersectionObserver`.
  - Micro-interacciones y efectos `hover` en tarjetas y botones.
- **Sección de Proyectos con Modales:** Cada proyecto destacado tiene una tarjeta que, al hacer clic, abre un modal con información detallada, tecnologías utilizadas y un enlace directo al repositorio de GitHub.
- **Formulario de Contacto Funcional:** Integrado con **Formspree** para recibir mensajes directamente en mi correo electrónico.
- **Iconografía Moderna:** Uso de Lucide Icons para una iconografía limpia y consistente.

## 🛠️ Tecnologías Utilizadas

### Frontend
- **HTML5:** Para la estructura semántica del contenido.
- **CSS3 y Tailwind CSS:**
  - **Tailwind CSS:** Utilizado a través de su CDN para un desarrollo rápido y basado en utilidades. La configuración se realiza directamente en el HTML.
  - **CSS Personalizado:** Para animaciones complejas (`@keyframes`), estilos de la barra de desplazamiento y efectos visuales únicos.
- **JavaScript (ES6+):**
  - Manipulación del DOM para la interactividad del menú móvil y los modales.
  - `IntersectionObserver` para animaciones de scroll de alto rendimiento.
  - Lógica para el efecto de máquina de escribir en la sección de héroe.

### Servicios Externos
- **Formspree:** Para gestionar el envío del formulario de contacto sin necesidad de un backend propio.
- **Google Fonts:** Para cargar las tipografías `Manrope` y `Space Mono`.

## ✉️ Contacto

Puedes contactarme a través del formulario en el sitio web o directamente a mi correo: `Jesusdyunes475@gmail.com`.

---
*Desarrollado con ❤️ por Jesús David Campo Yunes.*