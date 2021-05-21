<!DOCTYPE html>
<html lang="pt-BR">
  <head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>´Érica Além dos rótulos</title>
        
    <!--  <link rel="stylesheet" href="apresenta.js">-->
     <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.0.0-beta3/dist/js/bootstrap.bundle.min.js" integrity="sha384-JEW9xMcG8R+pH31jmWH6WWP0WintQrMb4s7ZOdauHnUtxwoG2vI5DkLtS3qm9Ekf" crossorigin="anonymous"></script>
     <script src="https://cdn.jsdelivr.net/npm/@popperjs/core@2.9.1/dist/umd/popper.min.js" integrity="sha384-SR1sx49pcuLnqZUnnPwx6FCym0wLsk5JZuNx2bPPENzswTNFaQU1RDvt3wT4gWFG" crossorigin="anonymous"></script>
     <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.0.0-beta3/dist/js/bootstrap.min.js" integrity="sha384-j0CNLUeiqtyaRmlzUHCPZ+Gy5fQu0dQ6eZ/xAww941Ai1SxSY+0EQqNXNE6DZiVc" crossorigin="anonymous"></script>
     <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/css/bootstrap.min.css">
     <script src="https://ajax.googleapis.com/ajax/libs/jquery/3.3.1/jquery.min.js"></script>
     <script src="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/js/bootstrap.min.js"></script>
     <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.1.3/css/bootstrap.min.css" integrity="sha384-MCw98/SFnGE8fJT3GXwEOngsV7Zt27NXFoaoApmYm81iuXoPkFOJwJ8ERdknLPMO" crossorigin="anonymous">
     <script src="https://code.jquery.com/jquery-3.3.1.slim.min.js" integrity="sha384-q8i/X+965DzO0rT7abK41JStQIAqVgRVzpbzo5smXKp4YfRvH+8abtTE1Pi6jizo" crossorigin="anonymous"></script>
     <script src="https://cdnjs.cloudflare.com/ajax/libs/popper.js/1.14.3/umd/popper.min.js" integrity="sha384-ZMP7rVo3mIykV+2+9J3UJ46jBk0WLaUAdn689aCwoqbBJiSnjAK/l8WvCWPIPm49" crossorigin="anonymous"></script>
     <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.1.3/js/bootstrap.min.js" integrity="sha384-ChfqqxuZUCnJSK3+MXmPNIyE6ZbWh2IMqE241rYiqJxyMiZ6OW/JmZQ5stwEULTy" crossorigin="anonymous"></script>
     <link rel="stylesheet" href="apresenta.css">
    </head>

<body class="cor">
  <audio id="demo" src="apresenta/Rag n Bone Man - Human (Official Video)_50k.mp3"></audio>
  <div>
    <button onclick="document.getElementById('demo').muted = true;">Mute</button>
  <!- ISTO ABAIXO É OPCIONAL->
    <button onclick="document.getElementById('demo').play()" hidden>Reproduzir o áudio</button>
    <button onclick="document.getElementById('demo').pause()" hidden>Pausar o áudio</button>
    <button onclick="document.getElementById('demo').volume+=0.1" hidden>Aumentar o volume</button>
    <button onclick="document.getElementById('demo').volume-=0.1" hidden>Diminuir o volume</button>
  </div>
  
  <!- ISTO EXECUTA O ÁUDIO AO ABRIR A PÁGINA->
  <script type="text/javascript">
  var v = document.getElementById('demo');
  v.play();
  </script>
  <div></div>
      <audio src="apresenta/alem.mp4" autoplay ></audio>
    <header >
     <main class="cor grid-1 ">      
      <nav class="container"> 
        <ul>
            <li class="color-yellow"><a href="apresenta.html">Home</a></li>
            <li class="color-yellow"><a href="sonho.html">Meus Sonhos</a></li>
            <li class="color-yellow"><a href="dificuldades.html">Momentos difíceis</a></li>
            <li class="color-yellow"><a href="super.html">Superação</a></li>
            <li class="color-yellow"><a href="agrade.html">Agradecimentos</a></li>
            
        </ul>
        <li>
      </nav>
     </main> 
    </header>
    <section class="section ">
        
        <a class=" btn-primary" href="carrocel.html" role="button"><h1 class="hero-text bot">Érica além dos rótulos</h1></a>
    </section>

  

    
    <footer class="cor ">
      
        <ul>
        <div class="footer-div">  
        <article >
            <div >
                <li class="cor "><a  href="https://github.com/Erica34124"><img src="apresenta/git.jpg" class=" icon-footer cor" alt="">Acesse o Github</a></li>
              <div class="card-container">
              </div>
            </div>
          </article>
        </div> 
        <div class="footer-div">  
          <article >
            <div >
                
                <li class="cor "><a href="https://www.linkedin.com/in/%C3%A9ricarodrigues34124/">
              <img src="apresenta/linked.png" class=" icon-footer " alt="">Acesse o linkedin</a></li>
              <div class="card-container">
              </div>
            </div>
          </article>
        </div >   
        </ul>
        
    </footer>
    
</body>
</html>