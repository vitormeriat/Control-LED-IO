Control LED IO
========================================================
## Teste de controle e conectividade de um Arduino utilizando Firmata + Node.JS + socket.io + Johnny-five + Visual Studio

Como diria o ditado: "Primeiro acenda um LED, depois domine o mundo!". Sendo assim este é um primeiro exemplo controlando um Arduino via browser tendo como base o socket.io.

## Módulos utilizados

* johnny-five
* express
* socket.io

Assim que clonar o projeto, restaure os módulos acima. Sobre o Johnny-Five, sua documentação pode ser encontrada [aqui](https://github.com/rwaldron/johnny-five/wiki).

Para utilizar o Node.js, seu Arduino tem de estar executando o Firmata. Sendo assim acesse o Arduino IDE, conecte seu Arduino no cabo USB, faça o upload do sketch do Firmata navegando no menu File > Examples > Firmdata > StandandFirmData.

Mais informações e um vídeo com o exemplo, pode ser encontrada [aqui](http://www.vitormeriat.com.br/programando-seu-arduino-com-visual-studio/).

## Executando

Abra o seu projeto no Visual Studio. O mesmo deve ter o "Node.js Tools for Visual Studio" instalado. Para executar o projeto fora do Visual Studio, é só tratar como um projeto Node.js padrão. 

No navegador abra a seguinte URL:

```
localhost:3000
```

Informe o valor em milissegundos no qual o LED deve piscar. Clique em "Configurar Delay" e veja a mágica acontecer!


# Circuito utilizado

![Arduino](https://github.com/vitormeriat/Control-LED-IO/blob/master/Doc/led-resistor.png)


# Demonstração

[![ScreenShot](https://github.com/vitormeriat/Control-LED-IO/blob/master/Doc/capa-youtube.jpeg)](https://www.youtube.com/watch?v=PGMgV3cE1VM)

## License
Licensed under the MIT license.
