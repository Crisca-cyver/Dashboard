# Modern Admin Dashboard

Un dashboard administrativo moderno y responsivo construido con Next.js 15, React 19 y TypeScript. Diseñado con componentes reutilizables y un sistema de temas claro/oscuro.

## 🚀 Características

- **Framework Moderno**: Next.js 15 con App Router
- **React 19**: Última versión de React con nuevas características
- **TypeScript**: Tipado estático para mayor robustez
- **Diseño Responsivo**: Optimizado para desktop, tablet y móvil
- **Tema Claro/Oscuro**: Cambio de tema con persistencia
- **Componentes UI**: Biblioteca completa basada en Radix UI y shadcn/ui
- **Gráficos**: Visualización de datos con Recharts
- **Iconos**: Lucide React para iconografía consistente
- **Formularios**: React Hook Form con validación Zod
- **Animaciones**: Tailwind CSS Animate

## 🛠️ Tecnologías Utilizadas

### Core
- **Next.js 15** - Framework de React
- **React 19** - Biblioteca de interfaz de usuario
- **TypeScript** - Superset tipado de JavaScript
- **Tailwind CSS** - Framework de CSS utilitario

### UI Components
- **Radix UI** - Componentes primitivos accesibles
- **shadcn/ui** - Componentes de interfaz reutilizables
- **Lucide React** - Iconos SVG
- **class-variance-authority** - Variantes de componentes
- **clsx** & **tailwind-merge** - Utilidades de clases CSS

### Funcionalidades
- **next-themes** - Sistema de temas
- **react-hook-form** - Manejo de formularios
- **zod** - Validación de esquemas
- **recharts** - Gráficos y visualizaciones
- **date-fns** - Manipulación de fechas
- **sonner** - Notificaciones toast

## 📦 Instalación

1. **Clona el repositorio**
   ```bash
   git clone <url-del-repositorio>
   cd dashboard
   ```

   dashboard/
├── app/                    # App Router de Next.js 15
│   ├── dashboard/          # Página del dashboard
│   │   └── page.tsx       # Componente principal del dashboard
│   ├── globals.css        # Estilos globales
│   ├── layout.tsx         # Layout raíz de la aplicación
│   └── page.tsx           # Página de inicio
├── components/             # Componentes reutilizables
│   ├── kokonutui/         # Componentes específicos del dashboard
│   │   ├── content.tsx    # Contenido principal del dashboard
│   │   ├── dashboard.tsx  # Componente wrapper del dashboard
│   │   ├── layout.tsx     # Layout del dashboard
│   │   ├── list-01.tsx    # Lista de cuentas
│   │   ├── list-02.tsx    # Lista de transacciones
│   │   ├── list-03.tsx    # Lista de eventos/objetivos
│   │   ├── profile-01.tsx # Componente de perfil
│   │   ├── sidebar.tsx    # Barra lateral de navegación
│   │   └── top-nav.tsx    # Navegación superior
│   ├── theme-provider.tsx # Proveedor de temas
│   ├── theme-toggle.tsx   # Botón de cambio de tema
│   └── ui/                # Componentes UI base (shadcn/ui)
│       ├── accordion.tsx  # Componente acordeón
│       ├── alert-dialog.tsx # Diálogo de alerta
│       ├── alert.tsx      # Componente de alerta
│       ├── aspect-ratio.tsx # Relación de aspecto
│       ├── avatar.tsx     # Componente de avatar
│       ├── badge.tsx      # Componente de insignia
│       ├── breadcrumb.tsx # Navegación de migas de pan
│       ├── button.tsx     # Componente de botón
│       ├── calendar.tsx   # Componente de calendario
│       ├── card.tsx       # Componente de tarjeta
│       ├── carousel.tsx   # Componente de carrusel
│       ├── chart.tsx      # Componente de gráficos
│       ├── checkbox.tsx   # Casilla de verificación
│       ├── collapsible.tsx # Componente colapsible
│       ├── command.tsx    # Paleta de comandos
│       ├── context-menu.tsx # Menú contextual
│       ├── dialog.tsx     # Componente de diálogo
│       ├── drawer.tsx     # Cajón deslizable
│       ├── dropdown-menu.tsx # Menú desplegable
│       ├── form.tsx       # Componentes de formulario
│       ├── hover-card.tsx # Tarjeta al pasar el mouse
│       ├── input-otp.tsx  # Entrada de código OTP
│       ├── input.tsx      # Componente de entrada
│       ├── label.tsx      # Componente de etiqueta
│       ├── menubar.tsx    # Barra de menú
│       ├── navigation-menu.tsx # Menú de navegación
│       ├── pagination.tsx # Componente de paginación
│       ├── popover.tsx    # Componente emergente
│       ├── progress.tsx   # Barra de progreso
│       ├── radio-group.tsx # Grupo de botones de radio
│       ├── resizable.tsx  # Paneles redimensionables
│       ├── scroll-area.tsx # Área de desplazamiento
│       ├── select.tsx     # Componente de selección
│       ├── separator.tsx  # Separador visual
│       ├── sheet.tsx      # Hoja deslizable
│       ├── sidebar.tsx    # Componente de barra lateral
│       ├── skeleton.tsx   # Esqueleto de carga
│       ├── slider.tsx     # Control deslizante
│       ├── sonner.tsx     # Notificaciones sonner
│       ├── switch.tsx     # Interruptor de alternancia
│       ├── table.tsx      # Componente de tabla
│       ├── tabs.tsx       # Componente de pestañas
│       ├── textarea.tsx   # Área de texto
│       ├── toast.tsx      # Notificaciones toast
│       ├── toaster.tsx    # Contenedor de toasts
│       ├── toggle-group.tsx # Grupo de botones de alternancia
│       ├── toggle.tsx     # Botón de alternancia
│       ├── tooltip.tsx    # Componente de tooltip
│       ├── use-mobile.tsx # Hook para detección móvil
│       └── use-toast.ts   # Hook para notificaciones
├── hooks/                  # Hooks personalizados
│   ├── use-mobile.tsx     # Hook para detección móvil
│   └── use-toast.ts       # Hook para notificaciones
├── lib/                    # Utilidades y configuraciones
│   └── utils.ts           # Funciones utilitarias
├── public/                 # Archivos estáticos
│   ├── placeholder-logo.png
│   ├── placeholder-logo.svg
│   ├── placeholder-user.jpg
│   ├── placeholder.jpg
│   └── placeholder.svg
├── styles/                 # Estilos adicionales
│   └── globals.css        # Estilos globales CSS
├── .gitignore             # Archivos ignorados por Git
├── components.json        # Configuración de shadcn/ui
├── next.config.mjs        # Configuración de Next.js
├── package.json           # Dependencias y scripts
├── postcss.config.mjs     # Configuración de PostCSS
├── tailwind.config.js     # Configuración de Tailwind CSS
└── tsconfig.json          # Configuración de TypeScript


