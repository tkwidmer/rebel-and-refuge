---
layout: default
title: About The Contest
permalink: '/about/'
hide_title: true

spotlight_a:
  style: 1
  orient: right
  content_align: left
  onscroll_image: fade-in

spotlight_b:
  style: 1
  orient: left
  content_align: left
  onscroll_image: fade-in
---
<div>
  {% capture content %}
  <h2>Lucky Rebel</h2>
  <p>
    Lucky Rebel is International Mr Bootblack 2018. He's is from Portland, Oregon. Lucky has been caring for leather since he was a kid. He learned how to take care of leather from his father, who rode motorcycles. Lucky created his Rubs and Suds back in 2015, for his wife Micky because he wasn't satisfied with the performance of the current products available when working on lighter colored leathers. As a artisan, Lucky believes in purchasing locally to develop his product. It's important for him to support other small business based in Portland. Lucky's product is the solution you are looking for cleaning and conditioning your soft leathers.
  </p>
  {% endcapture %}
  {% include components/spotlight.html settings=page.spotlight_b content=content image="/images/headshots/lucky.jpg"  %}
</div>
