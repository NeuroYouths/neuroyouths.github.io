---
layout: splash
permalink: /
header:
  overlay_filter: "rgba(252,255,175, 0.1)"
  overlay_image: "/assets/images/banner-2.png"
  permalink: /home-page/
  cta_label: "<i class='fa fa-group'></i>Sign Up Now to Participate (Ages 12-18) "
  cta_url: "https://georgetown.az1.qualtrics.com/jfe/form/SV_bI5IEZvdEQouj2Z"
  caption: "This project is funded by a research dissertation grant from the National Institute of Justice"
excerpt: 'Mapping young brains to reveal the biology of playing, learning and growing in the city.'
intro:
  - image_path: /assets/images/banner-youth-flux-2.png
    alt: "The Teen Brain in Flux"
    title: "How We Image the Developing Brain"
    excerpt: "Our brain imaging research shows major changes in brain shape, function and ability throughout the teenage years. These changes can serve to either promote or prevent life success."
    url: "/teenflux/"
    btn_label: "Learn More"
  - image_path: /assets/images/mm-free-feature.png
    alt: "Resources for Violence Prevention"
    title: "Resources for Violence Prevention"
    excerpt: "Community violence is a public health issue and should be treated as such, prevention will always be the most effective strategy."
    url: "https://www.cdc.gov/violenceprevention/index.html"
    btn_label: "Explore Our Resources"
social:
  - excerpt: '[<i class="fa fa-twitter"></i> @neuroyouths](https://twitter.com/neuroyouths){: .btn .btn--twitter} [<i class="fa fa-paypal"></i> Support Our Research](https://www.paypal.me/ShadyElDamaty){: .btn}'
  - excerpt: '{::nomarkdown}<iframe style="display: inline-block;" src="https://ghbtns.com/github-btn.html?user=neuroyouths&repo=NeuroYouths&type=star&count=true&size=large" frameborder="0" scrolling="0" width="160px" height="30px"></iframe> <iframe style="display: inline-block;" src="https://ghbtns.com/github-btn.html?user=neuroyouths&repo=NeuroYouths&type=fork&count=true&size=large" frameborder="0" scrolling="0" width="158px" height="30px"></iframe>{:/nomarkdown}'  
---

The NeuroYouths Project ([Award # NIJ 2016-R2-CX-0019](https://www.nij.gov/funding/awards/pages/award-detail.aspx?award=2016-R2-CX-0019)) is a National Institute of Justice (NIJ)-funded community-engaged dissertation research study on neighborhood health, violence and youth brain development. 

[Meet our Team](/about/)

## Community-Engaged Research
Our team seeks to shed light on how young brains grow and develop in the city. Developing brains are exceptionally plastic - showing great capability for rapid adaptation to overcome challenges and quickly learning by trial and error to acquire new skills. Images of the brain captured with Magnetic Resonance Imaging (MRI) have shown considerable changes in activity and structure related to the heightened plasticity in teenagers.

## [Families are Invited to Participate in our Study](/study_information/)
We are seeking families with teens aged 12-18 in the Washington, D.C metro area from communities challenged with violence to participate in our study.


{% include feature_row id="intro" %}

<!-- ## Tools for Action
### The Young Hacker's Cookbook for Positive Social Change
Cycles of violence in the District of Columbia have been documented since the city first began collecting crime reports in 1960. Today, young men and women ages 12-20 are estimated to be **~3x** as likely to be a victim of violence in the District of Columbia. Understanding the history and character of crime is the first step for effective neighborhood policing.
- image_path: /assets/images/dc-crime-map-banner.png
    alt: "Youth Victims in DC"
    title: "Hack the Violence! DC"
    excerpt: "Self-determination via technological empowerment is the most effective catalyst for social, health, governance and community-based innovation. Data is mightier than the sword. See our tutorials on getting started with the Open DC datasets to visualize maps of crime, community services, and other points of interest throughout the city."
    url: "/crimestats/"
    btn_label: "See DC Open Data Tutorials"
 -->

<!-- ### More Coming Soon!

A Brief History of Violence in the District of Columbia.  You have to understand the underlying historical threads of the social fabric behind crime in the district before you can do anything about it. (Ask for contributors?) -->

<!-- Resources for violence prevention. Crime Map, FBI UCR, CDC instruments, Office of Neighborhood Life, Mental Health? -->

<!-- {% include feature_row id="social" %} -->

__________________________________________________________________


<h3 class="archive__subtitle">{{ site.data.ui-text[site.locale].recent_posts | default: "Recent Posts" }}</h3>

{% for post in site.posts %}
  {% include archive-single.html %}
{% endfor %}
