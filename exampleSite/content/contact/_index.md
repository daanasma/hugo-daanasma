---
title: Contact
bg_image: images/mandala.png
description: Neem contact op

---
Heb je een vraag, suggestie of bezorgdheid? Twijfel niet om contact op te nemen en ik laat je zo snel mogelijk iets weten!

<form name="contact" class="contact-form width-normal" action="/thank-you/" method="POST" data-netlify="true"> <input type="hidden" name="form-name" value="contact" /> <!-- Text input--> <div class="form-group"> <label class="col-md-4 control-label" for="Name"></label> <div class="col-md-4"> <input id="contact-form-name" name="Name" type="text" placeholder="Naam" class="form-control input-md" required="" autocomplete="off"> </div> </div> <!-- Text input--> <div class="form-group"> <label class="col-md-4 control-label" for="Email"></label> <div class="col-md-4"> <input id="contact-form-email" name="Email" type="email" placeholder="E-mailadres" class="form-control input-md" required="" autocomplete="off"> </div> </div> <!-- Text input--> <div class="form-group"> <label class="col-md-4 control-label" for="Subject"></label> <div class="col-md-4"> <input id="contact-form-subject" name="Subject" type="text" placeholder="Onderwerp" class="form-control input-md" required="" autocomplete="off"> </div> </div> <!-- Textarea --> <div class="form-group"> <label class="col-md-4 control-label" for=""></label> <textarea class="form-control" id="contact-form-message" name="Message" placeholder="Boodschap" rows="8"></textarea> </div> <!-- Button --> <br><div class="form-group"> <button type="submit" value="Submit" id="Form-submit">Verstuur</button> </div> </form>