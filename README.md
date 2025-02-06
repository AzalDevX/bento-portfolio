# 🎨 Portfolio Template - Astro & Tailwind CSS

> Plantilla moderna y responsive para portfolio profesional construida con Astro y Tailwind CSS.

![Astro Badge](https://img.shields.io/badge/Astro-FF3E00?logo=astro&logoColor=fff&style=flat)
![Tailwind CSS Badge](https://img.shields.io/badge/Tailwind%20CSS-06B6D4?logo=tailwindcss&logoColor=fff&style=flat)
![TypeScript Badge](https://img.shields.io/badge/TypeScript-3178C6?logo=typescript&logoColor=fff&style=flat)

## ✨ Características Principales

- ⚡ **Alto Rendimiento**: Construido con Astro para carga rápida y eficiente
- 📱 **Totalmente Responsive**: Diseño adaptable a todos los dispositivos
- 🎨 **Modo Oscuro**: Implementación completa de tema claro/oscuro
- 🎭 **Animaciones Suaves**: Efectos de entrada y hover usando AOS
- 🧩 **Estructura Modular**: Componentes organizados y mantenibles
- 📊 **Datos Centralizados**: Gestión mediante JSON
- 🎯 **SEO Optimizado**: Metadata y estructura semántica

## 📁 Estructura del Proyecto

```
portfolio/
├── src/
│   ├── components/
│   │   ├── AboutMe.astro
│   │   ├── ContactInfo.astro
│   │   ├── Education.astro
│   │   ├── InteractiveCard.astro
│   │   ├── ProfileCard.astro
│   │   ├── ThemeSwitch.astro
│   │   └── WorkExperience.astro
│   ├── layouts/
│   │   └── BaseLayout.astro
│   ├── pages/
│   │   └── index.astro
│   └── styles/
│       └── global.css
├── data/
│   └── personal-data.json
├── astro.config.mjs
└── tailwind.config.mjs
```

## 🎨 Sistema de Diseño

### Paleta de Colores

#### Modo Claro

- **Fondos**: Gradientes de beige y chocolate
- **Texto**: Tonos de chocolate para contraste
- **Acentos**: Chocolate medio para elementos interactivos

#### Modo Oscuro

- **Fondos**: Tonos oscuros de chocolate
- **Texto**: Tonos claros de beige
- **Acentos**: Beige claro para elementos interactivos

### Componentes Principales

#### 1. ProfileCard

- Tarjeta de presentación principal
- Foto de perfil y datos básicos
- Animación de entrada fade-down

#### 2. AboutMe

- Sección de biografía personal
- Diseño limpio y legible
- Animación de entrada fade-up

#### 3. WorkExperience

- Experiencia laboral en timeline
- Animaciones en cascada
- Gradientes sutiles en tarjetas

#### 4. Education

- Formación académica
- Diseño de tarjetas con gradientes
- Animaciones secuenciales

#### 5. ContactInfo

- Información de contacto interactiva
- Enlaces con hover effects
- Tooltip informativo

#### 6. InteractiveCard

- Componente base reutilizable
- Efectos hover consistentes
- Soporte para modo oscuro

## 💾 Gestión de Datos

### Estructura del JSON

```json
{
  "profile": {
    "name": "",
    "title": "",
    "image": "",
    "description": ""
  },
  "about": {
    "description": "",
    "skills": []
  },
  "experience": [
    {
      "position": "",
      "company": "",
      "period": {
        "start": "",
        "end": ""
      },
      "responsibilities": []
    }
  ],
  "education": [
    {
      "title": "",
      "institution": "",
      "period": {
        "start": "",
        "end": ""
      }
    }
  ],
  "contact": {
    "email": "",
    "phone": "",
    "location": {
      "city": "",
      "country": "",
      "mapsUrl": ""
    }
  }
}
```

## 📱 Diseño Responsive

### Breakpoints

- 📱 **Mobile**: < 768px
- 💻 **Tablet**: 768px - 1024px
- 🖥️ **Desktop**: > 1024px

### Grid System

- Layout flexible usando CSS Grid
- Ajuste automático de columnas
- Espaciado consistente

## ⚡ Optimizaciones

### Rendimiento

- Componentes lazy-loaded
- Imágenes optimizadas
- CSS purificado

### Accesibilidad

- Estructura semántica HTML
- Contraste de colores WCAG
- Textos alternativos

### SEO

- Meta tags optimizados
- Estructura jerárquica
- URLs amigables

## 🚀 Guía de Inicio

1. **Clona el Repositorio**

   ```bash
   git clone https://github.com/AzalDevX/bento-portfolio.git
   cd bento-portfolio
   ```

2. **Instala Dependencias**

   ```bash
   npm install
   ```

3. **Configura tu Información**

   - Actualiza `data/personal-data.json`
   - Personaliza colores en `tailwind.config.mjs`

4. **Desarrollo Local**

   ```bash
   npm run dev
   ```

5. **Construcción**
   ```bash
   npm run build
   ```

## 🎯 Mejores Prácticas

### Mantenimiento

- Actualiza regularmente `personal-data.json`
- Usa nombres descriptivos para clases
- Mantén la estructura de componentes

### Personalización

- Modifica la paleta de colores en Tailwind
- Ajusta animaciones según necesidades
- Adapta la estructura del grid

### Desarrollo

- Mantén la separación de componentes
- Sigue convenciones de nombres
- Documenta cambios importantes

## 📝 Notas Importantes

- Optimizado para despliegue en CloudFlare
- Animaciones sutiles para mejor UX
- Estructura modular para fácil extensión

## 🤝 Contribuciones

1. Fork del proyecto
2. Crea rama para feature
   ```bash
   git checkout -b feature/AmazingFeature
   ```
3. Commit cambios
   ```bash
   git commit -m 'Add AmazingFeature'
   ```
4. Push a la rama
   ```bash
   git push origin feature/AmazingFeature
   ```
5. Abre Pull Request

## 🙏 Agradecimientos

- [Astro](https://astro.build)
- [Tailwind CSS](https://tailwindcss.com)
- [AOS Library](https://michalsnik.github.io/aos/)

---

Hecho con ❤️ por [lalo](https://lalo.lol/me)
