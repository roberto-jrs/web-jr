<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>RS Pinturas Brasil</title>
    <link rel="stylesheet" href="style1.css">
    <link rel="icon" type="image/x-icon" href="https://roberto-jrs.github.io/web-jr/icone.png">
    
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Nosifer&display=swap" rel="stylesheet">
  
  
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=Bebas+Neue&display=swap" rel="stylesheet">
    

</head>



<body>
	
	<div class="whats">
    <a href="https://wa.me/5515997121988?text=Olá! Gostaria de fazer um orçamento." target="_blank">
    <img src="https://roberto-jrs.github.io/web-jr/whatsappfundo.png" alt="Whatsapp" style="width: 60px; position: fixed; bottom: 43px; right: 43px; border-radius: 50px;"></a>
    </div>
	
    <div class="textfixo">
        <header>
            <nav>
                <ul>
                    <li><a href="#01">Home</a></li>
                    <li><a href="#02">Sobre</a></li>
                    <li><a href="#03">Fotos</a></li>
                    <li><a href="#04">Serviços</a></li>
                    <li><a href="https://roberto-jrs.github.io/web-jr/orcamento.html">Orçamento</a></li>
                    <li><a href="#06">Contato</a></li>
                </ul>
            </nav>
        </header>
    </div>
  
  <header>
	
  <div class="redes">
        
            <ul>
              
             <li>
      <a href="https://www.instagram.com/rs_pinturas_brasil_/" 
      target="_blank"><img src="https://roberto-jrs.github.io/web-jr/instagram.png" alt="Instagram" style="width: 58px;"></a> 
               </li>
            
          <li>
            <a href="https://www.facebook.com/rodrigo.sales.129142" 
            target="_blank"><img src="https://roberto-jrs.github.io/web-jr/Facebook.png" alt="Facebook" style="width: 35px;"></a>
            </li>
  
        
      </ul>
      </div>
      
      
	
      <!-- Aqui pra baixo é o texto do botão menu-->
  <div id="header">
      
    <a id="logo" href=""></a>
    <nav id="nav">
      <button aria-label="Abrir Menu" id="btn-mobile" aria-haspopup="true" aria-controls="menu" aria-expanded="false">
        <span id="hamburger"></span>
      </button>
      <ul id="menu" role="menu">
        <li><a href="#01">Home</a></li> <br>
        <li><a href="#02">Sobre</a></li> <br>
        <li><a href="#03">Fotos</a></li> <br>
        <li><a href="https://roberto-jrs.github.io/web-jr/orcamento.html">Orçamento</a></li> <br>
        <li><a href="#08">Contato</a></li>
      </ul>
    </nav>
        
         

        
    </div>
        
  </header>
  
    <script>
     
      const btnMobile = document.getElementById('btn-mobile');

function toggleMenu(event) {
  if (event.type === 'touchstart') event.preventDefault();
  const nav = document.getElementById('nav');
  nav.classList.toggle('active');
  const active = nav.classList.contains('active');
  event.currentTarget.setAttribute('aria-expanded', active);
  if (active) {
    event.currentTarget.setAttribute('aria-label', 'Fechar Menu');
  } else {
    event.currentTarget.setAttribute('aria-label', 'Abrir Menu');
  }
}

