<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Surpresa para Você!</title>
    <style>
        body {
            background-color: #1a1a1a; /* Fundo mais suave */
            font-family: 'Arial', sans-serif;
            color: #ecf0f1; /* Cor mais suave para o texto */
            margin: 0;
            padding: 20px;
            box-sizing: border-box;
            overflow-y: auto;
        }

        h1 {
            font-size: 5vw; /* Aumentei um pouco o título */
            color: #f39c12;
            text-align: center;
            margin: 20px 0;
            font-family: 'Arial', sans-serif;
            letter-spacing: 2px; /* Espaçamento entre letras para destacar mais */
        }

        .message {
            font-size: 2.5vw; /* Diminui um pouco o tamanho */
            margin: 20px 0;
            text-align: center;
            font-family: 'Verdana', sans-serif;
            color: #f0f0f0;
        }

        .heart {
            font-size: 8vw; /* Tamanho grande para o coração */
            color: #e74c3c;
            text-align: center;
            animation: pulse 1.5s infinite;
        }

        @keyframes pulse {
            0% { transform: scale(1); opacity: 0.8; }
            50% { transform: scale(1.2); opacity: 1; }
            100% { transform: scale(1); opacity: 0.8; }
        }

        .declaration {
            font-size: 2vw; /* Texto com fonte menor para deixar a leitura confortável */
            color: #ecf0f1;
            text-align: center;
            margin: 20px 0;
            font-family: 'Georgia', serif; /* Mudança de fonte para um toque mais elegante */
            line-height: 1.6;
        }

        .image-gallery {
            display: flex;
            justify-content: center;
            flex-wrap: wrap;
            margin: 20px 0;
        }

        .image-gallery img {
            width: 180px; /* Tamanho das imagens reduzido */
            margin: 10px;
            border-radius: 8px;
            transition: transform 0.3s;
        }

        .image-gallery img:hover {
            transform: scale(1.1);
        }

        audio {
            display: block;
            margin: 20px auto;
            width: 90%;
            max-width: 600px;
        }

        button {
            display: block;
            margin: 20px auto;
            padding: 12px 24px;
            font-size: 1.5rem;
            color: #fff;
            background-color: #e74c3c;
            border: none;
            border-radius: 8px;
            cursor: pointer;
            transition: background-color 0.3s;
        }

        button:hover {
            background-color: #c0392b;
        }
    </style>
