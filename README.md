<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Agendamento de Consultas</title>
    <link rel="stylesheet" href="https://fonts.googleapis.com/css2?family=Roboto:wght@400;500;700&display=swap">
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <div class="container">
        <h1>Consultorio William's</h1>
        <form id="appointment-form">
            <div class="form-group">
                <label for="name">Nome:</label>
                <input type="text" id="name" name="name" required>
            </div>
            <div class="form-group">
                <label for="cpf">CPF:</label>
                <input type="text" id="cpf" name="cpf" required>
            </div>
            <div class="form-group">
                <label for="email">E-mail:</label>
                <input type="email" id="email" name="email" required>
            </div>
            <div class="form-group">
                <label for="date">Data:</label>
                <input type="date" id="date" name="date" required>
            </div>
            <div class="form-group">
                <label for="time">Hora:</label>
                <input type="time" id="time" name="time" required>
            </div>
            <button type="submit">Agendar Consulta</button>
        </form>
        <div id="confirmation" class="hidden">
            <h2>Consulta Agendada!</h2>
            <p>Nome: <span id="conf-name"></span></p>
            <p>CPF: <span id="conf-cpf"></span></p>
            <p>E-mail: <span id="conf-email"></span></p>
            <p>Data: <span id="conf-date"></span></p>
            <p>Hora: <span id="conf-time"></span></p>
            <p>Status: <span id="conf-status"></span></p>
        </div>
    </div>
    <script src="script.js"></script>
</body>
</html>
