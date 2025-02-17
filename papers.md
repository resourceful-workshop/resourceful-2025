---
layout: default
title: RESOURCEFUL-2025
---
{% if jekyll.environment  == "production" %}
        {% assign basepath = "." %}
        {%else%}
        {% assign basepath = "" %}
        {% endif %}

# Accepted papers

## Talks

  *  <font size="4"> <b> Universal Dependencies Treebank for Uzbek </b> </font>  
  <span style="color:gray"> Arofat Akhundjanova, Luigi Talamo </span>  
  <button onclick="toggleAbstract('abstract1')">Show Abstract</button>
  <div id="abstract1" class="abstract" style="display:none;">We present the first Universal Dependencies treebank for Uzbek, a low-resource language from the Turkic family...</div>

  *  <font size="4"> <b> FoQA: A Faroese Question-Answering Dataset </b> </font>  
  <span style="color:gray"> Annika Simonsen, Dan Saattrup Nielsen, Hafsteinn Einarsson </span>  
  <button onclick="toggleAbstract('abstract2')">Show Abstract</button>
  <div id="abstract2" class="abstract" style="display:none;">We present FoQA, a Faroese extractive question-answering (QA) dataset with 2,000 samples, created using a semi-automated approach...</div>