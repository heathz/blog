---
layout: page
title: Contato
permalink: /contato/
---
<style type="text/css" media="screen">
	fieldset{border:0;}
	form{margin-left:200px;}
	input, textarea{padding:3px; margin-bottom:5px; border:1px solid #c0c0c0; -moz-border-radius:3px; -webkit-border-radius:3px;}
	input:focus, textarea:focus{border-color:#999;}
	label{display:block; font-size:1.2em; margin-top:5px;}
	textarea{overflow:auto; font:1.2em Arial, Helvetica, sans-serif; color:#333; line-height:1.6em;}
	.width230{width:230px;}
</style>

<form action="https://formspree.io/contato@timeu.com.br" method="POST" id="form-contato">
	<fieldset>
		<label for="nome">Nome:</label>
		<input type="text" class="width230" name="nome" id="nome" required />
        <label for="email">E-mail:</label>
		<input type="email" class="width230" name="_replyto" id="email" required />
        <label for="observa&ccedil;&otilde;es">Mensagem:</label>
		<textarea rows="5" cols="3" class="width230" name="msg" id="msg" required></textarea><br />
		<input type="hidden" name="_next" value="//timeu.com.br/thankyou.html" />
		<input type="text" name="_format" value="plain" style="display:none" />
		<input type="hidden" name="_subject" value="Contato do Site" />
		<input type="submit" value="Enviar" name="enviar" id="enviar_contato" />
	</fieldset>
</form>
