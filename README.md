
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
  ![image](https://github.com/juaneortiz1/Lab03CVDS/assets/97971732/447f0c7f-3961-414a-a1fd-035f2cda7ded)

- `eci.edu.cvds.tdd.aerodescuentos.CalculadorDescuentos`: Clase auxiliar que proporciona métodos para calcular descuentos.
  ![image](https://github.com/juaneortiz1/Lab03CVDS/assets/97971732/5f1bc72a-1699-44a5-a69e-61121c5eb628)

- `eci.edu.cvds.tdd.aerodescuentos.ExcepcionParametrosInvalidos`: Clase de excepción que se lanza cuando se ingresan parámetros inválidos.
  ![image](https://github.com/juaneortiz1/Lab03CVDS/assets/97971732/1abcc509-b66f-47c3-82dd-49921e887012)
  ![image](https://github.com/juaneortiz1/Lab03CVDS/assets/97971732/479701ae-02cf-429c-a447-b73b360eabb1)


