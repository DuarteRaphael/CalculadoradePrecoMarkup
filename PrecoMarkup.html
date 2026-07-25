<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Calculadora de Preço</title>
    <style>
        /* Reset básico */
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            background: linear-gradient(135deg, #74ebd5 0%, #ACB6E5 100%);
            min-height: 100vh;
            display: flex;
            justify-content: center;
            align-items: center;
        }

        .container {
            background: #fff;
            padding: 30px;
            border-radius: 12px;
            box-shadow: 0 8px 20px rgba(0,0,0,0.15);
            width: 100%;
            max-width: 400px;
        }

        h1 {
            text-align: center;
            margin-bottom: 20px;
            color: #333;
        }

        label {
            display: block;
            margin-bottom: 6px;
            font-weight: 600;
            color: #333;
        }

        input[type="text"],
        input[type="number"] {
            width: 100%;
            padding: 10px 12px;
            margin-bottom: 18px;
            border: 1px solid #ccc;
            border-radius: 8px;
            transition: border-color 0.3s, box-shadow 0.3s;
        }

        input:focus {
            border-color: #74ebd5;
            box-shadow: 0 0 6px rgba(116, 235, 213, 0.6);
            outline: none;
        }

        button {
            width: 100%;
            padding: 12px;
            background: linear-gradient(135deg, #74ebd5, #ACB6E5);
            border: none;
            border-radius: 8px;
            color: #fff;
            font-size: 16px;
            font-weight: bold;
            cursor: pointer;
            transition: transform 0.2s, box-shadow 0.2s;
        }

        button:hover {
            transform: translateY(-2px);
            box-shadow: 0 6px 12px rgba(0,0,0,0.15);
        }

        #resultado {
            margin-top: 20px;
            padding: 12px;
            background: #f9f9f9;
            border-radius: 8px;
            font-weight: bold;
            color: #444;
            text-align: center;
        }
    </style>
</head>
<body>
    <div class="container">
        <h1>Calculadora de Preço</h1>
        <label for="nome">Nome do produto:</label>
        <input type="text" id="nome" name="nome">

        <label for="precocusto">Preço de custo do produto:</label>
        <input type="number" id="precocusto" name="precocusto" step="0.01">

        <label for="DespesasFixas">Despesas fixas (%):</label>
        <input type="number" id="DespesasFixas" name="DespesasFixas" step="0.01">

        <label for="DespesasVariaveis">Despesas variáveis (%):</label>
        <input type="number" id="DespesasVariaveis" name="DespesasVariaveis" step="0.01">

        <label for="TaxaMaquina">Taxas Máquinas (%):</label>
        <input type="number" id="TaxaMaquina" name="TaxaMaquina" step="0.01">

        <label for="Aliquota">Imposto Simples (%):</label>
        <input type="number" id="Aliquota" name="Aliquota" step="0.01">

        <label for="LucroDesejado">Lucro desejado (%):</label>
        <input type="number" id="LucroDesejado" name="LucroDesejado" step="0.01">

        <button onclick="calcularPreco()">Calcular preço final</button>

        <div id="resultado"></div>
    </div>

    <script>
        function calcularPreco() {
            let precocusto = parseFloat(document.getElementById("precocusto").value);
            let DespesasFixas = parseFloat(document.getElementById("DespesasFixas").value);
            let DespesasVariaveis = parseFloat(document.getElementById("DespesasVariaveis").value);
            let TaxaMaquina = parseFloat(document.getElementById("TaxaMaquina").value);
            let Aliquota = parseFloat(document.getElementById("Aliquota").value);
            let LucroDesejado = parseFloat(document.getElementById("LucroDesejado").value);

            if (isNaN(precocusto) || isNaN(DespesasFixas) || isNaN(DespesasVariaveis) || isNaN(TaxaMaquina) || isNaN(Aliquota) || isNaN(LucroDesejado)) {
                document.getElementById("resultado").innerHTML = "Por favor, insira valores válidos.";
                return;
            }

            let precofinal = precocusto * (1 + DespesasFixas / 100 + DespesasVariaveis / 100 + TaxaMaquina / 100 + Aliquota / 100 + LucroDesejado / 100);

            document.getElementById("resultado").innerHTML = 
                "O preço final do produto é: R$ " + precofinal.toFixed(2) + "<br>" +
                "O lucro do produto é: R$ " + (precofinal - precocusto).toFixed(2);
        };
    </script>
</body>
</html>
