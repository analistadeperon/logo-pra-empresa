# logo-pra-empresa
<div id="app"></div>
<!DOCTYPE html>
<html>
<head>
    <title>Painel de login Matheus Deperon</title>
    <meta charset="utf-8" />
    <style type="text/css">
    @font-face {
      font-family: 'Sigmar One';
      font-style: normal;
      font-weight: 400;
      src: local('Sigmar One'), local('SigmarOne'), url(http://themes.googleusercontent.com/static/fonts/sigmarone/v4/aRAZJs6CY7SV6eSg6Wx4jxsxEYwM7FgeyaSgU71cLG0.woff) format('woff');
    }
    body{
        margin: 0;
        font: 14px Lucida sans;
        background: #333 url('https://images.madeiramadeira.com.br/product/images/97126750-papel-de-parede-paisagem-praia-coqueiro-viagem-mar-gg601prd0s81f0jcwd8l3-179-1-800x729.jpg') no-repeat;
        -webkit-background-size: cover;
          -moz-background-size: cover;
            -o-background-size: cover;
                background-size: cover;
        color: #fff;
    }
    a, a:active, a:focus{
        text-decoration: none;
        color: #fafafa;
    }
    #logo{
        font: 30px 'Sigmar One';
        text-align: center;
        padding: 0;
        margin: 5em 0 0;
        text-shadow: rgba(0,0,0,1) 0 0 5px;
    }
    #wrap{
        margin: 0 auto;
        max-width: 50%;
        background: rgba(255,255,255,.3);
        border-radius: 5px;
        text-shadow: rgba(0,0,0,.5) 1px 1px 0;
        box-shadow: rgba(0,0,0,.2) 0 0 3px;
        text-align: center;
        padding: 3em 1em;
    }
    hr{
        margin: 1em;
        border: 0;
        border-top: 1px rgba(0,0,0,.2) solid;
        border-bottom: 1px rgba(255,255,255,.2) solid;
    }
    </style>
</head>
<body>
   
    <form action="/login?">
        <p id="logo">Analista Matheus</p>
        <div id="wrap">
            <label for="username">
                Nome:
                <input name="username" type="text" />
            </label>
 
            <label for="password">
                Senha:
                <input name="password" type="password" />
            </label>
 
            <label for="login">
                <input name="login" type="submit" value="Login" />
            </label>
            <hr>
            <label for="sendpassword">
                <a href="/profile?mode=sendpassword">Esqueci minha senha</a>
            </label>
 
            <label for="autologin">
                <input name="autologin" id="autologin" tabindex="4" checked="checked" class="radio" type="checkbox" /> Conexão automática
            </label>
        </div>
    </form>
   
<html>
    <head>
        <meta charset="UTF-8">
        <link rel="stylesheet" href="../../assets/css/exemplo.css">
        <link rel="stylesheet" href="//maxcdn.bootstrapcdn.com/font-awesome/4.3.0/css/font-awesome.min.css">
        <link href="https://fonts.googleapis.com/css?family=Oswald:200" rel="stylesheet">
        <title>Usuários</title>
    </head>
    <body>
        <div class="container-table">
            <div class="content">
                <div id="formulario" class="formulario">
                    <div>
                        <form action="createUser.php" method="post">
                            <div id="title">
                                <h1 id="title-form">Cadastro de novo Usuário</h1>
                                <a class="close"><i class="fa fa-times-circle" aria-hidden="true"></i></a>
                            </div>
                            <div class="container-form">
                                <div class="input_div">
                                    <input class="input_form" type="text" name="name" placeholder="Digite seu Nome"
                                    value="" required>
                                </div>
                                <div class="input_div">
                                    <input class="input_form" type="text" name="email" placeholder="Digite seu Email"
                                    value="" required>
                                </div>
                                <div class="input_div">
                                    <input class="input_form" type="text" name="login" placeholder="Digite seu Login"
                                    value="" required>
                                </div>
                                <div class="input_div">
                                    <input class="input_form" type="password" name="password" placeholder="Digite sua Senha" required>
                                </div>
                                
                                 <div class="input_div">
                                    <input class="input_form" type="text" name="telefone" placeholder="Digite seu Telefone"
                                    value="" required>
                                </div>
                                 <div class="input_div">
                                    <input class="input_form" type="text" name="city" placeholder="Digite sua Cidade"
                                    value="" required>
                                </div>
                                 <div class="input_div">
                                    <input class="input_form" type="text" name="state" placeholder="Digite seu CPF "
                                    value="" required>
                                </div>
                                 <div class="input_div">
                                    Seu atendimento:
                                    <input type="radio" name="masc"
                                    value="Masculino" required> Bom
                                    <input type="radio" name="fem"
                                    value="Feminino" required> Ruim
                                </div>
                            </div>
                             <button class="send-buttons" name="action" value="create">  Cadastrar </button>
                            <button class="send-buttons" name="action" value="create"> enviar </button>
                            
          <p class="link">  
            Já tem conta?
            <a href="#paralogin"> Ir para Login </a>
             <button class="send-buttons" name="action" value="create"> entrar login </button>
             
