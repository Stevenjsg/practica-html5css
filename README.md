# Plantilla de sitio web HTML/TailwindCSS

## Pre-requisitos

- Tener instalado **_Node.js_**
- Tener activado **_pnpm_**.
  ==Si no tienes activado pnpm con la siguiente linea se activa.==
  `corepack prepare pnpm@8.7.6 --activate`

## Instalacion de paquetes

Una ves tenga intalado lo que se pide en los pre-requisitos. Procedmos a instalar los modulos que se usaran y para eso se necesita abrir la consola en la raiz del proyecto. Escribir en la consola/terminal:

- `npm install`

Se creara una nueva carpeta que se llama node_modules, si se creo los modulos se instalaron bien.

## Scripts para ejecutar los modulos

Este script te creara el .css que usara la pagina una vez termines tu diseño.

```bash
npm run build-css
# or
yarn build-css
# or
pnpm build-css
```

Para desarrollar y ver tus resultados usa el siguiente script:

```bash
npm run dev
# or
yarn dev
# or
pnpm dev
```

### Recurso que pueden ser de ayuda

- Iconos .svg ➡️ [Icons](https://tabler-icons.io/)
- Componentes con tailwind ➡️ [Flowbite](https://flowbite.com/docs/components/accordion/)
- Documentacion de Tailwind ➡️ [TailwindCSS](https://tailwindcss.com/docs/installation)
