---
layout: home
title: Home
date: 2025_09_16
---
# [Welcome to Terra A.D.]({{ site.baseurl }}/2025/09/16/Welcome_to_Terra_AD.html) Meatgrinder Documents

Your go-to resource for Meat Grinder Tabletop players playing in Mutant Crawl Classics. Some of this is paraphrased from their rulebook, and some of this is work of my own. I'm expanding their system's campaign setting and will include only stats that are original. My goal here is not to plagiarize, but to expand upon, so I will also give credit to [the system (Mutant Crawl Classics) and Goodman Games](https://goodman-games.com/store/product/mutant-crawl-classics-role-playing-game-2/). It's really cool if you're into old school table top role playing, and definitely worth the price tag.

---
## History
- ### Events
	 - [The Great Collapse]({{ site.baseurl }}/2025/09/16/The_Great_Collapse.html)
- ### Historical Factions
	- [The Ancient Ones]({{ site.baseurl }}/2025/09/16/The_Ancient_Ones.html)
- ### Items
    - [Artifacts of The Ancients]({{ site.baseurl }}/2025/09/16/Artifacts_of_The_Ancients.html)

---

## Places
- ### Regions
	- **The Shimmering Sands**
		- [The Shimmering Sands]({{ site.baseurl }}/2025/09/16/The_Shimmering_Sands.html)
	- **Xocust Wilderness**
		- [The Xocust Wilderness]({{ site.baseurl }}/2025/09/16/The_Xocust_Wilderness.html) 
		- [Xocust Mountain]({{ site.baseurl }}/2025/09/16/Xocust_Mountain.html)

---

## Tribes
- [The Clan Of Cog]({{ site.baseurl }}/2025/09/16/The_Clan_Of_Cog.html)
- [The Chozen Zuu]({{ site.baseurl }}/2025/09/16/The_Chosen_Zuu.html)
- [The Curators]({{ site.baseurl }}/2025/09/16/The_Curators.html)

---

## Latest Posts

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url | prepend: site.baseurl }}">{{ post.title }}</a>
      <span>{{ post.date | date: "%B %d, %Y" }}</span>
    </li>
  {% endfor %}
</ul>
