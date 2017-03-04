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

O programa usado para captura de tela, GNU/Linux, Simpĺe Screen Recorder é um dos mais populares, agora está disponível sua instalação com pacote `SNAP`. Anteriormente sua instalação estava disponível apenas por repositórios `PPA`.

Para instalar pelos [repositórios oficiais PPA], basta a dicionar da seguite maneira:



{% highlight python %}
      sudo add-apt-repository ppa:maarten-baert/simplescreenrecorder
{% endhighlight %}
 
Após adicionar o repositório

{% highlight python %}
      sudo apt-get update
{% endhighlight %}



{% highlight python %}
if __name__ =='__main__':
    img_thread = threading.Thread(target=downloadWallpaper)
    img_thread.start()
    st = '\rDownloading Image'
    current = 1
    while img_thread.is_alive():
        sys.stdout.write(st+'.'*((current)%5))
        current=current+1
        time.sleep(0.3)
    img_thread.join()
    print('\nImage of the day downloaded.')
{% endhighlight %}


[repositórios oficiais PPA]: https://launchpad.net/~maarten-baert/+archive/ubuntu/simplescreenrecorder/
