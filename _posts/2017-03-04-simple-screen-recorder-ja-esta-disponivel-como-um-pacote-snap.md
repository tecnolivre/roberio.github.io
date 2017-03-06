---
layout: post
title: "Simple Screen Recorder já está disponível como um pacote Snap"
date: 2017-03-04 18:45:49
image: '/assets/img/'
description:
main-class:
color:
tags: 
 - Linux
 - Tecnologia
 - Gravador de tela
 - simple Screen Recorder
 - Pacote SNAP
 - Ubuntu
categories:
 - Linux
 - Tecnologia
 - Ubuntu
twitter_text: Simple Screen Recorder já está disponível como um pacote Snap
introduction:
---
<figure>
	<img src="/images/imagens/sobre-simple-screen-recorder.png">
	<figcaption>Simple Screen Recorder</figcaption>
</figure>

O programa usado para captura de tela, GNU/Linux, Simpĺe Screen Recorder é um dos mais populares, agora está disponível sua instalação com pacote SNAP. Anteriormente sua instalação estava disponível apenas por repositórios PPA.

<figure>
	<img src="/images/imagens/simple.png">
	<figcaption>Simple Screen Recorder</figcaption>
</figure>


Para instalar pelos [repositórios oficiais PPA], basta a dicionar da seguite maneira:

{% highlight python %}
      sudo add-apt-repository ppa:maarten-baert/simplescreenrecorder
{% endhighlight %}
 
Após adicionar o repositório

{% highlight python %}
      sudo apt-get update
{% endhighlight %}
Para instalar, o comando abaixo, para sistema 32 bit 
{% highlight python %}
      sudo apt install simplescreenrecorder simplescreenrecorder-lib
{% endhighlight %}

Para Sistema 64 bit é necessário instalar a biblioteca a seguir:
{% highlight python %}
      sudo apt install simplescreenrecorder-lib:i386
{% endhighlight %}


Para instalar via SNAP, basta digitar o comando abaixo:

{% highlight python %}
      sudo snap install simplescreenrecorder-mardy
{% endhighlight %}


Agora é só instalar e começar a gravar.


Veja também!


[Lançamento da NASA]

[Ubuntu 17.04 beta vem com o kernel Linux 4.10]





[repositórios Oficiais PPA]: https://launchpad.net/~maarten-baert/+archive/ubuntu/simplescreenrecorder/

[Lançamento da NASA]: http://teclivre.com/tecnologia/enganharia/novidades/2017/03/04/NASA-lan%C3%A7a-software-que-permite-uso-de-forma-gratu%C3%ADta-a-tecnologias/

[Ubuntu 17.04 beta vem com o kernel Linux 4.10]:http://teclivre.com/tecnologia/linux/ubuntu/2017/02/28/ubuntu-1704-beta-vem-com-o-kernel-linux-410/




