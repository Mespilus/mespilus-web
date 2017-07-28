+++
title = "Contacte"
weight = 3
draft = false
date = "2017-07-27T18:18:30+02:00"
menu = true
+++

Ens trobem en ple cor del Poblenou, barri amb una presència històrica i actual de cooperativisme.
Ens podreu trobar al<br />
**Carrer de Venero 12, 08005 Barcelona**

<iframe class="map_embed" title="Cooperativa Mespilus" src="//maps.google.com/?ll=41.403062%2C2.202957&amp;spn=0.011492%2C0.022273&amp;ie=UTF8&amp;z=15&amp;t=roadmap&amp;sll=41.403062%2C2.202957&amp;sspn=0.011492%2C0.022273&amp;q=Carrer%20de%20Venero%2C%2012%2008005%20Barcelona%2C%20Espanya%20(Cooperativa%20Mespilus)&amp;output=embed" width="100%" height="450" frameborder="0" scrolling="no"></iframe><br />

#### Enviar una missatge

Estás interessat/da en rebre información sobre la cooperativa per formar-ne part? Ets un productor o proveïdor de productes d’agricultura biològica, comerç just o altres que puguin estar en sintonia amb els nostres principis? Completa el formulari seguënt i prem *enviar* -- el grup de comunicaciò responderan en breu:  

<form id="contactform" method="post" action="https://formspree.io/markschultz@thewaywest.com">
	<div class="field half first">
		<input type="text" name="name" id="name" placeholder="Nom complet"/>
	</div>
	<div class="field half">
		<input type="email" id="email" name="email" placeholder="Correu electrònic">
	</div>
	<div class="field">
		<textarea name="message" id="message" rows="4" placeholder="Missatge"></textarea>
	</div>
	<ul class="actions">
		<li><input type="submit" value="Enviar missatge" class="special" /></li>
		<li><input type="reset" value="Esborra entrades" /></li>
	</ul>
	<input type="hidden" name="_next" value="?sent#formspree" />
	<input type="hidden" name="_subject" value="Missatge del web" />
	<input type="text" name="_gotcha" style="display:none" />
</form>
<span id="contactformsent">Gràcies pel teu missatge! Algu us tornarà a contactar aviat.</span>

<script>
$(document).ready(function($) { 
    $(function(){
        if (window.location.search == "?sent") {
        	$('#contactform').hide();
        	$('#contactformsent').show();
        } else {
        	$('#contactformsent').hide();
        }
    });
});
</script>

{{< socialLinks >}}