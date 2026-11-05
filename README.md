Bienestar 360 - Prototipo Web Interactivo

Plataforma web interactiva orientada a la promocion de habitos saludables, bienestar integral y salud preventiva para usuarios adultos. Implementada como una aplicacion de pagina unica (SPA) responsiva con tecnologias web estandar (HTML5, CSS3 y JavaScript Vanilla) y desplegada en Firebase Hosting.

Enlaces del Proyecto

Demo en Produccion (Firebase Hosting): https://todoapp-f54d5.web.app/

Repositorio de Codigo: https://github.com/halcondorado123/Bienestar360.git

Sistema de Diseno y Accesibilidad

El diseno visual esta fundamentado en criterios de ergonomia cognitiva y en las directrices de accesibilidad WCAG 2.1 nivel AA:

Paleta de Colores:

Primario: Verde Esmeralda / Salvia (#2E7D32 / #10B981 / #81C784).

Menu Lateral: Verde Bosque Profundo (#0C271E).

Superficies: Neutro / Blanco (#F8F9FA / #FFFFFF).

Contraste: Texto principal en #212121 sobre fondo claro con ratio superior a 7:1.

Tipografia: Jerarquia establecida con la familia tipografica Inter / Roboto (interlineado base de 1.5).

Componentes UI: Tarjetas modulares con bordes redondeados (border-radius: 12px), microinteracciones directas y botones de accion accesibles.

Funcionalidades y Pantallas Implementadas

01 - Inicio (Dashboard General): Visualizacion de categorias principales (Alimentacion, Actividad Fisica, Descanso, Bienestar) y seleccion de recomendaciones destacadas.

02 - Explorar: Catalogo interactivo con filtrado facetado por categoria, objetivo y tipo de contenido, complementado con busqueda de texto en tiempo real.

03 - Detalle: Vista de lectura estructurada con pasos guiados y acciones directas para marcar habitos o almacenar en favoritos.

04 - Registro: Formulario de creacion de cuenta con validaciones de campos y terminos.

05 - Iniciar sesion: Modulo de autenticacion con enlaces directos hacia registro y recuperacion.

06 - Mi perfil: Administracion de informacion personal, seleccion de objetivos de salud y preferencias de contenido.

07 - Favoritos: Listado dinamico de contenidos guardados con opcion de remocion directa.

08 - Mis habitos: Rastreador de metas con barras de progreso interactivo para agua (vasos), ejercicio (minutos) y descanso (horas).

Tecnologias Utilizadas

Front-end: HTML5 semantico, CSS3 modular (Flexbox, CSS Grid, Tailwind CSS classes) y JavaScript Vanilla (ES6+).

Infraestructura y Alojamiento: Firebase Hosting (Google Cloud Platform).

Control de Versiones: Git y GitHub.

Instalacion y Ejecucion Local

Para clonar y ejecutar el proyecto en un entorno local:

# 1. Clonar el repositorio
git clone https://github.com/tu-usuario/bienestar-360-web.git

# 2. Entrar al directorio
cd bienestar-360-web

# 3. Servir localmente
npx serve public


Despliegue en Firebase Hosting

Para publicar modificaciones al entorno de produccion:

# Instalar herramientas de Firebase de forma global
npm install -g firebase-tools

# Iniciar sesion en la plataforma
firebase login

# Desplegar el contenido del directorio publico
firebase deploy --only hosting
