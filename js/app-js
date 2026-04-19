agregar.php (no recuerdo si este era necesario)
<?php
    include("conexion.php");

    $nombre = $_POST['nombre'];
    $cantidad = $_POST['cantidad'];
    $precio = $_POST['precio'];

    $sql = "INSERT INTO producto(nombreproducto, cantidadproducto, precioproducto)
    VALUES('$nombre', '$cantidad', '$precio')";

    $conexion->query($sql);

    header("Location: index.php");
?>
