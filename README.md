# ChallengeApp

## LOGO

![image](https://github.com/user-attachments/assets/d99554f7-2360-437f-8d73-f2f74b2d8a85)

## Integrantes

- Alfredo Mituy Okenve Obiang
- José Luis Obiang Ela Nanguang

## Eslogan

Supera tus retos, alcanza nuevas metas

## Resumen

La aplicación web permite a los usuarios crear, unirse y seguir su progreso en retos de hábitos comunitarios, como ejercicio y lectura. Fomenta la motivación y la constancia a través de la competencia amistosa y el apoyo social.

## Descripción

El objetivo de esta aplicación web es proporcionar una plataforma donde los usuarios puedan crear, unirse y seguir su progreso en retos de hábitos comunitarios. Cada usuario puede participar en diferentes desafíos personales (ejercicio, lectura, meditación, etc.), ver su progreso y el de otros usuarios, y compartir sus avances dentro de una comunidad de soporte. La idea es fomentar la motivación y la constancia a través de la competencia amistosa y la colaboración social.

### Funcionalidades, Requisitos, “Pliego de condiciones”...

- El usuario debe poder registrarse e iniciar sesión en la App
  - El usuario introducirá un nombre de usuario, el correo electrónico y una contraseña.
- El usuario debe poder crear nuevos retos y gestionarlos
  - El usuario indicará el tipo de reto según el nivel de complejidad (simple o complejo: con subtareas)
  - El usuario indicará el tipo de reto (privado, público).
- El usuario debe poder unirse a distintos retos e ir marcando su progreso en los mismos
- El usuario debe poder hacer comentarios y leer los de otros usuarios
- El usuario debe poder acceder al historial de retos que ha completado y también de los que ha creado.
- El usuario podrá recibir recompensas e insignias de los retos que vaya completando.
- El usuario debe poder añadir amigos a los que retar con retos privados
- El usuario podrá ver una estadística del progreso de todos sus retos.

### Funcionalidades opcionales, recomendables o futuribles

- El usuario podrá filtrar retos según la ubicación del usuario, el tipo de reto, nombre, etc.
- El usuario podrá cambiar el color de fondo de la página web (oscuro, claro).
- El usuario podrá elegir el idioma de la página web.
- El usuario podrá recibir notificaciones sobre su progreso y las medallas o recompensas que vaya obteniendo.

```mermaid
graph TD
    A[Funcionalidades y Requisitos de ChallengeApp] --> B[Registro e Inicio de Sesión]
    B --> B1[Registro con: Nombre de Usuario, Correo Electrónico, Contraseña]
    B --> B2[Iniciar Sesión con: Correo Electrónico y Contraseña]

    A --> C[Gestión de Retos]
    C --> C1[Crear nuevos retos]
    C1 --> C1a[Indicar nivel de complejidad: Simple o Complejo]
    C1 --> C1b[Indicar tipo de reto: Público o Privado]
    C --> C2[Gestionar retos creados]
    C --> C3[Unirse a retos]
    C --> C4[Marcar progreso en los retos]
    C --> C5[Acceder a historial de retos completados y creados]

    A --> D[Interacción Social]
    D --> D1[Hacer comentarios en retos]
    D --> D2[Leer comentarios de otros usuarios]
    D --> D3[Añadir amigos para retos privados]
  
    A --> E[Gamificación]
    E --> E1[Recibir recompensas e insignias]
    E --> E2[Ver estadísticas del progreso en retos]

    style A fill:#f9f,stroke:#333,stroke-width:2px;
    style B fill:#bbf,stroke:#333,stroke-width:2px;
    style C fill:#cfc,stroke:#333,stroke-width:2px;
    style D fill:#ffc,stroke:#333,stroke-width:2px;
    style E fill:#ffccbb,stroke:#333,stroke-width:2px;
```

# Enlaces de Gemini

[Gemini(Markdown & Github)](https://g.co/gemini/share/018e821a2eb5)
