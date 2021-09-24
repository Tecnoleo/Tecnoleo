Eae Joia?!✌🏻 
<!doctype html>
<html lang="pt_BR">

<head>
        <meta charset="utf-8">
        <title>aula</title>
        <link href="estilo/style.css" rel="stylesheet">
        <meta name="viewport" content="width = device-width, initial-scale=1.0">
        <link rel="preconnect" href="https://fonts.googleapis.com">
        <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
        <link href="https://fonts.googleapis.com/css2?family=Open+Sans:ital,wght@1,300;1,400&family=Yaldevi:wght@200;400&display=swap" rel="stylesheet">
        <style>
                .Ticket{
                display:flex;
                width: 100vw;
                height: 100vh;
                flex-direction: row;
                align-items: center;
                justify-content: center;


                }
                .ContornoTicket{
                margin-right: 70%;
                background-color: rgb(55, 4, 90);
                border: none;
                border-radius: 4px;
                color: white;
                font-family: 'Yaldevi', sans-serif;    font-size: 15px;
                box-shadow: inset 0 0 1em rgb(138, 90, 250), 0 0 3em rgb(54, 5, 170);


                

                }
                body{
                background-image: linear-gradient(45deg, #1C1C1C,#1C1C1C);
                margin: 0px;
                }

                .InputTicket{
                border-radius: 3px;
                border: none;
                margin-left: 4%;
                

                }
                textarea{
                font-family: 'Open Sans', sans-serif;
                margin-bottom: 4px;;

                }
                .TituloPrincipalTicket
                {
                text-align: center;
                margin-left: 25%;


                }
                .button{
                border: none;
                margin-left: 16%;
                color: white;
                background-color:rgba(138,43,226, 0.8);
                padding-right: 70px;
                padding-left: 70px;
                border-radius: 3px;
                }

                .pergunta{
                        margin-left: 10px;
                
                }



        </style>
<body>
                <div class="Ticket">
                        <form action="#" class="FormularioTicket" >
                                <fieldset class="ContornoTicket">
                                
                                        <div class="box">
                                                <label for="Mensagem" class="TituloPrincipalTicket"><span>Ticket Administração</span></label><br><br>

                                                <label for="flame"class="TituloInputTicket">Seu nome: </label><br>
                
                                                <input type="text"  class="InputTicket" size="27" placeholder="Nome completo"><br>
                
                                                <label for="numerocelular" class="TituloInputTicket" ">Seu Telefone: </label><br>
                
                                                <input type="text"  name="telefone" data-mask="(00) 000000000" data-mask-selectonfocus="true" maxlength="13" class="InputTicket" size="27" placeholder="Whatsapp">
                
                                                <label for="SeuEmail" class="TituloInputTicket">Seu E-mail: </label><br>
                
                                                <input type="email" placeholder="@exemplo.com"class="InputTicket" size="27"><br>
                
                                                <label for="Pergunta" class="Pergunta">Deseja receber  nossas novidades?</label><br>
                
                                                <input type="radio">
                
                                                <label for="SIm">Sim</label>
                
                                                <input type="radio">
                
                                                <label for="NAo">Nao</label><br>
                                                
                                                <label for="Sua mensagem">Sua mensagem:</label><br>
                
                                                <textarea name="Mensagem" id="CaixaMensagem" cols="30" rows="10" class="InputForm"></textarea><br>
                
                                                <input type="submit" class="button">
                                        <br>



                                        </div>
                                

                                </fieldset>
                </form>
        </div>
</body>
</html>
