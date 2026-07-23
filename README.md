<!DOCTYPE html>
<html lang="pt-BR">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">

<title>LUMI Control</title>

<style>
body {
    margin: 0;
    font-family: Arial, sans-serif;
    background: #111827;
    color: white;
}

.header {
    padding: 25px;
    text-align: center;
    background: #0f172a;
}

.logo {
    font-size: 32px;
    font-weight: bold;
    color: #22c55e;
}

.container {
    padding: 20px;
}

.card {
    background: #1f2937;
    padding: 20px;
    border-radius: 15px;
    margin-bottom: 15px;
}

button {
    width: 100%;
    padding: 15px;
    border: none;
    border-radius: 10px;
    background: #22c55e;
    color: #111;
    font-size: 18px;
    font-weight: bold;
}
</style>

</head>

<body>

<div class="header">
<div class="logo">LUMI</div>
<p>Controle inteligente para eventos</p>
</div>

<div class="container">

<div class="card">
<h2>🎉 Evento Atual</h2>
<p>Nenhum evento aberto</p>
<button>Novo Evento</button>
</div>

<div class="card">
<h2>🍻 Comandas</h2>
<p>Controle rápido de consumo</p>
<button>Abrir Comandas</button>
</div>

<div class="card">
<h2>📦 Estoque</h2>
<p>Acompanhe entradas e saídas</p>
<button>Ver Estoque</button>
</div>

</div>

</body>
</html>
