<!DOCTYPE html>

<html lang="it" dir="ltr">

    <head>

        <meta charset="UTF-8">
        <meta http-equiv="X-UA-Compatible" content="IE=edge">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">

        <title>Calcolatore GoodGame Empire</title>

        <!--Style-->
        <link rel="stylesheet" href="style.css">
        <link rel="shortcut icon" href="assets/images/favicon.ico" type=image/x-icon>
        <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.3/css/all.min.css"/>

        <!-- Boxiocns CDN Link -->
        <link href='https://unpkg.com/boxicons@2.0.7/css/boxicons.min.css' rel='stylesheet'>

        <!-- Jquery -->
        <script src="https://ajax.googleapis.com/ajax/libs/jquery/3.5.1/jquery.min.js"></script>

    </head>

    <body>

        
        <div class="loader-wrapper">
            <span class="loader"><span class="loader-inner"></span></span>
        </div>

        <!-- Sidebar -->
        <div class="sidebar close">
            <div class="logo-details">
            <i class='bx '><img src="assets/icons/logo.png" alt=""></i>
            <span class="logo_name">Calcolatori</span>
            </div>
            <ul class="nav-links">
            <li>
                <div class="iocn-link">
                <a href="#section1">
                    <i class='bx' ><img src="assets/icons/onore.PNG" alt=""></i>
                    <span class="link_name">Onore</span>
                </a>
                <i class='bx bxs-chevron-down arrow' ></i>
                </div>
                <ul class="sub-menu">
                <li><a class="link_name" href="#section1">Onore</a></li>
                <li><a href="#section1">Bonus Onore Gloria</a></li>
                <li><a href="#section2">Guadagno In Battaglia</a></li>
                </ul>
            </li>
            <li>
                <div class="iocn-link">
                <a href="#section3">
                    <i class='bx' ><img src="assets/icons/spie.PNG" alt=""></i>
                    <span class="link_name">Spionaggio</span>
                </a>
                <i class='bx bxs-chevron-down arrow' ></i>
                </div>
                <ul class="sub-menu">
                <li><a class="link_name" href="#section3">Spionaggio</a></li>
                <li><a href="#section3">Rischio Spio</a></li>
                </ul>
            </li>
            <li>
                <div class="iocn-link">
                <a href="#section4">
                    <i class='bx' ><img src="assets/icons/sabotaggi.PNG" alt=""></i>
                    <span class="link_name">Sabotaggi</span>
                </a>
                <i class='bx bxs-chevron-down arrow' ></i>
                </div>
                <ul class="sub-menu">
                <li><a class="link_name" href="#section4">Sabotaggio</a></li>
                <li><a href="#section4">Rischio Sabotaggio</a></li>
                </ul>
            </li>
            <li>
                <div class="iocn-link">
                <a href="#section5">
                    <i class='bx' ><img src="assets/icons/Campionato.PNG" alt=""></i>
                    <span class="link_name">Campionato</span>
                </a>
                <i class='bx bxs-chevron-down arrow' ></i>
                </div>
                <ul class="sub-menu">
                <li><a class="link_name" href="#section5">Campionato</a></li>
                <li><a href="#section5">Promozione</a></li>
                </ul>
            </li>
            <li>
                <div class="iocn-link">
                <a href="#section6">
                    <i class='bx' ><img src="assets/icons/fucina.png" alt=""></i>
                    <span class="link_name">Fucina</span>
                </a>
                <i class='bx bxs-chevron-down arrow' ></i>
                </div>
                <ul class="sub-menu">
                <li><a class="link_name" href="#section6">Fucina</a></li>
                <li><a href="#section6">Costo Energia</a></li>
                </ul>
            </li>
            <li>
                <a href="#impostazioni" class="button">
                <i class='bx bx-cog' ></i>
                <span class="link_name button">Impostazioni</span>
                </a>
                <ul class="sub-menu blank">
                <li><a class="link_name button" href="#impostazioni">Impostazioni</a></li>
                </ul>
            </li>
            <li>
                <div class="iocn-link">
                <a href="https://www.goodgamestudios.com/terms_it/" target="_blank">
                    <i class='bx bx-link-external' ></i>
                    <span class="link_name">Condizioni D'uso</span>
                </a>
                </div>
                <ul class="sub-menu">
                    <li><a class="link_name" href="https://www.goodgamestudios.com/terms_it/">Condizioni d'uso</a></li>
                </ul>
            </li>
        </div>

        <div class="alert hide">
            <span class="fas fa-exclamation-circle"></span>
            <span class="msg">Prossimamente...</span>
            <div class="close-btn">
               <span class="fas fa-times"></span>
            </div>
         </div>

        <!-- Pagina1 -->
        <section id="section1" class="home-section">
            <div class="home-content">
                <div class="icon-open">
                    <i class='bx bx-menu' ></i>
                    <span class="text">GoodGame Empire beta</span>
                </div>
                <!-- Bubbles -->
                <div class="bubbles">
                    <span class="one"></span>
                    <span class="two"></span>
                    <span class="three"></span>
                    <span class="four"></span>
                    <span class="five"></span>
                    <span class="six"></span>
                    <span class="seven"></span>
                    <span class="seven"></span>
                </div>
                <div class="bubbles">
                    <span class="one"></span>
                    <span class="two"></span>
                    <span class="three"></span>
                    <span class="four"></span>
                    <span class="five"></span>
                    <span class="six"></span>
                    <span class="seven"></span>
                    <span class="seven"></span>
                </div>
                <div class="bubbles">
                    <span class="one"></span>
                    <span class="two"></span>
                    <span class="three"></span>
                    <span class="four"></span>
                    <span class="five"></span>
                    <span class="six"></span>
                    <span class="seven"></span>
                    <span class="seven"></span>
                </div>
                <div class="bubbles">
                    <span class="one"></span>
                    <span class="two"></span>
                    <span class="three"></span>
                    <span class="four"></span>
                    <span class="five"></span>
                    <span class="six"></span>
                    <span class="seven"></span>
                    <span class="seven"></span>
                </div>
                <!-- Calcolatore Bonus Onore Per La GLoria -->
                <div class="container">
                    <input id="result1" class="result" type="text" name="answer" disabled="disabled">
                    <div class="input-text">
                        <input class="insert-text width-dynamic" id="value1" type="text" placeholder="Inserire" >
                        <input class="info-text width-dynamic" disabled="disabled" type="text" placeholder="Onore In Possesso" >
                    </div>
                </div>
                <!-- Ancora Con La Quale Passare Da Una Pagina All'Altra -->
                <div class="anchor">
                    <div class="anchor_text">1 / 6<br>Calcolatore Bonus Onore Gloria</div>
                    <a href="#section2" class="anchor_button"><i class='bx bx-right-arrow-circle'></i></a>
                </div>
            </div>        
        </section>

        <!-- Pagina2 -->
        <section id="section2" class="home-section">
            <div class="home-content">
                <!-- Bubbles -->
                <div class="bubbles">
                    <span class="one"></span>
                    <span class="two"></span>
                    <span class="three"></span>
                    <span class="four"></span>
                    <span class="five"></span>
                    <span class="six"></span>
                    <span class="seven"></span>
                    <span class="seven"></span>
                </div>
                <div class="bubbles">
                    <span class="one"></span>
                    <span class="two"></span>
                    <span class="three"></span>
                    <span class="four"></span>
                    <span class="five"></span>
                    <span class="six"></span>
                    <span class="seven"></span>
                    <span class="seven"></span>
                </div>
                <div class="bubbles">
                    <span class="one"></span>
                    <span class="two"></span>
                    <span class="three"></span>
                    <span class="four"></span>
                    <span class="five"></span>
                    <span class="six"></span>
                    <span class="seven"></span>
                    <span class="seven"></span>
                </div>
                <div class="bubbles">
                    <span class="one"></span>
                    <span class="two"></span>
                    <span class="three"></span>
                    <span class="four"></span>
                    <span class="five"></span>
                    <span class="six"></span>
                    <span class="seven"></span>
                    <span class="seven"></span>
                </div>
                <!-- Calcolatore Guadagno Onore -->
                <div class="container">
                    <input id="result2" class="result" type="text" name="answer" disabled="disabled">
                    <div class="input-text">
                        <input class="insert-text width-dynamic" id="value2" type="text" placeholder="Inserisci">
                        <input class="info-text width-dynamic" disabled="disabled" type="text" placeholder="Onore In Possesso" >
                    </div>
                    <div class="input-text">
                        <input class="insert-text width-dynamic" id="value3" type="text" placeholder="Inserisci">
                        <input class="info-text width-dynamic" disabled="disabled" type="text" placeholder="Onore Nemico" >
                    </div>
                    <div class="input-text">
                        <input class="insert-text width-dynamic" id="value4" type="text" placeholder="Inserisci">
                        <input class="info-text width-dynamic" disabled="disabled" type="text" placeholder="Bonus Comandante" >
                    </div>
                    <div class="input-text">
                        <input class="insert-text width-dynamic" id="value5" type="text" placeholder="Inserisci">
                        <input class="info-text width-dynamic" disabled="disabled" type="text" placeholder="Bonus Torre di ricerca" >
                    </div>
                    <div class="input-text">
                        <input class="insert-text width-dynamic" id="value6" type="text" placeholder="Inserisci">
                        <input class="info-text width-dynamic" disabled="disabled" type="text" placeholder="Bonus Sala Delle Leggende" >
                    </div>
                </div>
                <!-- Ancora Con La Quale Passare Da Una Pagina All'Altra -->
                <div class="anchor">
                    <div class="anchor_text">2 / 6<br>Calcolatore Guadagno Onore</div>
                    <a href="#section1" class="anchor_button"><i class='bx bx-left-arrow-circle'></i></a><a href="#section3" class="anchor_button"><i class='bx bx-right-arrow-circle'></i></a>
                </div>
            </div>        
        </section>

        <!-- Pagina3 -->
        <section id="section3" class="home-section">
            <div class="home-content">
                <!-- Bubbles -->
                <div class="bubbles">
                    <span class="one"></span>
                    <span class="two"></span>
                    <span class="three"></span>
                    <span class="four"></span>
                    <span class="five"></span>
                    <span class="six"></span>
                    <span class="seven"></span>
                    <span class="seven"></span>
                </div>
                <div class="bubbles">
                    <span class="one"></span>
                    <span class="two"></span>
                    <span class="three"></span>
                    <span class="four"></span>
                    <span class="five"></span>
                    <span class="six"></span>
                    <span class="seven"></span>
                    <span class="seven"></span>
                </div>
                <div class="bubbles">
                    <span class="one"></span>
                    <span class="two"></span>
                    <span class="three"></span>
                    <span class="four"></span>
                    <span class="five"></span>
                    <span class="six"></span>
                    <span class="seven"></span>
                    <span class="seven"></span>
                </div>
                <div class="bubbles">
                    <span class="one"></span>
                    <span class="two"></span>
                    <span class="three"></span>
                    <span class="four"></span>
                    <span class="five"></span>
                    <span class="six"></span>
                    <span class="seven"></span>
                    <span class="seven"></span>
                </div>
                <!-- Rischio Spio-->
                <div class="container">
                    <input id="result3" class="result" type="text" name="answer" disabled="disabled">
                    <div class="input-text">
                        <input class="insert-text width-dynamic" id="value7" type="text" placeholder="Inserisci">
                        <input class="info-text width-dynamic" disabled="disabled" type="text" placeholder="Quantità Di Spie Usate" >
                    </div>
                    <div class="input-text">
                        <input class="insert-text width-dynamic" id="value8" type="text" placeholder="Inserisci">
                        <input class="info-text width-dynamic" disabled="disabled" type="text" placeholder="Numero Di Guardie Cittadine Del Nemico" >
                    </div>
                    <div class="input-text">
                        <input class="insert-text width-dynamic" id="value9" type="text" placeholder="Inserisci">
                        <input class="info-text width-dynamic" disabled="disabled" type="text" placeholder="Precisione Spio" >
                    </div><br>
                </div>
                <!-- Ancora Con La Quale Passare Da Una Pagina All'Altra -->
                <div class="anchor">
                    <div class="anchor_text">3 / 6<br>Calcolatore Rischio Spionaggio</div>
                    <a href="#section2" class="anchor_button"><i class='bx bx-left-arrow-circle'></i></a><a href="#section4" class="anchor_button"><i class='bx bx-right-arrow-circle'></i></a>
                </div>
            </div>        
        </section>

        <!-- Pagina4 -->
        <section id="section4" class="home-section">
            <div class="home-content">
                <!-- Bubbles -->
                <div class="bubbles">
                    <span class="one"></span>
                    <span class="two"></span>
                    <span class="three"></span>
                    <span class="four"></span>
                    <span class="five"></span>
                    <span class="six"></span>
                    <span class="seven"></span>
                    <span class="seven"></span>
                </div>
                <div class="bubbles">
                    <span class="one"></span>
                    <span class="two"></span>
                    <span class="three"></span>
                    <span class="four"></span>
                    <span class="five"></span>
                    <span class="six"></span>
                    <span class="seven"></span>
                    <span class="seven"></span>
                </div>
                <div class="bubbles">
                    <span class="one"></span>
                    <span class="two"></span>
                    <span class="three"></span>
                    <span class="four"></span>
                    <span class="five"></span>
                    <span class="six"></span>
                    <span class="seven"></span>
                    <span class="seven"></span>
                </div>
                <div class="bubbles">
                    <span class="one"></span>
                    <span class="two"></span>
                    <span class="three"></span>
                    <span class="four"></span>
                    <span class="five"></span>
                    <span class="six"></span>
                    <span class="seven"></span>
                    <span class="seven"></span>
                </div>
                <!-- Rischio Sabotaggio-->
                <div class="container">
                    <input id="result4" class="result" type="text" name="answer" disabled="disabled">
                    <div class="input-text">
                        <input class="insert-text width-dynamic" id="value13" type="text" placeholder="Inserisci">
                        <input class="info-text width-dynamic" disabled="disabled" type="text" placeholder="Quantità Di Spie Usate" >
                    </div>
                    <div class="input-text">
                        <input class="insert-text width-dynamic" id="value14" type="text" placeholder="Inserisci">
                        <input class="info-text width-dynamic" disabled="disabled" type="text" placeholder="Numero Guardie Cittadine Nemico" >
                    </div>
                    <div class="input-text">
                        <input class="insert-text width-dynamic" id="value15" type="text" placeholder="Inserisci">
                        <input class="info-text width-dynamic" disabled="disabled" type="text" placeholder="Danni Inflitti" >
                    </div>
                </div>
                <!-- Ancora Con La Quale Passare Da Una Pagina All'Altra -->
                <div class="anchor">
                    <div class="anchor_text">4 / 6<br>Rischio Sabotaggio</div>
                    <a href="#section3" class="anchor_button"><i class='bx bx-left-arrow-circle'></i></a><a href="#section5" class="anchor_button"><i class='bx bx-right-arrow-circle'></i></a>
                </div>
            </div>
        </section>

        <!-- Pagina5 -->
        <section id="section5" class="home-section">
            <div class="home-content">
                <!-- Bubbles -->
                <div class="bubbles">
                    <span class="one"></span>
                    <span class="two"></span>
                    <span class="three"></span>
                    <span class="four"></span>
                    <span class="five"></span>
                    <span class="six"></span>
                    <span class="seven"></span>
                    <span class="seven"></span>
                </div>
                <div class="bubbles">
                    <span class="one"></span>
                    <span class="two"></span>
                    <span class="three"></span>
                    <span class="four"></span>
                    <span class="five"></span>
                    <span class="six"></span>
                    <span class="seven"></span>
                    <span class="seven"></span>
                </div>
                <div class="bubbles">
                    <span class="one"></span>
                    <span class="two"></span>
                    <span class="three"></span>
                    <span class="four"></span>
                    <span class="five"></span>
                    <span class="six"></span>
                    <span class="seven"></span>
                    <span class="seven"></span>
                </div>
                <div class="bubbles">
                    <span class="one"></span>
                    <span class="two"></span>
                    <span class="three"></span>
                    <span class="four"></span>
                    <span class="five"></span>
                    <span class="six"></span>
                    <span class="seven"></span>
                    <span class="seven"></span>
                </div>
                <!-- Rischio Spio-->
                <div class="container" style="width: 800px;">
                    <input id="result5" class="result" type="text" name="answer" disabled="disabled">
                    <div class="input-text">
                        <input class="insert-text width-dynamic" id="value17" type="text" placeholder="Inserisci">
                        <input class="info-text width-dynamic" disabled="disabled" type="text" placeholder="Quantità Medaglie Oro" >
                    </div>
                    <div class="input-text">
                        <input class="insert-text width-dynamic" id="value18" type="text" placeholder="Inserisci">
                        <input class="info-text width-dynamic" disabled="disabled" type="text" placeholder="Quantità Medaglie Argento" >
                    </div>
                    <div class="input-text">
                        <input class="insert-text width-dynamic" id="value19" type="text" placeholder="Inserisci">
                        <input class="info-text width-dynamic" disabled="disabled" type="text" placeholder="Quantità Medaglie Bronzo" >
                    </div>
                    <div class="input-text">
                        <input class="insert-text width-dynamic" id="value20" type="text" placeholder="Inserisci">
                        <input class="info-text width-dynamic" disabled="disabled" type="text" placeholder="Quantità Medaglie Vetro" >
                    </div>
                    <div class="input-text">
                        <input class="insert-text width-dynamic" id="value21" type="text" placeholder="Inserisci">
                        <input class="info-text width-dynamic" disabled="disabled" type="text" placeholder="Quantità Medaglie Rame" >
                    </div>
                    <div class="input-text">
                        <input class="insert-text width-dynamic" id="value22" type="text" placeholder="Inserisci">
                        <input class="info-text width-dynamic" disabled="disabled" type="text" placeholder="Quantità Medaglie Pietra" >
                    </div>
                    <div class="input-text">
                        <input class="insert-text width-dynamic" id="value23" type="text" placeholder="Inserisci">
                        <input class="info-text width-dynamic" disabled="disabled" type="text" placeholder="Quantità Medaglie Legno" >
                    </div>
                </div>
                <!-- Ancora Con La Quale Passare Da Una Pagina All'Altra -->
                <div class="anchor">
                    <div class="anchor_text">5 / 6<br>Calcolo Promozione</div>
                    <a href="#section4" class="anchor_button"><i class='bx bx-left-arrow-circle'></i></a><a href="#section6" class="anchor_button"><i class='bx bx-right-arrow-circle'></i></a>
                </div>
            </div> 
        </section>
            
        <!-- Pagina6 -->
        <section id="section6" class="home-section">
            <div class="home-content">
                <!-- Bubbles -->
                <div class="bubbles">
                    <span class="one"></span>
                    <span class="two"></span>
                    <span class="three"></span>
                    <span class="four"></span>
                    <span class="five"></span>
                    <span class="six"></span>
                    <span class="seven"></span>
                    <span class="seven"></span>
                </div>
                <div class="bubbles">
                    <span class="one"></span>
                    <span class="two"></span>
                    <span class="three"></span>
                    <span class="four"></span>
                    <span class="five"></span>
                    <span class="six"></span>
                    <span class="seven"></span>
                    <span class="seven"></span>
                </div>
                <div class="bubbles">
                    <span class="one"></span>
                    <span class="two"></span>
                    <span class="three"></span>
                    <span class="four"></span>
                    <span class="five"></span>
                    <span class="six"></span>
                    <span class="seven"></span>
                    <span class="seven"></span>
                </div>
                <div class="bubbles">
                    <span class="one"></span>
                    <span class="two"></span>
                    <span class="three"></span>
                    <span class="four"></span>
                    <span class="five"></span>
                    <span class="six"></span>
                    <span class="seven"></span>
                    <span class="seven"></span>
                </div>
                <!-- -->
                <div class="container">
                    <input id="result6" class="result" type="text" name="answer" disabled="disabled">
                    <div class="input-text">
                        <input class="insert-text width-dynamic" id="value16" type="text" placeholder="Inserisci">
                        <input class="info-text width-dynamic" disabled="disabled" type="text" placeholder="Livello Decorazione" >
                    </div>
                </div>
                <!-- Ancora Con La Quale Passare Da Una Pagina All'Altra -->
                <div class="anchor">
                    <div class="anchor_text">6 / 6<br>Costo Energia Fusione</div>
                    <a href="#section5" class="anchor_button"><i class='bx bx-left-arrow-circle'></i></a>
                </div>
            </div> 
        </section>

        <!-- Setting Section -->
        <section section id="section11">
            <div class="setting">
                <h1 class="setting_title"></h1>
            </div>
        </section>
        
        <!-- Footer -->
        <footer>
            <div class="footer_text"><span>©2021 GOODGAME STUDIOS, INC. TUTTI I DIRITTI RISERVATI. Tutti i marchi qui riportati sono di proprietà dei rispettivi detentori.</span><a href="https://www.goodgamestudios.com/terms_it/"><i class='bx bx-link-external terms'></i></a></div>
        </footer>
        
        <!-- Qui Comincia Javascript-->
        <script type="text/javascript" src="app.js"></script>
        <script>
            $(window).on("load",function(){
              $(".loader-wrapper").fadeOut("slow");
            });
        </script>

    </body>
</html>
