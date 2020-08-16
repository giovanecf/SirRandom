<h1 align="center">SirRandom🤖</h1> 
<p align="center">
Sketch para robô seguidor de linha, com a plataforma Arduino. O código foi usado como nas competições **OBR** e **TJR**.
(Não ganhamos, mas talvez você tenha mais ~~sorte~~ que a gente)
</p>

<p align="center">
<img src="https://img.shields.io/static/v1?label=Plataforma&message=Arduino&color=00979D&style=flat&logo=arduino"/>
<img src="https://img.shields.io/static/v1?label=build&message=passing&color=4ac41c&style=flat"/>
</p>

<br/>

<h3 align="center">
 <a href="#status">Status</a> •
 <a href="#features">Features</a> • 
 <a href="#pre-requisitos">Pré-requisitos</a> • 
 <a href="#bibliotecas">Bibliotecas</a> •
 <a href="#hardware">Hardware</a> • 
 <a href="#autor">Autor</a>
</h3>

<h2 id="status">Status</h2>

<p>🥳 O projeto está concluído!! 🥳</br><small>rev:16/08/20</small></p> 
 
<h2 id="features">Features</h2>

Para competição, era necessário implementar algumas funcionalidades. Eis as que conseguimos completar, com algumas de bônus(não necessárias diretamente):

- [x] Diferenciar preto, branco e verde;
- [x] Não se perder em gaps(pedaços de linhas faltantes)
- [x] Método encapsulado para controle dos motores
- [x] Debug dos sensores pela Serial.
 
<h2 id="pre-requisitos">Pré-requisitos</h2>

<p>Quanto a bibliotecas, usamos apenas um: Servo.h, que é inclusa no enviroment 
do <b>Arduino</b>, independente da IDE que escolha.</p>

<p>Quanto a IDE, naturalmente pode-se usar a oficial em que se pode baixar no <a href="https://www.arduino.cc/en/Main/Software">site oficial</a>, ou pode ser usado o VS Code👌. Para o ele, use a extensão oficial: <a href="https://marketplace.visualstudio.com/items?itemName=vsciot-vscode.vscode-arduino">vscode-arduino</a></p>
 
<h2 id="bibliotecas">Bibliotecas</h2>

  <p>Como dito antes, usamos apenas uma:</p>
✅ Server.h

<h2 id="hardware">Hardware</h2>

<h3>Arduino</h3>
✔️ Arduino MEGA
<p>Usamos o MEGA por pela quantidade de portas que seria necessário pela configuração no nosso robô. Verá a seguir.</p>

<h3>Sensores</h3>
✔️ 1x Barra de sensores IR [8portas]</br>
✔️ 2x Sensores de cor(tsc3200) [5portas/cada]

<h3>Atuadores</h3>
✔️ 1x Shield L293D motores CC [6portas]
 
<h2 id="autor">Autor</h2>

 <img style="border-radius: 50%;" src="https://avatars0.githubusercontent.com/u/17338976?s=460&u=b5b325738af4dba6d51cbf2e8e335ca389bc493d&v=4" width="100px;" alt="Geovani Castro"/>
 
 <sub><b>Geovani Castro</b></sub>
</br>

🤔 Qualquer dúvida, 👋🏽 entre em contato!

[![Linkedin Badge](https://img.shields.io/badge/-Geovani_Castro-blue?style=flat-square&logo=Linkedin&logoColor=white&link=https://www.linkedin.com/in/geovani-castro-149733104/)](https://www.linkedin.com/in/geovani-castro-149733104/) 
[![Gmail Badge](https://img.shields.io/badge/-geovani537@gmail.com-c14438?style=flat-square&logo=Gmail&logoColor=white&link=mailto:geovani537@gmail.com)](mailto:geovani537@gmail.com)

