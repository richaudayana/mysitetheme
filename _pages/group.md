---
layout: page
title: group
permalink: /group/
nav: true
description: Sustainable Energy Systems Laboratory (SENSL)
---
For openings in my research group, please see [Openings](#openings).

## Members

{% for member in site.data.members%}

<div class="row">
<div class="col">
  <img src="{{ site.url }}{{ site.baseurl }}/assets/teampics/{{ member.photo }}"
       class="img-responsive" width="22%" style="float: left;vertical-align:middle;margin:20px 20px" />

  <h4>{{ member.name }}</h4>
  <i>{{ member.info }}<br>email: {{ member.email }}</i>
  <ul style="overflow: hidden">

  {% if member.number_educ == 1 %}
  <li> {{ member.education1 }} </li>
  {% endif %}

  {% if member.number_educ == 2 %}
  <li> {{ member.education1 }} </li>
  <li> {{ member.education2 }} </li>
  {% endif %}

  {% if member.number_educ == 3 %}
  <li> {{ member.education1 }} </li>
  <li> {{ member.education2 }} </li>
  <li> {{ member.education3 }} </li>
  {% endif %}

  {% if member.number_educ == 4 %}
  <li> {{ member.education1 }} </li>
  <li> {{ member.education2 }} </li>
  <li> {{ member.education3 }} </li>
  <li> {{ member.education4 }} </li>
  {% endif %}

  {% if member.number_educ == 5 %}
  <li> {{ member.education1 }} </li>
  <li> {{ member.education2 }} </li>
  <li> {{ member.education3 }} </li>
  <li> {{ member.education4 }} </li>
  <li> {{ member.education5 }} </li>
  {% endif %}

  </ul>
</div>
</div>
{% endfor %}

## Current Undergraduate Students
None

### Former Students and Visitors
- Evelyn Wilson, Freshman Undergraduate Researcher, OSU-ECE, 2021-2022
- Paul Megna, Undergraduate Research Assistant, OSU-ECE, 2021

## Openings

### Undergraduate Students
Undergraduate students at OSU who are interested in working with Dr. Cui on
research are encouraged to schedule an appointment by email. To be eligible for
funded opportunities, please reach out by the end of June every year.

### Master's Student Positions
Master's student positions are currently only offered to students who are
enrolled at OSU. Students focusing on power and energy systems, scientific
computing, or software engineering with a strong interest in programming are
encouraged to contact Dr. Cui.

### PhD Student Positions
The Sustainable Energy Systems Laboratory (SENSL) at Oklahoma State University
is accepting applications for multiple fully funded Ph.D. students for fall
2023. The successful candidates will work with Prof. Hantao Cui in one of the
following areas in collaboration with national laboratories and industry
partners:

1.  High-performance scientific computing for power system simulations.
    Understanding of computational methods in power systems in required.
    Proficiency in one of the following programming languages is required: C,
    Python, Julia, C++, or Rust. Knowledge of CUDA, FPGA, or distributed memory
    systems is a plus.

Candidates who *meet the above requirements* with a strong background in power,
control, or computing are required. Candidates with a Master’s degree in related
fields will be given preferences.

*Please send inquiries to Hantao Cui [h.cui@okstate.edu](h.cui@okstate.edu) with
your CV, transcripts, TOEFL/IELTS/GRE scores, and one sample publication (or a
link to a code repository) if applicable.* A minimum GPA of 80% and a GRE
Analytical Writing score of 3.5 is required. Also, check out the graduate
application process at
https://gradcollege.okstate.edu/application-process/index.html. **All inquiries
will be carefully reviewed. Please understand that due to the high volume of
emails, it is impossible to reply to every inquiry.** Dr. Cui will follow up if
further actions are needed.

Prof. Cui is the author of the power system analysis software
[ANDES](https://docs.andes.app), which is being used worldwide in universities
and laboratories for research. He is presently developing laboratory facilities
for high-performance power systems computing and real-time closed-loop
simulation. For further information regarding research, please see the
Sustainable Energy Systems Laboratory website at
[https://sensl.ece.okstate.edu](https://sensl.ece.okstate.edu).

The School of Electrical and Computer Engineering at Oklahoma State University
has a history of strong power programs. Students have access to the OSU Pete
Supercomputer and state-of-the-art computing facilities. Oklahoma State
University is in Stillwater, Oklahoma, a safe city of 50,000 residents with
affordable housing of high quality. Stillwater is about 65 miles from two
cosmopolitan cities—Tulsa and Oklahoma City—that are replete with restaurants,
entertainment, museums, sporting events, major airports, and shopping.

Applications for admission in the fall of 2022 are due March 31, 2023.
