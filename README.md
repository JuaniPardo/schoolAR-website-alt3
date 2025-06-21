# SchoolAR Website

Este proyecto es un sitio web estático para SchoolAR, una plataforma de gestión escolar. El sitio web está construido con [Astro](https://astro.build/) y [Tailwind CSS](https://tailwindcss.com/).

## Tecnologías utilizadas

- **Astro**: Framework para construir sitios web estáticos con soporte para componentes.
- **Tailwind CSS 3.x**: Framework de CSS utilitario para diseño rápido y responsivo.
- **TypeScript**: Superset de JavaScript que añade tipado estático.

## Características

- Diseño responsivo (mobile-first)
- Modo oscuro/claro
- Optimizado para SEO
- Accesibilidad básica
- Estructura modular y componentes reutilizables

## Estructura del proyecto

```
schoolAR-website/
├── public/             # Archivos estáticos (imágenes, favicon, etc.)
├── src/
│   ├── components/     # Componentes reutilizables
│   ├── layouts/        # Layouts de página
│   ├── pages/          # Páginas del sitio
│   ├── styles/         # Estilos globales
│   └── assets/         # Otros recursos (imágenes, fuentes, etc.)
├── astro.config.mjs    # Configuración de Astro
├── tailwind.config.mjs # Configuración de Tailwind CSS
├── tsconfig.json       # Configuración de TypeScript
└── package.json        # Dependencias y scripts
```

## Páginas implementadas

1. **Inicio**: Página principal con descripción de SchoolAR y llamados a la acción.
2. **Sobre Nosotros**: Historia de la empresa, misión, visión y equipo.
3. **Servicios**: Detalle de los módulos y funcionalidades de SchoolAR.
4. **Testimonios**: Opiniones de usuarios de la plataforma.
5. **Contacto**: Formulario de contacto e información de contacto.

## Requisitos

- Node.js 18 o superior
- npm o yarn

## Instalación

1. Clona el repositorio:
```bash
git clone https://github.com/tu-usuario/schoolAR-website.git
cd schoolAR-website
```

2. Instala las dependencias:
```bash
npm install
```

## Desarrollo

Para iniciar el servidor de desarrollo:

```bash
npm run dev
```

El sitio estará disponible en `http://localhost:4321`.

## Construcción

Para construir el sitio para producción:

```bash
npm run build
```

Los archivos generados estarán en la carpeta `dist/`.

## Vista previa de producción

Para previsualizar la versión de producción:

```bash
npm run preview
```

## Notas de versiones

### Compatibilidad de dependencias

Este proyecto utiliza Tailwind CSS v3.3.5 para mantener la compatibilidad con @astrojs/tailwind v5.0.0. 
La versión original del proyecto intentaba usar Tailwind CSS v4.0.0, pero esto causaba un conflicto de dependencias
ya que @astrojs/tailwind v5.x requiere Tailwind CSS v3.x.

## Licencia

Este proyecto está bajo la Licencia MIT.