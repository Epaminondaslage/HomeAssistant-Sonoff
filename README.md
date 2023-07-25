<td style="width: 20%;"><img src="/img/top_ha_sonoff.png" width="100%"></td>

# Índice 
* [Introdução](#Introdução)
* [Integração com o Ewelink ](#Integração-com-o-Ewelink)

# Introdução

Os dispositivos Sonoff são uma linha de produtos de automação residencial desenvolvidos pela ITEAD, uma empresa especializada em eletrônica e IoT. Esses dispositivos são baseados em microcontroladores e geralmente contêm módulos de comunicação sem fio, como Wi-Fi ou RF (Radiofrequência).

Cada dispositivo Sonoff é projetado para executar funções específicas, como interruptores inteligentes, tomadas inteligentes, relés de potência, sensores de movimento, termostatos, lâmpadas inteligentes e muito mais. Eles são projetados para serem facilmente integrados em redes domésticas existentes, permitindo que os usuários controlem e monitorem remotamente seus dispositivos e eletrodomésticos conectados por meio de smartphones, tablets ou computadores.

Os dispositivos Sonoff podem ser controlados usando o App eWeLink, que fornece uma interface intuitiva para gerenciar os dispositivos. Além disso, esses dispositivos também podem ser integrados a outras plataformas de automação residencial e sistemas de gerenciamento de dispositivos IoT, como o Home Assistant, permitindo maior flexibilidade e personalização para os usuários.

Uma característica importante dos dispositivos Sonoff é a capacidade de suportar modos de operação tanto na LAN (Local Area Network) quanto na nuvem. No modo LAN, os dispositivos podem ser controlados diretamente pela rede local, garantindo maior privacidade e desempenho mais rápido. Já no modo em nuvem, eles podem ser acessados através da internet, permitindo o controle remoto mesmo quando o usuário não está em casa.

Essa flexibilidade e a ampla variedade de dispositivos Sonoff disponíveis tornam essa linha de produtos uma escolha popular para projetos de automação residencial e aplicações IoT, oferecendo uma solução eficiente e acessível para tornar as residências mais inteligentes e conectadas.

# Integração com o Ewelink 

<table border="0"><body><tr>
<td style="width: 50%;"><img src="/img/fig01.png" width="50%" /></td></tr><tr>
<td style="text-align: center;">Com o "HACS" instalado, vá em "Integrações".</td></tr></body></table>

<table border="0"><body><tr>
<td style="width: 50%;"><img src="/img/fig02.png" width="50%" /></td></tr><tr>
<td style="text-align: center;">Procure a integração "Sonoff" e instale.</td></tr></body></table>

<table border="0"><body><tr>
<td style="width: 50%;"><img src="/img/fig03.png" width="50%" /></td></tr><tr>
<td style="text-align: center;">Uma vez instalado esta tela será apresentada.</td></tr></body></table>

<table border="0"><body><tr>
<td style="width: 50%;"><img src="/img/fig04.png" width="50%" /></td></tr><tr>
<td style="text-align: center;">O proximo passo é ir em "Configurações" e "Dispositivos e Serviços".</td></tr></body></table>

<table border="0"><body><tr>
<td style="width: 50%;"><img src="/img/fig05.png" width="50%" /></td></tr><tr>
<td style="text-align: center;">Abra a Integração "Sonoff"</td></tr></body></table>

<table border="0"><body><tr>
<td style="width: 50%;"><img src="/img/fig06.png" width="50%" /></td></tr><tr>
<td style="text-align: center;">Clicar em "Adicionar Entrada".</td></tr></body></table>

<table border="0"><body><tr>
<td style="width: 50%;"><img src="/img/fig08.png" width="50%" /></td></tr><tr>
<td style="text-align: center;">Depois de instalado entre com seu usuário e senha do ewelink.</td></tr></body></table>

<table border="0"><body><tr>
<td style="width: 50%;"><img src="/img/fig07.png" width="50%" /></td></tr><tr>
<td style="text-align: center;">Após confirmar todos os dispositivos cadastrados no ewelink irão aparecer no Home Assistant</td></tr></body></table>

<table border="0"><body><tr>
<td style="width: 50%;"><img src="/img/fig09.png" width="50%" /></td></tr><tr>
<td style="text-align: center;">Agora basta acrescentar os "Cards" conforme cada dispositivo.</td></tr></body></table>

Recentemente a Sonoff disponibilizou o modo DIY para os dispositivos se conectarem ao home Assistant. Visite o site  https://sonoff.tech/product-review/how-sonoff-works-with-home-assistant/ para ver esta nova funcionalidade.

# Sites relacionados ao Home Assistant - Sonoff

* https://ewelink.cc/
* https://ewelink.cc/ewelink-works-with-home-assistant/

# Status do Projeto

![Badge em Desenvolvimento](http://img.shields.io/static/v1?label=STATUS&message=EM%20DESENVOLVIMENTO&color=GREEN&style=for-the-badge)


