---
layout: default
---

<!-- Information -->
<div class="jumbotron information">

    <p> For AI and ML systems aimed to assist decision-making in real-world scenarios, it is crucial to perform complex reasoning under uncertainty <b>reliably and efficiently</b>. However, contemporary machine learning is often criticized as being sensitive to data-perturbations, lacking guarantees on their predictions, and having little or no causal and symbolic reasoning capabilities. Further underpinning the relevance of these challenges, various regulatory bodies have released statements and frameworks aimed at building trustworthy AI.</p>

    <p>The field of tractable probabilistic models (TPMs) is a very appealing approach for many of these challenges, as TPMs enable reliable (<b>exact or coming with approximation guarantees</b>) and efficient reasoning for a wide range of tasks, by design. The spectrum of TPMs consists of a wide variety of techniques including models with tractable likelihoods (e.g., <b>normalizing flow</b> and <b>autoregressive models</b>), tractable marginals (e.g., <b>bounded-treewidth models</b> and <b>determinantal point processes</b>), and more complex tractable reasoning tasks (e.g., <b>circuits</b>) and is dynamically evolving.</p>

    <p>This year’s workshop on <b>Tractable Probabilistic Modeling</b> aims to highlight the connection between <b>trustworthy artificial intelligence</b> (in a broad sense) and tractable reasoning. The workshop aims to <b>highlight recent advancements in the field</b> of TPMs and their <b>potential impact in settings of trustworthy AI</b> (e.g. fairness, robustness, causality, neuro-symbolic AI).</p>
</div>


<!-- Content -->

<h2>Confirmed Speakers</h2>

<div class="row justify-content-center people-widget text-center">

{% for item in site.data.speakers  %}

<div class="col-12 col-sm-12 col-md-6 col-lg-4 col-xl-4">
  <a href="{{ item.url }}">
  <div class="team-member">

    {% if item.img %}
    <img src="{{ site.baseurl }}/assets/speakers/{{ item.img }}" class="img-responsive img-circle avatar-x2 avatar-circle" alt="">
    {% else %}
    <div class="avatar-x2 avatar-circle" style="background: #ddd;">
      <i class="fa fa-user" style="font-size: 220px; color: #eee; margin-top:20px;"></i>
    </div>
    {% endif %}
    <h4>{{ item.name }}</h4>
    <p class="text-muted">{{ item.affiliation }}</p>
  </div>
  </a>
</div>

{% endfor %}

</div>

<h2>Workshop Program</h2>
The workshop will happen in person at the Universitat Pompeu Fabra, Barcelona, Spain on July 19th, 2024.

Details TBA.
<!-- The workshop <a href="/program">program</a> is online! -->

<h2>Call for Papers</h2>
<p>TBA</p>

<p>
<br/>
See <a href="/cfp">submission instructions</a> for details.</p>

<h2>Important Dates</h2>

<p>All times are end of day AOE.</p>

<ul>

{% for item in site.deadlines  %}

  <li>{{ item.item }}: <strong>{{ item.date }}</strong></li>

{% endfor %}

</ul>

<h2>Organizers</h2>

<div class="row justify-content-center people-widget text-center">

<div class="col-12 col-sm-4 col-md-3 col-lg-2 col-xl-2">
  <a href="{{ item.url }}">
  <div class="team-member">
    <!-- <img src="{{ site.baseurl }}/assets/speakers/{{ item.img }}" class="img-responsive img-circle avatar avatar-circle" alt=""></br> -->
    <strong>{{ item.name }}</strong>
    <!-- <p class="text-muted">{{ item.affiliation }}</p> -->
  </div>
  </a>
</div>

</div>


<ul>

{% for item in site.data.organizers  %}

  <li><a href="{{ item.url }}"><strong>{{ item.name }}</strong></a>, {{ item.affiliation }}</li>

{% endfor %}

</ul>




