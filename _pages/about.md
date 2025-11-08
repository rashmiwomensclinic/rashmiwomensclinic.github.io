---
permalink: /
# title: "Academic Pages is a ready-to-fork GitHub Pages template for academic personal websites"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

**Dr. Suchith Hoblidar** is a Consultant Obstetrician and Gynaecologist, Laparoscopic Surgeon and Infertility Specialist with over 19 years of experience and committed to providing excellent patient care. She is a professor in the department of OBG at **AJ Institute of Medical Sciences and Research Centre**, and a consultant Obstetrician & Gynaecologist, Laparoscopic Surgeon and Infertility Specialist.  She has expertise in **vaginal deliveries**, **scarless hysterectomy**, **laparoscopic surgeries**, **hysteroscopy** and **gynaec cancer surgeries**.

She started **Rashmi Women's and Multi-Speciality Clinic** in 2024 and provides comprehensive services across pregnancy & childbirth care, fertility & reproductive health, gynaecological procdures, and cervical & gynaecological cancer care.  

The clinic is located at 'Vishram' Ground Floor, Nairkere road, near Brahmagiri Circle, Udupi.  
You can walk in or schedule an appointment by phone at [**76765 81025**](tel:7676581025).  
<!-- ![Clinic photo](/images/IMG_1530.JPG) -->
<img src="{{ site.baseurl }}/images/IMG_1530.JPG" alt="Photo of the Clinic" style="max-width: 50%; height: auto; margin: 1.5rem 0;">  
<a href="https://maps.app.goo.gl/5PLQ7hBXHrg5dYFt5" target="_blank" rel="noopener noreferrer">Location on Google Maps</a>

## Latest Articles

{% assign latest_posts = site.posts | limit: 5 %}

<ul>
{% for post in latest_posts %}
  <li>
    <a href="{{ post.url | relative_url }}">{{ post.title }}</a> 
    <span class="text-muted small">({{ post.date | date: "%B %-d, %Y" }})</span>
  </li>
{% endfor %}
</ul>