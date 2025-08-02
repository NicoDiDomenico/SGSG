# SGSG - Sistema de Gestión de Socios para Gimnasios

## Descripción del proyecto

**SGSG** es un sistema de escritorio desarrollado en **C# (.NET Framework)** que gestiona integralmente el funcionamiento de gimnasios. Permite la administración de socios, turnos, rutinas, personal, máquinas, equipamientos y horarios, garantizando un control operativo completo.

El sistema busca aumentar la eficiencia en la gestión diaria de un gimnasio, mejorar la experiencia de los socios y ofrecer herramientas de toma de decisiones al Dueño/Administrador.

---

## Características principales

- **Gestión de Socios**  
  Registro, modificación, baja lógica y restauración de socios. Control de cuotas y acceso al gimnasio.

- **Gestión de Turnos**  
  Administración de reservas de turnos por parte del Asistente, con control de cupos, horarios y entrenadores.  
  Envío automático de notificaciones por correo electrónico.

- **Gestión de Rutinas**  
  Creación, modificación y seguimiento de rutinas de entrenamiento (calentamiento, entrenamiento y estiramiento).

- **Gestión del Gimnasio**  
  Administración de máquinas, ejercicios, equipamiento y personal.  
  Asignación de entrenadores a horarios y control de permisos.

- **Módulo de Seguridad**  
  Control de accesos por roles y acciones específicas.  
  Auditoría de logins y acciones críticas.

- **Reportes y estadísticas**  
  Reportes PDF con datos cruzados y gráficos para la toma de decisiones.

---

## Tecnologías utilizadas

- **Lenguaje:** C# (.NET Framework, ADO.NET)
- **Base de datos:** SQL Server (con procedimientos almacenados)
- **Arquitectura:** MVC (Controlador, DAO, Modelo)
- **Frontend:** WinForms
- **IDE:** Visual Studio

---

## Roles del sistema

- **Dueño/Administrador:** Control total del sistema.
- **Asistente:** Gestión de turnos y socios.
- **Entrenador:** Gestión de rutinas y seguimiento de socios.

---

## Instalación y ejecución

1. Clonar el repositorio
2. Configurar la base de datos en SQL Server utilizando los scripts incluidos
3. Abrir el proyecto en Visual Studio
4. Compilar y ejecutar la solución

---

## Autor

**Di Domenico Nicolás Alejandro**  
Trabajo de Diploma - Proyecto SGSG
