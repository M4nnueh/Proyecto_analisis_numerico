# Proyecto Análisis Numérico

Frontend de la plataforma **NumTech Academy** — una aplicación Angular para el aprendizaje de Análisis Numérico.

## Requisitos previos

- [Node.js](https://nodejs.org/) v18 o superior
- npm v9 o superior

## Instalación

```bash
npm install
```

## Servidor de desarrollo

```bash
ng serve
```

Abre el navegador en `http://localhost:4200/`. La aplicación se recargará automáticamente al modificar los archivos fuente.

## Compilar para producción

```bash
ng build
```

Los artefactos de compilación se guardan en el directorio `dist/`.

## Estructura del proyecto

```
src/
├── app/
│   ├── anuncios/          # Componente de anuncios
│   ├── auth/              # Configuración de autenticación
│   ├── blog.component/    # Componente de blog/noticias
│   ├── components/        # Componentes compartidos (header)
│   ├── cursos/            # Detalle de cursos
│   ├── dashboard-admin/   # Dashboard del administrador
│   ├── dashboard-estudiante/ # Dashboard del estudiante
│   ├── dashboard-profesor/   # Dashboard del profesor
│   ├── evaluar/           # Evaluaciones y cuestionarios
│   ├── home/              # Página principal
│   ├── login/             # Inicio de sesión
│   ├── nosotros/          # Página "Nosotros"
│   ├── preguntas/         # Banco de preguntas
│   ├── register/          # Registro de usuarios
│   ├── services/          # Servicios (auth, admin, etc.)
│   └── temas/             # Gestión de temas y detalle
├── index.html
├── main.ts
└── styles.css
```

## Tecnologías

- **Angular** 21
- **Bootstrap** 5
- **Font Awesome** 7
- **Chart.js** 4
