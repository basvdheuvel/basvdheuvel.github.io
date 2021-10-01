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

* 2021: [AGERE 2021](https://2021.splashcon.org/home/agere-2021) with [Jorge A. Pérez](https://www.jperez.nl/)
  <br />
  Towards Practical Protocol Verification via Minimal Orchestration in ACP
  <br />
  \[
  [PDF (Extended Abstract)]({{site.url}}{{site.baseurl}}/assets/static/agere21.pdf)
  \]

* 2021: [ICE 2021](https://www.discotec.org/2021/ice) with [Jorge A. Pérez](https://www.jperez.nl/)
  <br />
  Deadlock Freedom for Asynchronous and Cyclic Process Networks
  <br />
  \[
  [PDF](https://cgi.cse.unsw.edu.au/~eptcs/paper.cgi?ICE2021.3.pdf)
  \]

* 2021: Draft with [Jorge A. Pérez](https://www.jperez.nl/)
  <br />
  A Decentralized Analysis of Multiparty Protocols
  <br />
  \[
  [PDF](https://arxiv.org/pdf/2101.09038)
  \]

* 2020: [PLACES 2020](http://places20.by.di.fc.ul.pt/) with [Jorge A. Pérez](https://www.jperez.nl/)
  <br />
  Session Type Systems based on Linear Logic: Classical versus Intuitionistic
  <br />
  \[
  [PDF](https://arxiv.org/pdf/2004.01320v1)
  \]

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
