---
layout: default-md
section: Virtues
title: Virtues
subtitle: In vestibulum massa quis arcu lobortis tempus. Nam pretium arcu in odio vulputate luctus.
---

## Introduction

Virtue-based ethical theories focus on helping people develop good character traits, such as [kindness](kindness) and [generosity](generosity). These character traits will, in turn, allow a person to make the correct decisions later on in life. Virtue theorists also emphasize the need for people to learn how to break bad habits of character, like [greed](greed) or [anger](anger)

Dates back to the ancient Greek thinkers and is thus the oldest type of ethical theory in Western philosophy. **Plato discussed four key virtues**: [wisdom](wisdom), [courage](courage), [temperance](temperance) and [justice](justice).

[Spiritism](/spiritism) teaches that a major part of a persons spiritual evolution comes about by changes in conduct. Virtues like [empathy](empathy), [charity](charity), [indulgence](indulgence) , [humility](humility), and [love](love) are vital to achieving a higher level of existence. Without these virtues (along with intellectual progress) a person can never achieve their true potential. 

## Our List of Virtues
Since we are frequently updating the list of virtues, be sure to be back or subscribe for notifications for updates.

<div class="left">
    <ul>
        {% for post in site.pages %}
        {% for tag in post.tags %}
        {% if tag == "virtue" %}
            <li>
                <a href="{{ post.url }}">{{ post.title }}</a><br>
                <p>{{ post.subtitle }}</p>
            </li>
        {% endif %}
        {% endfor %}
        {% endfor %}
    </ul>
</div>