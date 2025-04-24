# Clave Segura Pro - Generador de Contraseñas

## Descripción
Un generador de contraseñas moderno y elegante desarrollado con HTML, CSS y JavaScript vanilla. La aplicación permite a los usuarios crear contraseñas seguras y personalizables con una interfaz atractiva que implementa tendencias de diseño contemporáneas.

## Características Principales
- Generación de contraseñas con opciones personalizables
- Ajuste de longitud mediante control deslizante (6-25 caracteres)
- Inclusión opcional de mayúsculas, números y símbolos
- Función de copiado al portapapeles con un solo clic
- Notificaciones mediante toast notifications
- Interfaz completamente en español

## Aspectos Técnicos y Prácticas Modernas

### Diseño UI/UX
- **Glassmorphism**: La aplicación implementa el popular efecto de glassmorphism con fondos semitransparentes, desenfoque (blur) y bordes sutiles para crear una sensación de profundidad y modernidad.
- **Toast Notifications**: Incorpora notificaciones tipo "toast" no intrusivas para informar al usuario cuando la contraseña ha sido copiada al portapapeles.
- **Animaciones**: Incluye animaciones de entrada suaves para los elementos y fondos dinámicos que mejoran la experiencia de usuario.
- **Tipografía personalizada**: Utiliza fuentes personalizadas (Comic y Clouds) para darle un carácter único a la interfaz.

### Código y Estructura
- **JavaScript Vanilla**: Utiliza JavaScript puro sin dependencias externas, lo que mejora el rendimiento y evita sobrecarga innecesaria.
- **Separación de Responsabilidades**: Mantiene el HTML, CSS y JavaScript en archivos separados siguiendo las mejores prácticas de desarrollo web.
- **CSS Moderno**: Implementa características de CSS moderno como flexbox, animaciones, transformaciones y variables.

## Estructura del Proyecto
```
clave-segura-pro/
│
├── index.html          # Estructura HTML principal
├── style.css           # Estilos CSS y animaciones
├── script.js           # Funcionalidad JavaScript
└── font/               # Directorio de fuentes personalizadas
    ├── Comic.ttf
    └── Clouds.otf
```

## Cómo Ejecutar el Proyecto
1. Clona o descarga todos los archivos del repositorio
2. Mantén la estructura de archivos intacta, especialmente el directorio de fuentes
3. Abre el archivo `index.html` en cualquier navegador web moderno
4. Alternativamente, puedes alojar los archivos en cualquier servidor web estático

## Uso
1. Ajusta la longitud de la contraseña usando el control deslizante
2. Selecciona las opciones deseadas (mayúsculas, números, símbolos)
3. Haz clic en "Crear Contraseña" para generar una nueva contraseña
4. Usa el botón "Copiar" para copiar la contraseña al portapapeles
5. Una notificación toast te confirmará que la contraseña fue copiada exitosamente
