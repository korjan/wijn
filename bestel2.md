---
layout: page
title: Bestellen
permalink: /bestel2/
---

## Bestellen

<form action="https://formspree.io/korjanvanwieringen@gmail.com"
      method="POST">
    <div class="control">
      <label for="_order">Wat wilt u bestellen?</label>
      <textarea name="_order" class="textarea"></textarea>
    </div>
    <div class="control">
      <label for="_phone">Op welk telefoonnummer kan ik u bereiken?</label>
      <input type="phone" name="_phone" class="input"/>
    </div>
    <div class="control">
      <input type="hidden" name="_next" value="//www.wijnvanmartijn.nl/bedankt"/>
      <input type="hidden" name="_subject" value="Nieuwe bestelling" />
      <input type="text" name="_gotcha" style="display:none" />
      <button type="submit" class="button">Bestelling plaatsen</button>
    </div>
</form>
<br/>
<p>of bel:
<a href="tel:+31648469638">06-48469638</a>
Of stuur mij een appje: <a href="whatsapp://send?phone=+31648469638&text=Hello%2C%20World!">whatsapp</a>
</p>
