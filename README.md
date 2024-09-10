Java: Explicación de Funciones

1. Método insertarVentas(int departamento, int mes, double venta):
   - Propósito: Inserta o modifica una venta en la posición especificada del arreglo ventas.
   - Funcionamiento:
     - Recibe tres parámetros: departamento (índice), mes (índice), y venta (valor).
     - Valida que los índices de departamento y mes sean correctos usando métodos de validación.
     - Si los índices son válidos, actualiza la venta en ventas[departamento][mes].
     - Si los índices no son válidos, imprime un mensaje de error.

2. Método buscarVenta(int departamento, int mes):
   - Propósito: Busca y devuelve una venta específica en el arreglo ventas.
   - Funcionamiento:
     - Recibe dos parámetros: departamento (índice) y mes (índice).
     - Valida que los índices de departamento y mes sean correctos.
     - Si los índices son válidos, devuelve el valor en ventas[departamento][mes].
     - Si los índices no son válidos, imprime un mensaje de error y devuelve -1.

3. Método eliminarVentasDepartamento(int departamento):
   - Propósito: Elimina (pone en cero) todas las ventas de un departamento específico.
   - Funcionamiento:
     - Recibe un parámetro: departamento (índice).
     - Valida que el índice del departamento sea correcto.
     - Si el índice es válido, recorre todas las posiciones de ventas[departamento] y las pone en 0.0.
     - Si el índice no es válido, imprime un mensaje de error.

Python: Explicación de Funciones

1. Método insertar_ventas(self, departamento, mes, venta):
   - Propósito: Inserta o modifica una venta en la lista ventas.
   - Funcionamiento:
     - Recibe tres parámetros: departamento (índice), mes (índice), y venta (valor).
     - Valida que los índices de departamento y mes sean correctos usando métodos de validación.
     - Si los índices son válidos, actualiza la venta en ventas[departamento][mes].
     - Si los índices no son válidos, imprime un mensaje de error.

2. Método buscar_venta(self, departamento, mes):
   - Propósito: Busca y devuelve una venta específica en la lista ventas.
   - Funcionamiento:
     - Recibe dos parámetros: departamento (índice) y mes (índice).
     - Valida que los índices de departamento y mes sean correctos.
     - Si los índices son válidos, devuelve el valor en ventas[departamento][mes].
     - Si los índices no son válidos, imprime un mensaje de error y devuelve -1.

3. Método eliminar_ventas_departamento(self, departamento):
   - Propósito: Elimina (pone en cero) todas las ventas de un departamento específico.
   - Funcionamiento:
     - Recibe un parámetro: departamento (índice).
     - Valida que el índice del departamento sea correcto.
     - Si el índice es válido, reemplaza la lista ventas[departamento] con una lista de ceros.
     - Si el índice no es válido, imprime un mensaje de error.
