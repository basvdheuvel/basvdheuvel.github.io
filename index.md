---
layout: default
---
I'm a postdoctoral researcher at [Karlsruhe University of Applied Sciences](https://h-ka.de) (DE) and the [University of Freiburg](https://www.uni-freiburg.de/) (DE; my office is here), since November 2023.
Together with [Peter Thiemann](http://www2.informatik.uni-freiburg.de/~thiemann/) and Martin Sulzmann, I work on the trace-based analysis of data races in concurrent programs.

I did my PhD at the [Bernoulli
Institute](https://www.rug.nl/research/bernoulli/), [University of
Groningen](https://www.rug.nl/) (NL) for the VIDI project [Unifying Correctness
for Communicating Software](https://www.jperez.nl/vidi) under the supervision of
[Jorge A. Pérez](https://www.jperez.nl/), from October 2019 until September 2023.
I will defend my thesis on 2024-04-02 12:45, at University of Groningen's [Academy Building](https://maps.app.goo.gl/mZbXtoFdBy1Lcb737); you can find an extended preprint of my dissertation on [ArXiv](https://arxiv.org/abs/2402.09595).

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

<h4>Conferences</h4>

* 2023: [APLAS 2023](https://conf.researchr.org/home/aplas-2023) with Joseph W. N. Paulus, [Daniele Nantes-Sobrinho](https://vtss.doc.ic.ac.uk/people/nantes.html) and [Jorge A. Pérez](https://www.jperez.nl/)
    <br />
    Typed Non-determinism in Functional and Concurrent Calculi
    <br />
    \[
    [PDF (extended version)](https://arxiv.org/pdf/2205.00680.pdf)
    \]

* 2023: [RV 2023](https://rv23.csd.auth.gr/) with [Jorge A. Pérez](https://www.jperez.nl/) and Rares A. Dobre
    <br />
    Monitoring Blackbox Implementations of Multiparty Session Protocols
    <br />
    \[
    [PDF (extended version)](https://arxiv.org/pdf/2306.04204.pdf)
    \]

* 2022: [OOPSLA 2022](https://2022.splashcon.org/track/splash-2022-oopsla) with [Emanuele D'Osualdo](https://www.emanueledosualdo.com/), [Dan Frumin](https://groupoid.moe/) and [Jorge A. Pérez](https://www.jperez.nl/)
    <br />
    A Bunch of Sessions: A Propositions-as-Sessions Interpretation of Bunched Implications in Channel-Based Concurrency
    <br />
    \[
    [PDF](https://dl.acm.org/doi/pdf/10.1145/3563318)
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
