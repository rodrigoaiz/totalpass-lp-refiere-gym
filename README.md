# TotalPass - Landing Page Refiere Gimnasios

Landing page para la campaña de referidos de gimnasios, estudios y spas de TotalPass. Esta página permite a los propietarios de gimnasios registrarse para formar parte de la red de aliados de TotalPass.

## 📋 Descripción

Esta es una landing page desarrollada con HTML, CSS (Tailwind CSS) y configurada para ejecutarse en un contenedor Docker con Apache. La página incluye:

- Formulario de registro para propietarios de gimnasios
- Información sobre los beneficios de ser aliado TotalPass
- Casos de éxito de gimnasios aliados
- Diseño responsive y moderno

## 🛠️ Tecnologías

- **HTML5** - Estructura de la página
- **Tailwind CSS** - Framework de CSS para estilos
- **PostCSS** - Procesador de CSS
- **Apache** - Servidor web
- **Docker** - Contenedorización

## 📦 Instalación

### Requisitos previos
- Node.js (versión 14 o superior)
- Git

### 1. Clonar el repositorio
```bash
git clone <url-del-repositorio>
cd totalpass-lp-refiere-gym-usuarios
```

### 2. Instalar dependencias
```bash
npm install
```

## 🚀 Scripts disponibles

### Desarrollo local

```bash
# Compilar CSS una sola vez
npm run build

# Modo desarrollo con auto-compilación y servidor local
npm run dev

# Solo compilar CSS en modo watch (sin servidor)
npm run watch:css

# Generar CSS inline (para optimización)
npm run inline
```

## 🖥️ Uso

### Desarrollo local
1. Ejecuta `npm run dev` para iniciar el servidor de desarrollo
2. Abre tu navegador en `http://localhost:4323`
3. Los cambios en CSS se compilarán automáticamente

### Formulario
El formulario está configurado para enviar datos a Salesforce. Para configurarlo:

1. Edita los valores `oid` y `retURL` en los formularios HTML
2. Ajusta los nombres de los campos según tu configuración de Salesforce

## 📝 Notas importantes

- **CSS**: Los cambios en `src/input.css` requieren compilación con `npm run build`

## 🤝 Contribución

1. Fork el proyecto
2. Crea una rama para tu feature (`git checkout -b feature/nueva-funcionalidad`)
3. Commit tus cambios (`git commit -m 'Agregar nueva funcionalidad'`)
4. Push a la rama (`git push origin feature/nueva-funcionalidad`)
5. Abre un Pull Request
