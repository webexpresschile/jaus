# Digital Architect Studio

Este es el repositorio para la página web (landing page) de **Digital Architect Studio**, una agencia especializada en ingeniería web premium y experiencias digitales de alto rendimiento.

## 🚀 Tecnologías Utilizadas

- **HTML5**: Estructura semántica del contenido.
- **Tailwind CSS**: Framework de utilidades CSS (cargado vía CDN) para un diseño moderno y responsivo.
- **CSS Personalizado**: Clases y variables CSS específicas (`styles.css`) para efectos como degradados (`signature-gradient`) y fondos tipo *glassmorphism*.
- **Fuentes**: 
  - [Manrope](https://fonts.google.com/specimen/Manrope) (Titulares)
  - [Inter](https://fonts.google.com/specimen/Inter) (Cuerpo del texto)
- **Íconos**: [Material Symbols Outlined](https://fonts.google.com/icons) de Google.

## 📁 Estructura del Proyecto

```text
├── index.html           # Documento principal de la página
├── styles.css           # Estilos base personalizados
├── tailwind.config.js   # Configuración del tema para Tailwind
└── README.md            # Documentación del proyecto
```

## 🛠️ Cómo Iniciar

Al ser un proyecto estático sin dependencias pesadas de Node.js o módulos locales (Node/NPM no son estrictamente requeridos ya que Tailwind carga su configuración por CDN), puedes levantar la página fácilmente:

1. **Visualización Directa**:
   Haz doble clic sobre el archivo `index.html` para abrirlo en tu navegador predeterminado.

2. **Usando Live Server (Recomendado)**:
   Si usas VS Code, instala la extensión "Live Server" y haz clic derecho sobre `index.html` -> "Open with Live Server" para ver los cambios con auto-recarga.

3. **Usando Python**:
   Para levantar rápidamente un servidor local, abre tu terminal en este directorio y ejecuta:
   ```bash
   python3 -m http.server 8000
   ```
   Luego, visita `http://localhost:8000`.

## ✨ Características Principales

- **Diseño Premium**: Paleta de colores moderna con modo oscuro editorial y degradados atractivos.
- **Enfoque SEO y Conversión**: Arquitectura directa y llamadas a la acción (CTAs) claras enfocadas estrictamente en leads comerciales.
- **Portafolio Interactivo**: Cuadrícula de proyectos (masonry effect) con micro-animaciones en *hover*.
- **Totalmente Responsivo**: Adaptable a todos los dispositivos, preservando la estética e integridad en tablets y smartphones.

---
© 2024 Digital Architect Studio. Todos los derechos reservados.
