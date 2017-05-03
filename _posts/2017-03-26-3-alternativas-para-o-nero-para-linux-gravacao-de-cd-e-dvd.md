---
layout: post
title: "Alternativas para o Nero para Linux Gravação de CD e DVD"
date: 2017-03-26 17:21:17
image: '/assets/img/'
description:
main-class:
color:
tags:
- Linux
- Tecnologia
- Nero

categories:
- Linux
- Tecnologia
twitter_text: Alternativas para o Nero para Linux Gravação de CD e DVD
introduction:
---

Eu não tive um computador de trabalho com uma unidade de mídia ótica em quase um ano agora, ea verdade é, eu não perdi. Tecnicamente eu tenho um dispositivo USB externo CD / DVD, mas eu nem mesmo puxado para fora de sua caixa.

Então, por que eu tenho pensado tanto sobre a leitura e escrita desses pequenos discos redondos ultimamente? <!--more-->

Só porque eu parei de usar DVDs e CDs (e nunca entrei em Blu-ray) não significa que eles tenham desaparecido. Pessoalmente, eu ainda tenho anos de backup, cópias originais de jogos e música e filmes, que eu realmente deveria fazer backups de antes que eles se deterioram. Mas há milhões de pessoas ainda encontrando usos para discos físicos todos os dias.

Precisa dar cinquenta cópias de algum pedaço de dados o mais barato possível? Talvez você queira fazer uma cópia de um filme caseiro ou a versão moderna de um mixtape para alguém que só tem acesso a um CD ou DVD player para reprodução. Talvez você dirigir uma das dezenas, senão centenas de milhões de carros na estrada ao redor do globo ainda ostentando um leitor de CD como o leitor de música primária. Talvez você precise substituir o sistema operacional oh uma máquina mais antiga que apenas não vai arrancar a partir de USB.

Qualquer que seja a razão, ainda há uma boa chance de que todos nós ainda estaremos usando mídia ótica para os próximos anos. Para aqueles que fizeram a mudança de software proprietário para software de fonte aberta nos últimos anos, você pode estar à procura de uma ferramenta que permite rasgar e gravar discos com facilidade.

Embora a maioria dos sistemas operacionais modernos tenham instalações básicas construídas hoje em dia (Nautilus, também conhecido como Gnome Files, funciona bem se você estiver apenas olhando para arrastar e soltar alguns arquivos em um disco), há ocasiões em que a funcionalidade avançada de um programa como o Nero foi útil. Aqui estão alguns programas de código aberto para trabalhar com mídias ópticas que você deve verificar para aqueles em um sistema Linux.

<script async src="//pagead2.googlesyndication.com/pagead/js/adsbygoogle.js"></script>
<!-- teclivre -->
<ins class="adsbygoogle"
     style="display:inline-block;width:728px;height:90px"
     data-ad-client="ca-pub-1738697462902889"
     data-ad-slot="4405393702"></ins>
<script>
(adsbygoogle = window.adsbygoogle || []).push({});
</script>
<figure>

	<img src="/images/imagens/2017-03-26-Alternativas-para-o-nero-para-linux-gravacao-de-cd-e-dvd.png">
	<figcaption>Image By: [Silver Spoon]</figcaption>
</figure>


## Brasero

Quando eu ainda estava usando mídia ótica com regularidade, [Brasero] era o meu programa para criar CDs e DVDs. Projetado para o Gnome e embalado para a maioria das principais distribuições Linux, Brasero apresenta uma interface GUI limpa e empacotada para criar uma variedade de tipos de disco. Ao abri-lo pela primeira vez, você recebe escolhas para criar um novo projeto de áudio, vídeo ou dados, além de criar uma cópia 1: 1 de um disco existente ou gravar uma cópia de uma imagem criada anteriormente. Ele também vem com um editor de capa, que não é quase tão avançado como usar um programa separado para criar sua capa, mas ainda é um bom-de-ter.

Uma coisa boa que eu gosto sobre Brasero é a interface plugável, permitindo que uma variedade de ferramentas diferentes para ser adicionado separadamente, incluindo ferramentas não-livres para trabalhar com, por exemplo, CSS criptografado DVD vídeo.

O código-fonte da Brasero é mantido em um [repositório git] hospedado pela Fundação Gnome, e está disponível como código aberto sob os termos da GPL, versão 2 ou superior.


## K3b

Para aqueles mais alinhados com o universo do KDE, o [K3b] (abreviatura para KDE Burn Baby Burn) é uma ótima alternativa. Como o Brasero, o K3b suporta uma variedade de diferentes tipos de discos e formatos. Ele suporta várias ferramentas de linha de comando diferentes (das quais falaremos em pouco) para serem usadas no back-end do aplicativo, permitindo que você tenha muito mais controle sobre o processo de criação do disco. Em essência, o K3b é apenas uma interface agradável para essas bibliotecas.

K3b não viu uma nova versão em um par de anos, mas o software existente é estável e bastante completo, para que não deve ser uma grande preocupação para a maioria dos usuários.

O K3b é liberado sob os termos da versão 2 da GPL e seu [código-fonte] está disponível no site do projeto KDE.

## Utilitários de linha de comando


Para muitos que fizeram a mudança para o Linux, a linha de comando é uma opção convincente para fazer as coisas. Por que a gravação de discos ópticos deve ser diferente?

Qual ferramenta usar depende um pouco do que você espera fazer. Abaixo está um breve esboço de algumas das ferramentas que você pode considerar. Cada um tem seu próprio conjunto de recursos suportados, por isso, se você está esperando para um tipo específico de disco de gravação.

[Cdrdao] é uma ferramenta bastante simples para gravar CDs no modo disk-at-once (DAO).

[Cdrkit] é um fork de [cdrtools], principalmente projetado para manter a licença CPL quando a licença do projeto original mudou. É um conjunto de programas relacionados para gravar CD-R e DVDs, criar imagens, extrair áudio de CD e tarefas relacionadas.

[Dvd+rw-tools], como o próprio nome indica, fornece ferramentas de escrita de linha de comando para DVDs, mas também suporta o formato de disco Blu-ray. No entanto, não grava CDs.

[Libburnia] é um conjunto de ferramentas relacionadas e bibliotecas que podem gravar CDs, DVDs e discos Blu-ray.


Quais ferramentas de código aberto você usa para trabalhar com CDs e DVDs? Há, naturalmente, outras opções além destas escolhas óbvias, que você prefere? E, claro, espero que vá sem dizer, mas vou afirmá-lo de qualquer maneira, certifique-se de que você tem os direitos legais para fazer cópias de qualquer software, música ou filmes que você pretende gravar.

[Fonte]


Essa informação foi útil? Compartilhe!



[Silver Spoon]: https://commons.wikimedia.org/wiki/File:CDs.JPG
[Brasero]: https://wiki.gnome.org/Apps/Brasero
[repositório git]: https://git.gnome.org/browse/brasero/
[K3b]: https://userbase.kde.org/K3b
[código-fonte]: https://userbase.kde.org/K3b
[Cdrdao]: cdrdao.sourceforge.net
[Cdrkit]: https://launchpad.net/cdrkit
[cdrtools]:cdrtools.sourceforge.net/private/cdrecord.html
[Dvd+rw-tools]: fy.chalmers.se/~appro/linux/DVD+RW/
[Libburnia]: http://libburnia-project.org/
[Fonte]: https://opensource.com/life/16/9/alternatives-nero-cd-burning?sc_cid=7016000000127ECAAY
