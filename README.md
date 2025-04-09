<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Tienda Online</title>
    <style>
        body {
            display: flex;
            font-family: Arial, sans-serif;
            margin: 0;
        }
        .sidebar {
            width: 250px;
            background: #333;
            color: white;
            padding: 20px;
            height: 100vh;
        }
        .sidebar h2 {
            text-align: center;
        }
        .sidebar ul {
            list-style: none;
            padding: 0;
        }
        .sidebar ul li {
            padding: 10px;
            cursor: pointer;
        }
        .sidebar ul li:hover {
            background: #444;
        }
        .content {
            flex-grow: 1;
            padding: 20px;
            display: flex;
            flex-wrap: wrap;
            gap: 20px;
        }
        .product-card {
            display: flex;
            flex-direction: column;
            align-items: center;
            width: 220px;
            border-radius: 10px;
            overflow: hidden;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
            background: white;
            padding: 10px;
            text-align: center;
        }
        .product-card img {
            width: 100%;
            border-radius: 10px;
        }
        .product-info {
            padding: 10px;
            font-size: 14px;
        }
        
        .product-info a {
            color: #0b35df;
            font-weight: bold;
            text-decoration: none;
        }

        .product-info h4, h3 {
            color: #000000;
        }

        
    </style>
    
</head>
<body>
    <div class="sidebar">
        <h2>Categorías</h2>
        <ul>
            <li> <a href="WebChatGpt.html">Todos los productos</a></li>
            <li onclick="showSection('electrodomesticos')">Electrodomésticos</li>
            <li onclick="showSection('modaMujer')">Moda Mujer y Hombre</li>
            <li onclick="showSection('hogar')">Hogar y mascotas</li>
            <li onclick="showSection('juguetes')">Juguetes y coleccionismo</li>
            <li onclick="showSection('motor')">Motor y accesorios</li>
            <li onclick="showSection('iluminacion')">Iluminación</li>
        </ul>
    </div>
    


    <div class="content">
        <!-- Electrodomésticos -->
        <div id="electrodomesticos" class="section">
            <div class="product-card">
                <img src="https://ae-pic-a1.aliexpress-media.com/kf/Sa3678677ca4f4afcb867b7b5bd991b22l.jpg" alt="Freidora sin aceite">
                <div class="product-info"> 
                    <p>
                        <h3 class="titulo">Freidora sin aceite</h3>
                        <a href="https://s.click.aliexpress.com/e/_oEm2kFx" target="_blank">
                            Freidora Sin Aceite, 8 Menús Prestablecidos y Modo Manual, 1400W, Panel LED Táctil, Air Fryer de 4,2 Litros de Capacidad, Cesta Antiadherente, Libre de BPA, Color Azul
                            <h4>Ahora precio: EUR 53.99</h4>
                        </a>
                    </p>
                </div>
            </div>
            <div class="product-card">
                <img src="https://ae-pic-a1.aliexpress-media.com/kf/S9f00bb5ee66f4fe889dd300e8aae93b17.jpg" alt="cafetera">
                <div class="product-info"> 
                    <p>
                        <h3 class="titulo">Cafetera de goteo</h3>
                        <a href="https://s.click.aliexpress.com/e/_oEyDpip" target="_blank">
                            Cafetera de Goteo Eléctrica, con Filtro Reutilizable, Pantalla LCD, Programable 24 Horas, Auto Limpieza (Descalcificación), Capacidad 12 Tazas, Mantiene Café Caliente 40 Minutos, Sin BPA, 950W
                            <h4>Ahora precio: EUR 32.99</h4>
                        </a>
                    </p>
                </div>
            </div>
            <div class="product-card">
                <img src="https://ae-pic-a1.aliexpress-media.com/kf/Sfdc2a05cce214fe895e72b91e6bc84ccz.png" alt="secador">
                <div class="product-info"> 
                    <p>
                        <h3 class="titulo">Secador de ropa plegable</h3>
                        <a href="https://s.click.aliexpress.com/e/_okRhQVj" target="_blank">
                            Secador de ropa plegable para el hogar, secador inteligente para bebés y adultos, secador portátil de viaje con control remoto
                            <h4>Ahora precio: EUR 43.19</h4>
                        </a>
                    </p>
                </div>
            </div>
        </div>





        <!-- Moda Mujer -->
        <div id="modaMujer" class="section">
            <div class="product-card">
                <img src="https://ae-pic-a1.aliexpress-media.com/kf/S43cad47ab78b4a2a91ecc2b90a870df0v.jpg" alt="Vestido mujer">
                <div class="product-info">
                    <p>
                      <h3 class="titulo"> Vestido mujer</h3>
                      <a href="https://s.click.aliexpress.com/e/_ol4dWZB" target="_blank">
                        Mia Muse Vestidos de mujer Otoño Invierno Simple Color sólido Manga larga Cuello simulado Una línea de cintura alta Dobladillo acampanado Vestidos cortos casuales
                        <h4>Ahora precio: EUR 12.59</h4>
                      </a>
                    </p>
                </div>
            </div>
            <div class="product-card">
                <img src="https://ae-pic-a1.aliexpress-media.com/kf/S7c69d890704c407da46f8bb4b8cb9c32X.jpg" alt="Vestido mujer">
                <div class="product-info">
                    <p>
                      <h3 class="titulo"> Vestido verano</h3>
                      <a href="https://s.click.aliexpress.com/e/_okpFjZB" target="_blank">
                        Nuevo vestido explosivo de verano de alta sensibilidad con correa halter Spice Girl bolso vestido a la cadera
                        <h4>Ahora precio: EUR 8.36</h4>
                      </a>
                    </p>
                </div>
            </div>
            <div class="product-card">
                <img src="https://ae-pic-a1.aliexpress-media.com/kf/S731549c7b31c46e6a3fc9750569753a6A.jpg" alt="Vestido mujer">
                <div class="product-info">
                    <p>
                      <h3 class="titulo"> Conjunto pantalon y chaqueta</h3>
                      <a href="https://s.click.aliexpress.com/e/_oCVwNcz" target="_blank">
                        Conjuntos de dos piezas para mujer, cárdigan elegante y a la moda, abrigos de manga larga, pantalones con cordón, traje liso con bolsillo
                        <h4>Ahora precio: EUR 9.89</h4>
                      </a>
                    </p>
                </div>
            </div>
        </div>





        <!-- Hogar -->
        <div id="hogar" class="section">
            <div class="product-card">
                <img src="https://ae-pic-a1.aliexpress-media.com/kf/E8762a5331ab5460db8a80c472102567f1.jpg" alt="gatos">
                <div class="product-info">
                    <p>
                        <h3 class="titulo">Arbol rascador</h3>
                        <a href="https://s.click.aliexpress.com/e/_okjrvit" target="_blank">
                            Árbol Rascador 50x35x138 cm Gris Poste De Sisal Natural  Arbol para Gatos con Plataforma Torre Rascador Escalador para 2-3 Gatos Medianos Estable Rascador con Nidos Hamaca Plataformas Juguete. 
                           <h4>Ahora precio: EUR 35.25</h4>
                        </a>
                    </p>
                </div>
            </div>
            <div class="product-card">
                <img src="https://ae-pic-a1.aliexpress-media.com/kf/Sd21fcdd143ea45c1aa98e610e3990871I.jpg" alt="espuma">
                <div class="product-info">
                    <p>
                        <h3 class="titulo">Espuma absorbente de sonido</h3>
                        <a href="https://s.click.aliexpress.com/e/_omOZKk1" target="_blank">
                            TOUO Espuma absorbente de sonido 6-48 Uds paneles de espuma acústica insonorización de pared estudio tratamiento acústico Material absorbente de sonido 
                           <h4>Ahora precio: EUR 6.99</h4>
                        </a>
                    </p>
                </div>
            </div>
            <div class="product-card">
                <img src="https://ae-pic-a1.aliexpress-media.com/kf/S6214af811f0841a491fa05ba55fefff75.jpg" alt="pared">
                <div class="product-info">
                    <p>
                        <h3 class="titulo">Ladrillo 3D</h3>
                        <a href="https://s.click.aliexpress.com/e/_oCxoysZ" target="_blank">
                            70cm * 1m patrón de ladrillo 3D paneles de pared papel tapiz DIY impermeable para sala de estar dormitorio cocina fondo decoración de pared 
                           <h4>Ahora precio: EUR 2.29</h4>
                        </a>
                    </p>
                </div>
            </div>
        </div>





        <!-- Juguetes -->
        <div id="juguetes" class="section">
            <div class="product-card">
                <img src="https://ae-pic-a1.aliexpress-media.com/kf/Sd29329d5d56e463ba45ef38a304e0526Y.jpg" alt="Serie Pokemon">
                <div class="product-info">
                    <p>
                        <h3 class="titulo">Pokemon Game Boy Color</h3>
                        <a href="https://s.click.aliexpress.com/e/_okYTJXJ" target="_blank">
                            Serie Pokemon azul cristal oro verde rojo plata amarillo versión ESP juego GBC en caja para cartucho de videojuego de 16 bits sin Manual
                            <h4>Ahora precio: EUR 11.49</h4>
                        </a>
                    </p>
                </div>
            </div>
            <div class="product-card">
                <img src="https://ae-pic-a1.aliexpress-media.com/kf/S3aa4f8bfceb14503a1cf7504c79f74ees.jpg" alt="Serie Llavero">
                <div class="product-info">
                    <p>
                        <h3 class="titulo">Llavero de coche</h3>
                        <a href="https://s.click.aliexpress.com/e/_oDo8BL3" target="_blank">
                            LLavero de coche modelo de aleación electrochapada, GTR R34 RS7, decoración de colección de Metal fundido a presión, exquisita caja de regalo, 1/64
                            <h4>Ahora precio: EUR 6.29</h4>
                        </a>
                    </p>
                </div>
            </div>
            <div class="product-card">
                <img src="https://ae-pic-a1.aliexpress-media.com/kf/S80b91a22f64f49c79c64ab5651113095J.jpg" alt="moto">
                <div class="product-info">
                    <p>
                        <h3 class="titulo">Kawasaki Ninja H2R 1/12</h3>
                        <a href="https://s.click.aliexpress.com/e/_ol5wATB" target="_blank">
                            1/12 motocicleta H2R Diecast aleación simulada-modelo de coche decoración de oficina vehículos estáticos pasatiempos coleccionables regalos para niños juguete
                            <h4>Ahora precio: EUR 6.09</h4>
                        </a>
                    </p>
                </div>
            </div>
        </div>





        <!-- Motor -->
        <div id="motor" class="section">
            <div class="product-card">
                <img src="https://ae-pic-a1.aliexpress-media.com/kf/Sb9b0ee27f7d542ebb36c0d6bd27f8f5fo.jpg" alt="Dash Cam">
                <div class="product-info">                   
                    <p>
                        <h3 class="titulo">REDTIGER F9 Dash Cam</h3>
                        <a href="https://s.click.aliexpress.com/e/_oFvmH2H" target="_blank">
                            Dash Cam Cam 4K WiFi delantero y trasero GPS cámara de coche para modo de estacionamiento Dvr de coche para visión nocturna grabadora de coche por Control de aplicación
                            <h4>Ahora precio: EUR 78.89</h4>
                        </a>
                    </p>
                </div>
            </div>
            <div class="product-card">
                <img src="https://ae-pic-a1.aliexpress-media.com/kf/A8d9614b7dc55486da7a88e748940f174k.jpg" alt="bateria">
                <div class="product-info">                  
                    <p>
                        <h3 class="titulo">Arrancador de bateria</h3>
                        <a href="https://s.click.aliexpress.com/e/_ol4GxeV" target="_blank">
                            99800mAh portátil arranque de coche pico 5000A banco de energía carga 12V equipo de arranque automático aceite diésel batería de emergencia de coche
                            <h4>Ahora precio: EUR 32.155</h4>
                        </a>
                    </p>
                </div>
            </div>
            <div class="product-card">
                <img src="https://ae-pic-a1.aliexpress-media.com/kf/S69808646e6bc4a91a3e4ec14bc6cdfc5U.png" alt="limpiador">
                <div class="product-info">                  
                    <p>
                        <h3 class="titulo">Pulverizador de espuma</h3>
                        <a href="https://s.click.aliexpress.com/e/_oCeL3Hf" target="_blank">
                            Pulverizador de espuma de 2L para lavado de coches, regadera de espuma manual, pulverizador de presión de aire, botella de agua de desinfección de plástico, Herramientas de limpieza de coche
                            <h4>Ahora precio: EUR 7.89</h4>
                        </a>
                    </p>
                </div>
            </div>
        </div>





        <!-- Iluminación -->
        <div id="iluminacion" class="section">
            <div class="product-card">
                <img src="https://ae01.alicdn.com/kf/S42a761cbfa2349c48e0d24f1f02468bbg.jpg" alt="Cabeza móvil">
                <div class="product-info">                   
                    <p>
                        <h3 class="titulo">Cabeza móvil RGBW</h3>
                        <a href="https://s.click.aliexpress.com/e/_okYTJXJ" target="_blank">
                            Luces LED con cabezal móvil de barra de 8x15W, iluminación RGBW con DMX 512 para controlador DJ Disco KTV, foco para fiesta, boda, club nocturno
                            <h4>Ahora precio: EUR 292.99</h4>
                        </a>
                    </p>
                </div>
            </div>
        
        <div class="product-card">
                <img src="https://ae-pic-a1.aliexpress-media.com/kf/Sb3232b3cca50473f8c11effe4b0ba478r.jpg" alt="Cabeza móvil">
                <div class="product-info">
                    <p>
                        <h3 class="titulo">ESHINY RG RGB láser</h3>
                        <a href="https://s.click.aliexpress.com/e/_okJGLtX" target="_blank">
                            ESHINY RG RGB láser 8/12/32 patrones proyector DJ luz ambiental fiesta de baile Navidad iluminación de escenario lámpara de discoteca Show Z20D2
                            <h4>Ahora precio: EUR 41.79<br></h4>
                        </a> 
                    </p>
                </div>
            </div>
        
        <div class="product-card">
                <img src="https://ae-pic-a1.aliexpress-media.com/kf/Sfa7d8bcec8c540f990f33e3169cc71ad7.jpg" alt="laser">
                <div class="product-info">
                    <p>
                        <h3 class="titulo">Láser RGB de 500mw</h3>
                        <a href="https://s.click.aliexpress.com/e/_omjM9PL" target="_blank">
                            Nuevo proyector de escáner de línea de haz láser RGB de 500mw, efecto de iluminación de escenario para discoteca, fiesta de baile, boda, vacaciones, Bar, Club, luces DMX
                            <h4>Ahora precio: EUR 54.50</h4>
                        </a> 
                    </p>
                </div>
            </div>
         </div>












    </div>

    <script>
        function showSection(category) {
            document.querySelectorAll('.section').forEach(section => {
                section.style.display = 'none';
            });
            document.getElementById(category).style.display = 'block';
        }
    </script>
</body>
</html>
