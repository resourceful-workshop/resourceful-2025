---
layout: default
title: RESOURCEFUL-2020
---
{% if jekyll.environment  == "production" %}
        {% assign basepath = "." %}
        {%else%}
        {% assign basepath = "" %}
        {% endif %}


## Speakers

<div>

    <div class="iblock headshotbox ">
        <img src="{{basepath}}/images/organizers/Judith.jpeg" class="headshot">
        <a href="https://www.linkedin.com/in/judith-gaspers-aaa501b9/" class="headshotaffiliation"> Judith Gaspers </a>
        <div class="headshotname"> Amazon </div>
    </div> 

    <div class="iblock headshotbox ">
        <img src="{{basepath}}/images/organizers/Gabriel.jpg" class="headshot">
        <a href="https://www.kth.se/profile/skantze" class="headshotaffiliation"> Gabriel Skantze </a>
        <div class="headshotname"> KTH </div>
    </div>

   <div class="iblock headshotbox ">
        <img src="{{basepath}}/images/organizers/wondwossen.jpeg" class="headshot">
        <a href="https://www.linkedin.com/in/wondisho/?originalSubdomain=et" class="headshotaffiliation"> Wondwossen Mulugeta </a>
        <div class="headshotname"> Addis Ababa University </div>
   </div>

</div>


**Judith Gaspers: Spoken language understanding in low-resource scenarios**
 
In this talk, I will present work towards two low-resource scenarios in industry spoken language understanding (SLU). The first scenario is concerned with bootstrapping an SLU model for a new language with limited target language data. I will show how transfer learning (with source data selection) from multiple source languages can be applied for this use case with the goal of decreasing target language data requirements and computational costs. The second scenario concerns features with limited data in an otherwise high-resource language, thus leading to data imbalance. Aiming to boost performance of low-frequency features without over-fitting, I will present a model in which methods for handling data balancing are leveraged indirectly via an auxiliary task which makes use of a class-balanced batch generator and (possibly) synthetic data.



**Gabriel Skantze: Collecting dialogue data for conversational systems**

When developing conversational systems, dialog data is typically needed. However, it is often challenging to collect enough data which are also representative of the conversational domain that is being modelled.  In this talk, I will discuss different alternatives for collecting such data, and the problems that these different methods are associated with. I will include examples where we have collected data for human-robot interaction in public settings, as well as large scale data collections using crowdsourcing. 



**Wondwossen Mulugeta: Pure data for NLP**

Machine Learning approaches, mainly supervised methods, depends on the quality of the data set provided during training. Beyond the frequently cited “big data” requirement, the need for quality data seems to be overlooked for under-resourced languages. While the relatively developed languages have data sets with sufficient size and quality, under-resourced languages are lacking such value affecting both effectiveness and efficiency of NLP modules. The main cause of this challenge, from my experience, is accelerated by the provision of online platforms which encouraged people to be authors allowing impure and erroneous data to be available on social media and blogs. It is also common to see that many research attempts are done by taking data sets from such platforms without sufficient validation of the quality of data at lower level language constructs. Such data sets are known to suffer mainly from morphological and syntactic anomalies which will pose a challenge for the learning methods in bringing trustworthy patterns and models.  My talk, with the above background, will focus on the required initiatives either for authoring tools and extensions on existing platforms or independent mechanisms for the purpose of improving the quality of data for efficient learning models. It is my belief that initiatives in authoring tools for under-resourced languages and low-level NLP modules for purifying data will greatly help machine learning approaches with limited data size.


Contact: [resourceful2020@easychair.org](mailto:resourceful2020@easychair.org)
