# SMIM - Servicios de Instalación y Mantenimiento en República Dominicana

Sitio web moderno desarrollado con Astro para SMIM, empresa especializada en servicios en República Dominicana:

- 🌡️ **Aire Acondicionado**: Instalación, mantenimiento y reparación adaptados al clima tropical
- 📹 **Cámaras de Seguridad**: Sistemas de videovigilancia profesional
- 🚪 **Portones Eléctricos**: Automatización de accesos

## 🇩🇴 Optimizado para República Dominicana

El sitio está completamente optimizado para SEO local en República Dominicana:
- Meta tags geográficos para Santo Domingo
- Contenido localizado para RD
- Datos estructurados (Schema.org) para negocios locales
- Keywords específicas para el mercado dominicano
- Información de contacto con códigos de área de RD (+1 809, +1 829)

## 🚀 Tecnologías

- **Astro** - Framework web moderno
- **TypeScript** - Tipado estático
- **CSS** - Estilos personalizados con diseño responsivo

## 📦 Instalación

```bash
npm install
```

## 🛠️ Comandos Disponibles

| Comando                | Acción                                      |
| :--------------------- | :------------------------------------------ |
| `npm run dev`          | Inicia servidor de desarrollo en `localhost:4321` |
| `npm run build`        | Construye el sitio para producción en `./dist/` |
| `npm run preview`      | Vista previa del sitio construido localmente |

## 📁 Estructura del Proyecto

```
/
├── public/
│   └── favicon.svg
├── src/
│   ├── layouts/
│   │   └── Layout.astro          # Layout principal con navegación
│   └── pages/
│       ├── index.astro            # Página de inicio
│       ├── aire-acondicionado.astro
│       ├── camaras-seguridad.astro
│       ├── portones-electricos.astro
│       └── contacto.astro
└── package.json
```

## 🎨 Características

- ✅ Diseño moderno y responsivo
- ✅ Navegación intuitiva
- ✅ **Optimizado para SEO en República Dominicana**
- ✅ Meta tags geográficos y Open Graph
- ✅ Datos estructurados (Schema.org)
- ✅ Página de contacto con WhatsApp integrado
- ✅ Secciones detalladas de cada servicio
- ✅ Diseño mobile-first
- ✅ Keywords localizadas para RD
- ✅ Múltiples canales de contacto (teléfono, WhatsApp, email)

## 🌐 Páginas

- **Inicio**: Presentación de servicios optimizada para RD con llamadas a la acción
- **Aire Acondicionado**: Información detallada sobre climatización en clima tropical
- **Cámaras de Seguridad**: Sistemas de videovigilancia adaptados a RD
- **Portones Eléctricos**: Automatización de portones y accesorios
- **Contacto**: Múltiples canales de contacto (teléfono, WhatsApp, email) sin formulario

## 📝 Personalización

Para personalizar el contenido:

1. **Datos de contacto**: 
   - Footer: `src/layouts/Layout.astro`
   - Página de contacto: `src/pages/contacto.astro`
   - Actualiza los números de teléfono (+1 809, +1 829)
   - Modifica los enlaces de WhatsApp

2. **SEO y ubicación**:
   - Schema.org: `src/components/SchemaOrg.astro`
   - Meta tags: `src/layouts/Layout.astro`
   - Coordenadas GPS para Santo Domingo

3. **Colores y estilos**:
   - Variables CSS: `src/layouts/Layout.astro`

4. **Contenido localizado**:
   - Todas las páginas incluyen referencias a República Dominicana
   - Keywords optimizadas para búsquedas locales

## 🚀 Despliegue

El sitio puede ser desplegado en cualquier plataforma que soporte sitios estáticos:

- Vercel
- Netlify
- GitHub Pages
- Cloudflare Pages

```bash
npm run build
```

El sitio construido estará en la carpeta `./dist/`

## 📄 Licencia

© 2025 SMIM. Todos los derechos reservados.
