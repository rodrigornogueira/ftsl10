---
layout: post
title: Presenças confirmadas!
excerpt: Palestras e cursos confirmados para o X FTSL
image: presencas-confirmadas.png
---
<div>
      <div class="row ">
        <div>
          <span>A avaliação de trabalhos já começou. Estes são os palestrantes e instrutores selecionados que já confirmarem sua presença no X FTSL:<a name="presencas_confirmadas"></a></span>
        </div>
      </div>

      <ul>	

          {% for convidado in site.convidados %}
		<li><span style="display: inline-block; padding:5px "><a href="{{site.baseurl}}{{ convidado.url }}">{{ convidado.title }}</a></span></li>                      
          {% endfor %}

	</ul>	

</div>

A organização do FTSL agradece ao engajamento da comunidade de software livre, sem a qual o evento não seria possível.

<a href="{{ site.baseurl }}/index.html">Voltar</a>
