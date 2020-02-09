---
layout: postwofooterwoimage
title: Bliv medlem
description:
image: assets/images/joinus.jpg
nav-menu: true
---
Indmeldelsesblanket for almindeligt medlemskab af TinkerTank

For at blive medlem af TinkerTank, skal du udfylde nedenstående form. Medlemskabet er gyldigt når vi har modtaget den udfyldte formular, samt indbetalt medlemskontigent på 50kr pr måned, på kontonummer: 5321 0256366.

<form action="https://formspree.io/{{ site.email }}" method="POST">
  <div class="field half first">
    <label for="name">Fulde navn</label>
    <input type="text" name="name" id="name" />
  </div>
  <div class="field half">
    <label for="adresse">Adresse</label>
    <input type="text" name="adresse" id="adresse" />
  </div>
  <div class="field half first">
    <label for="telefon">Telefon</label>
    <input type="text" name="telefon" id="telefon" />
  </div>
  <div class="field half">
    <label for="email">Email</label>
    <input type="text" name="email" id="email" />
  </div>
  <div class="field">
    <a href="{{ site.baseurl }}/vedtaegter.pdf" target="_blank"> Vedtægter.pdf</a> <br>
    Jeg skriver under på, at jeg har læst og accepteret foreningens vedtægter og medlemsvilkår for almindeligt medlemskab. <br>
  </div>
  <ul class="actions">
    <li><input type="submit" value="Indsend" class="special" /></li>
    <li><input type="reset" value="Slet" /></li>
  </ul>
</form>
