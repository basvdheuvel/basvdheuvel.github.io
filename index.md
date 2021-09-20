---
layout: default
---

Since October 2019 I am a PhD student at the [Bernoulli
Institute](https://www.rug.nl/research/bernoulli/), [University of
Groningen](https://www.rug.nl/) (NL) for the VIDI project [Unifying Correctness
for Communicating Software](https://www.jperez.nl/vidi) under the supervision of
[Jorge A. Pérez](https://www.jperez.nl/).

<hr />

<h3>Selected Publications</h3>

* 2021: [AGERE 2021](https://2021.splashcon.org/home/agere-2021) with Jorge A. Pérez
  <br />
  [Towards Practical Protocol Verification via Minimal Orchestration in ACP](https://2021.splashcon.org/details/agere-2021-papers/1/Towards-Practical-Protocol-Verification-via-Minimal-Orchestration-in-ACP)
  [(Extended Abstract)]({{site.url}}{{site.baseurl}}/assets/static/agere21.pdf)

* 2021: Draft with Jorge A. Pérez
  <br />
  [A Decentralized Analysis of Multiparty Protocols](https://arxiv.org/abs/2101.09038)

* 2020: [PLACES 2020](http://places20.by.di.fc.ul.pt/) with Jorge A. Pérez
  <br />
  [Session Type Systems based on Linear Logic: Classical versus Intuitionistic](https://cgi.cse.unsw.edu.au/~eptcs/paper.cgi?PLACES2020.1.pdf)
  <br />
  [Presentation]({{site.lfs_prefix}}/assets/static/types2020.mp4) at [TYPES 2020](https://types2020.di.unito.it/)

{% for post in site.posts %}
  <div id="post-short">
    <a href="{{site.url}}{{site.baseurl}}{{post.url}}">
      <h3>{{post.title}}</h3>
    </a>
    <i>posted on {{ post.date | date: "%-d %b %Y" }}</i>
    <p>
      {% if post.excerpt %}
        {{ post.excerpt }}
      {% else %}
        {{ post.content }}
      {% endif %}
    </p>
  </div>
{% endfor %}
