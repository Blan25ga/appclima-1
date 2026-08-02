# App Clima 🌤️

Una aplicación web interactiva y moderna para consultar el clima en tiempo real de cualquier parte del mundo. Desarrollada con HTML5, CSS3, JavaScript Vanilla y Bootstrap 5.

El proyecto está diseñado para ser ligero, responsivo y fácil de integrar con servicios de hosting como Netlify.

## Características 🌟

- **Búsqueda Global**: Obtén el clima en tiempo real de cualquier ciudad o país.
- **Información Detallada**:
  - Temperatura en grados Celsius (°C) y Fahrenheit (°F).
  - Humedad relativa.
  - Velocidad del viento.
  - Nivel de precipitaciones.
  - Iconos dinámicos que cambian según el estado del clima actual.
- **Fecha y Hora**: Visualización del día de la semana y la fecha de la consulta local.
- **Diseño Responsivo**: Adaptado para dispositivos móviles, tablets y ordenadores de escritorio gracias a Bootstrap 5.

## Tecnologías Utilizadas 🛠️

- **HTML5 & CSS3**: Estructura y estilos adaptados.
- **JavaScript (ES6+)**: Lógica de consumo de API y manipulación dinámica del DOM.
- **Bootstrap 5.2.0**: Framework CSS para un diseño ágil y responsivo.
- **Bootstrap Icons**: Para la iconografía del sistema.
- **WeatherAPI (vía RapidAPI)**: API utilizada para obtener la información meteorológica.

## Estructura del Proyecto 📂

```
appclima-1/
├── css/
│   └── style.css          # Estilos personalizados de la aplicación
├── javascript/
│   └── script.js          # Lógica de consumo de la API de clima
├── index.html             # Estructura principal y maquetado HTML
└── README.md              # Documentación del proyecto
```

## Configuración y Uso Local 💻

1. **Clonar el repositorio**:
   ```bash
   git clone https://github.com/Blan25ga/appclima-1.git
   ```

2. **Abrir el proyecto**:
   Simplemente abre el archivo `index.html` en tu navegador favorito o utiliza la extensión **Live Server** en Visual Studio Code.

3. **API Key (WeatherAPI)**:
   La aplicación utiliza RapidAPI para conectarse a WeatherAPI. La clave de desarrollo está configurada directamente en `javascript/script.js`.

## Despliegue en Netlify 🚀

Esta aplicación se puede subir directamente a Netlify conectando este repositorio de GitHub. 

### Pasos para desplegar:
1. Ve a [Netlify](https://www.netlify.com/).
2. Inicia sesión y haz clic en **Add new site** > **Import an existing project**.
3. Selecciona **GitHub** y autoriza el acceso a este repositorio (`appclima-1`).
4. En las configuraciones de compilación, deja los campos vacíos (ya que es un proyecto de HTML/JS estático y no requiere compilación).
5. Haz clic en **Deploy site** ¡y listo! Tu web estará online en segundos.
