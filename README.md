# Portfolio personal

Portfolio personal de **Hugo Frías Martínez**, desarrollado con Astro y React. Presenta experiencia profesional, habilidades, proyectos, formación académica y cursos, con una interfaz responsive, animaciones y soporte para temas claro y oscuro.

## Características

- Interfaz responsive para móvil, tablet y escritorio.
- Componentes interactivos construidos con React y Framer Motion.
- Efectos visuales de glassmorphism.
- Tema claro y oscuro.
- Generación estática y rendimiento optimizado con Astro.
- Secciones de experiencia, habilidades, proyectos, cursos y educación.

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
- `awards`: cursos y certificaciones.

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
- Email: [hugofriasmtz@hotmail.com](mailto:hugofriasmtz@hotmail.com)

## 🛠 Primeros pasos

### Requisitos previos

- Node.js (v18+ recommended)
- npm / yarn / bun

### Instalación

```bash
git clone https://github.com/yourusername/portfolio.git
cd portfolio

# Install dependencies
npm install
# or
yarn install
# or
bun install

# Start development server
npm run dev
# or
yarn dev
# or
bun dev
```

Visita `http://localhost:4321` en tu navegador para ver el sitio en desarrollo.

## 🧩 Personalización del portfolio

Todo el contenido se encuentra en `src/lib/data.ts`. Actualiza los siguientes elementos para personalizarlo:

### 1. Información personal

```ts
export const personalInfo = {
  name: "Your Name",
  location: "Your Location",
  email: "your.email@example.com",
  github: "https://github.com/yourusername",
  linkedin: "https://www.linkedin.com/in/yourusername/",
};
```

### 2. Experiencia laboral

```ts
export const workExperience = [
  {
    company: "Company Name",
    location: "Location",
    position: "Your Position",
    period: "Start Date - End Date",
    achievements: [
      "Achievement 1",
      "Achievement 2",
    ],
  },
];
```

### 3. Formación académica

```ts
export const education = [
  {
    institution: "University Name",
    location: "Location",
    degree: "Your Degree",
    period: "Start Date - End Date",
    achievements: [
      "Achievement 1",
      "Achievement 2",
    ],
  },
];
```

### 4. Habilidades

```ts
export const skills = {
  programmingLanguages: ["TypeScript", "Python"],
  frontendDevelopment: ["React", "Next.js"],
  // and more...
};
```

### 5. Proyectos

```ts
export const projects = [
  {
    title: "Project Name",
    github: "https://github.com/yourusername/project",
    description: [
      "What it does",
      "Technologies used",
    ],
  },
];
```

### 6. Cursos y certificaciones

```ts
export const awards = [
  {
    name: "Award Name",
    issuer: "Issuer",
    date: "Date",
    type: "Type",
    position: "Position",
  },
];
```

## 📦 Build de producción

```bash
npm run build
# or
yarn build
# or
bun run build
```

Para previsualizar localmente la build de producción:

```bash
npm run preview
# or
yarn preview
```

## 📤 Despliegue

Puedes desplegar el proyecto fácilmente en plataformas como **Vercel**, **Netlify**, **GitHub Pages** o cualquier servicio de alojamiento estático.

## Licencia

Este proyecto está distribuido bajo la licencia MIT. Consulta [`LICENSE`](LICENSE) para ver los detalles.
