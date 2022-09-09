---
layout: default
---

Since October 2019 I am a PhD student at the [Bernoulli
Institute](https://www.rug.nl/research/bernoulli/), [University of
Groningen](https://www.rug.nl/) (NL) for the VIDI project [Unifying Correctness
for Communicating Software](https://www.jperez.nl/vidi) under the supervision of
[Jorge A. Pérez](https://www.jperez.nl/).

Currently, I am visiting with [Stephanie Balzer](https://www.cs.cmu.edu/~balzers/) at [Carnegie Mellon University](https://www.cmu.edu/) in Pittsburgh, Pennsylvania, USA.

<hr />

<h3>Selected Publications</h3>

<h4>Journals</h4>

* 2022: [Science of Computer Programming](https://www.sciencedirect.com/journal/science-of-computer-programming) with [Jorge A. Pérez](https://www.jperez.nl/)
    <br />
    A decentralized analysis of multiparty protocols
    <br />
    \[
    [PDF](https://www.sciencedirect.com/science/article/pii/S0167642322000739/pdfft?md5=a96ed53547393c15d62a057ca3f1c711&pid=1-s2.0-S0167642322000739-main.pdf)
    \]

<h4>Workshops</h4>

* 2022: [EXPRESS/SOS 2022](https://express-sos2022.github.io/) with  [Jorge A. Pérez](https://www.jperez.nl/)
  <br />
  Asynchronous Functional Sessions: Cyclic and Concurrent
  <br />
  \[
  [PDF](https://cgi.cse.unsw.edu.au/~eptcs/paper.cgi?EXPSOS22.5.pdf)
  \]

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
