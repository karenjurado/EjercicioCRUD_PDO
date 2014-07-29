EjercicioCRUD_PDO
=================
<!DOCTYPE html>
<html>

<head>
	<meta charset='utf-8'>?	
	<link href="Stylo.css" rel="stylesheet" type="text/css">

    <center><nav >
        <ul class='nav'>
            <li><a href="Index.html"> Inicio </a></li>
            <li><a href="#"> Registros </a>
                <ul>
                <li><a href="Profesores.html"> Profesores </a></li>
                <li><a href="Materias.html"> Asignaturas </a></li>
                <li><a href="Laboratorios.html"> Laboratorios </a></li>
                </ul>
            </li>
            <li><a href="Consultas.html"> Consultas </a></li>
            <li><a href="Asignacion.html"> Asignación</a></li>
        </ul>
    </nav></center>	

</head>
	
<body>

	<div class='Titulo'>
		<br><center><h2>Registros de Profesores</h2></center>
	</div>
		
	<div id='Contenedor'>

		<div id='Profesores'class='Formu'>
			<form action='conexionbs.php' method='POST' name='CrudCliente'>
				<h3 class='Titulo'>Información Profesores</h3>
				<center><table border='0px'>
				<tr><center><td>Cedula: </td></center>
				<td><center><input type='text' id='cedula' name='cedula'></center></td></tr>
				<tr><center><td>Nombre: </td></center>
				<td><center><input type='text' id='nombre' name='nombre'></center></td></tr>
				<tr><center><td>Telefono: </td></center>
				<td><center><input type='text' id='telefono' name='telefono'></center></td></tr>
				<tr><center><td>Direccion: </td></center>
				<td><center><input type='text' id='direccion' name='direccion'></center></td></tr>
				</table></center><br>
				
		</div>	
		
		<div id='Botones' class='Botones'>
				<input type='button' name='boton' id='boton' value='Buscar'><br>
				<input name="submit" type="submit" value='Guardar'><br>
				<input type='button' name='boton' id='boton' value='Modificar'/><br>
				<input type='button' name='boton' id='boton' value='Actualizar'/><br>
				<input type='button' name='boton' id='boton' value='Eliminar'><br>
			</form>
		</div>		
		
	</div>	

</body>

</html>
