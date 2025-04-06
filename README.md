# 📱 Aplicación de Tareas con React Native

## Descripción del Proyecto
Este proyecto fue desarrollado como parte del parcial de la asignatura de Desarrollo de Aplicaciones Móviles. Consiste en una aplicación de lista de tareas (To-Do) que implementa autenticación de usuarios y almacenamiento local de datos. El objetivo principal era demostrar la comprensión de los conceptos fundamentales de React Native vistos en clase.

## 🛠️ Tecnologías y Dependencias Utilizadas
- **React Native**: Framework para desarrollo de aplicaciones móviles
- **Expo**: Plataforma para facilitar el desarrollo de React Native
- **Firebase**: Para la autenticación de usuarios
  - firebase/app
  - firebase/auth
- **AsyncStorage**: Para almacenamiento local de datos
  - @react-native-async-storage/async-storage
- **React Navigation**: Para la navegación entre pantallas
  - @react-navigation/native
  - @react-navigation/stack
  - react-native-screens
  - react-native-safe-area-context
  - react-native-gesture-handler
- **Expo Vector Icons**: Para los íconos de la aplicación
  - @expo/vector-icons

### Instalación de Dependencias
```bash
# Instalación de dependencias principales
npm install expo firebase @react-native-async-storage/async-storage

# Instalación de React Navigation y dependencias relacionadas
npm install @react-navigation/native @react-navigation/stack
npm install react-native-screens react-native-safe-area-context
npm install react-native-gesture-handler

# Expo Vector Icons viene incluido con Expo
