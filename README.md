# GitHub Copilot Mobile

Una aplicación móvil nativa desarrollada con **Flutter** que lleva la potencia de GitHub Copilot directamente a tu dispositivo. Inspirada en Open Code, esta aplicación permite a los desarrolladores acceder a sugerencias de código y asistencia de IA en tiempo real desde cualquier lugar.

## 🚀 Características

- **Asistente de Código Inteligente**: Obtén sugerencias de código impulsadas por IA en tiempo real.
- **Interfaz Móvil Optimizada**: Diseñada para ser fluida y responsiva en dispositivos iOS y Android.
- **Integración con GitHub**: Conecta tu cuenta de GitHub para acceder a tus repositorios.
- **Chat Interactivo**: Conversaciones en tiempo real con el asistente de IA.
- **Historial de Conversaciones**: Guarda y revisa tus consultas anteriores.
- **Acciones Rápidas**: Acceso directo a funciones como completado de código, debugging, documentación y revisión de código.
- **Modo Oscuro**: Soporte completo para tema claro y oscuro que se adapta automáticamente.
- **Soporte Multiplataforma**: Funciona en iOS, Android, Web y escritorio (Windows, macOS, Linux).

## 🛠️ Tecnologías

- **Framework**: Flutter 3.41.4
- **Lenguaje**: Dart 3.11.1
- **Plataformas Soportadas**: iOS, Android, Web, Windows, macOS, Linux

## 📦 Estructura del Proyecto

```
github_copilot_mobile/
├── lib/
│   ├── main.dart              # Punto de entrada de la aplicación
│   ├── screens/               # Pantallas de la aplicación
│   │   ├── home_screen.dart   # Pantalla principal con acciones rápidas
│   │   ├── chat_screen.dart   # Pantalla de chat con el asistente
│   │   └── settings_screen.dart # Configuración de la aplicación
│   ├── widgets/               # Componentes reutilizables
│   ├── services/              # Servicios de API y lógica de negocio
│   ├── models/                # Modelos de datos
│   └── utils/                 # Utilidades y constantes
├── assets/                    # Imágenes, fuentes y otros recursos
├── test/                      # Pruebas unitarias
├── android/                   # Configuración específica de Android
├── ios/                       # Configuración específica de iOS
├── web/                       # Configuración específica de Web
├── windows/                   # Configuración específica de Windows
├── macos/                     # Configuración específica de macOS
├── linux/                     # Configuración específica de Linux
├── pubspec.yaml              # Dependencias del proyecto
└── README.md                 # Este archivo
```

## 🚀 Primeros Pasos

### Requisitos Previos

- Flutter 3.41.4 o superior
- Dart 3.11.1 o superior
- Un dispositivo o emulador iOS/Android

### Instalación

1. **Clona el repositorio**:
   ```bash
   git clone https://github.com/edies76/Github-copilot-mobile.git
   cd Github-copilot-mobile
   ```

2. **Instala las dependencias**:
   ```bash
   flutter pub get
   ```

3. **Ejecuta la aplicación**:
   ```bash
   flutter run
   ```

## 📱 Plataformas Soportadas

- **iOS**: Requiere iOS 12.0 o superior
- **Android**: Requiere Android 5.0 (API 21) o superior
- **Web**: Compatible con navegadores modernos
- **Desktop**: Windows, macOS y Linux

## 🔧 Desarrollo

### Ejecutar en Modo Debug

```bash
flutter run -d <device_id>
```

### Ejecutar en un Dispositivo Específico

```bash
# Ver dispositivos disponibles
flutter devices

# Ejecutar en Android
flutter run -d android

# Ejecutar en iOS
flutter run -d ios

# Ejecutar en Web
flutter run -d chrome
```

### Compilar para Producción

**Android**:
```bash
flutter build apk --release
```

**iOS**:
```bash
flutter build ios --release
```

**Web**:
```bash
flutter build web --release
```

## 🎨 Funcionalidades Implementadas

### Pantalla Principal (Home)
- ✅ Tarjeta de bienvenida personalizada
- ✅ Acciones rápidas con iconos
- ✅ Historial de conversaciones recientes
- ✅ Navegación fluida entre secciones

### Pantalla de Chat
- ✅ Interfaz de chat interactiva
- ✅ Burbujas de mensajes diferenciadas (usuario/asistente)
- ✅ Campo de texto con envío mediante Enter
- ✅ Timestamps formatados
- ✅ Respuestas simuladas del asistente

### Pantalla de Configuración
- ✅ Gestión de cuenta de GitHub
- ✅ Configuración de API Key
- ✅ Toggle de modo oscuro
- ✅ Control de notificaciones
- ✅ Selector de idioma
- ✅ Información de la versión
- ✅ Enlaces a términos y privacidad

### Características Generales
- ✅ Material Design 3
- ✅ Modo oscuro automático según preferencias del sistema
- ✅ Navegación inferior con 3 secciones
- ✅ Tipografía Google Fonts (Inter)
- ✅ Animaciones y transiciones suaves

## 📝 Contribuciones

Las contribuciones son bienvenidas. Por favor, abre un issue o un pull request para sugerencias y mejoras.

## 🚧 Próximas Características

- 🔄 Integración real con GitHub Copilot API
- 🔐 Autenticación OAuth con GitHub
- 💾 Persistencia de conversaciones en base de datos local
- 🔍 Búsqueda en historial de conversaciones
- 📊 Estadísticas de uso
- 🌐 Soporte multilenguaje completo (i18n)
- 🎤 Entrada de voz para consultas
- 📤 Compartir código generado
- 🔔 Sistema de notificaciones push
- ⚙️ Configuración avanzada de preferencias del asistente

## 📄 Licencia

Este proyecto está bajo la licencia MIT. Consulta el archivo `LICENSE` para más detalles.

## 👨‍💻 Desarrollado por

Desarrollado con la ayuda de **Manus** - Un agente de IA autónomo.

---

**Nota**: Esta aplicación es un proyecto en desarrollo. Las características y funcionalidades pueden cambiar.
