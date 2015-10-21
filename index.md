---
layout: default
---

<div class="pure-g">
<div class="pure-u-1 pure-u-md-2-3">
  <p>Crowdsourcing is an established approach for producing and analyzing data that can be represented as a human-assisted computation system.</p>

  <p><strong>Mechanical Tsar</strong> is an engine for running a highly customizable hosted crowdsourcing platform controlling the entire annotation process including such elements as task allocation, worker ranking and result aggregation. Read the <a href="/about">About</a> page for details.</p>
</div>
<div class="pure-u-1 pure-u-md-1-3 align-center">
  <img src="https://media.githubusercontent.com/media/mtsar/mtsar.github.io/master/media/logo.png" alt="Mechanical Tsar" style="height: 10em">
</div>
</div>

## Happy Users

The engine is successfully used by several research projects.

* [Yet Another RussNet](http://russianword.net/en/), a large open WordNet-like thesaurus for Russian through crowdsourcing, founded in 2013.
* [RUSSE](http://russe.nlpub.ru/), the first international workshop on Russian semantic similarity evaluation, founded in 2014.

Please [note us](https://github.com/mtsar/mtsar.github.io/issues) if you want to be mentioned on this page.

## Latest News

<ul>
{% for post in site.posts limit:5 %}
<li>
<span class="post-meta">{{ post.date | date: "%b %-d, %Y" }}</span>
  <a class="post-link" href="{{ post.url | prepend: site.baseurl }}">{{ post.title }}</a>
</li>
{% endfor %}
</ul>

Other news are available on the [Posts](/posts) page. Also, we have an [RSS feed](/posts.xml).

## Get Started

The simplest way to start using Mechanical Tsar is pulling our Docker image. Just consult our [Running on Docker](https://github.com/dustalov/mtsar/wiki/Running-on-Docker) guide to get started. It is also possible to deploy the engine on [Heroku](https://github.com/dustalov/mtsar/wiki/Running-on-Heroku), on [systemd](https://github.com/dustalov/mtsar/wiki/Running-on-systemd) and on a regular [Linux](https://github.com/dustalov/mtsar/wiki/Running) box.

More documentation is available in English on [GitHub Wiki](https://github.com/dustalov/mtsar/wiki) and on [NLPub](https://nlpub.ru/Mechanical_Tsar) in Russian. In case if you need support, ask a question on [NLPub Q&A](http://qa.nlpub.ru/c/mtsar) either in Russian or English.

## Citation

If you publish work that uses Mechanical Tsar, please cite it as follows.

* Ustalov, D.: [A Crowdsourcing Engine for Mechanized Labor](http://dx.doi.org/10.15514/ISPRAS-2015-27%283%29-25). Proceedings of the Institute for System Programming, Vol. 27(3), 351–364 (2015)

{% highlight latex %}
{% raw %}
@article{Ustalov:15:ispras,
  author    = {Ustalov, D.},
  title     = {{A Crowdsourcing Engine for Mechanized Labor}},
  journal   = {Proceedings of the Institute for System Programming},
  pages     = {351--364},
  volume    = {27},
  number    = {3},
  year      = {2015},
  address   = {Moscow},
  publisher = {ISP RAS},
  issn      = {2220-6426},
  doi       = {10.15514/ISPRAS-2015-27(3)-25},
  language  = {english},
}
{% endraw %}
{% endhighlight %}

## Copyright

Copyright &copy; 2014&ndash;{{ site.time | date: '%Y' }} [Dmitry Ustalov].

[Dmitry Ustalov]: https://ustalov.name/

<a href="https://github.com/mtsar"><img style="position: absolute; top: 0; right: 0; border: 0; width: 149px; height: 149px;" src="//aral.github.io/fork-me-on-github-retina-ribbons/right-graphite@2x.png" alt="Fork me on GitHub"></a>
