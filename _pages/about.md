---
permalink: /
title: "About Me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

<h2 id="about">About</h2>

I am a PhD student in Computer Science at [Rensselaer Polytechnic Institute](https://www.rpi.edu/), advised by [Dr. Mohammad Mohammadi Amiri](https://mmamiri.github.io/). My research focuses on **trustworthy and privacy-preserving AI**, with emphasis on machine unlearning, multi-agent LLM safety, representation-level privacy control, and alignment.

Alongside academic research, I collaborate with industry teams to translate research into deployable systems, including current work on secure KV-cache sharing in multi-agent LLM architectures.

I hold a B.Sc. in Electrical Engineering with a minor in Computer Science from the [National University of Sciences and Technology (NUST)](https://nust.edu.pk/).

<h2 id="research">Research Focus</h2>

* Machine unlearning and selective forgetting for foundation models
* Privacy and leakage control in sequential multi-agent LLM pipelines
* Alignment-preserving fine-tuning and safety-retention under adaptation
* Robust evaluation of harmful/manipulative model behavior
* Privacy-aware data valuation and trustworthy AI systems

<h2 id="publications">Publications</h2>

{% for post in site.publications reversed %}
* [{{ post.title }}]({{ post.url }}) — {{ post.venue }}
{% endfor %}

<h2 id="talks">Talks</h2>

{% for post in site.talks reversed %}
* [{{ post.title }}]({{ post.url }}){% if post.venue %} — {{ post.venue }}{% endif %}
{% endfor %}

<h2 id="teaching">Teaching</h2>

{% for post in site.teaching reversed %}
* [{{ post.title }}]({{ post.url }})
{% endfor %}

<h2 id="contact">Profiles</h2>

* [Google Scholar]({{ site.author.googlescholar }})
* [ResearchGate]({{ site.author.researchgate }})
* [LinkedIn](https://www.linkedin.com/in/{{ site.author.linkedin }})
* [GitHub](https://github.com/{{ site.author.github }})
