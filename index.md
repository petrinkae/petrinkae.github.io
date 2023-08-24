---
excerpt: ""
title: ""
author_profile: true

---

I'm a data & graphics reporter on [Chalkbeat](https://chalkbeat.org/)'s [data visuals](https://dataviz.chalkbeat.org/) team, where I collaborate with local reporters to tell data-driven stories about education. Occasionally I work with [Votebeat](https://www.votebeat.org/), as well. Check out my [recent Chalkbeat bylines](https://www.chalkbeat.org/authors/kae-petrin) and my [broader portfolio](https://authory.com/KaePetrin). I also do part-time, project-based data analysis and viz for the [Mississippi River Basin Ag & Water Desk](https://agwaterdesk.org/).

In 2020, I cofounded the [Trans Journalists Association](https://transjournalists.org/) with several dozen other journalists; I have since run many of its internal operations and served as an interim board member to oversee the association's nonprofit incorporation. 

I present on queer and trans coverage best practices, data reporting and visualization tools, and the intersections of these topics at universities, industry conferences, custom-designed workshops, and newsrooms around the U.S. 

Previously, as a digital reporter at [St. Louis Public Radio](https://news.stlpublicradio.org/people/kae-m-petrin), I created graphics, built newsroom-wide tools, and covered data-driven stories across beats. Before that, I was an editorial assistant at [St. Louis Magazine](https://www.stlmag.com/topics/kae-m-petrin/). I also served on the [St. Louis Pro chapter](http://www.stlspj.com/about/) of the Society of Professional Journalists’s board of directors as secretary and a finance committee member from 2017 to 2023.

While working in Missouri and Illinois, I also produced freelance investigations, breaking news, web redesigns, and entertainment criticism, and spent a year in healthcare as a data analyst. Throughout my career in local news I have contributed data analyses and visualizations to reporting that has been recognized by the Education Writers Association, multiple chapters of the Society for Professional Journalists, the Missouri Broadcaster Association, and regional Edward R. Murrow Awards.

<h1>What I've been up to</h1>

<div class="activities">
{% for pub in site.data.interviews %}
    {% if pub.show_flag == "TRUE" %}
        {% if pub.link %}
            <h3><a href="{{ pub.link }}">{{ pub.title }}</a></h3>
        {% else %}
            <h3>{{ pub.title }}</h3>
        {% endif %}
        <h6><em>With {{pub.event}} on {{ pub.date }}</em></h6>
    {% endif %}
{% endfor %}
</div>