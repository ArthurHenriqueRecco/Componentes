<!DOCTYPE html>
<html lang="pt-BR">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Guia Completo - Circuitos do Tinkercad</title>

<style>
*{
    margin:0;
    padding:0;
    box-sizing:border-box;
    font-family:Arial, Helvetica, sans-serif;
}

body{
    background:#f5f7fa;
    display:flex;
}

.sidebar{
    width:280px;
    height:100vh;
    overflow:auto;
    position:fixed;
    background:#1e293b;
    color:white;
    padding:20px;
}

.sidebar h2{
    margin-bottom:20px;
    text-align:center;
}

.sidebar a{
    display:block;
    color:white;
    text-decoration:none;
    padding:10px;
    border-radius:5px;
    margin-bottom:5px;
}

.sidebar a:hover{
    background:#334155;
}

.content{
    margin-left:300px;
    padding:30px;
    max-width:1200px;
}

header{
    background:linear-gradient(135deg,#2563eb,#0ea5e9);
    color:white;
    padding:40px;
    border-radius:15px;
    margin-bottom:30px;
}

.card{
    background:white;
    padding:25px;
    margin-bottom:20px;
    border-radius:15px;
    box-shadow:0 3px 10px rgba(0,0,0,0.1);
}

.card h2{
    color:#2563eb;
    margin-bottom:15px;
}

.component{
    border-left:5px solid #2563eb;
    padding-left:15px;
    margin:20px 0;
}

.component h3{
    color:#0f172a;
    margin-bottom:10px;
}

.component p{
    margin-bottom:8px;
    line-height:1.6;
}

footer{
    text-align:center;
    padding:20px;
    color:#64748b;
}

ul{
    padding-left:20px;
}

li{
    margin-bottom:5px;
}
</style>
</head>
<body>

<div class="sidebar">
    <h2>Tinkercad Circuitos</h2>

    <a href="#introducao">Introdução</a>
    <a href="#circuitos">O que é a Aba Circuitos</a>
    <a href="#basicos">Componentes Básicos</a>
    <a href="#resistores">Resistores</a>
    <a href="#capacitores">Capacitores</a>
    <a href="#diodos">Diodos e LEDs</a>
    <a href="#transistores">Transistores</a>
    <a href="#sensores">Sensores</a>
    <a href="#motores">Motores</a>
    <a href="#displays">Displays</a>
    <a href="#botoes">Botões e Chaves</a>
    <a href="#arduino">Arduino</a>
    <a href="#instrumentos">Instrumentos</a>
    <a href="#projetos">Projetos</a>
</div>

<div class="content">

<header>
    <h1>Guia Completo da Aba Circuitos do Tinkercad</h1>
    <p>
        Aprenda para que serve cada componente eletrônico disponível
        na plataforma Tinkercad Circuitos.
    </p>
</header>

<section id="introducao" class="card">
    <h2>Introdução</h2>

    <p>
        O Tinkercad é uma plataforma online gratuita que permite criar
        circuitos eletrônicos e simular seu funcionamento em tempo real.
    </p>

    <p>
        A aba Circuitos é muito utilizada para aprender eletrônica,
        programação Arduino e automação sem a necessidade de comprar
        componentes físicos.
    </p>
</section>

<section id="circuitos" class="card">
    <h2>O que é a Aba Circuitos?</h2>

    <p>
        A aba Circuitos é um laboratório virtual onde você pode:
    </p>

    <ul>
        <li>Montar circuitos eletrônicos</li>
        <li>Programar Arduino</li>
        <li>Testar sensores</li>
        <li>Criar projetos de automação</li>
        <li>Simular motores e LEDs</li>
        <li>Utilizar instrumentos de medição</li>
    </ul>
</section>

<section id="basicos" class="card">
    <h2>Componentes Básicos</h2>

    <div class="component">
        <h3>Protoboard (Breadboard)</h3>
        <p><strong>O que é:</strong> placa de testes sem solda.</p>
        <p><strong>Para que serve:</strong> montar circuitos temporários rapidamente.</p>
    </div>

    <div class="component">
        <h3>Fios</h3>
        <p><strong>O que é:</strong> condutores elétricos.</p>
        <p><strong>Para que serve:</strong> conectar componentes.</p>
    </div>

    <div class="component">
        <h3>Bateria</h3>
        <p><strong>O que é:</strong> fonte de energia.</p>
        <p><strong>Para que serve:</strong> alimentar circuitos eletrônicos.</p>
    </div>

    <div class="component">
        <h3>Fonte de Alimentação</h3>
        <p><strong>O que é:</strong> gerador ajustável de tensão.</p>
        <p><strong>Para que serve:</strong> fornecer energia controlada ao circuito.</p>
    </div>
</section>

<section id="resistores" class="card">
    <h2>Resistores</h2>

    <div class="component">
        <h3>Resistor</h3>
        <p><strong>O que é:</strong> componente que limita corrente elétrica.</p>
        <p><strong>Para que serve:</strong> proteger LEDs e controlar corrente.</p>
    </div>

    <div class="component">
        <h3>Potenciômetro</h3>
        <p><strong>O que é:</strong> resistor variável.</p>
        <p><strong>Para que serve:</strong> ajuste de brilho, volume e tensão.</p>
    </div>
</section>

<section id="capacitores" class="card">
    <h2>Capacitores</h2>

    <div class="component">
        <h3>Capacitor</h3>
        <p><strong>O que é:</strong> dispositivo que armazena energia elétrica.</p>
        <p><strong>Para que serve:</strong> filtragem e estabilização de tensão.</p>
    </div>
</section>

<section id="diodos" class="card">
    <h2>Diodos e LEDs</h2>

    <div class="component">
        <h3>Diodo</h3>
        <p><strong>O que é:</strong> permite corrente em apenas um sentido.</p>
        <p><strong>Para que serve:</strong> proteção e retificação.</p>
    </div>

    <div class="component">
        <h3>LED</h3>
        <p><strong>O que é:</strong> diodo emissor de luz.</p>
        <p><strong>Para que serve:</strong> sinalização visual.</p>
    </div>

    <div class="component">
        <h3>LED RGB</h3>
        <p><strong>O que é:</strong> LED com três cores internas.</p>
        <p><strong>Para que serve:</strong> produzir milhões de combinações de cores.</p>
    </div>
</section>

<section id="transistores" class="card">
    <h2>Transistores</h2>

    <div class="component">
        <h3>Transistor NPN</h3>
        <p><strong>O que é:</strong> chave eletrônica.</p>
        <p><strong>Para que serve:</strong> acionar motores, relés e LEDs.</p>
    </div>

    <div class="component">
        <h3>Transistor PNP</h3>
        <p><strong>O que é:</strong> transistor complementar ao NPN.</p>
        <p><strong>Para que serve:</strong> controle de cargas eletrônicas.</p>
    </div>
</section>

<section id="sensores" class="card">
    <h2>Sensores</h2>

    <div class="component">
        <h3>Sensor de Temperatura TMP36</h3>
        <p>Utilizado para medir temperatura ambiente.</p>
    </div>

    <div class="component">
        <h3>LDR</h3>
        <p>Detecta intensidade luminosa.</p>
    </div>

    <div class="component">
        <h3>Sensor Ultrassônico HC-SR04</h3>
        <p>Mede distância utilizando ondas sonoras.</p>
    </div>

    <div class="component">
        <h3>Sensor PIR</h3>
        <p>Detecta movimento de pessoas.</p>
    </div>

    <div class="component">
        <h3>Sensor de Inclinação</h3>
        <p>Detecta mudanças de posição.</p>
    </div>
</section>

<section id="motores" class="card">
    <h2>Motores</h2>

    <div class="component">
        <h3>Motor DC</h3>
        <p>Produz rotação contínua.</p>
    </div>

    <div class="component">
        <h3>Servo Motor</h3>
        <p>Controla posição angular com precisão.</p>
    </div>

    <div class="component">
        <h3>Motor de Passo</h3>
        <p>Realiza movimentos extremamente precisos.</p>
    </div>
</section>

<section id="displays" class="card">
    <h2>Displays</h2>

    <div class="component">
        <h3>Display LCD 16x2</h3>
        <p>Exibe textos e valores numéricos.</p>
    </div>

    <div class="component">
        <h3>Display de 7 Segmentos</h3>
        <p>Exibe números de 0 a 9.</p>
    </div>
</section>

<section id="botoes" class="card">
    <h2>Botões e Chaves</h2>

    <div class="component">
        <h3>Push Button</h3>
        <p>Botão momentâneo utilizado para entradas digitais.</p>
    </div>

    <div class="component">
        <h3>Chave SPST</h3>
        <p>Liga e desliga circuitos.</p>
    </div>

    <div class="component">
        <h3>Chave DIP</h3>
        <p>Permite configurações manuais em circuitos.</p>
    </div>
</section>

<section id="arduino" class="card">
    <h2>Arduino</h2>

    <div class="component">
        <h3>Arduino Uno R3</h3>
        <p>
            Microcontrolador mais utilizado do Tinkercad.
        </p>

        <ul>
            <li>14 portas digitais</li>
            <li>6 entradas analógicas</li>
            <li>PWM</li>
            <li>USB</li>
        </ul>
    </div>

    <div class="component">
        <h3>Arduino Nano</h3>
        <p>Versão compacta do Arduino Uno.</p>
    </div>
</section>

<section id="instrumentos" class="card">
    <h2>Instrumentos de Medição</h2>

    <div class="component">
        <h3>Multímetro</h3>
        <p>Mede tensão, corrente e resistência.</p>
    </div>

    <div class="component">
        <h3>Osciloscópio</h3>
        <p>Permite visualizar sinais elétricos em gráficos.</p>
    </div>
</section>

<section id="projetos" class="card">
    <h2>Projetos Possíveis</h2>

    <ul>
        <li>Semáforo automático</li>
        <li>Estação meteorológica</li>
        <li>Casa inteligente</li>
        <li>Sistema de irrigação</li>
        <li>Alarme residencial</li>
        <li>Controle de motores</li>
        <li>Robótica educacional</li>
        <li>Automação industrial básica</li>
    </ul>
</section>

<footer>
    <p>
        Guia Completo da Aba Circuitos do Tinkercad © 2026
    </p>
</footer>

</div>

</body>
</html>
