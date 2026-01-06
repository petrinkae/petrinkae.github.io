---
excerpt: ""
title: ""
author_profile: true

---

I'm a data journalist, business and nonprofit leader, and lecturer focused on media and government accountability. I speak internationally on data and investigative reporting, LGBT communities and transgender rights coverage, and media analysis. You can find my work in Columbia Journalism Review, the International Journalists’ Network, Nieman Reports, the Global Investigative Journalism Network, and more.

Right now, I'm a John S. Knight Journalism Fellow in residence at Stanford University for the 2025-26 school year.

Normally, I'm a [data & graphics reporter](https://dataviz.chalkbeat.org/) for Civic News Company, where I collaborate with local reporters at [Chalkbeat](https://chalkbeat.org/), [Votebeat](https://www.votebeat.org/), and [Healthbeat](https://www.healthbeat.org/) to tell data-driven stories about education, voting rights, and public health. Check out my [recent Chalkbeat bylines](https://www.chalkbeat.org/authors/kae-petrin) and my [broader portfolio](https://authory.com/PetrinKae). 

In 2020, I cofounded the [Trans Journalists Association](https://transjournalists.org/) with several dozen other journalists; I have since run many of its internal operations and directed the organization's development to an incorporated grassroots nonprofit. I have served in various roles there, ranging from executive director to co-executive director to board president.

Previously, as a digital reporter at [St. Louis Public Radio](https://news.stlpublicradio.org/people/kae-m-petrin), I created graphics, built newsroom-wide tools, and covered data-driven stories across beats. Before that, I was an editorial assistant at [St. Louis Magazine](https://www.stlmag.com/topics/kae-m-petrin/). I also served on the [St. Louis Pro chapter](http://www.stlspj.com/about/) of the Society of Professional Journalists’s board of directors as secretary and a finance committee member from 2017 to 2023.

While working in Missouri and Illinois, I also produced freelance investigations, breaking news, web redesigns, and entertainment criticism, and spent a year in healthcare as a data analyst. Throughout my career in local news I have contributed data analyses and visualizations to reporting that has been recognized by the Education Writers Association, LION Local Journalism Awards,  multiple chapters of the Society for Professional Journalists, the Missouri Broadcaster Association, and regional Edward R. Murrow Awards.

<h1>What I've been up to</h1>

<div class="activities">
{% for pub in site.data.combined %}
    {% if pub.page == "Updates" and pub.show_flag == "TRUE" %}
        {% if pub.url %}
            <h3><a href="{{ pub.url }}">{{ pub.title }}</a></h3>
        {% else %}
            <h3>{{ pub.title }}</h3>
        {% endif %}
        <h6><em>With {{ pub.organization }} on {{ pub.start_date }}</em></h6>
    {% endif %}
{% endfor %}
</div>
