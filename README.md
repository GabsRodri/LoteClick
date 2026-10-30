# LoteClick 🏗️

**Plataforma web para la gestión y administración de procesos en empresas constructoras.**

LoteClick es una aplicación web desarrollada como proyecto académico de Ingeniería de Sistemas de la Universidad Piloto de Colombia. Su propósito es apoyar la gestión de información y procesos de una empresa constructora mediante una plataforma centralizada, organizada y accesible según los roles de usuario.

El proyecto busca facilitar la administración de usuarios, la organización de procesos y el seguimiento de la información relacionada con la actividad constructiva.

## 🎯 Objetivo del proyecto

Desarrollar una solución tecnológica que facilite la gestión de procesos de una empresa constructora, proporcionando herramientas para organizar la información, administrar usuarios y ofrecer funcionalidades diferenciadas según las responsabilidades de cada rol.

## ⚙️ Funcionalidades

Entre las funcionalidades contempladas en el sistema se encuentran:

- **Autenticación de usuarios:** registro e inicio de sesión.
- **Gestión de roles:** acceso diferenciado para administradores, supervisores y empleados.
- **Control de acceso:** protección de rutas y funcionalidades según el rol del usuario.
- **Gestión administrativa:** herramientas para la administración de usuarios y procesos.
- **Gestión de lotes:** funcionalidades orientadas a la organización y seguimiento de lotes.
- **Gestión de proyectos:** administración de información relacionada con los proyectos de construcción.

*Nota: las funcionalidades se encuentran sujetas al estado de implementación de cada módulo.*

## 🛠️ Tecnologías utilizadas

| Tecnología | Aplicación |
|---|---|
| [Next.js](https://nextjs.org/) | Framework para el desarrollo de la aplicación web. |
| [React](https://react.dev/) | Construcción de interfaces de usuario. |
| [JavaScript](https://developer.mozilla.org/es/docs/Web/JavaScript) | Lógica de la aplicación. |
| [Supabase](https://supabase.com/) | Servicios de base de datos y autenticación. |
| [PostgreSQL](https://www.postgresql.org/) | Sistema de gestión de bases de datos utilizado por Supabase. |
| [Tailwind CSS](https://tailwindcss.com/) | Estilos y diseño de la interfaz. |
| [Git](https://git-scm.com/) y [GitHub](https://github.com/) | Control de versiones y gestión del código fuente. |

## 👥 Roles de usuario

La aplicación contempla tres roles principales:

- **Administrador:** encargado de las funciones administrativas y la gestión de usuarios.
- **Supervisor:** orientado a la supervisión y seguimiento de procesos relacionados con los lotes.
- **Empleado:** dispone de funcionalidades relacionadas con la gestión de sus proyectos y actividades.

Cada rol cuenta con permisos y accesos diferenciados dentro de la aplicación.

## 🚀 Instalación y ejecución local

### Requisitos previos

Para ejecutar el proyecto necesitas:

- [Node.js](https://nodejs.org/)
- npm
- Una cuenta y un proyecto configurado en [Supabase](https://supabase.com/).
- Git.

### 1. Clonar el repositorio

```bash
git clone https://github.com/GabsRodri/LoteClick.git
```

### 2. Acceder al directorio

```bash
cd LoteClick
```

### 3. Instalar las dependencias

```bash
npm install
```

### 4. Configurar las variables de entorno

Crea un archivo `.env.local` en la raíz del proyecto y agrega las credenciales de tu proyecto de Supabase:

```env
NEXT_PUBLIC_SUPABASE_URL=TU_SUPABASE_PROJECT_URL
NEXT_PUBLIC_SUPABASE_ANON_KEY=TU_SUPABASE_ANON_KEY
```

Puedes obtener estos valores desde la configuración de API de tu proyecto en Supabase.

**Importante:** no compartas claves privadas ni credenciales sensibles en el repositorio.

### 5. Ejecutar el servidor de desarrollo

```bash
npm run dev
```

### 6. Abrir la aplicación

Ingresa desde tu navegador a:

```text
http://localhost:3000
```

## 📁 Estructura del proyecto

El proyecto utiliza la arquitectura de Next.js App Router. La organización general del código se basa en directorios para páginas, componentes, funcionalidades y configuración de servicios.

```text
LoteClick/
├── app/
│   ├── components/
│   ├── protected/
│   ├── sign-in/
│   ├── sign-up/
│   └── ...
├── utils/
│   └── supabase/
├── public/
├── package.json
└── README.md
```

*La estructura puede variar según la evolución del proyecto.*

## 🎓 Contexto académico

Proyecto desarrollado en el marco de la formación académica del programa de Ingeniería de Sistemas de la Universidad Piloto de Colombia.

## 👩‍💻 Repositorio

[Consultar el código fuente de LoteClick en GitHub](https://github.com/GabsRodri/LoteClick).
