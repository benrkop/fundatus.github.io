---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: home
---
![](./media/Background.png)

# Welcome to FUNdamental!
An international collective working towards a guide for the safe and effective application of transcranial focused ultrasound for neuromodulation. Here, experts come together and delineate best practices, provide guidance for new labs, report on future perspectives, and more!


[Get to know us](./about/){: .btn .btn-purple .mx-auto}

---

### Our organization

We can consider listing the names of people here.

### Our repository contributors

<ul class="list-style-none">
{% for contributor in site.github.contributors %}
  <li class="d-inline-block mr-1">
     <a href="{{ contributor.html_url }}"><img src="{{ contributor.avatar_url }}" width="32" height="32" alt="{{ contributor.login }}"/></a>
  </li>
{% endfor %}
</ul>


<!--
[I'm an inline-style link](https://www.google.com)

[I'm a relative reference to a repository file](../blob/master/LICENSE)

You can find a link to our full size logo [here](./media/FundamentalLogo1.png). -->
