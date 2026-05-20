# Interacción Completa: Entrada, Acción y Salida (Ejercicio 8)

Este proyecto implementa un flujo de datos dinámico donde el programa captura información introducida por el usuario y la procesa para actualizar la interfaz en tiempo real.

## 🚀 Funcionalidades
* **Captura de Texto (Input):** Utiliza el control `TextField` para permitir la entrada de datos por teclado.
* **Procesamiento de Eventos:** Al activar el botón, el programa extrae el contenido del campo de texto mediante el método `getText()`.
* **Actualización Reactiva:** El texto capturado se asigna inmediatamente a una `Label`, demostrando cómo los controles pueden comunicarse entre sí.
* **Layout Vertical:** Organiza los tres elementos en un `VBox` con un espaciado de 10 píxeles para asegurar una disposición clara y ordenada.

## 🛠️ Estructura técnica
El código destaca por la integración de controles estándar de JavaFX:
* **`TextField`**: Nodo especializado para la edición de una sola línea de texto.
* **Captura Dinámica**: El uso de `campo.getText()` dentro de la expresión lambda permite obtener el valor actual del campo en el preciso instante del clic.
* **Flujo de Datos**:
    1. El usuario escribe en el `TextField`.
    2. El `Button` dispara el `EventHandler`.
    3. La `Label` recibe y muestra la información.
* **Diseño UI/UX**: Se define una ventana de 300x200 píxeles, tamaño óptimo para un formulario de entrada simple.