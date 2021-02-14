---
title: 'Records for Reparations'
date: 2021-02-08 00:00:00
description: A set of links and other resources for discourse on reparations in the United States.
featured_image: '/images/posts/liberation-cycle.jpg'
---

I'm collecting the following resources to serve as a reference library as I begin the journey—personally, professionally & politically—to make our nation and our world more whole and more just through reparations.

It is surely far from comprehensive, but I will add resources here as I find them or as they're shared with me. I hope you, too, find them useful.

---

# Essays

{% for essay in site.data.reparations.essays %}

{{ essay.author }}, "{{ essay.title }}" [[{{ essay.publisher }}]({{ essay.url }})] [<a class="js-no-ajax" target="_blank" href="{{ essay.pdf | relative_url }}">PDF</a>]

{% endfor %}

---

# Books

{% for book in site.data.reparations.books %}

{{ book.author }}, "{{ book.title }}", {{ book.publisher }}. [[Green Apple]({{ book.gab }})] [[SFPL]({{ book.sfpl }})]

{% endfor %}

---

# Organizations

{% for org in site.data.reparations.organizations %}

{{ org.name }} [{{ org.acronym }}({{ org.url }})]

{% endfor %}

---

# Reminders

> "Our concerns are rooted not in the impracticality of reparations but in something more existential. If we conclude that the conditions in black America are not inexplicable but are instead precisely what you’d expect of a community that for centuries has lived in America’s crosshairs, then what are we to make of the world’s oldest democracy?

> What I’m talking about is more than recompense for past injustices—more than a handout, a payoff, hush money, or a reluctant bribe. What I’m talking about is a national reckoning that would lead to spiritual renewal ... Reparations would mean a revolution of the American consciousness, a reconciling of our self-image as the great democratizer with the facts of our history.

--Ta-Nehisi Coates

---

Post header image via the [Intersectional Environmentalist](https://twitter.com/isxenviro).