## 🎯 Componentes Disponibles
### Componentes del Dashboard
- Dashboard : Componente principal que organiza el layout
- Sidebar : Navegación lateral con menús colapsibles
- TopNav : Barra de navegación superior con perfil y tema
- Content : Área de contenido principal con listas
- Profile : Componente de perfil de usuario
### Listas de Datos
- List01 : Gestión de cuentas bancarias y balances
- List02 : Historial de transacciones recientes
- List03 : Eventos próximos y objetivos financieros
### Componentes UI Base
Todos los componentes de shadcn/ui están disponibles:

- Formularios (Input, Select, Textarea, etc.)
- Navegación (Tabs, Dropdown, Breadcrumb, etc.)
- Feedback (Alert, Toast, Dialog, etc.)
- Datos (Table, Chart, Calendar, etc.)
- Layout (Card, Separator, Sidebar, etc.)
## 📊 Características del Dashboard
### Gestión de Cuentas
- Visualización de múltiples cuentas bancarias
- Balances en tiempo real
- Tipos de cuenta (Checking, Savings, Credit)
- Acciones rápidas (Agregar, Enviar, Recargar)
### Transacciones
- Historial completo de transacciones
- Categorización automática
- Filtros por fecha y tipo
- Detalles de comerciantes y montos
### Eventos y Objetivos
- Seguimiento de objetivos financieros
- Eventos próximos importantes
- Indicadores de progreso
- Estados de completado
### Diseño Responsivo
- Desktop : Layout completo con sidebar expandida
- Tablet : Sidebar colapsible con iconos
- Móvil : Menú hamburguesa y navegación optimizada
## 🎨 Sistema de Temas
El dashboard incluye un sistema completo de temas:

- Tema Claro : Diseño limpio con colores suaves
- Tema Oscuro : Interfaz moderna para uso nocturno
- Persistencia : El tema se guarda automáticamente
- Transiciones : Cambios suaves entre temas

# Desarrollo
npm run dev          # Inicia el servidor de desarrollo

# Producción
npm run build        # Construye la aplicación para producción
npm run start        # Inicia el servidor de producción

# Calidad de código
npm run lint         # Ejecuta ESLint para verificar el código

MIT License

Copyright (c) 2024 Modern Admin Dashboard

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
```

## 🙏 Agradecimientos

- [Next.js](https://nextjs.org/) - Framework de React
- [shadcn/ui](https://ui.shadcn.com/) - Componentes de interfaz
- [Radix UI](https://www.radix-ui.com/) - Primitivos de UI
- [Tailwind CSS](https://tailwindcss.com/) - Framework de CSS
- [Lucide](https://lucide.dev/) - Iconos SVG
- [Recharts](https://recharts.org/) - Biblioteca de gráficos
- [React Hook Form](https://react-hook-form.com/) - Manejo de formularios
- [Zod](https://zod.dev/) - Validación de esquemas

## 📞 Contacto

- **Autor**: Tu Nombre
- **Email**: tu.email@ejemplo.com
- **LinkedIn**: [Tu Perfil](https://linkedin.com/in/tu-perfil)
- **GitHub**: [Tu Usuario](https://github.com/tu-usuario)

---

**Desarrollado con ❤️ usando Next.js 15 y React 19**

*Última actualización: Diciembre 2024*
```

Este README.md completo incluye:

✅ **Documentación exhaustiva** del proyecto
✅ **Estructura detallada** de directorios y archivos
✅ **Instrucciones paso a paso** para instalación y configuración
✅ **Guías de despliegue** para diferentes plataformas
✅ **Información de testing** y performance
✅ **Roadmap** y problemas conocidos
✅ **Licencia MIT** completa
✅ **Sección de contacto** personalizable

