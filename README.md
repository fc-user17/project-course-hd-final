# 🛠️ Help Desk - Sistema de Soporte Técnico

Sistema web de soporte técnico desarrollado como proyecto académico para el curso de **Herramientas de Desarrollo de Software**.

El sistema tiene como finalidad permitir la gestión de incidencias o tickets de soporte técnico dentro de una organización, facilitando la comunicación entre usuarios, técnicos y administradores.

El proyecto se desarrolla aplicando herramientas y prácticas de desarrollo colaborativo, control de versiones, integración continua, contenedores y despliegue de aplicaciones.

---

## 📌 Descripción del proyecto

**Help Desk** es una plataforma web que permite a los usuarios registrar problemas o incidencias relacionadas con equipos, sistemas, aplicaciones, redes u otros servicios tecnológicos.

Los técnicos de soporte pueden visualizar, gestionar y resolver los tickets asignados, mientras que los administradores pueden supervisar las incidencias, gestionar usuarios y consultar estadísticas del sistema.

El proyecto busca demostrar no solamente el desarrollo de una aplicación web, sino también la aplicación de un flujo de trabajo profesional utilizando herramientas de desarrollo modernas.

---

## 🎯 Objetivo general

Desarrollar e implementar un sistema web de soporte técnico que permita gestionar incidencias mediante un flujo organizado de registro, asignación, seguimiento y resolución de tickets, aplicando herramientas de control de versiones, colaboración, integración continua, contenedores y despliegue.

---

## 🎯 Objetivos específicos

- Implementar un sistema de autenticación de usuarios.
- Gestionar diferentes roles dentro del sistema.
- Permitir el registro y seguimiento de tickets.
- Permitir la asignación de tickets a técnicos.
- Gestionar prioridades y estados de las incidencias.
- Permitir la comunicación mediante comentarios.
- Implementar un dashboard con información general de los tickets.
- Aplicar Git para el control de versiones.
- Utilizar ramas para organizar el desarrollo de funcionalidades.
- Utilizar Pull Requests para integrar cambios.
- Aplicar buenas prácticas de commits.
- Gestionar tareas mediante Issues.
- Aplicar integración continua.
- Implementar la aplicación mediante contenedores Docker.
- Realizar el despliegue de la aplicación en un entorno cloud.

---

# 👥 Roles del sistema

El sistema contará con tres roles principales.

## 👤 Usuario

El usuario es quien reporta los problemas.

Puede:

- Iniciar sesión.
- Registrar tickets.
- Consultar sus tickets.
- Visualizar el estado de sus incidencias.
- Agregar comentarios.
- Consultar la solución de un ticket.
- Cerrar un ticket cuando el problema haya sido solucionado.

---

## 🧑‍💻 Técnico

El técnico es responsable de atender las incidencias.

Puede:

- Visualizar tickets asignados.
- Consultar información de los tickets.
- Cambiar el estado de una incidencia.
- Cambiar la prioridad.
- Agregar comentarios.
- Registrar la solución.
- Marcar un ticket como resuelto.

---

## 👨‍💼 Administrador

El administrador supervisa el funcionamiento del sistema.

Puede:

- Gestionar usuarios.
- Gestionar técnicos.
- Gestionar categorías.
- Visualizar todos los tickets.
- Asignar tickets.
- Modificar prioridades.
- Consultar estadísticas.
- Gestionar configuraciones del sistema.

---

# 🎫 Gestión de tickets

Los tickets representan las incidencias reportadas por los usuarios.

Cada ticket contará con información como:

- Código del ticket.
- Título.
- Descripción.
- Usuario que reportó el problema.
- Técnico asignado.
- Categoría.
- Prioridad.
- Estado.
- Fecha de creación.
- Fecha de actualización.
- Fecha de resolución.
- Comentarios.
- Solución registrada.

---

## 🔄 Estados de un ticket

El flujo básico de atención será:

```text
┌─────────┐
│ ABIERTO │
└────┬────┘
     ↓
┌───────────┐
│ ASIGNADO  │
└─────┬─────┘
      ↓
┌─────────────┐
│ EN PROGRESO │
└──────┬──────┘
       ↓
┌───────────┐
│ RESUELTO  │
└─────┬─────┘
      ↓
┌──────────┐
│ CERRADO  │
└──────────┘
