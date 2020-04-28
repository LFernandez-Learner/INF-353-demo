---
title: Home
layout: default
---
<div class="header">Welcome to Musical Instruments Website!</div>

<div class="paragraph">There are over 2000 musical instruments from around the world, and there are 6 different types of genres of music where each one of them have own groups with sounds and relation of instruments, such as what are similar and differences.</div>


{% for groups_of_musical_instrument in site.groups_of_musical_instruments %}
  <div class="h4">{{ groups_of_musical_instrument.title }}</div>
  <p><div class="border5">{{ groups_of_musical_instrument.content }}</div></p>
{% endfor %}

<div class="quote">Quote:
"People are like musical instruments: their sound depends on who touches them." -Virgil
</div>