</head>
<body>
    <h1>Surpresa, meu amor!</h1>
    <div class="message">
        <p>Eu te amo muito, você é a razão do meu sorriso todos os dias.</p>
        <p>Espero que tenha um dia maravilhoso e saiba que sempre estou pensando em você.</p>
    </div>
    <div class="heart">❤️</div>
    <div class="declaration">
        <p>Conhecer você foi a melhor coisa que me aconteceu esse ano</p>
        <p>Você é a razão da minha felicidade, meu pensamento pela manhã, meu sonho durante a noite.</p>
    </div>
    

    <!-- Player de áudio -->
    <audio id="background-music" loop>
        <source src="https://www.dropbox.com/scl/fi/1acqxuzzc7bebfh0w365b/K-a-m-a-i-t-a-c-h-i-Julieta-Prod.MarcusMaia.mp3?rlkey=pshadq4suvr57xnbuk6h2mswh&st=fg46608c&dl=1" type="audio/mp3">
        Seu navegador não suporta o elemento de áudio.
    </audio>

    <!-- Botão para tocar a música -->
    <button id="play-button">Tocar Música</button>

    <script>
        const audio = document.getElementById('background-music');
        const playButton = document.getElementById('play-button');

        // Reproduz a música ao clicar no botão
        playButton.addEventListener('click', function () {
            audio.play().then(() => {
                playButton.style.display = 'none'; // Oculta o botão após iniciar a música
            }).catch((error) => {
                console.error('Erro ao tentar reproduzir a música:', error);
            });
        });

        // Tenta remover o "mute" e reproduzir a música quando a página é carregada
        window.onload = function () {
            audio.play().catch((error) => {
                console.log('Autoplay bloqueado pelo navegador. Interação necessária:', error);
            });
        };
    </script>

    <div class="declaration">
        <p>Meu amor, quero que saiba que eu te amo e que estou aqui com você e por você para o que precisar. Eu sei que eu sou chato e me aturar não é uma coisa fácil, mas tenho muitas coisas para melhorar em meu jeito de ser. Sei brincar, mas também sei levar a sério. Você faz eu querer ser melhor a cada dia. Eu te disse que iria colorir sua vida preto e branco, mas na verdade foi você que acabou colorindo a minha vida de uma forma que eu nem sou capaz de descrever. E eu também te dedico essa música, pois Kamaitachi queria encontrar Jasmin além de seus sonhos, mas eu te encontrei nessa realidade. Saiba que eu te AMO!</p>
        <p>Eu te amo ❤️
            Eu te amo ❤️
            Eu te amo ❤️
            Eu te amo ❤️
            Eu te amo ❤️
            Eu te amo ❤️
            Eu te amo ❤️
            Eu te amo ❤️
            Eu te amo ❤️
            Eu te amo ❤️
            Eu te amo ❤️
            Eu te amo ❤️
            Eu te amo ❤️
            Eu te amo ❤️
            Eu te amo ❤️
            Eu te amo ❤️
            Eu te amo ❤️
            Eu te amo ❤️
            Eu te amo ❤️
            Eu te amo ❤️
            Eu te amo ❤️
            Eu te amo ❤️
            Eu te amo ❤️
             Eu te amo ❤️
              Eu te amo ❤️
               Eu te amo ❤️
                Eu te amo ❤️
                 Eu te amo ❤️
                  Eu te amo ❤️
                   Eu te amo ❤️
                    Eu te amo ❤️
                     Eu te amo ❤️
                      Eu te amo ❤️
                       Eu te amo ❤️
                        Eu te amo ❤️
                         Eu te amo ❤️
                          Eu te amo ❤️
                           Eu te amo ❤️
                            Eu te amo ❤️
                             Eu te amo ❤️
                              Eu te amo ❤️
                               Eu te amo ❤️
                                Eu te amo ❤️
                                Eu te amo ❤️
                               Eu te amo ❤️
                              Eu te amo ❤️
                             Eu te amo ❤️
                            Eu te amo ❤️
                           Eu te amo ❤️
                          Eu te amo ❤️
                         Eu te amo ❤️
                        Eu te amo ❤️
                       Eu te amo ❤️
                      Eu te amo ❤️
                     Eu te amo ❤️
                    Eu te amo ❤️
                   Eu te amo ❤️
                  Eu te amo ❤️
                 Eu te amo ❤️
                Eu te amo ❤️
               Eu te amo ❤️
              Eu te amo ❤️
             Eu te amo ❤️
            Eu te amo ❤️
            Eu te amo ❤️
             Eu te amo ❤️
              Eu te amo ❤️
               Eu te amo ❤️
                Eu te amo ❤️
                 Eu te amo ❤️
                  Eu te amo ❤️
                   Eu te amo ❤️
                    Eu te amo ❤️
                     Eu te amo ❤️
                      Eu te amo ❤️
                       Eu te amo ❤️
                        Eu te amo ❤️
                         Eu te amo ❤️
                          Eu te amo ❤️
                           Eu te amo ❤️
                            Eu te amo ❤️
                             Eu te amo ❤️
                              Eu te amo ❤️
                               Eu te amo ❤️
                                Eu te amo ❤️
                                Eu te amo ❤️
                               Eu te amo ❤️
                              Eu te amo ❤️
                             Eu te amo ❤️
                            Eu te amo ❤️
                           Eu te amo ❤️
                          Eu te amo ❤️
                         Eu te amo ❤️
                        Eu te amo ❤️
                       Eu te amo ❤️
                      Eu te amo ❤️
                     Eu te amo ❤️
                    Eu te amo ❤️
                   Eu te amo ❤️
                  Eu te amo ❤️
                 Eu te amo ❤️
                Eu te amo ❤️
               Eu te amo ❤️
              Eu te amo ❤️
             Eu te amo ❤️
            Eu te amo ❤️
            Eu te amo ❤️
            Eu te amo ❤ ️
            Eu te amo ❤  ️
            Eu te amo ❤   ️
            Eu te amo ❤    ️
            Eu te amo  ❤    ️
            Eu te amo   ❤    ️
            Eu te amo    ❤    ️
            Eu te amo     ❤    ️
            Eu te amo      ❤    ️
            Eu te amo       ❤    ️
            Eu te amo        ❤    ️
            Eu te amo         ❤    ️
            Eu te am o         ❤    ️
            Eu te am  o         ❤    ️
            Eu te am   o         ❤    ️
            Eu te am    o         ❤    ️
            Eu te a m    o         ❤    ️
            Eu te a  m    o         ❤    ️
            Eu te a   m    o         ❤    ️
            Eu te a    m    o         ❤    ️
            Eu te  a    m    o         ❤    ️
            Eu te   a    m    o         ❤    ️
            Eu te    a    m    o         ❤    ️
            Eu te     a    m    o         ❤    ️
            Eu te      a    m    o         ❤    ️
            Eu te       a    m    o         ❤    ️
            Eu te        a    m    o         ❤    ️
            Eu te         a    m    o         ❤    ️
            Eu t e         a    m    o         ❤    ️
            Eu t  e         a    m    o         ❤    ️
            Eu t   e         a    m    o         ❤    ️
            Eu t    e         a    m    o         ❤    ️
            Eu  t    e         a    m    o         ❤    ️
            Eu   t    e         a    m    o         ❤    ️
            Eu    t    e         a    m    o         ❤    ️
            Eu     t    e         a    m    o         ❤    ️
            Eu      t    e         a    m    o         ❤    ️
            Eu       t    e         a    m    o         ❤    ️
            Eu        t    e         a    m    o         ❤    ️
            Eu         t    e         a    m    o         ❤    ️
            E u         t    e         a    m    o         ❤    ️
            E  u         t    e         a    m    o         ❤    ️
            E   u         t    e         a    m    o         ❤    ️
            E    u         t    e         a    m    o         ❤    ️
             E    u         t    e         a    m    o         ❤    ️
              E    u         t    e         a    m    o         ❤    ️
               E    u         t    e         a    m    o         ❤    ️
                E    u         t    e         a    m    o         ❤    ️
                 E    u         t    e         a    m    o         ❤   ️
                  E    u         t    e         a    m    o         ❤  ️
                   E    u         t    e         a    m    o         ❤ ️
                    E    u         t    e         a    m    o         ❤️
                     E    u         t    e         a    m    o        ❤️
                      E    u         t    e         a    m    o       ❤️
                       E    u         t    e         a    m    o      ❤️
                        E    u         t    e         a    m    o     ❤️
                         E    u         t    e         a    m    o    ❤️
                          E    u         t    e         a    m    o   ❤️
                           E    u         t    e         a    m    o  ❤️
                            E    u         t    e         a    m    o ❤️
                             E    u         t    e         a    m    o❤️
                              E    u         t    e         a    m   o❤️
                               E    u         t    e         a    m  o❤️
                                E    u         t    e         a    m o❤️
                                 E    u         t    e         a    mo❤️
                                  E    u         t    e         a   mo❤️
                                   E    u         t    e         a  mo❤️
                                    E    u         t    e         a mo❤️
                                     E    u         t    e         amo❤️
                                      E    u         t    e        amo❤️
                                       E    u         t    e       amo❤️
                                        E    u         t    e      amo❤️
                                         E    u         t    e     amo❤️
                                          E    u         t    e    amo❤️
                                           E    u         t    e   amo❤️
                                            E    u         t    e  amo❤️
                                             E    u         t    e amo❤️
                                              E    u         t    eamo❤️
                                               E    u         t   eamo❤️
                                                E    u         t  eamo❤️
                                                 E    u         t eamo❤️
                                                  E    u         teamo❤️
                                                   E    u        teamo❤️
                                                    E    u       teamo❤️
                                                     E    u      teamo❤️
                                                      E    u     teamo❤️
                                                       E    u    teamo❤️
                                                        E    u   teamo❤️
                                                         E    u  teamo❤️
                                                          E    u teamo❤️
                                                           E    uteamo❤️
                                                            E   uteamo❤️
                                                            Eu te amo ❤️
                                                            Eu te amo ❤️
                                                            Eu te amo ❤️
                                                            Eu te amo ❤️
                                                            Eu te amo ❤️
                                                            Eu te amo ❤️
                                                            Eu te amo ❤️
                                                            Eu te amo ❤️
                                                            Eu te amo ❤️
                                                           Eu te   amo ❤️
                                                          Eu te     amo ❤️
                                                         Eu te       amo ❤️
                                                        Eu te         amo ❤️
                                                       Eu te           amo ❤️
                                                      Eu te             amo ❤️
                                                     Eu te               amo ❤️
                                                    Eu te                 amo ❤️
                                                   Eu te                   amo ❤️
                                                  Eu te                     amo ❤️
                                                  Eu te                     amo ❤️
                                                  Eu te                     amo ❤️
                                                  Eu te                     amo ❤️
                                                  Eu te                     amo ❤️
                                                  Eu te                     amo ❤️
                                                  Eu te                     amo ❤️
                                                  Eu te                     amo ❤️
                                                  Eu te                     amo ❤️
                                                  Eu te                     amo ❤️
                                                  Eu te                     amo ❤️
                                                  Eu te                     amo ❤️
                                                  Eu te                     amo ❤️
                                                  Eu te                     amo ❤️
                                                  Eu te                     amo ❤️
                                                  Eu te                     amo ❤️
                                                  Eu te                     amo ❤️
                                                  Eu te                     amo ❤️
                                                  Eu te                     amo ❤️
                                                  Eu te                     amo ❤️
                                                  Eu te                     amo ❤️
                                                  Eu te                     amo ❤️
                                                  Eu te                     amo ❤️
                                                  Eu te                     amo ❤️
                                                  Eu te                     amo ❤️
                                                   Eu te                   amo ❤️
                                                    Eu te                 amo ❤️
                                                     Eu te               amo ❤️
                                                      Eu te             amo ❤️
                                                       Eu te           amo ❤️
                                                        Eu te         amo ❤️
                                                         Eu te       amo ❤️
                                                          Eu te     amo ❤️
                                                           Eu te   amo ❤️
                                                            Eu te amo ❤️
                                                            Eu te amo ❤️
                                                            Eu te amo ❤️
                                                            Eu te amo ❤️
                                                            Eu te amo ❤️
                                                           Eu te amo ❤️
                                                          Eu te amo ❤️
                                                         Eu te amo ❤️
                                                        Eu te amo ❤️
                                                       Eu te amo ❤️
                                                      Eu te amo ❤️
                                                     Eu te amo ❤️
                                                    Eu te amo ❤️
                                                   Eu te amo ❤️
                                                  Eu te amo ❤️
                                                 Eu te amo ❤️
                                                Eu te amo ❤️
                                               Eu te amo ❤️
                                              Eu te amo ❤️
                                             Eu te amo ❤️
                                            Eu te amo ❤️
                                           Eu te amo ❤️
                                          Eu te amo ❤️
                                         Eu te amo ❤️
                                        Eu te amo ❤️
                                       Eu te amo ❤️
                                      Eu te amo ❤️
                                     Eu te amo ❤️
                                    Eu te amo ❤️
                                   Eu te amo ❤️
                                  Eu te amo ❤️
                                 Eu te amo ❤️
                                Eu te amo ❤️
                               Eu te amo ❤️
                              Eu te amo ❤️
                             Eu te amo ❤️
                            Eu te amo ❤️
                           Eu te amo ❤️
                          Eu te amo ❤️
                         Eu te amo ❤️
                        Eu te amo ❤️
                       Eu te amo ❤️
                      Eu te amo ❤️
                     Eu te amo ❤️
                    Eu te amo ❤️
                   Eu te amo ❤️
                  Eu te amo ❤️
                 Eu te amo ❤️
                Eu te amo ❤️
               Eu te amo ❤️
              Eu te amo ❤️
             Eu te amo ❤️
            Eu te amo ❤️
             Eu te amo ❤️
              Eu te amo ❤️
               Eu te amo ❤️
                Eu te amo ❤️
                 Eu te amo ❤️
                E u te amo ❤️
               E  u te amo ❤️
              E   u te amo ❤️
             E    u te amo ❤️
            E     u te amo ❤️
            E    u  te amo ❤️
            E   u   te amo ❤️
            E  u    te amo ❤️
            E u     te amo ❤️
            Eu      te amo ❤️
            Eu      te amo ❤️
            Eu      te amo ❤️
            Eu      te amo ❤️
            Eu      te amo ❤️
            Eu      te amo ❤️
            Eu     t e amo ❤️
            Eu    t  e amo ❤️
            Eu   t   e amo ❤️
            Eu  t    e amo ❤️
            Eu t     e amo ❤️
            Eu t    e  amo ❤️
            Eu t   e   amo ❤️
            Eu t  e    amo ❤️
            Eu t e     amo ❤️
            Eu te      amo ❤️
            Eu te      amo ❤️
            Eu te      amo ❤️
            Eu te      amo ❤️
            Eu te      amo ❤️
            Eu te      amo ❤️
            Eu te     a mo ❤️
            Eu te    a  mo ❤️
            Eu te   a   mo ❤️
            Eu te  a    mo ❤️
            Eu te a     mo ❤️
            Eu te a    m o ❤️
            Eu te a   m  o ❤️
            Eu te a  m   o ❤️
            Eu te a m    o ❤️
            Eu te am     o ❤️
            Eu te am    o  ❤️
            Eu te am   o   ❤️
            Eu te am  o    ❤️
            Eu te am o     ❤️
            Eu te amo      ❤️
            Eu te amo      ❤️
            Eu te amo      ❤️
            Eu te amo      ❤️
            Eu te amo      ❤️
            Eu te amo      ❤️
            Eu te amo     ❤ ️
            Eu te amo    ❤  ️
            Eu te amo   ❤   ️
            Eu te amo  ❤    ️
            Eu te amo ❤     ️
            Eu te amo ❤    ️ 
            Eu te amo ❤   ️  
            Eu te amo ❤  ️   
            Eu te amo ❤ ️    
            Eu te amo ❤️     
            Eu te amo ❤️
            ️Eu te amo ❤
            ❤️Eu te amo 
             ❤️Eu te amo
            o ❤️Eu te am
            mo ❤️Eu te a
            amo ❤️Eu te 
             amo ❤️Eu te
            e amo ❤️Eu t
            te amo ❤️Eu 
             te amo ❤️Eu
            u te amo ❤️E
            Eu te amo ❤️
            ️Eu te amo ❤
            ❤️Eu te amo 
             ❤️Eu te amo
            o ❤️Eu te am
            mo ❤️Eu te a
            amo ❤️Eu te 
             amo ❤️Eu te
            e amo ❤️Eu t
            te amo ❤️Eu 
             te amo ❤️Eu
            u te amo ❤️E
            Eu te amo ❤️
            ️Eu te amo ❤
            ❤️Eu te amo 
             ❤️Eu te amo
            o ❤️Eu te am
            mo ❤️Eu te a
            amo ❤️Eu te 
             amo ❤️Eu te
            e amo ❤️Eu t
            te amo ❤️Eu 
             te amo ❤️Eu
            u te amo ❤️E
            Eu te amo ❤️
            Eu te amo ❤️
             Eu te amo ❤️
              Eu te amo ❤️
               Eu te amo ❤️
                Eu te amo ❤️
                 Eu te amo ❤️
                  Eu te amo ❤️
                   Eu te amo ❤️
                    Eu te amo ❤️
                     Eu te amo ❤️
                      Eu te amo ❤️
                     Eu te   amo ❤️
                    Eu te     amo ❤️
                   Eu te       amo ❤️
                  Eu te         amo ❤️
                 Eu te           amo ❤️
                Eu te             amo ❤️
               Eu te               amo ❤️
              Eu te                 amo ❤️
             Eu te                   amo ❤️
            Eu te                     amo ❤️
             Eu te                   amo ❤️
              Eu te                 amo ❤️
               Eu te               amo ❤️
                Eu te             amo ❤️
                 Eu te           amo ❤️
                  Eu te         amo ❤️
                   Eu te       amo ❤️
                    Eu te     amo ❤️
                     Eu te   amo ❤️
                      Eu te amo ❤️
                       Eu teamo ❤️
                        Eu tamo ❤️
                         Eu amo ❤️
                          Euamo ❤️
                           Eamo ❤️
                            amo ❤️
                           amo ❤️ 
                          amo ❤️e 
                         amo ❤️te 
                        amo ❤️ te 
                       amo ❤️u te 
                      amo ❤️Eu te 
                     amo ❤️  Eu te 
                    amo ❤️    Eu te 
                   amo ❤️      Eu te 
                  amo ❤️        Eu te 
                 amo ❤️          Eu te 
                amo ❤️            Eu te 
               amo ❤️              Eu te 
              amo ❤️                Eu te 
             amo ❤️                  Eu te 
            amo ❤️                    Eu te 
             amo ❤️                  Eu te 
              amo ❤️                Eu te 
               amo ❤️              Eu te 
                amo ❤️            Eu te 
                 amo ❤️          Eu te 
                  amo ❤️        Eu te 
                   amo ❤️      Eu te 
                    amo ❤️    Eu te 
                     amo ❤️  Eu te 
                      amo ❤️Eu te 
                       amo ❤Eu te 
                        amo Eu te 
                         amoEu te 
                          amEu te 
                           aEu te 
                            Eu te 
                           Eu te ️
                          Eu te ❤️
                         Eu te  ❤️
                        Eu te o ❤️
                       Eu te mo ❤️
                      Eu te amo ❤️
                     Eu te   amo ❤️
                    Eu te     amo ❤️
                   Eu te       amo ❤️
                  Eu te         amo ❤️
                 Eu te           amo ❤️
                Eu te             amo ❤️
               Eu te               amo ❤️
              Eu te                 amo ❤️
             Eu te                   amo ❤️
            Eu te                     amo ❤️
             Eu te                   amo ❤️
              Eu te                 amo ❤️
               Eu te               amo ❤️
                Eu te             amo ❤️
                 Eu te           amo ❤️
                  Eu te         amo ❤️
                   Eu te       amo ❤️
                    Eu te     amo ❤️
                     Eu te   amo ❤️
                      Eu te amo ❤️
                       Eu teamo ❤️
                        Eu tamo ❤️
                         Eu amo ❤️
                          Euamo ❤️
                           Eamo ❤️
                            amo ❤️
                           amo ❤️ 
                          amo ❤️e 
                         amo ❤️te 
                        amo ❤️ te 
                       amo ❤️u te 
                      amo ❤️Eu te 
                     amo ❤️  Eu te 
                    amo ❤️    Eu te 
                   amo ❤️      Eu te 
                  amo ❤️        Eu te 
                 amo ❤️          Eu te 
                amo ❤️            Eu te 
               amo ❤️              Eu te 
              amo ❤️                Eu te 
             amo ❤️                  Eu te 
            amo ❤️                    Eu te 
             amo ❤️                  Eu te 
              amo ❤️                Eu te 
               amo ❤️              Eu te 
                amo ❤️            Eu te 
                 amo ❤️          Eu te 
                  amo ❤️        Eu te 
                   amo ❤️      Eu te 
                    amo ❤️    Eu te 
                     amo ❤️  Eu te 
                      amo ❤️Eu te 
                       amo ❤Eu te 
                        amo Eu te 
                         amoEu te 
                          amEu te 
                           aEu te 
                            Eu te 
                           Eu te ️
                          Eu te ❤️
                         Eu te  ❤️
                        Eu te o ❤️
                       Eu te mo ❤️
                      Eu te amo ❤️
                      Eu te amo ❤️
                      Eu te amo ❤️
                      Eu te amo ❤️
                      Eu te amo ❤️
                      Eu te amo ❤️
                      Eu te amo ❤️
                      Eu te amo ❤️
                      Eu te amo ❤️
                      Eu te amo ❤️
                      Eu te amo ❤️
                      Eu te amo ❤️
                     Eu te amo ❤️
                    Eu te amo ❤️
                   Eu te amo ❤️
                  Eu te amo ❤️
                 Eu te amo ❤️
                Eu te amo ❤️
               Eu te amo ❤️
              Eu te amo ❤️
             Eu te amo ❤️
            Eu te amo ❤️
            Eu te amo ❤️
            Eu te amo ❤️
            Eu te amo ❤️
            Eu te amo ❤️
            Eu te amo ❤️
            Eu te amo ❤️
            Eu te amo ❤️
            Eu te amo ❤️
            Eu te amo ❤️
            Eu te amo ❤️
            Eu te amo ❤️
            Eu te amo ❤️
            Eu te amo ❤️
            Eu te amo ❤️
            Eu te amo ❤️
            Eu te amo ❤️
            Eu te amo ❤️
            Eu te amo ❤️
            Eu te amo ❤️
            Eu te amo ❤️
            Eu te amo ❤️
            Eu te amo ❤️
            Eu te amo ❤️
            Eu te amo ❤️
            Eu te amo ❤️
            Eu te amo ❤️
            Eu te amo ❤️
            Eu te amo ❤️
            Eu te amo ❤️
            Eu te amo ❤️
            Eu te amo ❤️
            Eu te amo ❤️
            Eu te amo ❤️
            Eu te amo ❤️
            </p>
    </div>
</body>
</html>
