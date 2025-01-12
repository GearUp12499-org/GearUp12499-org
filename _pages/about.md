---
title: "Gear Up - About Us"
layout: textlay
excerpt: "Gear Up - About Us"
sitemap: false
permalink: /about/
---

# About Gear Up

<br>

**Gear Up is a FIRST Tech Challenge robotics team based in San Diego, California.**

The team had its humble origins in 2013 as a group of elementary school students interested in robotics. We started our journey with the FIRST Lego League in third grade, competing against other teams with robots built our of LEGOs. As we developed our technical skillset and learned how to work together, we progressed as a team to the FIRST Tech Challenge (FTC). In a larger competition with more advanced tasks, the robots are now built from a mix of off-the shelf and custom-made parts--- no longer the simple LEGO machines from before. 

Over the course of the past five years, we have won numerous awards for both our robot performance and outreach efforts. Our team emphasizes individual learning on the member's part. While we look to our mentors for ideas and guidance when we run into challenging issues, all of our work is done by the students, from designing the chassis to creating 3D-printed parts to developing algorithms to accurately run the robot. In addition, part of our team's mission is to bring STEM to our community. In light of this, we organized numerous outreach events, from holding presentations at our library and elementary school to hosting panel sessions with professionals working in STEM.

Because we are high school students, we have had to learn a multitude of different skills to succeed in FTC. From using project management to keep track of tasks, goals, and deadlines, to utilizing computer-aided design (CAD) to create custom 3D-printed parts for our robot, to reading through countless pages of documentation to familizarixe ourselves with the Java programming langauge, we have always had to learn new skills and solve challenges as a team in order to succeed. We pride ourselves on working together as a team, listening to each member's ideas and making sure everyone has a voice in the team's decisions.

### Awards

#### Centerstage (2023-2024)
🏅 Tao-Lovelace Combined League Tournament
- Winning Alliance Team (2nd Pick)

#### Powerplay (2022-2023)
🏅 Euclid League Tournament
- Connect Award Winner
- Control Award 2nd Place
- Finalist Alliance Captain

🏆 San Diego Regional Championship
- Connect Award 3rd Place

#### Freight Frenzy (2021-2022)
🏅 Descartes League Tournament
- Inspire Award Second Place
- Winning Alliance 1st Pick
- Connect Award Finalist
- Motivate Award Finalist
- Control Award Finalist

#### Ultimate Goal (2020-2022)
🏅 Descartes League Qualifier
- Top Ranked 3rd Place

🏅 Descartes League Scrimmage
- Top Ranked 2nd Place

#### Skystone (2019-2020)
🏅 Descartes League Tournament
- Collins Aerospace Innovate Award Finalist
- Design Award Winner
- Semifinal Alliance

#### Relic Recovery (2017-2018)
🏅 League Tournament
- Finalist Alliance
- Inspire Award Third Place

🏆 San Diego Regional Tournament
- Qualified for World Championship

🌎 World Championship
- Placed 32nd out of 64 teams

### Social Media

**Instagram:** [@gearup_12499](https://www.instagram.com/gearup_12499/)

**YouTube Channel:** [Gear Up](https://www.youtube.com/channel/UCO8Uq6jTFN_uF80hEzFgdQA)

**Twitter:** [@gearup_12499](https://twitter.com/gearup_12499)

<br>

### Sponsors

**Thank you to all of our sponsors for supporting our team!**

{% assign number_printed = 0 %}
{% for pic in site.data.sponsors %}

{% assign even_odd = number_printed | modulo: 4 %}

{% if even_odd == 0 %}
<div class="row">
{% endif %}

<div class="col-sm-3 clearfix">
<img src="{{ site.url }}{{ site.baseurl }}/images/into_the_deep/sponsors/{{ pic.image }}" class="img-responsive" width="70%" style="float: left" />
</div>

{% assign number_printed = number_printed | plus: 1 %}

{% if even_odd > 2 %}
</div>
{% endif %}
{% endfor %}

#### Affiliated with Robotics Inspiring Science and Engineering (RISE)
![]({{ site.url }}{{ site.baseurl }}/images/into_the_deep/sponsors/image23.png){: style="width: 10%; float: center; margin: 0px"}
