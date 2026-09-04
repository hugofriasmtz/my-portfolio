# Portafolio personal

Portafolio personal de **Hugo Frías Martínez**, desarrollado con Astro y React. Presenta experiencia profesional, habilidades, proyectos y formación académica, con una interfaz adaptable, animaciones y soporte para temas claro y oscuro.

## Características

- Interfaz adaptable para móvil, tablet y escritorio.
- Componentes interactivos construidos con React y Framer Motion.
- Efectos visuales de glassmorphism.
- Tema claro y oscuro.
- Generación estática y rendimiento optimizado con Astro.
- Secciones de experiencia, habilidades, proyectos y educación.

## Tecnologías

- Astro 5
- React 19
- TypeScript
- Tailwind CSS 4
- Framer Motion
- Lucide React

## Requisitos

- Node.js 18 o superior.
- npm, yarn o bun.

## Instalación y desarrollo

```bash
git clone https://github.com/hugofriasmtz/my-portfolio.git
cd my-portfolio
npm install
npm run dev
```

El sitio estará disponible en `http://localhost:4321`.

## Scripts disponibles

| Comando | Descripción |
| --- | --- |
| `npm run dev` | Inicia el servidor de desarrollo. |
| `npm run build` | Genera la versión de producción. |
| `npm run preview` | Previsualiza la build de producción. |
| `npm run astro` | Ejecuta la CLI de Astro. |

## Personalización

El contenido principal se encuentra en [`src/lib/data.ts`](src/lib/data.ts). Allí puedes actualizar:

- `personalInfo`: nombre, ubicación, correo y enlaces profesionales.
- `workExperience`: experiencia laboral y logros.
- `education`: formación académica.
- `skills`: lenguajes, herramientas, frontend, bases de datos y sistemas operativos.
- `projects`: proyectos y enlaces a sus repositorios.

La página principal se compone en [`src/pages/index.astro`](src/pages/index.astro), y los estilos globales están en [`src/styles/global.css`](src/styles/global.css).

## Build de producción

```bash
npm run build
npm run preview
```

El proyecto puede desplegarse en Vercel, Netlify, GitHub Pages o cualquier servicio compatible con sitios estáticos.

## Contacto

- GitHub: [hugofriasmtz](https://github.com/hugofriasmtz)
- LinkedIn: [hugofriasmtz](https://www.linkedin.com/in/hugofriasmtz/)
- Correo electrónico: [hugofriasmtz@hotmail.com](mailto:hugofriasmtz@hotmail.com)

## Licencia

Este proyecto está distribuido bajo la licencia MIT. Consulta [`LICENSE`](LICENSE) para ver los detalles.
