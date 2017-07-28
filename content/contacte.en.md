+++
title = "Contact"
weight = 3
draft = false
date = "2017-07-27T18:18:30+02:00"
menu = true
+++

We are located in the heart of Poblenou, a neighborhood with strong ties to the cooperative movement, both historically and today.
You can find us at<br />
**Carrer de Venero 12, 08005 Barcelona**

<iframe class="map_embed" title="Cooperativa Mespilus" src="//maps.google.com/?ll=41.403062%2C2.202957&amp;spn=0.011492%2C0.022273&amp;ie=UTF8&amp;z=15&amp;t=roadmap&amp;sll=41.403062%2C2.202957&amp;sspn=0.011492%2C0.022273&amp;q=Carrer%20de%20Venero%2C%2012%2008005%20Barcelona%2C%20Espanya%20(Cooperativa%20Mespilus)&amp;output=embed" width="100%" height="450" frameborder="0" scrolling="no"></iframe><br />

#### Send us a message

Would you like to receive more information about Mespilus, or join us? Are you a producer or distributor or organic produce or products,a "fair trade" company, or another association aligned with our core principals? Fill out the form below and click *send* -- the communications team will reply shortly:  

<form id="contactform" method="post" action="https://formspree.io/markschultz@thewaywest.com">
	<div class="field half first">
		<input type="text" name="name" id="name" placeholder="Full Name"/>
	</div>
	<div class="field half">
		<input type="email" id="email" name="email" placeholder="Email Address">
	</div>
	<div class="field">
		<textarea name="message" id="message" rows="4" placeholder="Message"></textarea>
	</div>
	<ul class="actions">
		<li><input type="submit" value="Send message" class="special" /></li>
		<li><input type="reset" value="Clear entries" /></li>
	</ul>
	<input type="hidden" name="_next" value="?sent#formspree" />
	<input type="hidden" name="_subject" value="Missatge del web" />
	<input type="text" name="_gotcha" style="display:none" />
</form>
<span id="contactformsent">Thank you for your message! Some one will get back to you soon...</span>

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