# Seba's Website �

![Seba Website](public/astropaper-og.jpg)
![Typescript](https://img.shields.io/badge/TypeScript-007ACC?style=for-the-badge&logo=typescript&logoColor=white)
![Astro](https://img.shields.io/badge/Astro-FF5D01?style=for-the-badge&logo=astro&logoColor=white)

Mi sitio web personal construido con [Astro](https://astro.build/), donde comparto mis proyectos, pensamientos y aprendizajes sobre desarrollo de software y tecnología.

## 👋 Sobre mí

Soy **Sebastian Martínez** (seba), ingeniero de desarrollo con experiencia en **Go**, **React**, **Python** y otras tecnologías. Me apasiona aprender constantemente, tanto dentro como fuera del mundo del desarrollo de software.

Puedes encontrarme como **seba5dev** o **sebalab** en diferentes plataformas.

## 🔥 Características

- [x] Markdown type-safe
- [x] Rendimiento super rápido
- [x] Accesible (Teclado/VoiceOver)
- [x] Responsive (móvil ~ escritorio)
- [x] SEO-friendly
- [x] Modo claro y oscuro
- [x] Búsqueda fuzzy
- [x] Posts en borrador y paginación
- [x] Sitemap y RSS feed
- [x] Generación dinámica de imágenes OG para posts
- [x] Tema personalizado con colores cyber azul
- [x] Fuente Raleway para una apariencia moderna

## 🚀 Estructura del Proyecto

```bash
/
├── public/
│   ├── assets/
|   ├── pagefind/ # generado automáticamente en build
│   └── favicon.svg
│   └── toggle-theme.js
├── src/
│   ├── assets/
│   │   └── icons/
│   │   └── images/
│   ├── components/
│   ├── data/
│   │   └── blog/
│   │       └── posts.md
│   ├── layouts/
│   └── pages/
│   └── styles/
│   └── utils/
│   └── config.ts
│   └── constants.ts
│   └── content.config.ts
└── astro.config.ts
```

## � Tech Stack

**Framework Principal** - [Astro](https://astro.build/)  
**Type Checking** - [TypeScript](https://www.typescriptlang.org/)  
**Estilos** - [TailwindCSS](https://tailwindcss.com/)  
**Búsqueda Estática** - [Pagefind](https://pagefind.app/)  
**Iconos** - [Tablers](https://tabler-icons.io/)  
**Formateo de Código** - [Prettier](https://prettier.io/)  
**Linting** - [ESLint](https://eslint.org)  
**Fuente** - [Raleway](https://fonts.google.com/specimen/Raleway) (Google Fonts)

## 🛠️ Desarrollo Local

Para ejecutar este proyecto localmente:

```bash
# Instalar dependencias
pnpm install

# Iniciar servidor de desarrollo
pnpm run dev
```

El sitio estará disponible en `http://localhost:4321`

### Con Docker

Si prefieres usar Docker:

```bash
# Construir la imagen
docker build -t seba-website .

# Ejecutar el contenedor
docker run -p 4321:80 seba-website
```

## 🧞 Comandos

Todos los comandos se ejecutan desde la raíz del proyecto:

| Comando                  | Acción                                              |
| :----------------------- | :-------------------------------------------------- |
| `pnpm install`           | Instala las dependencias                            |
| `pnpm run dev`           | Inicia servidor local en `localhost:4321`           |
| `pnpm run build`         | Construye el sitio para producción en `./dist/`     |
| `pnpm run preview`       | Previsualiza el build localmente antes de desplegar |
| `pnpm run format:check`  | Verifica el formato del código con Prettier         |
| `pnpm run format`        | Formatea el código con Prettier                     |
| `pnpm run sync`          | Genera tipos TypeScript para módulos Astro         |
| `pnpm run lint`          | Ejecuta ESLint                                      |

## 📝 Personalización

Este sitio está personalizado con:

- **Esquema de colores cyber azul**: Tonos azules tecnológicos y vibrantes
- **Fuente Raleway**: Tipografía sans-serif moderna y elegante
- **Contenido personalizado**: Página About y posts adaptados a mi experiencia

## 📜 Licencia

Este proyecto está basado en [AstroPaper](https://github.com/satnaing/astro-paper) creado por [Sat Naing](https://satnaing.dev).

---

**Tema base:** [AstroPaper](https://github.com/satnaing/astro-paper) por [Sat Naing](https://satnaing.dev) - Licensed under the MIT License  
**Personalización y contenido:** Sebastian Martínez (seba5dev)
