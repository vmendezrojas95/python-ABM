# python-ABM
Se modifica un archivo .txt para simular una base de datos local.

Consigna:
- clientes.txt : con los siguientes campos en cada registro (línea, renglon): DNI, Nombre Completo, Telefono, direccion, estado, codigo de barra
- peliculas.txt: campos: código de barra, titulo, genero, estado, DNI del cliente (solo cuando la pelicula esté en préstamo)

1 - Préstamo de Película : puede tener un sub-Menú que tenga las opciones:
    A - Consultar todos los títulos/películas disponible (verificando el campo estado)
    B - Registrar préstamo (deberá buscar la película y cambiar el campo de estado a "P" de prestado y en el cliente con "O" de ocupado)
    C - Registrar Devolución (pedir datos necesarios para buscar el cliente y la pelicula, y cambiar el campo de estado dejándolo con "D" de disponible)

2 - Gestión del cliente: tendrá un sub-menú:
    A - Alta de cliente
    C - Consulta estado del cliente
    M - Modificar teléfono o direccion del cliente
    E - Eliminar cliente (deberán eliminar el registro y verificar que el archivo no quede con un registro en blanco)

3 - Gestión de pelicula:
    A - Alta Pelicula
    C - Modificar Pelicula
    E - Eliminar Pelicula
