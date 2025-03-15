# CODIGOS-DE-ERROR-AUTOMOVILES
TODO TIPO DE CODIGOS DE ERROR DE UN AUTOMOVIL Y SUS SOLUCIONES
            border-radius: 10px;
            max-width: 80%;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
            transition: transform 0.3s ease;
        }
        .codigo-error:hover {
            transform: scale(1.05);
        }
        .codigo-error h2 {
            color: #e74c3c;
            font-size: 1.8em;
        }
        .codigo-error p {
            font-size: 1.1em;
            line-height: 1.6em;
        }
        .codigo-error p strong {
            color: #34495e;
        }
        footer {
            background-color: #34495e;
            color: white;
            padding: 10px;
            text-align: center;
        }
        footer p {
            font-size: 1em;
            margin: 0;
        }
    </style>
    <script>
        // Función para filtrar los errores mediante el buscador
        function buscarError() {
            var input = document.getElementById('search-bar');
            var filter = input.value.toUpperCase();
            var codigoErrores = document.querySelectorAll('.codigo-error');
            
            codigoErrores.forEach(function(codigoError) {
                var titulo = codigoError.querySelector('h2').innerText.toUpperCase();
                if (titulo.indexOf(filter) > -1) {
                    codigoError.style.display = "";
                } else {
                    codigoError.style.display = "none";
                }
            });
        }
    </script>
</head>
<body>

<header>
    <h1>Códigos de Error - Mecatrónica Automotriz</h1>
</header>

<div class="search-container">
    <input type="text" id="search-bar" placeholder="Buscar código de error..." onkeyup="buscarError()">
    <button onclick="buscarError()">Buscar</button>
</div>

<!-- Código de error 1 -->
<div class="codigo-error">
    <h2>Código: P0300 - Fallo en el encendido del motor</h2>
    <p><strong>Descripción:</strong> Este código indica que hay un fallo de encendido en uno o más cilindros del motor...</p>
    <p><strong>Solución:</strong> Revisar las bujías, cables de encendido, bobinas de encendido...</p>
</div>

<!-- Código de error 2 -->
<div class="codigo-error">
    <h2>Código: P0340 - Sensor de posición del árbol de levas</h2>
    <p><strong>Descripción:</strong> Este código indica un problema con el sensor de posición del árbol de levas...</p>
    <p><strong>Solución:</strong> Verificar el sensor de posición del árbol de levas y reemplazarlo si es necesario.</p>
</div>

<!-- Código de error 3 -->
<div class="codigo-error">
    <h2>Código: P0420 - Eficiencia del catalizador por debajo del umbral</h2>
    <p><strong>Descripción:</strong> Este código aparece cuando el sistema de monitoreo del catalizador detecta que el rendimiento del catalizador es inferior...</p>
    <p><strong>Solución:</strong> Revisar el catalizador y los sensores de oxígeno para determinar si necesitan ser reemplazados.</p>
</div>

<!-- Código de error 4 -->
<div class="codigo-error">
    <h2>Código: P0171 - Mezcla de combustible demasiado pobre (banco 1)</h2>
    <p><strong>Descripción:</strong> Este código indica que el motor está recibiendo una mezcla de combustible muy pobre (demasiado aire y poco combustible).</p>
    <p><strong>Solución:</strong> Revisar los sensores de oxígeno, el filtro de aire, y las mangueras de vacío.</p>
</div>

<!-- Código de error 5 -->
<div class="codigo-error">
    <h2>Código: P0135 - Sensor de oxígeno, circuito calefacción (banco 1, sensor 1)</h2>
    <p><strong>Descripción:</strong> Este código indica un problema con el circuito calefactor del sensor de oxígeno en el banco 1, sensor 1.</p>
    <p><strong>Solución:</strong> Inspeccionar el cableado del sensor y reemplazar el sensor de oxígeno si es necesario.</p>
</div>

<!-- Código de error 6 -->
<div class="codigo-error">
    <h2>Código: P0101 - Error en el sensor de flujo de aire masivo (MAF)</h2>
    <p><strong>Descripción:</strong> Este código aparece cuando el sensor de flujo de aire masivo (MAF) detecta que el flujo de aire no es el esperado...</p>
    <p><strong>Solución:</strong> Inspeccionar el sensor MAF y limpiar o reemplazar el filtro de aire si es necesario.</p>
</div>

<!-- Código de error 7 -->
<div class="codigo-error">
    <h2>Código: P0128 - Termostato del motor funciona por debajo de la temperatura ideal</h2>
    <p><strong>Descripción:</strong> Este código se activa cuando el termostato no está funcionando correctamente, lo que afecta la temperatura del motor...</p>
    <p><strong>Solución:</strong> Verificar el termostato y considerar su reemplazo si es necesario.</p>
</div>

<!-- Código de error 8 -->
<div class="codigo-error">
    <h2>Código: P0440 - Fallo en el sistema de control de emisiones EVAP</h2>
    <p><strong>Descripción:</strong> Este código aparece cuando hay una fuga o fallo en el sistema EVAP de control de emisiones...</p>
    <p><strong>Solución:</strong> Inspeccionar las mangueras de vacío y las válvulas del sistema EVAP.</p>
</div>

<!-- Código de error 9 -->
<div class="codigo-error">
    <h2>Código: P0500 - Error en el sensor de velocidad del vehículo</h2>
    <p><strong>Descripción:</strong> Este código indica que el sensor de velocidad del vehículo no está funcionando correctamente...</p>
    <p><strong>Solución:</strong> Verificar el sensor de velocidad y su conexión al sistema eléctrico.</p>
</div>

<!-- Código de error 10 -->
<div class="codigo-error">
    <h2>Código: P0700 - Error en el sistema de control del transmisor</h2>
    <p><strong>Descripción:</strong> Este código indica un fallo en el sistema de control del transmisor del vehículo...</p>
    <p><strong>Solución:</strong> Revisar el sistema de transmisión y los sensores involucrados.</p>
</div>

<footer>
    <p>&copy; 2025 Mecatrónica Automotriz. Todos los derechos reservados.</p>
</footer>

</body>
</html>
