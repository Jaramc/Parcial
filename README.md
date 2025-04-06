
## 🚀 Instalación y Ejecución
Para instalar y ejecutar este proyecto:

1. Clonar este repositorio
2. Instalar las dependencias con `npm install`
3. Configurar el proyecto en Firebase y actualizar la configuración en `src/api/firebase.js`
4. Ejecutar `expo start` para iniciar la aplicación

## 💡 Conceptos Aplicados
Durante el desarrollo de este parcial, se aplicaron los siguientes conceptos vistos en clase:

- **Autenticación con Firebase**: Implementación de registro e inicio de sesión.
- **Contextos en React**: Uso del Context API para manejar el estado global.
- **AsyncStorage**: Almacenamiento local de datos en el dispositivo.
- **Navegación**: Implementación de navegación entre pantallas y protección de rutas.
- **Estructura de Proyectos**: Organización modular del código siguiendo las prácticas recomendadas.

## 🔄 Desarrollo del Parcial
El desarrollo del parcial siguió las etapas recomendadas en clase:

1. Configuración inicial del proyecto y Firebase
2. Implementación de la autenticación de usuarios
3. Desarrollo de la funcionalidad de tareas
4. Implementación del almacenamiento local
5. Mejoras en la interfaz de usuario

Durante el desarrollo, enfrenté algunos desafíos técnicos como problemas con la navegación después del login y errores en las importaciones debido a nombres incorrectos de carpetas, pero logré resolverlos aplicando los conocimientos adquiridos en clase.

## 🎨 Sistema de Colores
Siguiendo las indicaciones del profesor, implementé un sistema de colores centralizado para mantener la consistencia visual en toda la aplicación:

```javascript
// Ejemplo de colors.js
export default {
  principal: '#4a6da7',
  variante1: '#3a5d97',
  variante2: '#5a7db7',
  // ... más colores
}
