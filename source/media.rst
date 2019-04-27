Media Appearances
-----------------

{% assign tv = site.data.tv %} {% assign news = site.data.news %}

Stop the Press!
~~~~~~~~~~~~~~~

I welcome media inquires. I enjoy speaking on technology in general,
computer science research (including my own), and historical, social,
ethical, and legal issues in computing.

Direct inquiries are welcome. Please contact `Justin
Goldstein <justin.goldstein@finnpartners.com>`__ and `Adam
Zeiff <adam.zeiff@finnpartners.com>`__ for inquiries in connection with
my work at IEEE. You may also contact `Loyola University Chicago Media
Relations
Group <https://www.luc.edu/news/?utm_medium=redirect&utm_campaign=loyola-redirects&utm_source=newsroom>`__.

Television Interviews
~~~~~~~~~~~~~~~~~~~~~

{% for appearance in tv.items %}

{{ appearance.station }}, *{{ appearance.title }}*, `{{ appearance.url
}} <%7B%7B%20appearance.url%20%7D%7D>`__, {{ appearance.date }}

{% endfor %}

Newspapers and Magazines
~~~~~~~~~~~~~~~~~~~~~~~~

{% for appearance in news.items %}

{{ appearance.publication }}, *{{ appearance.title }}*, `{{
appearance.url }} <%7B%7B%20appearance.url%20%7D%7D/>`__, {{
appearance.date }}

{% endfor %}
