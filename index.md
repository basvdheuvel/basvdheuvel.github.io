---
layout: default
---
I'm a postdoctoral researcher at [HKA Karlsruhe](https://h-ka.de) (DE) and the [University of Freiburg](https://www.uni-freiburg.de/) (DE; my office is here), since November 2023.
Together with [Peter Thiemann](http://www2.informatik.uni-freiburg.de/~thiemann/) and Martin Sulzmann, I work on the trace-based analysis of data races in concurrent programs.

I did my PhD at the [Bernoulli
Institute](https://www.rug.nl/research/bernoulli/), [University of
Groningen](https://www.rug.nl/) (NL) for the VIDI project [Unifying Correctness
for Communicating Software](https://www.jperez.nl/vidi) under the supervision of
[Jorge A. Pérez](https://www.jperez.nl/), from October 2019 until September 2023.
In April 2024 I successfully defended my dissertation, titled "Correctly Communicating Software: Distributed, Asynchronous, and Beyond" and available [here](https://research.rug.nl/en/publications/correctly-communicating-software-distributed-asynchronous-and-bey).

<hr />

### Selected Publications

#### Journals

* 2024 (to appear): [Logical Methods in Computer Science (LMCS)](https://lmcs.episciences.org/) with [Jorge A. Pérez](https://www.jperez.nl/)
    <br />
    Asynchronous Session-Based Concurrency: Deadlock-freedom in Cyclic Process Networks
    <br />
    \[
    [PDF (preprint)](https://arxiv.org/pdf/2111.13091)
    \]

* 2024: [Journal of Logical and Algebraic Methods in Programming (JLAMP)](https://www.sciencedirect.com/journal/journal-of-logical-and-algebraic-methods-in-programming) with [Jorge A. Pérez](https://www.jperez.nl/)
    <br />
    Comparing Session Type Systems derived from Linear Logic
    <br />
    \[
    [PDF (preprint)](https://arxiv.org/pdf/2401.14763)
    \]

* 2022: [Science of Computer Programming](https://www.sciencedirect.com/journal/science-of-computer-programming) with [Jorge A. Pérez](https://www.jperez.nl/)
    <br />
    A decentralized analysis of multiparty protocols
    <br />
    \[
    [PDF](https://www.sciencedirect.com/science/article/pii/S0167642322000739/pdfft?md5=a96ed53547393c15d62a057ca3f1c711&pid=1-s2.0-S0167642322000739-main.pdf)
    \]

#### Conferences

* 2024: [ECOOP](https://conf.researchr.org/home/issta-ecoop-2024) with [Farzaneh Derakhshan](http://gauss.cs.iit.edu/~fderakhshan/) and [Stephanie Balzer](https://www.cs.cmu.edu/~balzers/)
    <br />
    Information Flow Control in Cyclic Process Networks
    <br />
    \[
    [PDF (extended version)](https://arxiv.org/pdf/2407.02304)
    \]

* 2024: [MFPS](https://oxford24.github.io/) with [Daniele Nantes-Sobrinho](https://vtss.doc.ic.ac.uk/people/nantes.html), Joseph W. N. Paulus and [Jorge A. Pérez](https://www.jperez.nl/)
    <br />
    Typed Non-determinism in Concurrent Calculi: The Eager Way
    <br />
    \[
    [PDF (preprint)](https://oxford24.github.io/assets/mfps-papers/MFPS24-9.pdf)
    \]

* 2023: [APLAS](https://conf.researchr.org/home/aplas-2023) with Joseph W. N. Paulus, [Daniele Nantes-Sobrinho](https://vtss.doc.ic.ac.uk/people/nantes.html) and [Jorge A. Pérez](https://www.jperez.nl/)
    <br />
    Typed Non-determinism in Functional and Concurrent Calculi
    <br />
    \[
    [PDF (extended version)](https://arxiv.org/pdf/2205.00680.pdf)
    \]

* 2023: [RV](https://rv23.csd.auth.gr/) with [Jorge A. Pérez](https://www.jperez.nl/) and Rares A. Dobre
    <br />
    Monitoring Blackbox Implementations of Multiparty Session Protocols
    <br />
    \[
    [PDF (extended version)](https://arxiv.org/pdf/2306.04204.pdf)
    \]

* 2022: [OOPSLA](https://2022.splashcon.org/track/splash-2022-oopsla) with [Emanuele D'Osualdo](https://www.emanueledosualdo.com/), [Dan Frumin](https://groupoid.moe/) and [Jorge A. Pérez](https://www.jperez.nl/)
    <br />
    A Bunch of Sessions: A Propositions-as-Sessions Interpretation of Bunched Implications in Channel-Based Concurrency
    <br />
    \[
    [PDF](https://dl.acm.org/doi/pdf/10.1145/3563318)
    \]

#### Workshops

* 2022: [EXPRESS/SOS](https://express-sos2022.github.io/) with  [Jorge A. Pérez](https://www.jperez.nl/)
  <br />
  Asynchronous Functional Sessions: Cyclic and Concurrent
  <br />
  \[
  [PDF](https://cgi.cse.unsw.edu.au/~eptcs/paper.cgi?EXPSOS22.5.pdf)
  \]

* 2021: [ICE](https://www.discotec.org/2021/ice) with [Jorge A. Pérez](https://www.jperez.nl/)
  <br />
  Deadlock Freedom for Asynchronous and Cyclic Process Networks
  <br />
  \[
  [PDF](https://cgi.cse.unsw.edu.au/~eptcs/paper.cgi?ICE2021.3.pdf)
  \]

* 2020: [PLACES](http://places20.by.di.fc.ul.pt/) with [Jorge A. Pérez](https://www.jperez.nl/)
  <br />
  Session Type Systems based on Linear Logic: Classical versus Intuitionistic
  <br />
  \[
  [PDF](https://arxiv.org/pdf/2004.01320v1)
  \]
  
### Academic Activity

* 2024: [ICE](https://www.discotec.org/2024/ice) program committee member, *awarded best program committee member*
* 2024: [FORTE](https://www.discotec.org/2024/forte) artefact evaluation committee member

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
