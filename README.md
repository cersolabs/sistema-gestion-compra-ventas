# Sistema de Gestión de Compras y Ventas de Productos Dietéticos en C++

## Descripción del Proyecto

Van a trabajar con un programa en C++ que simula un sistema básico de gestión de compras y ventas de productos dietéticos. El programa permite registrar transacciones, visualizar detalles, buscar y actualizar transacciones, y calcular ganancias o pérdidas basadas en las transacciones registradas.

## Requisitos

1. **Registro de Transacciones (Función: `registerTransactio`)**
   - Implementen una función `registerTransactio(transaction t)` que permita registrar transacciones de compra o venta de productos dietéticos.
   - Cada transacción debe incluir:
     - Tipo de transacción (`compra` o `venta`).
     - Nombre del producto.
     - Cantidad comprada o vendida.
     - Precio unitario del producto.
   - Asegúrense de que la transacción se registre correctamente en el arreglo global `transactions` y que no se supere el límite máximo de transacciones permitidas.

2. **Visualización de Transacciones (Función: `viewTransactions`)**
   - Implementen una función `viewTransactions()` que permita visualizar todas las transacciones registradas hasta el momento.
   - La función debe mostrar los detalles de cada transacción: tipo de transacción, producto, cantidad y precio unitario.

3. **Búsqueda de Transacciones (Función: `searchTransaction`)**
   - Implementen una función `searchTransaction()` que permita buscar transacciones por nombre de producto.
   - Si se encuentran transacciones para el producto especificado, deben mostrarlas. Si no se encuentran, deben indicar que no se encontraron transacciones para ese producto.

4. **Actualización de Transacciones (Función: `updateTransaction`)**
   - Implementen una función `updateTransaction()` que permita actualizar los detalles de una transacción existente, buscando por el nombre del producto.
   - Los detalles que se pueden actualizar incluyen el tipo de transacción, nombre del producto, cantidad y precio unitario.
   - Si el producto no se encuentra, la función debe mostrar un mensaje indicándolo.

5. **Cálculo de Ganancias o Pérdidas (Función: `calculateProfitLoss`)**
   - Implementen una función `calculateProfitLoss()` que calcule y muestre las ganancias o pérdidas totales basadas en las transacciones de compra y venta.
   - Deben considerar los precios y cantidades registradas para calcular el valor total de las compras y ventas, y determinar si hay una ganancia o pérdida neta.

6. **Menú Interactivo**
   - El programa debe contar con un menú interactivo que ofrezca las siguientes opciones:
     1. Registrar Transacción (`registerTransactio`).
     2. Ver Detalles de las Transacciones (`viewTransactions`).
     3. Buscar Transacción (`searchTransaction`).
     4. Actualizar Transacción (`updateTransaction`).
     5. Calcular Ganancias o Pérdidas (`calculateProfitLoss`).
     6. Salir.
   - Deben implementar este menú en la función `main()` y asegurarse de que el programa siga ejecutándose hasta que el usuario decida salir.

## Tareas

1. **Implementación del Código**
2. **Pruebas del Programa**
   - Ejecuta el programa e ingresa diferentes transacciones para probar todas las funcionalidades.
   - Asegurate de que el programa maneje correctamente las condiciones límite, como intentar registrar más transacciones de las permitidas o buscar un producto que no existe.

3. **Documentación**
   - Elaborar en un archivo README.md una breve documentación que describa cómo funciona el programa y cómo se deben ingresar las transacciones.
   - Incluir capturas de pantalla de la ejecución del programa mostrando las diferentes opciones y funcionalidades.

4. **Entrega**
   - Suban el código del programa y la documentación a un repositorio de GitHub.
   - Asegúrense de que el repositorio sea público y que contenga un archivo `README.md` que explique cómo ejecutar el programa.

## Evaluación

Serán evaluados en base a la correcta implementación de las funciones solicitadas, la calidad del código, la realización de pruebas completas y la claridad de la documentación entregada.

