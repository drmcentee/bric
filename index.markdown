---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: splash
permalink: /
hidden: false
header:
  overlay_color: "#8c8c8c"
  actions:
    - label: "Book Now"
      url: "https://www.eventbrite.co.uk/e/bronchoscopy-for-intensive-care-bric-course-tickets-35202715269"

feature_row1:
  - image_path: /assets/images/procedure.jpeg
    alt: "Expert Tuition"
    title: "Expert Tuition"
    excerpt: "Learn indications, methodology and how to handle complications from experts in the field"
  - image_path: /assets/images/learn_anatomy.jpeg
    alt: "Anatomy"
    title: "Anatomy & Physiology"
    excerpt: "Relevant theorhetical knowledge to get you going as quickly as possible"
  - image_path: /assets/images/bronchoscope.jpg
    alt: "Practical"
    title: "Practical"
    excerpt: "Multiple practical hands-on sessions with mutliple modalities to practice under expert tuition and advice"

gallery:
  - image_path: /assets/images/ambu_logo.png
    alt: "Ambu"
  - image_path: /assets/images/olympus_logo.png
    alt: "Olympus"
  - image_path: /assets/images/pentax_logo.jpeg
    alt: "Pentax"
  - image_path: /assets/images/boston_scientific_logo.png
    alt: "Boston Scientific"
  - image_path: /assets/images/fisher_paykel_logo.jpeg
    alt: "Fisher Paykel"
  - image_path: /assets/images/cw_logo.png
    alt: "CW"
---

The Bronchoscopy for Intensive Care (BrIC) Course is a multidisciplinary one-day hands-on training bronchoscopy course for those involved in acute care of patients (anaesthetics, intensive care, emergency medicine and acute medicine).  

It is designed to improve bronchoscopy skills for a variety of indications, including airway haemorrhage and percutaneous tracheostomy.  The course is predominantly workshop based, with hands-on practice and dedicated bronchoscopy simulator time.  

Teaching will be delivered by a highly experienced international faculty and includes the opportunity to test established and new devices.

{% include feature_row id="feature_row1" %}

## Recent Posts
{% for post in site.posts limit: 5 %}
  {{ post.date | date: "%-d %B %Y" }} - [{{post.title}}]({{ post.url }})
{% endfor %}

## Supported by:
{% include gallery %}

