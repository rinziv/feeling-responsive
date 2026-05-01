---
layout: page
title: "Categorie blog"
subheadline: "Archivio tematico"
teaser: "Esplora gli articoli per area: ansia, coppia, genitorialita e crescita personale."
permalink: "/blog/categorie/"
---
Questa pagina raccoglie tutti gli articoli del blog suddivisi per categoria editoriale.

## Ansia

{% assign posts_ansia = site.posts | where_exp: "post", "post.categories contains 'ansia'" %}
{% if posts_ansia.size > 0 %}
{% for post in posts_ansia %}
- [{{ post.title }}]({{ site.url }}{{ site.baseurl }}{{ post.url }})
{% endfor %}
{% else %}
- Nessun articolo disponibile.
{% endif %}

## Coppia

{% assign posts_coppia = site.posts | where_exp: "post", "post.categories contains 'coppia'" %}
{% if posts_coppia.size > 0 %}
{% for post in posts_coppia %}
- [{{ post.title }}]({{ site.url }}{{ site.baseurl }}{{ post.url }})
{% endfor %}
{% else %}
- Nessun articolo disponibile.
{% endif %}

## Genitorialita

{% assign posts_genitorialita = site.posts | where_exp: "post", "post.categories contains 'genitorialita'" %}
{% if posts_genitorialita.size > 0 %}
{% for post in posts_genitorialita %}
- [{{ post.title }}]({{ site.url }}{{ site.baseurl }}{{ post.url }})
{% endfor %}
{% else %}
- Nessun articolo disponibile.
{% endif %}

## Crescita personale

{% assign posts_crescita = site.posts | where_exp: "post", "post.categories contains 'crescita-personale'" %}
{% if posts_crescita.size > 0 %}
{% for post in posts_crescita %}
- [{{ post.title }}]({{ site.url }}{{ site.baseurl }}{{ post.url }})
{% endfor %}
{% else %}
- Nessun articolo disponibile.
{% endif %}
