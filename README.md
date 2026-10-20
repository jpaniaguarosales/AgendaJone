# AgendaJone

AgendaJone es una aplicación de escritorio desarrollada en Java y JavaFX para organizar eventos. Permite crear eventos personales, de trabajo y de formación, asignarles una fecha y una prioridad, consultar la lista, eliminarlos y marcarlos como completados.

## Funcionalidades

- Crear eventos personales, de trabajo y de formación.
- Asignar una fecha y una prioridad a cada evento.
- Añadir información específica según el tipo: ubicación, cliente u horas de formación.
- Consultar los eventos en una lista que muestra cada prioridad con un color.
- Eliminar un evento seleccionado.
- Marcar un evento como completado.

## Requisitos

- JDK 21.
- JavaFX SDK 21.0.10.
- Eclipse IDE con soporte para proyectos Java.

## Cómo abrir y ejecutar el proyecto

1. Clona el repositorio desde GitHub o descárgalo en tu ordenador.
2. En Eclipse, importa la carpeta como **Existing Projects into Workspace**.
3. Configura las bibliotecas de JavaFX en las propiedades del proyecto. El archivo `.classpath` incluido apunta a `C:/javafx-sdk-21.0.10/lib`; cambia esa ruta para que coincida con la ubicación del JavaFX SDK en tu ordenador.
4. Ejecuta `app.Main` como una aplicación Java.

## Estructura

- `src/app`: punto de entrada y ventanas de la interfaz gráfica.
- `src/eventos`: clases que representan los distintos tipos de evento.
- `src/logic`: lógica para añadir, consultar, eliminar y completar eventos.

## Nota sobre los datos

Los eventos se guardan en memoria mientras la aplicación está abierta. Al cerrar la aplicación, la lista de eventos no se conserva.
