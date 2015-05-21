---
layout: page
title: "speaking"
date: 2015-05-19 16:16
comments: true
sharing: true
footer: true
---

I've always perceived sharing knowledge as a way of giving back to the community for what I've learned from it. That's why I love speaking and sharing what I've learned over the course of my career.

## Talks

Here's a list of my talks I've given over the course of past years.


<div class="speaking">
<ul>

{% for talk in site.data.talks.past_talks %}

<li class="speaking">
<h3> {{ talk.name }} </h3>
  <div class="container-fluid">
    <div class="row">
     <div class="col-md-8">
       <p>
        <i class="fa fa-calendar"></i> {{ talk.dates }}
       </p>
       <p>
        <i class="fa fa-map-marker"></i> {{ talk.location }}
       </p>
       <p>
        <i class="fa fa-users"></i> <a href="{{ talk.url }}">{{ talk.conference }}</a>
       </p>
       <p>
        <i class="fa fa-file-o"></i> <a href="{{ talk.slides }}">Presentation</a>
       </p>
     </div>
   </div>
  </div>
</li>

{% endfor %}

</ul>
</div>

## Workshops

Apart from being an active speaker I also run a series of workshops. Here's a list of the ones I've run in the past:

* [UICollectionView Berlin](https://speakerdeck.com/paweldudek/custom-collection-view-layouts-2)
* TDD Wroclaw
* [TDD Gdansk](https://speakerdeck.com/paweldudek/tdd-workshop-gdansk)
* [UICollectionView Krakow](https://speakerdeck.com/paweldudek/custom-collection-view-layouts-1)
* TDD Minsk
* [UICollectionView Warsaw](https://speakerdeck.com/paweldudek/custom-collection-view-layouts)
* TDD Berlin
* [TDD Cracow](https://speakerdeck.com/paweldudek/tdd-workshop)
* TDD Warsaw

## Videos

Here you can check out recording of the talks I've given in the past.

{% youtube -QqEFOklw0o %}

{% youtube EblLyiRX230 %}
