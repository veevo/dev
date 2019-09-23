---
title: About
description: Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.  TODO
date: 2019-02-01 19:00:00
tags:
- about
---

<div>

    <h2>All <strong>Topics</strong></h2>
    <div class="left">
        <ul>
            {% for post in site.pages %}
            {% for tag in post.tags %}
            {% if tag == "about" %}
                <li>
                                        <p>{{ post.subtitle }}</p>
                </li>
            {% endif %}
            {% endfor %}
            {% endfor %}
            </li>
        </ul>
    </div>

</section>

