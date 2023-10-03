<!-- No borrar o modificar -->
[Inicio](./index.md)

## Sesión 5 


<!-- Su documentación aquí -->
## Actividad:   Diseñar un formulario de pedido de un producto
Objetivo:

Aplicar los conocimientos sobre los tipos de etiquetas HTML para diseñar un formulario de pedido de un producto.

- Instrucciones:

- Crear un nuevo documento HTML.
- Crear un formulario con los siguientes campos:
- Nombre del producto
- Cantidad
- Precio unitario
- Precio total
- Dirección de envío
- Información de contacto - (nombre, - correo electrónico, número de teléfono)
- Agregar los siguientes campos relacionados al formulario:
- Método de pago
- Fecha de entrega
- Comentarios
- Utilizar las etiquetas HTML apropiados para cada campo.

```html
<!DOCTYPE html>
<html>
<head>
    <title>Formulario de Pedido</title>
</head>
<body>
    <h1>Formulario de Pedido</h1>
    <form action="procesar_pedido.php" method="post">
        <label for="nombre_producto">Nombre del Producto:</label>
        <input type="text" id="nombre_producto" name="nombre_producto" required><br><br>

        <label for="cantidad">Cantidad:</label>
        <input type="number" id="cantidad" name="cantidad" required><br><br>

        <label for="precio_unitario">Precio Unitario:</label>
        <input type="number" id="precio_unitario" name="precio_unitario" required><br><br>

        <label for="precio_total">Precio Total:</label>
        <input type="number" id="precio_total" name="precio_total" readonly><br><br>

        <label for="direccion_envio">Dirección de Envío:</label>
        <textarea id="direccion_envio" name="direccion_envio" rows="4" required></textarea><br><br>

        <label for="nombre_contacto">Nombre de Contacto:</label>
        <input type="text" id="nombre_contacto" name="nombre_contacto" required><br><br>

        <label for="correo_electronico">Correo Electrónico:</label>
        <input type="email" id="correo_electronico" name="correo_electronico" required><br><br>

        <label for="numero_telefono">Número de Teléfono:</label>
        <input type="tel" id="numero_telefono" name="numero_telefono" required><br><br>

        <label for="metodo_pago">Método de Pago:</label>
        <select id="metodo_pago" name="metodo_pago">
            <option value="tarjeta">Tarjeta de Crédito</option>
            <option value="efectivo">Efectivo</option>
            <option value="transferencia">Transferencia Bancaria</option>
        </select><br><br>

        <label for="fecha_entrega">Fecha de Entrega:</label>
        <input type="date" id="fecha_entrega" name="fecha_entrega"><br><br>

        <label for="comentarios">Comentarios:</label><br>
        <textarea id="comentarios" name="comentarios" rows="4"></textarea><br><br>

        <input type="submit" value="Enviar Pedido">
    </form>
</body>
</html>

```