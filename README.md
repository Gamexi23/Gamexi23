<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Agenda de Citas Médicas - Clinic Cloud</title>
    <style>
        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            margin: 1;
            padding: 1;
            background-color: #f5f5f5;
            color: #333;
        }

        header {
            background-color: #1e90ff;
            color: #fff;
            text-align: center;
            padding: 10px 0;
        }

        .container {
            max-width: 800px;
            margin: 20px auto;
            padding: 20px;
            background-color: #fff;
            border-radius: 10px;
            box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
        }

        h1 {
            text-align: center;
            color: #1e90ff;
        }

        form {
            margin-top: 20px;
        }

        label {
            font-weight: bold;
        }

        input[type="text"], input[type="date"], input[type="time"], select {
            width: 100%;
            padding: 10px;
            margin: 5px 0;
            border: 1px solid #ccc;
            border-radius: 5px;
            box-sizing: border-box;
        }

        input[type="submit"] {
            background-color: #1e90ff;
            color: #fff;
            padding: 10px 20px;
            border: none;
            border-radius: 5px;
            cursor: pointer;
        }

        input[type="submit"]:hover {
            background-color: #0d70db;
        }
    </style>
</head>
<body>
    <header>
        <h1>Agenda de Citas Médicas - Clinic Cloud</h1>
    </header>

    <div class="container">
        <h2>Crear Nueva Cita</h2>

        <form>
            <label for="paciente">Nombre del Paciente:</label>
            <input type="text" id="paciente" name="paciente" required>

            <label for="fecha">Fecha de la Cita:</label>
            <input type="date" id="fecha" name="fecha" required>

            <label for="hora">Hora de la Cita:</label>
            <input type="time" id="hora" name="hora" required>

            <label for="tipo_cita">Tipo de Cita:</label>
            <select id="tipo_cita" name="tipo_cita">
                <option value="Consulta Médica">Consulta Médica</option>
                <option value="Revisión General">Revisión General</option>
                <option value="Especialidad">Especialidad</option>
            </select>

            <input type="submit" value="Guardar Cita">
        </form>
    </div>
</body>
</html>
