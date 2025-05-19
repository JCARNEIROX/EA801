<h1 style="color:white; font-size:30px; text-align:center;">Sistema de Segurança para Cofres</h1>

<div align="center">
    <img src="https://github.com/JCARNEIROX/EA801/blob/main/Projeto2/imagens/cofre.jpg">
</div></div>

<p style="color:white; font-size:20px; text-align:left;">
    Neste projeto foi desenvolvido o protótipo de um cofre eletrônico por meio da placa BitDogLab. Além dos recursos existente na placa, foram usados também os seguintes periféricos:
    <ul style="color:white; font-size:20px";>
    <li>Teclado Matricial 4x3</li>
    <li>Servo Motor</li>
    <li>Chave fim de curso</li>
    <li>Acelerômetro MPU-6050</li>
    </ul>
</p>
<p style="color:white; font-size:20px; text-align:left;">
    Portanto esse projeto visou a implementação de periféricos externos à placa BitDogLab, os quais apresentam diferentes protocolos de comunicação. Enquanto o teclado matricial utiliza a comunicação paralela, o servo motor e o acelerômetro MPU-6050 fazem uso da comunicação serial I2C. Além do uso dos periféricos, o projeto também contou com a utilização dos 2 núcleos da Raspberry para divisão de tarefas, de forma que um núcleo foi usado exclusivamente para o controle do display OLED, enquanto o outro foi usado para as demais tarefas. O projeto foi desenvolvido em linguagem de programação Micropyton. Devido a limitações no fornecimento de componentes, a chave de fim de curso foi substituída por um botão, que apresenta o mesmo funcionamento.
</p>
<p style="color:white; font-size:20px; text-align:left;">
    O fluxograma da execução do projeto está descrito na imagem abaixo:
</p>
<div align="center">
    <img src="https://github.com/JCARNEIROX/EA801/blob/main/Projeto2/imagens/Fluxograma.png">
</div></div>

<h2 style="color:white; font-size:25px; text-align:left;">Resultados </h2>

<p style="color:white; font-size:20px; text-align:left;">
    Através da execução da descrição da seção anterior, deseja-se alcançar os seguintes resultados:  
</p>

<div align="center">
    <table>
        <tr>
            <td><img src="https://github.com/JCARNEIROX/EA801/blob/main/Projeto1/imagens/frente.jpg" width="300" height="300"></td>
            <td><img src="https://github.com/JCARNEIROX/EA801/blob/main/Projeto1/imagens/inicio.jpg" width="300" height="300"></td>
        </tr>
        <tr>
            <td><img src="https://github.com/JCARNEIROX/EA801/blob/main/Projeto1/imagens/start.jpg" width="300" height="300"></td>
            <td><img src="https://github.com/JCARNEIROX/EA801/blob/main/Projeto1/imagens/placar.jpg" width="300" height="300"></td>
        </tr>
    </table>
</div>
<p style="color:white; font-size:20px; text-align:left;">
    A imagem acima mostra os estados que se passam durante o jogo na placa. A seguir tem-se um gif de uma simulação de uma jogada por um dos jogadores.
</p>
<div align="center">
    <img src="https://github.com/JCARNEIROX/EA801/blob/main/Projeto1/imagens/gif.gif" width="600" height="600">
</div></div>

<h2 style="color:white; font-size:25px; text-align:left;">Instruções de utilização</h2>
<p style="color:white; font-size:20px; text-align:left;">
    As instruções de configuração da sua placa pode ser encontrada no repositório do projeto  <a href="https://github.com/BitDogLab/BitDogLab" target="_blank">BitDogLab</a>, após feita as configurações caso esteja utilizando o VSCode pode carregar os arquivos <b>.py</b> localizados no diretório do <a href="https://github.com/JCARNEIROX/EA801/blob/main/Projeto2" target="_blank">Projeto2</a> na memória da placa <b>Raspberry Pi Pico </b>. Caso surja um erro durante o carregamento de um dos arquivos devido ao <i>import</i> do módulo <a href="https://github.com/JCARNEIROX/EA801/blob/main/Projeto1/ssd1306.py" target="_blank">ssd1306.py</a> faça também o upload do mesmo.
</p>

<p style="color:white; font-size:20px; text-align:left;">
    Conheça mais sobre o projeto e também sobre os componentes da placa, assim como tenha acesso a cursos e tutoriais com códigos em <a href="https://bitdoglab.webcontent.website/" target="_blank">BitDogLab.org</a>
</p>

<h2 style="color:white; font-size:25px; text-align:left;">Autores</h2>
<p style="color:white; font-size:20px; text-align:left;">
    João Victor Gomes Carneiro <b>RA:</b> 239738<br>
    Gustavo Elias da Silva <b>RA:</b> 236236<br>
    <b> Faculdade de Engenharia Elétrica e Computação (FEEC) </b>
</p>
