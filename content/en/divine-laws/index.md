---
title: Divine Laws
description: In vestibulum massa quis arcu lobortis tempus. Nam pretium arcu in odio vulputate luctus.
---

## About Divine Laws
Natural law, divine law, is comprised of the unchanging, eternal laws that govern the universe ̶ both the laws of nature that govern our physical realm, and which are studied by our scientific researchers, as well as the ethical laws, or rules for proper, moral action, the essence of which is contained in the instruction to love your neighbor and do for him what you’d wish for you.

God’s law is written in the conscience of each one of us, but over time, has been forgotten or misunderstood, which is why it must be revealed to us once again. The sprits tell us that, one day, everyone will fully comprehend the law, for that is the destiny toward which progress is inevitably leading us¹.


## Our List of Divine Laws
We are frequently updating our virtues so be sure to be back or subscribe for notifications on updates.

<div class="left">
    <ul>
        {% for post in site.pages %}
        {% for tag in post.tags %}
        {% if tag == "divine-law" %}
            <li>
                                <p>{{ post.subtitle }}</p>
            </li>
        {% endif %}
        {% endfor %}
        {% endfor %}
    </ul>
</div>
