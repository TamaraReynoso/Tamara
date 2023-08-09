<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="Mi.css">
    <title>Calculator</title>
    <style>
 
    </style>
</head>
   <center><h1>¡CALCULADORA!</h1></center>
<body>
    <div class="calculator">
        <input type="text" id="Resultado" placeholder="0">
        <div class="num-container">
            <button class="s-button" onclick="appendNumber('7')">7</button>
            <button class="s-button" onclick="appendNumber('8')">8</button>
            <button class="s-button" onclick="appendNumber('9')">9</button>
            <button class="s-button" onclick="appendOperator('+')">+</button>
        </div>

        <div class="num-container">
            <button class="s-button" onclick="appendNumber('4')">4</button>
            <button class="s-button" onclick="appendNumber('5')">5</button>
            <button class="s-button" onclick="appendNumber('6')">6</button>
            <button class="s-button" onclick="appendOperator('-')">-</button>
        </div>

        <div class="num-container">
            <button class="s-button" onclick="appendNumber('1')">1</button>
            <button class="s-button" onclick="appendNumber('2')">2</button>
            <button class="s-button" onclick="appendNumber('3')">3</button>
            <button class="s-button" onclick="appendOperator('/')">/</button>
        </div>

        <div class="num-container">
            <button class="s-button" onclick="clearInput()">C</button>
            <button class="s-button" onclick="appendNumber('0')">0</button>
            <button class="s-button" onclick="appendDecimal()">.</button>
            <button class="s-button" onclick="appendOperator('*')">x</button>
        </div>

        <div class="num-container-2">
            <button class="s-button" onclick="removeLast()">←</button>
            <button class="s-button" onclick="calcular()">=</button>
        </div>
    </div>

    <script>
        let inputElement = document.getElementById('Resultado');
        let shouldResetInput = false;

        function appendNumber(number) {
            if (shouldResetInput) {
                inputElement.value = number;
                shouldResetInput = false;
            } else {
                inputElement.value += number;
            }
        }

        function appendOperator(operator) {
            if (!shouldResetInput) {
                inputElement.value += operator;
                shouldResetInput = false;
            }
        }

        function appendDecimal() {
            if (!inputElement.value.includes('.')) {
                inputElement.value += '.';
            }
        }

        function calcular() {
            console.log(inputElement.value)
            try {
                inputElement.value = eval(inputElement.value);
            } catch (error) {
                inputElement.value = 'Error';
            }
            shouldResetInput = true;
        }

        function clearInput() {
            inputElement.value = '';
        }

        function removeLast() {
            inputElement.value = inputElement.value.slice(0, -1);
        }
    </script>
</body>

</html>
