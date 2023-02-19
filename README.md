# Projeto Escola

# O nosso sistema está em "DESENVOLVIMENTO"
## Versão 1.0

## Temo uma interface Moderna e Simples!

![image](https://user-images.githubusercontent.com/103225660/219918438-d88d4e07-48e5-4760-bab7-a6924a45b581.png)
<br>
![image](https://user-images.githubusercontent.com/103225660/219918638-1279d907-82b2-49f0-8a5d-113d09c07222.png)
<br>
![image](https://user-images.githubusercontent.com/103225660/219918474-de1a115c-cdc8-4830-bf26-3c43100c6df0.png)


## Contamos Com uma Pagina de Login bem Moderna e Simples!

![image](https://user-images.githubusercontent.com/103225660/219918992-8263acbc-fa6d-415c-82c4-8341f57ee8d5.png)


## Contamos Com Mapa do Site!

![image](https://user-images.githubusercontent.com/103225660/219918806-166768e9-ee53-49e3-8040-8eb3db2f6830.png)

# Contamos com um Portal de Notícias Bem simples!

![image](https://user-images.githubusercontent.com/103225660/219919579-c89ee07a-53b1-41d6-bd88-b176ea705e04.png)

![image](https://user-images.githubusercontent.com/103225660/219919674-917aa21a-d02e-47c7-832e-2d9c7276b218.png)

![image](https://user-images.githubusercontent.com/103225660/219919696-522e0d21-dd42-45e9-ac07-ba67a9d4e446.png)

### Códio da Nossa LandingPage

#### Códio HTML5
```
<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <style></style>
    <link rel="stylesheet" href="css/style.css">
    <link rel="shortcut icon" href="favicon.png" type="image/x-icon">
    <title>Home - Projeto Escola</title>
</head>
<body>
    
    <header>
        <div class="logo">
            <img src="img/LOGO.png" alt="...Error">
        </div>
        <input type="checkbox" id="nav_check" hidden>
        <nav>
           <div class="logo">
                <img src="img/LOGO.png" alt="...Error">
            </div>
            <ul>
                <li>
                    <a href="index.html" class="active">Home</a>
                </li>
                <li>
                    <a href="pages/relogios.html">Área do Professor</a>
                </li>
                <li>
                    <a href="#">Área do Aluno</a>
                </li>
                <li>
                    <a href="register/cadastro.html">Cadastro</a>
                </li>
                <li>
                    <a href="register/index.html">Login</a>
                </li>
                <li>
                    <a href="#contato">Contato</a>
                </li>
            </ul>
        </nav>

        <label for="nav_check" class="hamburger">
            <div></div>
            <div></div>
            <div></div>
        </label>
    </header>


    <div class="img-background">
        <img src="img/927bb6fe1058c70104a6c0dd133510be.png" alt="Error...">
    </div>

    <div class="container">
        <h1>Portal do Aluno</h1>
        <div class="area">
        <h2><a href="#">Área do Professor</a></h2>
        <h2><a href="#">Área do Alunor</a></h2>
        <h2><a href="register/cadastro.html">Área do Cadastro</a></h2>
        <h2><a href="register/index.html">Login</a></h2>
        </div>
    </div>

    <footer>
        <div class="aplicativo">
            <ul>
                <h3>Aplicativo</h3>
                <li><a href="index.html">Home</a></li>
                <li><a href="register/index.html">Login</a></li>
                <li><a href="mapa.html">Mapa do Site</a></li>
            </ul>

        </div>
        <div class="social">
            <h3>Social</h3>
            <li><a href="https://instagram.com/eiikaiosilva">Instagram</a></li>
            <li><a href="https://github.com/KaioYt">GitHub</a></li>
            <li><a href="noticias/">Portal de Notícias</a></li>
        </div>
        <div class="contato">
            <a href="#">Contato</a>
        </div>
    </footer>
    
    <script src="https://www.drcode.com.br/nofollow/aviso-cookies/drcode.cookies.js"></script>
    <script>
      avisoCookiesDrcode({})
    </script>


    <script src="https://www.drcode.com.br/nofollow/aviso-cookies/drcode.cookies.js"></script>
    <script src="js/script.js"></script>
    
</body>

</html>
```

#### Códio CSS3

```
body::-webkit-scrollbar {
    width: 8px;         
  }
  
  body::-webkit-scrollbar-track {
    background: none;        
  }
  
  body::-webkit-scrollbar-thumb {
    background-color: #c7c7c7aa;    
    border-radius: 20px;      
    border:  none;  
  }
  
  
  
  
  @import url('https://fonts.googleapis.com/css2?family=Poppins:wght@500&display=swap');
  
  *{
      padding: 0;
      margin: 0;
      box-sizing: border-box;
      list-style: none;
      text-decoration: none;
  }
  
  body{
      font-family: 'Poppins', sans-serif;
      background: #fff;
      transition: 0.3s all;
      margin: 0 auto;
      align-items: center;
      max-width: 1400px;
  }
  
  img{
      width: 70%;
      align-items: center;
      transition: 0.3s all;
  }
  
  header{
      width: 80%;
      height: 70px;
      background: #fefefe;
      display: flex;
      align-items: center;
      justify-content: space-between;
      padding: 0 40px;
      border-radius:  0 0 10px 10px;
      margin: 0 auto;
      transition: 0.3s all;
  }
  
  .logo{
      width: 120px;
      margin-top: 8px;
      transition: 0.3s all;
  }
  
  nav .logo{
      display: none;
      transition: 0.3s all;
  }
  
  nav ul{
      display: flex;
      transition: 0.3s all;
  }
  
  nav ul li a{
      color: #212526;
      display: block;
      margin:  0 2px;
      font-weight: 600;
      padding: 8px 18px;
      border-radius: 30px;
      transition: 0.3s all;
  }
  
  nav ul li a:hover{
      color: rgb(78, 78, 78);
      transform: scale(1.06);
      transition: 0.3s all;
  }
  
  nav ul li a.active{
      background: rgb(4, 148, 214);
      color: #fff;
  }
  
  .hamburger{
      display: none;
      height: fit-content;
      cursor: pointer;
      padding: 3px 8px;
      border-radius: 5px;
      transition: 0.2s;
  }
  
  .hamburger:hover{
      background: #f6f4ff;
  }
  
  .hamburger div{
      width: 30px;
      height: 2px;
      margin: 6px 0;
      background: #212526;
  }
  
  @media only screen and (max-width: 1100px) {
      header{
          width: 90%;
          padding: 0 20px;
      }
  
      nav{
          position: absolute;
          left: -300px;
          top: 0;
          z-index: 999;
          width: 280px;
          height: 100vh;
          background-color: #fefefe;
          transition: 0.2s;
          box-shadow:  2px 0 20px 0 rgba(0, 0, 0, 0.05);
      }
  
      #nav_check:checked ~ nav{
          left: 0;
      }
  
      nav .logo{
          display: block;
          height: 70px;
          display: flex;
          align-items: center;
          margin-left: 30px;
      }
  
      nav ul li a{
          margin-bottom: 5px;
          padding: 10px 15px;
          border-radius: 5px;
      }
  
      nav ul{
          display: block;
          padding: 0 20px;
          margin-top: 30px;
      }
  
      .hamburger{
          display: block;
  
      }
  }



 /*----------------------------*/


.img-background{
    width: 100%;
    height: 100vh;
 }

.container{
    position: absolute;
    background-color: #ffffff;
    padding: 50px;
    width: 50%;
    top: 400px;
    left: 25%;
    box-shadow: rgb(78, 78, 78) 0px 0px 40px;
    border-radius: 20px;
    transition: 0.3s all;
}

.container h1{
    font-weight: bold;
    align-items: center;
    font-size: 40px;
    transition: 0.3s all;
}

.container h2{
    background-color: rgb(39, 124, 194);
    margin-top: 15px;
    padding: 10px;
    transition: 0.3s all;
}

.container a{
    text-decoration: none;
    color: white;
    transition: 0.3s all;
}

.container h2:hover{
    transition: 0.3s all;
    transform: scale(1.03);
    border-bottom-left-radius: 20px;
    border-top-right-radius: 20px;
    cursor: pointer;
}

.container h2:active{
    background-color: #212526;
    transition: 0.3s all;
    transform: scale(0.9);
}


/*---------------FOOTER-------------------*/

footer{
    justify-content: center;
    background-color: rgb(39, 124, 194);
    color: white;
    margin-top: 150px;
    padding: 20px;
    border-top-right-radius: 50px;
    border-top-left-radius: 50px;
    box-shadow: rgba(0, 0, 0, 0.25) 0px 54px 55px, rgba(0, 0, 0, 0.12) 0px -12px 30px, rgba(0, 0, 0, 0.12) 0px 4px 6px, rgba(0, 0, 0, 0.17) 0px 12px 13px, rgba(0, 0, 0, 0.09) 0px -3px 5px;
}

footer h3{
    font-weight: bold;
}

footer a{
    color: rgb(180, 180, 180);
}

footer ul{
    display: flex;
    flex-direction: column;
}

.aplicativo{
    align-items: center;
    margin-left: 350px;
    margin-top: 50px;
}

.social{
    align-items: center;
    margin-left: 650px;
    margin-top: -75px;
}

.contato a{
    align-items: center;
    margin-left: 900px;
    position: relative;
    top: -50px;
    background-color: #fff;
    padding: 10px 50px 10px;
    color: rgb(39, 124, 194);
    font-weight: bold;
    border-radius: 15px;
    transition: 0.3s all;
}

.contato a:hover{
    cursor: pointer;
    transition: 0.3s all;
    font-size: 18px;
}

```
