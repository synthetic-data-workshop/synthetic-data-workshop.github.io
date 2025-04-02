---
title: Home
---

# Synthetic Data: Representation and/vs Representativeness
## A Workshop at the Aarhus 2025 Conference

Synthetic data is increasingly used throughout the AI development pipeline to address three primary challenges surrounding data use - data scarcity, privacy concerns, and data representativeness or diversity.
With the introduction of the AI Act, these three challenges take on new urgency.
Creating synthetic data clearly addresses the data scarcity problem and over a decade of research has interrogated the possibilities of differential privacy, yet little attention has been paid to whether and how data diversity is addressed in these systems.
When applied to data, the term representation has multiple definitions, including both “representativeness,” which describes quantitative metrics of how many instances of a particular kind or grouping are in a dataset, and “representation,” which concerns the qualities that tend to be assigned to groups and individuals.
In this workshop we will explore synthetic data with a view to this plurality of representation as essential to responsible AI development practices.

<div class="toc" markdown="1">
## Contents:

{% for lesson in site.pages %}
{% if lesson.nav == true %}- [{{ lesson.title }}]({{ lesson.url | relative_url }}){% endif %}
{% endfor %}
</div>

Organizers: Hannah Devinney, Katherine Harrison, Vagrant Gautam, and Irina Shklovski
 
> built using [Jekyll](https://jekyllrb.com/) and [GitHub Pages](https://pages.github.com/)
>
> images and content: cc-by-sa <a href="https://github.com/{{ site.github_username }}">{{ site.author }}</a> {{ site.pub_year}} (get [source code]({{ site.repo }})).
> Last build date: {{ site.time | date: "%Y-%m-%d" }}.
>
> <a href="http://creativecommons.org/licenses/by-sa/4.0/" rel="license"><img style="border-width: 0;" src="https://i.creativecommons.org/l/by-sa/4.0/88x31.png" alt="Creative Commons License" /></a>
