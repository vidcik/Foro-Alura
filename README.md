# Foro Estilo Reddit

Este es un proyecto de un foro básico que simula el estilo de Reddit, donde los usuarios pueden registrarse, iniciar sesión, crear temas, y eliminar mensajes. La información de los usuarios y los temas se guarda en `localStorage` del navegador para persistir los datos entre sesiones.

## Funcionalidades

- **Registro de usuario**: Los usuarios pueden registrarse con un nombre de usuario, contraseña y una foto de perfil.
- **Inicio de sesión**: Los usuarios pueden iniciar sesión con su nombre de usuario y contraseña registrados.
- **Creación de temas**: Una vez iniciada la sesión, los usuarios pueden crear temas con un título y contenido.
- **Eliminar temas**: Los usuarios pueden eliminar los temas que hayan creado desde la interfaz de usuario.
- **Foto de perfil**: El perfil del usuario incluye una foto que se muestra en la interfaz después de iniciar sesión.

## Requisitos

- Navegador web moderno con soporte para `localStorage`.
- Sin necesidad de servidor, ya que todo se maneja en el cliente (navegador).

## Estructura del Proyecto

El proyecto está compuesto por un único archivo HTML (`index.html`) que contiene todo el código JavaScript y los estilos necesarios para el funcionamiento del foro.

- `index.html`: Contiene la interfaz de usuario, los formularios de registro e inicio de sesión, y la lógica de creación y eliminación de temas.
- `localStorage`: La información del usuario y los temas se guarda en el `localStorage` del navegador.

## Instrucciones de Uso

1. **Abrir el archivo HTML**: Descarga o clona este proyecto y abre el archivo `index.html` en tu navegador.
2. **Registrar un nuevo usuario**:
   - Introduce un nombre de usuario, una contraseña y selecciona una foto de perfil.
   - Haz clic en "Registrar" para crear tu cuenta.
3. **Iniciar sesión**:
   - Introduce el nombre de usuario y la contraseña del usuario registrado.
   - Haz clic en "Iniciar sesión" para acceder al foro.
4. **Crear un nuevo tema**:
   - Una vez dentro del foro, puedes escribir un título y contenido para un nuevo tema.
   - Haz clic en "Crear tema" para publicarlo.
5. **Eliminar un tema**:
   - Cada tema tiene un botón "Borrar" que permite eliminarlo.
   - Al eliminar un tema, se actualizará la lista de temas mostrada.

## Mejoras Futuras

- **Persistencia a largo plazo**: Actualmente, los datos se almacenan solo en `localStorage` del navegador. Se podría integrar con una base de datos para almacenar la información de forma más permanente.
- **Autenticación avanzada**: Implementar un sistema de autenticación con backend para manejar usuarios y sesiones de manera más segura.
- **Estilo avanzado**: Mejorar el diseño visual con CSS y/o frameworks como Bootstrap.

## Contribuciones

Si deseas contribuir a este proyecto, siéntete libre de enviar un pull request o abrir un problema (issue) si encuentras algún error.

## Licencia

Este proyecto está bajo la Licencia MIT - consulta el archivo [LICENSE](LICENSE) para más detalles.