btnMobile.addEventListener('click', toggleMenu);
btnMobile.addEventListener('touchstart', toggleMenu);
    
    </script>
  
  
  
  
      <!-- Aqui pra cima é o texto do botão menu -->
  

    <div class="tinta06">
      <img src="https://roberto-jrs.github.io/web-jr/SUAIB KAZI - PINTEREST.png" alt="" style="width: 350px;">
      </div>

      <div class="autoria1">
        © SUAIB KAZI - PINTEREST
    </div>

    <div>
        <main id="01">
            <h1>RS Pinturas Brasil</h1>
        <div class="frase">
            <p>Colorindo o mundo com arte e qualidade</p>
        </div>

        <div class="marca0">
        <img src="https://roberto-jrs.github.io/web-jr/simbolomarca.png" alt="" style="width: 25px;">

        </div>

        
            
        </main>
    </div>
    <br>
    <div class="somos">
        <main>
            <h2 id="02">Quem Somos?</h2>
        </main>
        <div class="quemsomos">
         <p>                                                                                                                           
                <main>
		<strong> Primeiramente não somos uma empresa que você somente pesquisa, somos a empresa que você precisa!</strong> </main>
                 </div> <br>
	    <main class="textsomos">
                    Somos especialistas em serviços de pintura de alta qualidade para clientes residenciais, 
                    comerciais e industriais. Nossa equipe de profissionais experientes trabalha em parceria 
                    com cada cliente para criar um plano personalizado que atenda às necessidades e 
                    expectativas. Comprometidos com a sustentabilidade, usamos apenas os melhores materiais 
                    e técnicas ecologicamente corretos. Oferecemos preços justos e transparentes e estamos 
                    comprometidos em fornecer a você um serviço excepcional e resultados surpreendentes. 
                    Entre em contato conosco hoje mesmo para agendar uma consulta e receber um orçamento gratuito.
                    Estamos ansiosos para ajudá-lo a transformar o seu espaço em algo incrível.
                </p>
            </main>
    
    </div>
	
	<div class="imgcel" id="03">
    <div id="slider">
        <img class="selected" src="https://roberto-jrs.github.io/web-jr/002.jpeg" alt="Image1" style="height: 300px;">
        <img src="https://roberto-jrs.github.io/web-jr/012.jpeg" alt="Image2" style="height: 300px;">
        <img src="https://roberto-jrs.github.io/web-jr//004.jpeg" alt="Image3" style="height: 300px;">
        <img src="https://roberto-jrs.github.io/web-jr/007.jpeg" alt="Image4" style="height: 300px;">
        <img src="https://roberto-jrs.github.io/web-jr/003.jpeg" alt="Image5" style="height: 300px;">
        <img src="https://roberto-jrs.github.io/web-jr//008.jpeg" alt="Image6" style="height: 300px;">
        <img src="https://roberto-jrs.github.io/web-jr/010.jpeg" alt="Image7" style="height: 300px;">
        <img src="https://roberto-jrs.github.io/web-jr/011.jpeg" alt="Image8" style="height: 300px;">
    </div>
</div>

    <script>

let time = 5000,
    currentImageIndex = 0,
    images = document
                .querySelectorAll("#slider img")
    max = images.length;

function nextImage() {

    images[currentImageIndex]
        .classList.remove("selected")

    currentImageIndex++

    if(currentImageIndex >= max)
        currentImageIndex = 0

    images[currentImageIndex]
        .classList.add("selected")

}

function start() {
    setInterval(() => {
        // troca de image
        nextImage()
    }, time)
    
}

window.addEventListener("load", start)



    </script>
	
	
    <div class="slideshow" id="03">
    <section id="slideshow">
        <div class="entire-content">
            <div class="content-carrousel">
                <figure class="shadow"><img src="https://roberto-jrs.github.io/web-jr/002.jpeg" alt="4" border="0"></figure>
                <figure class="shadow"><img src="https://roberto-jrs.github.io/web-jr/003.jpeg" alt="5" border="0"></figure>
                <figure class="shadow"><img src="https://roberto-jrs.github.io/web-jr//004.jpeg" alt="6" border="0"></figure>
                <figure class="shadow"><img src="https://roberto-jrs.github.io/web-jr/007.jpeg" alt="7" border="0"></figure>
                <figure class="shadow"><img src="https://roberto-jrs.github.io/web-jr//008.jpeg" alt="8" border="0"></figure>
                <figure class="shadow"><img src="https://roberto-jrs.github.io/web-jr/009.jpeg" alt="9" border="0"></figure>
                <figure class="shadow"><img src="https://roberto-jrs.github.io/web-jr/010.jpeg" alt="9" border="0"></figure>
                <figure class="shadow"><img src="https://roberto-jrs.github.io/web-jr/011.jpeg" alt="9" border="0"></figure>
                <figure class="shadow"><img src="https://roberto-jrs.github.io/web-jr/012.jpeg" alt="9" border="0"></figure>
        </div>
