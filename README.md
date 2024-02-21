
# Aerolínea - Sistema de Cálculo de Tarifas

Este proyecto implementa un sistema de cálculo de tarifas para una aerolínea. El sistema determina el costo del boleto de avión en función de la tarifa base, la anticipación con la que se compra el boleto y la edad del pasajero, aplicando diferentes descuentos según ciertas condiciones.

## Desarrollo Guiado por Pruebas (TDD)

Este proyecto sigue el enfoque de Desarrollo Guiado por Pruebas (TDD), donde se escriben pruebas unitarias antes de implementar el código funcional. El proceso típico de TDD se basa en los siguientes pasos:

1. **Red:** Se escribe una prueba unitaria que describe el comportamiento esperado del código.
2. **Green:** Se implementa la funcionalidad mínima necesaria para que la prueba pase.
3. **Refactor:** Se refactoriza el código para mejorar su diseño y legibilidad, manteniendo las pruebas pasadas.

El uso de TDD nos permite asegurar que el código implementado cumpla con los requisitos especificados y que se mantenga correctamente a lo largo del tiempo, facilitando la detección temprana de errores y la incorporación de nuevas funcionalidades de manera segura.

## Estructura del Proyecto

El proyecto está organizado en los siguientes paquetes y clases:

- `eci.edu.cvds.tdd.aerodescuentos.Tarifa`: Clase principal que contiene la lógica de cálculo de tarifas.
- `eci.edu.cvds.tdd.aerodescuentos.CalculadorDescuentos`: Clase auxiliar que proporciona métodos para calcular descuentos.
- `eci.edu.cvds.tdd.aerodescuentos.ExcepcionParametrosInvalidos`: Clase de excepción que se lanza cuando se ingresan parámetros inválidos.

