<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Documentación de Fabricación Digital</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }
        
        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            line-height: 1.6;
            color: #333;
            background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
            padding: 20px;
        }
        
        .container {
            max-width: 1200px;
            margin: 0 auto;
            background: white;
            border-radius: 20px;
            box-shadow: 0 20px 60px rgba(0,0,0,0.3);
            overflow: hidden;
        }
        
        header {
            background: linear-gradient(135deg, #2c3e50 0%, #34495e 100%);
            color: white;
            padding: 40px;
            text-align: center;
        }
        
        header h1 {
            font-size: 2.5em;
            margin-bottom: 10px;
            text-shadow: 2px 2px 4px rgba(0,0,0,0.3);
        }
        
        header p {
            font-size: 1.2em;
            opacity: 0.9;
        }
        
        .content {
            padding: 40px;
        }
        
        .proyecto {
            margin-bottom: 60px;
            padding-bottom: 40px;
            border-bottom: 3px solid #e0e0e0;
        }
        
        .proyecto:last-child {
            border-bottom: none;
        }
        
        .proyecto h2 {
            color: #667eea;
            font-size: 2em;
            margin-bottom: 20px;
            padding-bottom: 10px;
            border-bottom: 3px solid #667eea;
        }
        
        .descripcion {
            background: #f8f9fa;
            padding: 20px;
            border-radius: 10px;
            margin-bottom: 30px;
            border-left: 5px solid #667eea;
        }
        
        .galeria {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 20px;
            margin-top: 20px;
        }
        
        .imagen-container {
            position: relative;
            overflow: hidden;
            border-radius: 15px;
            box-shadow: 0 5px 15px rgba(0,0,0,0.1);
            transition: transform 0.3s ease, box-shadow 0.3s ease;
        }
        
        .imagen-container:hover {
            transform: translateY(-5px);
            box-shadow: 0 10px 25px rgba(0,0,0,0.2);
        }
        
        .imagen-container img {
            width: 100%;
            height: 300px;
            object-fit: cover;
            display: block;
        }
        
        .imagen-caption {
            background: rgba(0,0,0,0.8);
            color: white;
            padding: 15px;
            text-align: center;
            font-size: 0.9em;
        }
        
        .paso {
            background: #fff3cd;
            padding: 15px 20px;
            margin: 15px 0;
            border-radius: 8px;
            border-left: 5px solid #ffc107;
        }
        
        .paso h4 {
            color: #856404;
            margin-bottom: 8px;
        }
        
        .materiales, .herramientas {
            background: #d1ecf1;
            padding: 20px;
            border-radius: 10px;
            margin: 20px 0;
            border-left: 5px solid #17a2b8;
        }
        
        .materiales h3, .herramientas h3 {
            color: #0c5460;
            margin-bottom: 10px;
        }
        
        ul {
            margin-left: 20px;
            margin-top: 10px;
        }
        
        ul li {
            margin: 8px 0;
        }
        
        footer {
            background: #2c3e50;
            color: white;
            text-align: center;
            padding: 20px;
            margin-top: 40px;
        }
        
        .nota {
            background: #d4edda;
            border-left: 5px solid #28a745;
            padding: 15px;
            border-radius: 8px;
            margin: 20px 0;
        }
        
        .nota strong {
            color: #155724;
        }
    </style>
</head>
<body>
    <div class="container">
        <header>
            <h1>🔧 Documentación de Fabricación Digital</h1>
            <p>Impresión 3D • Corte Láser • Electrónica</p>
        </header>
        
        <div class="content">
            <!-- PROYECTO 1: IMPRESIÓN 3D -->
            <div class="proyecto">
                <h2>🖨️ Proyecto 1: Impresión 3D</h2>
                
                <div class="descripcion">
                    <p><strong>Objetivo:</strong> Fabricar una pieza tridimensional mediante la tecnología de impresión 3D por deposición de material fundido (FDM).</p>
                    <p><strong>Tiempo estimado:</strong> 2-4 horas (dependiendo del tamaño y complejidad)</p>
                </div>
                
                <div class="materiales">
                    <h3>📦 Materiales</h3>
                    <ul>
                        <li>Filamento PLA (1.75mm)</li>
                        <li>Cama de impresión limpia</li>
                        <li>Adhesivo para cama (opcional)</li>
                    </ul>
                </div>
                
                <div class="herramientas">
                    <h3>🛠️ Equipo</h3>
                    <ul>
                        <li>Impresora 3D FDM</li>
                        <li>Software de diseño 3D (Fusion 360, Tinkercad, etc.)</li>
                        <li>Software de laminado (Cura, PrusaSlicer)</li>
                        <li>Computadora</li>
                    </ul>
                </div>
                
                <div class="paso">
                    <h4>Paso 1: Diseño 3D</h4>
                    <p>Se diseñó el modelo 3D utilizando software CAD. Se consideraron las dimensiones, tolerancias y orientación óptima para la impresión.</p>
                </div>
                
                <div class="galeria">
                    <div class="imagen-container">
                        <img src="imagen2.jpg" alt="Pieza impresa 3D">
                        <div class="imagen-caption">Pieza impresa en 3D con detalle de las capas visibles</div>
                    </div>
                    <div class="imagen-container">
                        <img src="https://via.placeholder.com/400x300/764ba2/ffffff?text=Vista+de+Capas" alt="Laminado">
                        <div class="imagen-caption">Vista de capas en el software de laminado</div>
                    </div>
                    <div class="imagen-container">
                        <img src="https://via.placeholder.com/400x300/f093fb/ffffff?text=Configuraci%C3%B3n+de+Impresi%C3%B3n" alt="Configuración">
                        <div class="imagen-caption">Configuración de parámetros de impresión</div>
                    </div>
                </div>
                
                <div class="paso">
                    <h4>Paso 2: Laminado (Slicing)</h4>
                    <p>Se importó el archivo STL al software de laminado y se configuraron los parámetros: altura de capa (0.2mm), relleno (20%), soportes, velocidad de impresión (50mm/s).</p>
                </div>
                
                <div class="paso">
                    <h4>Paso 3: Impresión</h4>
                    <p>Se cargó el archivo G-code en la impresora, se niveló la cama, se precalentó el extrusor y se inició la impresión.</p>
                </div>
                
                <div class="galeria">
                    <div class="imagen-container">
                        <img src="https://via.placeholder.com/400x300/4facfe/ffffff?text=Impresi%C3%B3n+en+Proceso" alt="Imprimiendo">
                        <div class="imagen-caption">Proceso de impresión en la primera capa</div>
                    </div>
                    <div class="imagen-container">
                        <img src="https://via.placeholder.com/400x300/00f2fe/ffffff?text=Pieza+Completa" alt="Pieza terminada">
                        <div class="imagen-caption">Pieza completada en la cama de impresión</div>
                    </div>
                    <div class="imagen-container">
                        <img src="https://via.placeholder.com/400x300/43e97b/ffffff?text=Pieza+Final" alt="Resultado final">
                        <div class="imagen-caption">Pieza final después del post-procesamiento</div>
                    </div>
                </div>
                
                <div class="nota">
                    <strong>💡 Nota:</strong> Se realizó post-procesamiento lijando las superficies y removiendo soportes con cuidado para obtener un mejor acabado superficial.
                </div>
            </div>
            
            <!-- PROYECTO 2: CORTE LÁSER -->
            <div class="proyecto">
                <h2>⚡ Proyecto 2: Corte Láser de Cubo</h2>
                
                <div class="descripcion">
                    <p><strong>Objetivo:</strong> Fabricar un cubo mediante corte láser de material acrílico o MDF, con ensamblaje mediante encastres.</p>
                    <p><strong>Tiempo estimado:</strong> 30-45 minutos (corte + ensamblaje)</p>
                </div>
                
                <div class="materiales">
                    <h3>📦 Materiales</h3>
                    <ul>
                        <li>Lámina de acrílico o MDF de 3mm</li>
                        <li>Pegamento para acrílico (opcional)</li>
                        <li>Papel de enmascarar</li>
                    </ul>
                </div>
                
                <div class="herramientas">
                    <h3>🛠️ Equipo</h3>
                    <ul>
                        <li>Cortadora láser CO2</li>
                        <li>Software de diseño vectorial (Inkscape, Illustrator, CorelDRAW)</li>
                        <li>Computadora</li>
                        <li>Extractor de humos</li>
                    </ul>
                </div>
                
                <div class="paso">
                    <h4>Paso 1: Diseño Vectorial</h4>
                    <p>Se diseñaron las 6 caras del cubo con encastres tipo "finger joints" en software vectorial. Se calcularon las dimensiones considerando el grosor del material (3mm) y el kerf del láser.</p>
                </div>
                
                <div class="galeria">
                    <div class="imagen-container">
                        <img src="https://via.placeholder.com/400x300/fa709a/ffffff?text=Dise%C3%B1o+Vectorial" alt="Diseño vectorial">
                        <div class="imagen-caption">Diseño vectorial de las caras del cubo con encastres</div>
                    </div>
                    <div class="imagen-container">
                        <img src="https://via.placeholder.com/400x300/fee140/ffffff?text=Piezas+Cortadas" alt="Piezas cortadas">
                        <div class="imagen-caption">Piezas cortadas en la cortadora láser</div>
                    </div>
                    <div class="imagen-container">
                        <img src="https://via.placeholder.com/400x300/30cfd0/ffffff?text=Proceso+de+Corte" alt="Cortando">
                        <div class="imagen-caption">Proceso de corte láser en acción</div>
                    </div>
                </div>
                
                <div class="paso">
                    <h4>Paso 2: Configuración y Corte</h4>
                    <p>Se configuró la potencia del láser (70%), velocidad (20mm/s) y frecuencia según el material. Se colocó el material en la cama y se ejecutó el corte.</p>
                </div>
                
                <div class="paso">
                    <h4>Paso 3: Ensamblaje</h4>
                    <p>Se retiraron las piezas, se limpió el material enmascarante y se ensamblaron las 6 caras mediante los encastres. Se aplicó pegamento en las uniones para mayor resistencia.</p>
                </div>
                
                <div class="galeria">
                    <div class="imagen-container">
                        <img src="https://via.placeholder.com/400x300/38f9d7/ffffff?text=Ensamblaje" alt="Ensamblando">
                        <div class="imagen-caption">Proceso de ensamblaje de las piezas</div>
                    </div>
                    <div class="imagen-container">
                        <img src="https://via.placeholder.com/400x300/4facfe/ffffff?text=Cubo+Completo" alt="Cubo terminado">
                        <div class="imagen-caption">Cubo completamente ensamblado</div>
                    </div>
                    <div class="imagen-container">
                        <img src="https://via.placeholder.com/400x300/667eea/ffffff?text=Detalle+Final" alt="Detalle">
                        <div class="imagen-caption">Detalle de los encastres y acabado final</div>
                    </div>
                </div>
                
                <div class="nota">
                    <strong>⚠️ Importante:</strong> Siempre usar el extractor de humos durante el corte láser y verificar que no haya flamas en el material durante el proceso.
                </div>
            </div>
            
            <!-- PROYECTO 3: PCB -->
            <div class="proyecto">
                <h2>💡 Proyecto 3: PCB con 3 LEDs</h2>
                
                <div class="descripcion">
                    <p><strong>Objetivo:</strong> Diseñar y fabricar una placa de circuito impreso (PCB) que encienda 3 LEDs alimentados por una batería.</p>
                    <p><strong>Tiempo estimado:</strong> 1-2 horas (diseño + fabricación + soldadura)</p>
                </div>
                
                <div class="materiales">
                    <h3>📦 Materiales</h3>
                    <ul>
                        <li>3 LEDs (color a elección)</li>
                        <li>3 Resistencias de 220Ω</li>
                        <li>Portapilas para batería de 9V</li>
                        <li>Placa PCB virgen</li>
                        <li>Estaño para soldar</li>
                        <li>Cable de conexión</li>
                    </ul>
                </div>
                
                <div class="herramientas">
                    <h3>🛠️ Equipo</h3>
                    <ul>
                        <li>Software de diseño PCB (KiCAD, Eagle, EasyEDA)</li>
                        <li>Fresadora CNC o método de transferencia térmica</li>
                        <li>Cautín y soporte</li>
                        <li>Multímetro</li>
                        <li>Cortador de PCB</li>
                    </ul>
                </div>
                
                <div class="paso">
                    <h4>Paso 1: Diseño del Circuito</h4>
                    <p>Se diseñó el circuito esquemático con 3 LEDs en paralelo, cada uno con su resistencia limitadora de corriente de 220Ω, conectados a una fuente de 9V.</p>
                </div>
                
                <div class="galeria">
                    <div class="imagen-container">
                        <img src="https://via.placeholder.com/400x300/ff6b6b/ffffff?text=Esquem%C3%A1tico" alt="Esquemático">
                        <div class="imagen-caption">Diagrama esquemático del circuito</div>
                    </div>
                    <div class="imagen-container">
                        <img src="https://via.placeholder.com/400x300/4ecdc4/ffffff?text=Dise%C3%B1o+PCB" alt="Diseño PCB">
                        <div class="imagen-caption">Diseño del layout del PCB</div>
                    </div>
                    <div class="imagen-container">
                        <img src="https://via.placeholder.com/400x300/ffe66d/ffffff?text=PCB+Fabricado" alt="PCB virgen">
                        <div class="imagen-caption">PCB después del proceso de fabricación</div>
                    </div>
                </div>
                
                <div class="paso">
                    <h4>Paso 2: Fabricación del PCB</h4>
                    <p>Se transfirió el diseño a la placa de cobre mediante fresado CNC. Se limpió la placa y se verificaron las pistas de cobre.</p>
                </div>
                
                <div class="paso">
                    <h4>Paso 3: Soldadura de Componentes</h4>
                    <p>Se soldaron los componentes en el siguiente orden: resistencias, LEDs (respetando polaridad) y finalmente el portapilas. Se verificó cada conexión con el multímetro.</p>
                </div>
                
                <div class="galeria">
                    <div class="imagen-container">
                        <img src="https://via.placeholder.com/400x300/a8e6cf/ffffff?text=Componentes+Soldados" alt="Soldadura">
                        <div class="imagen-caption">Componentes soldados en el PCB</div>
                    </div>
                    <div class="imagen-container">
                        <img src="https://via.placeholder.com/400x300/ffd3b6/ffffff?text=Prueba+de+LEDs" alt="Probando">
                        <div class="imagen-caption">Prueba de funcionamiento con batería conectada</div>
                    </div>
                    <div class="imagen-container">
                        <img src="https://via.placeholder.com/400x300/ffaaa5/ffffff?text=Circuito+Funcionando" alt="Funcionando">
                        <div class="imagen-caption">Los 3 LEDs encendidos correctamente</div>
                    </div>
                </div>
                
                <div class="nota">
                    <strong>✅ Resultado:</strong> El circuito funciona correctamente. Los 3 LEDs se encienden con brillo uniforme al conectar la batería de 9V. Se verificó el consumo de corriente y todas las conexiones están firmes.
                </div>
            </div>
        </div>
        
        <footer>
            <p>📚 Documentación de Fabricación Digital | 2024</p>
            <p>Impresión 3D • Corte Láser • Electrónica</p>
        </footer>
    </div>
</body>
</html>
