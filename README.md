# Lab07 — CRUD de Usuarios con Room

Aplicación Android nativa de gestión de usuarios con persistencia local usando **Room Database**, **Jetpack Compose** y **Material3**.

## Descripción

App de gestión de usuarios con:
- **CRUD básico** de usuarios (nombre y apellido)
- Persistencia local con **Room**
- Arquitectura **MVVM**
- UI moderna con **Jetpack Compose** y **Material3**

## Tecnologías

- **Kotlin**
- **Jetpack Compose**
- **Material3**
- **Room Database**
- **MVVM**
- **Gradle Kotlin DSL**

## Estructura

```
app/src/main/java/com/example/myapplication/
├── ui/theme/     → Tema Material3
├── User.kt       → Entidad Room
├── UserDao.kt    → DAO
├── UserDatabase.kt → Base de datos
├── ScreenUser.kt → UI Compose
└── MainActivity.kt
```

## Cómo ejecutar

Abrir en Android Studio y ejecutar en un dispositivo/emulador con API 24+.
