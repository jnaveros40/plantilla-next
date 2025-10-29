# 🚀 Plantilla Next.js Profesional

Una plantilla moderna y lista para producción construida con las últimas tecnologías web. Perfecta para iniciar tu próximo proyecto con una base sólida y profesional.

## ✨ Características

- ⚛️ **Next.js 16** - Framework React de última generación
- 🔷 **TypeScript** - Tipado estático para código más seguro
- 💨 **Tailwind CSS 4** - Estilos utilitarios modernos
- 🎨 **Sistema de Colores Centralizado** - Paleta personalizable en `src/styles/`
- 🌓 **Modo Oscuro/Claro** - Soporte automático de temas
- 📱 **PWA Ready** - Instalable como aplicación nativa
- 🧩 **Componentes Reutilizables** - Footer, InstallPWA y más
- ⚡ **React 19** - Última versión con React Compiler
- 🎯 **ESLint** - Código limpio y consistente
- 📦 **Optimizado** - Build optimizado para producción

## 🎨 Sistema de Colores

El proyecto incluye una paleta de colores centralizada que puedes personalizar fácilmente:

- **`src/styles/colors.ts`** - Definición de colores en TypeScript
- **`src/styles/variables.css`** - Variables CSS globales

Simplemente modifica estos archivos para cambiar toda la apariencia de la aplicación.

## 📁 Estructura del Proyecto

```
plantilla/
├── public/              # Archivos estáticos y PWA
│   ├── manifest.json    # Configuración PWA
│   ├── service-worker.js
│   └── IngNavs.png
├── src/
│   ├── app/             # App Router de Next.js
│   │   ├── page.tsx     # Página principal
│   │   ├── layout.tsx   # Layout raíz
│   │   ├── globals.css  # Estilos globales
│   │   └── Home.css     # Estilos de la home
│   ├── components/      # Componentes reutilizables
│   │   ├── Footer.tsx
│   │   ├── Footer.css
│   │   ├── InstallPWA.tsx
│   │   └── InstallPWA.css
│   └── styles/          # Sistema de diseño
│       ├── colors.ts    # Paleta de colores
│       └── variables.css # Variables CSS
├── package.json
├── tsconfig.json
└── next.config.ts
```

## 🚀 Inicio Rápido

### Prerequisitos

- Node.js 18+ 
- npm, yarn, pnpm o bun

### Instalación

1. **Clona el repositorio:**
```bash
git clone https://github.com/jnaveros40/plantilla-next.git
cd plantilla-next
```

2. **Instala las dependencias:**
```bash
npm install
# o
yarn install
# o
pnpm install
```

3. **Inicia el servidor de desarrollo:**
```bash
npm run dev
```

4. **Abre tu navegador en:**
```
http://localhost:3000
```

## 📜 Scripts Disponibles

| Script | Descripción |
|--------|-------------|
| `npm run dev` | Inicia el servidor de desarrollo |
| `npm run build` | Crea el build de producción |
| `npm run start` | Inicia el servidor de producción |
| `npm run lint` | Ejecuta el linter ESLint |

## 🎯 Personalización

### Cambiar Colores

Edita `src/styles/colors.ts` o `src/styles/variables.css`:

```typescript
// src/styles/colors.ts
export const colors = {
  primary: {
    main: '#6366f1',    // Tu color primario
    light: '#818cf8',
    dark: '#4f46e5',
  },
  // ... más colores
}
```

### Modificar el Logo

Reemplaza `/public/IngNavs.png` con tu logo.

### Personalizar PWA

Edita `public/manifest.json` para cambiar nombre, iconos y configuración de la PWA.

## 📱 Progressive Web App (PWA)

Esta plantilla está lista para funcionar como PWA:

1. ✅ Manifest configurado
2. ✅ Service Worker incluido
3. ✅ Componente de instalación (`InstallPWA`)
4. ✅ Iconos adaptables para Android/iOS

## 🌐 Deployment

### Vercel (Recomendado)

[![Deploy with Vercel](https://vercel.com/button)](https://vercel.com/new/clone?repository-url=https://github.com/jnaveros40/plantilla-next)

### Otras Plataformas

La aplicación puede desplegarse en cualquier plataforma que soporte Next.js:

- **Netlify**
- **Railway**
- **AWS Amplify**
- **Docker**

```bash
# Build para producción
npm run build
npm run start
```

## 🛠️ Tecnologías

- [Next.js 16](https://nextjs.org/) - Framework React
- [React 19](https://react.dev/) - Librería UI
- [TypeScript](https://www.typescriptlang.org/) - Tipado estático
- [Tailwind CSS 4](https://tailwindcss.com/) - Framework CSS
- [ESLint](https://eslint.org/) - Linter de código

## 👨‍💻 Desarrollado por

**Ing Navs**
- 🌐 [Website](https://ingnavs.vercel.app/)
- 📱 WhatsApp: +57 302 509 1063

## 🤝 Contribuciones

Las contribuciones son bienvenidas. Por favor:

1. Fork el proyecto
2. Crea una rama para tu feature (`git checkout -b feature/AmazingFeature`)
3. Commit tus cambios (`git commit -m 'Add some AmazingFeature'`)
4. Push a la rama (`git push origin feature/AmazingFeature`)
5. Abre un Pull Request

## 📞 Soporte

Si necesitas ayuda para crear tu aplicación web personalizada, contáctame por WhatsApp.

---

⭐ Si te gusta este proyecto, dale una estrella en GitHub!
