---
layout: default
title: Contact
---

<div class="row">
<!-- Map Column -->
<div class="col-md-8">
<!-- Embedded Google Map -->
<iframe width="100%" height="400px" frameborder="0" scrolling="no" marginheight="0" marginwidth="0" src="http://maps.google.com/maps?hl=en&amp;ie=UTF8&amp;ll=37.0625,-95.677068&amp;spn=56.506174,79.013672&amp;t=m&amp;z=4&amp;output=embed"></iframe>
</div>
<!-- Contact Details Column -->
<div class="col-md-4">
<h3>Contact Details</h3>
<p>
IUT d'Elbeuf<br>Elbeuf-sur-Seine, 76500<br>
</p>
<p><i class="fa fa-phone"></i> 
<abbr title="Phone">T</abbr>: 07 84 39 12 20</p>
<p><i class="fa fa-envelope-o"></i> 
<abbr title="Email">E</abbr>: <a href="mailto:name@example.com">contact@remi.mathe.com</a>
</p>
<p><i class="fa fa-clock-o"></i> 
<abbr title="Hours">H</abbr>: Lundi - Vendredi: 9:00 à 17:00 PM</p>
<ul class="list-unstyled list-inline list-social-icons">
<li>
<a href="#"><i class="fa fa-facebook-square fa-2x"></i></a>
</li>
<li>
<a href="#"><i class="fa fa-linkedin-square fa-2x"></i></a>
</li>
<li>
<a href="#"><i class="fa fa-twitter-square fa-2x"></i></a>
</li>
<li>
<a href="#"><i class="fa fa-google-plus-square fa-2x"></i></a>
</li>
</ul>
</div>
</div>
<div class="row">
<div class="col-md-8">
<h3>Contactez moi...</h3>
<form name="sentMessage" id="contactForm" novalidate>
<div class="control-group form-group">
<div class="controls">
<label>NOM Prénom:</label>
<input type="text" class="form-control" id="name" required data-validation-required-message="Please enter your name.">
<p class="help-block"></p>
</div>
</div>
<div class="control-group form-group">
<div class="controls">
<label>Numéro de téléphone:</label>
<input type="tel" class="form-control" id="phone" required data-validation-required-message="Please enter your phone number.">
</div>
</div>
<div class="control-group form-group">
<div class="controls">
<label>Email:</label>
<input type="email" class="form-control" id="email" required data-validation-required-message="Please enter your email address.">
</div>
</div>
<div class="control-group form-group">
<div class="controls">
<label>Message:</label>
<textarea rows="10" cols="100" class="form-control" id="message" required data-validation-required-message="Please enter your message" maxlength="999" style="resize:none"></textarea>
</div>
</div>
<div id="success"></div>
<!-- For success/fail messages -->
<button type="submit" class="btn btn-primary">Envoyer</button>
</form>
</div>
</div>