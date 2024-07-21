---
title: Team
nav:
  order: 3
  tooltip: About our team
---

#### {% include icon.html icon="fa-solid fa-users" %}Team

We are a young group starting to grow!

{%
  include button.html
  icon="fa-solid fa-handshake-angle"
  text="Join the Team"
  link="contact"
  style="button"
%}

{% include section.html %}

{% include list.html data="members" component="portrait" filters="role: pi" %}
{% include list.html data="members" component="portrait" filters="role: ^(?!pi$)" %}




