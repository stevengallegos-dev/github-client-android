# 📱 GitHub Client Android

Aplicación Android desarrollada con **Kotlin y Jetpack Compose** que permite gestionar repositorios de GitHub mediante su **API REST**.

El proyecto fue realizado con fines académicos a partir de una base proporcionada por el docente y posteriormente ampliado con autenticación, consumo de API y funcionalidades para la gestión de repositorios.

## 👨‍💻 Autor

**Steven Gallegos**  
Estudiante de Ingeniería de Software

## 🚀 Funcionalidades

- Inicio de sesión mediante usuario y Personal Access Token de GitHub.
- Consulta de repositorios desde la API de GitHub.
- Creación de nuevos repositorios.
- Edición de nombre y descripción.
- Eliminación de repositorios con confirmación.
- Actualización automática de la lista después de realizar operaciones.
- Cierre de sesión.
- Manejo de estados mediante ViewModel y StateFlow.

## 🛠️ Tecnologías utilizadas

- Kotlin
- Jetpack Compose
- Material Design 3
- Retrofit
- OkHttp
- Gson
- GitHub REST API
- Coroutines
- StateFlow
- ViewModel
- SharedPreferences
- Gradle

## 🔐 Autenticación

La aplicación utiliza un **Personal Access Token (PAT)** para autenticar las solicitudes realizadas a GitHub.

El token se ingresa desde la pantalla de inicio de sesión y se utiliza para autorizar las peticiones realizadas mediante Retrofit y OkHttp.

> ⚠️ Los tokens de acceso son información privada y nunca deben publicarse dentro del repositorio.

## 📱 Flujo principal

```text
Inicio de sesión
       ↓
Autenticación
       ↓
GitHub REST API
       ↓
Lista de repositorios
       ↓
Crear / Editar / Eliminar
```

## ⚙️ Ejecución

1. Clonar el repositorio:

```bash
git clone https://github.com/stevengallegos-dev/github-client-android.git
```

2. Abrir el proyecto en **Android Studio**.
3. Esperar la sincronización de Gradle.
4. Ejecutarlo en un emulador o dispositivo Android.
5. Iniciar sesión con un usuario de GitHub y un Personal Access Token válido.

## 🎓 Contexto académico

El proyecto comenzó como un laboratorio enfocado en interfaces Android con **Jetpack Compose**.

A partir de la base proporcionada por el docente, se ampliaron las funcionalidades para incorporar la integración con la **API REST de GitHub**, autenticación y operaciones de creación, edición y eliminación de repositorios.

## 📌 Estado

**Funcional** — permite autenticarse, consultar y gestionar repositorios de GitHub desde la aplicación Android.