---
layout: default
title: About The Contest
permalink: '/rubs-and-suds/'
hide_title: true

items:
  style: 1
  size: medium
  onscroll: fade-in

spotlight_b:
  style: 1
  orient: left
  content_align: left
  onscroll_image: fade-in

spotlight_a:
  style: 1
  orient: right
  content_align: left
  onscroll_image: fade-in
---

<div>
  {% capture content %}
  <h2>Rebel Rubs</h2>
  <p>
    Hand made in small batches in Portland Oregon, Rebel Rubs is an all organic and all natural leather conditioner. Made from a bee's wax base, it contains shelf stable coconut oil. It's safe to use on lightly colored leathers like white and tan and it will not darken the leather. It's safe to use on softer leathers like garments and boots that do not take a shine. It protects against mold and mildew and helps to waterproof leather. To use, simply apply a small portion with your hands and massage into the leather.
  </p>

  <p>
    Allergy Notification: Contains Coconut.
  </p>

  <a href="/shop" class="button">Buy Now</a>

  {% endcapture %}
  {% include components/spotlight.html settings=page.spotlight_b content=content image="/images/product/rubs.jpg"  %}

  {% capture content %}
  <h2>Rebel Suds</h2>
  <p>
    Rebel Suds is hand made in Portland Oregon. This glycerine based soap is perfect for all types of leather. It cleans, disinfects, deodorizes, and protects against mold, mildew, and fungus. To use it, just lather up a brush and apply to the leather. Wipe it off after you're done. It's as simple as that.
  </p>

  <a href="/shop" class="button">Buy Now</a>

  {% endcapture %}
  {% include components/spotlight.html settings=page.spotlight_a content=content image="/images/product/soap.jpg"  %}
</div>

<section class="wrapper style3 small align-center">
  <div class="inner">
    <br />
    <h2>Testimonials</h2>

    <p>Rebel Suds and Rubs are used by bootblacks all over the United States. Here's what they have had to say...</p>
    {% assign content = "" | split: "" %}

      {% capture x %}
        <h3>Dara</h3>
        <h5>International Ms Bootblack 2014 </h5>
        <br />
        <p>"Rebel Suds quickly became my go-to leather soap from the first time I used it. It produces a rich lather for whisking dirt away, and wipes off leaving no residue. It’s the only leather cleaner for me!"</p>
        <br />

      {% endcapture %}
      {% assign content = content | push: x %}

      {% capture x %}
        <h3>Erick Joseph</h3>
        <h5>International Mr Bootblack 2016 </h5>
        <br />
        <p>"I LOOOOOOVE Rebel Rubs and Suds! Only product I used during my year as IMBB2016. It leaves the leather not only looking fresh and clean but it smells INCREDIBLE."</p>
        <br />
      {% endcapture %}
      {% assign content = content | push: x %}

      {% capture x %}
        <h3>Monica Glass</h3>
        <br />
        <p>"You used your rub on my green leather shoes and it moisturized and conditiond them better than anything i could have hoped for! Thank you!"</p>
        <br />
      {% endcapture %}
      {% assign content = content | push: x %}

      {% capture x %}
        <h3>Teagan</h3>
        <h5>International Ms Bootblack 2018 </h5>
        <br />
        <p> "Lucky's products are a staple in my bootblack kit. Rebel rub's is my most versatile conditioner. It's for that reason that it's become the only I carry when I go on trips. When packing space is tight, Rebel Rubs is my choice. I truely can use it on just about anything I need to condition." </p>
        <br />

      {% endcapture %}
      {% assign content = content | push: x %}

      {% capture x %}
        <h3>Geoff Millard</h3>
        <h5>California State Bootblack 2018 </h5>
        <br />
        <p>"No Bootblack kit is really complete without Rebel Rubs. It will condition the oldest pair of boots that sits in your stand with the same ease it conditions any exotics you’ll see. Being colorless it preserves fantastic colors in your leathers and stitches, even leaving your whites perfectly white with no yellowing over time."</p>
        <br />
      {% endcapture %}
      {% assign content = content | push: x %}

      {% capture x %}
        <h3>Moxie Minion</h3>
        <h5>Northwest Bootblack 2018</h5>
        <br />
        <p>"Within moments of having my corset done using Lucky Suds, I was tracking him down to buy my own jar. It left the leather feeling more soft and supple than I had managed to get using other products. A year and a half later both Suds and Rubs are my go to products now. The most important part for me, being a person who is rather scent sensitive, is neither product is overly fragrant. You are left with clean, soft leather that doesn’t smell like chemicals. All the stars go to Lucky for his Suds and Rubs."</p>
        <br />
      {% endcapture %}
      {% assign content = content | push: x %}

    {% include components/items.html settings=page.items items=content %}
  </div>
</section>
