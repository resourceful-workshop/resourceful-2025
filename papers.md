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

  *  <font size="4"> <b> Automatic Validation of the Non-Validated Spanish Speech Data of Common Voice 17.0 </b> </font>  
  <span style="color:gray"> Carlos Daniel Hernández Mena, Barbara Scalvini, Dávid í Lág </span>  
  <button onclick="toggleAbstract('abstract3')">Show Abstract</button>
  <div id="abstract3" class="abstract" style="display:none;">Mozilla Common Voice is a crowdsourced project that aims to create a public, multilingual dataset of voice recordings...</div>

  *  <font size="4"> <b> WikiQA-IS: Assisted Benchmark Generation and Automated Evaluation of Icelandic Cultural Knowledge in LLMs </b> </font>  
  <span style="color:gray"> Þórunn Arnardóttir, Elías Bjartur Einarsson, Garðar Ingvarsson Juto, Þorvaldur Páll Helgason, Hafsteinn Einarsson </span>  
  <button onclick="toggleAbstract('abstract4')">Show Abstract</button>
  <div id="abstract4" class="abstract" style="display:none;">This paper presents WikiQA-IS, a novel question-answering dataset focusing on Icelandic culture and history...</div>

<script>
function toggleAbstract(id) {
    var abstract = document.getElementById(id);
    if (abstract.style.display === "none") {
        abstract.style.display = "block";
    } else {
        abstract.style.display = "none";
    }
}
</script>
