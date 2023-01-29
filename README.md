# Configuración de DaisyUI

[DaisyUI](https://daisyui.com)

## Crear proyecto

```
yarn create vite
```

> √ Project name: ... config-daisy-ui
> √ Select a framework: » Vue
> √ Select a variant: » JavaScript

## Dependencias de desarrollo

```
yarn add -D \
@vue/compiler-sfc \
autoprefixer \
daisyui \
postcss \
tailwindcss
```

## Archivos de configuración

> postcss.config.cjs

```
module.exports = {
  plugins: [require('tailwindcss'), require('autoprefixer')],
};
```

> tailwind.config.cjs

```
module.exports = {
  content: ['./src/**/*.{vue,js,ts}'],
  plugins: [require('daisyui')],
};
```

> src/tailwind.css

```
@tailwind base;
@tailwind components;
@tailwind utilities;
```

> src/style.css

```
@import './tailwind.css';
...
```

# Comandos basicos

1. Clonar proyecto
2. yarn
3. yarn dev