</section>
</div>



<br>
<main>
    <div class="servicos2">
        <h2 id="04">Serviços</h2>
    </div>
</main>

<main class="locais">
<strong> Residencial   &nbsp;&nbsp;&nbsp;&nbsp;   ●   &nbsp;&nbsp;&nbsp;&nbsp;  Comercial   &nbsp;&nbsp;&nbsp;&nbsp;   ●   &nbsp;&nbsp;  Industrial </strong>
</main> <br>
<div class="servicos">
    
    <ul>
        <li>Pintura interna de paredes, tetos e pisos;</li>
        <li>Pintura externa de fachadas, portas e janelas;</li>
        <li>Pintura de móveis e objetos de decoração;</li>
        <li>Texturização de paredes e tetos;</li>
        <li>Aplicação de papel de parede;</li>
        <li>Pintura de superfícies metálicas;</li>
        <li>Pintura de telhados e coberturas;</li>
        <li>Pintura de piscinas e áreas de lazer;</li>
        <li>Pintura de quadras esportivas;</li>
        <li>Lavagem e pintura de calçadas e pisos externos;</li>
        <li>Lavagem de fachada predial;</li>
        <li>Pintura predial;</li>
        <li>Restauração e pintura de superfícies com infiltrações ou mofo.</li>
    </ul>

</div>

	    <div class="orçamento">
        <main>
            &nbsp;Faça agora mesmo um orçamento gratuito <br><br>
            <a href="https://roberto-jrs.github.io/web-jr/orcamento.html" button class="cta-btn" style= "font-family: 'Roboto', sans-serif;">Solicitar Orçamento</button></a>
        </main>
    </div>

    <div class="contat", id="06">
    <main>
    <p>
        &nbsp;&nbsp;&nbsp;Rodrigo Sales <br>
        &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;(15) 99712-1988 
        <a href="https://wa.me/5515997121988?text=Olá! Gostaria de fazer um orçamento." target="_blank">
        <img src="https://roberto-jrs.github.io/web-jr/whatsapp.png" id="img" alt="Whatsapp" style="width: 18px;"><br></a>
        &nbsp;&nbsp;&nbsp;Tatuí - SP
    </p>
    </main>
    </div>
  
  <div class="contatel", id="08">
    <main>
    <p>
        &nbsp;&nbsp;&nbsp;Rodrigo Sales <br>
        &nbsp;&nbsp;&nbsp;(15) 99712-1988 <br>
        &nbsp;&nbsp;&nbsp;Tatuí - SP
    </p>
    </main>
    </div>
  
  
  

    <div class="tinta03"></div>

    <div class="autoria2">
        © FIEDELS - ADOBE STOCK
    </div>

  
  <div class="tintona">
    <img src="https://roberto-jrs.github.io/web-jr/ROBERT KNESCHKE - ADOBE STOCK.png" alt="tinta05" 
         style="width: 500px;">
  </div>

    <div class="tinta05">
        © ROBERT KNESCHKE - ADOBE STOCK
      
    </div>
	
	
	

        <footer>
            <p> <em> Transformando paredes em telas e ambientes em obras de arte.</em><br> 
                © 2019 | RS Pinturas Brasil - Todos os direitos reservados</p>
        </footer>

        
	<!-- 

        Gostou do meu desenvolvimento com este site? Entre em contato comigo pelo meu email, 
        ficarei feliz em fazer um orçamento para você - roberto_aki@hotmail.com. Até mais! 
                                                                                    
                                                                               Junior Siqueira
-->

</body>
</html>
