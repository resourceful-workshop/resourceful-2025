---
layout: default
title: RESOURCEFUL-2025
---
{% if jekyll.environment  == "production" %}
        {% assign basepath = "/resourceful-2025" %}
        {%else%}
        {% assign basepath = "/resourceful-2025" %}
        {% endif %}

## Preliminary workshop schedule

The workshop will take place on **March 2nd, 2025**.

<hr>

**9:00 - 9:10** Welcome

**9:10 - 9:40** Keynote I, Beáta Megyesi: Unlocking Hidden Histories: AI and Expert Collaboration in Deciphering Rare Scripts

**9:40 - 10:00** Oral talks I

  *  <font size="4"> <b> The Application of Corpus-Based Language Distance Measurement to the Diatopic Variation Study (on the Material of the Old Novgorodian Birchbark Letters) </b> </font>  
  <span style="color:gray"> Afanasev, Ilia and Lyashevskaya, Olga </span>  
  <button onclick="toggleAbstract('abstract6')">Show Abstract</button>
  <div id="abstract6" class="abstract" style="display:none;">
    The paper presents a computer-assisted exploration of a set of texts, where qualitative analysis complements the linguistically-aware vector-based language distance measurements, interpreting them through close reading and thus proving or disproving their conclusions. It proposes using a method designed for small raw corpora to explore the individual, chronological, and gender-based differences within an extinct single territorial lect, known only by a scarce collection of documents. The material under consideration is the Novgorodian birchbark letters, a set of rather small manuscripts (not a single one is more than 1000 tokens) that are witnesses of the Old Novgorodian lect, spoken on the territories of modern Novgorod and Staraya Russa at the first half of the first millennium CE. The study shows the existence of chronological variation, a mild degree of individual variation, and almost absent gender-based differences. Possible prospects of the study include its application to the newly discovered birchbark letters and using an outgroup for more precise measurements.
  </div>

**10:00 - 10:30** Coffee break

**10:30 - 11:00** Keynote II, 

**11:00 - 12:00** Oral talks II

  *  <font size="4"> <b> 11:00 - 11:20: Voices of Luxembourg: Tackling Dialect Diversity in a Low-Resource Setting </b> </font>  
  <span style="color:gray"> Hosseini-Kivanani, Nina and Schommer, Christoph and Gilles, Peter </span>  
  <button onclick="toggleAbstract('abstract5')">Show Abstract</button>
  <div id="abstract5" class="abstract" style="display:none;">
    Dialect classification is essential for preserving linguistic diversity, particularly in low-resource languages such as Luxembourgish. This study introduces one of the first systematic approaches to classifying Luxembourgish dialects, addressing phonetic, prosodic, and lexical variations across four major regions. We benchmarked multiple models, including state-of-the-art pre-trained speech models like Wav2Vec2, XLSR-Wav2Vec2, and Whisper, alongside traditional approaches such as Random Forest and CNN-LSTM. To overcome data limitations, we applied targeted data augmentation strategies and analyzed their impact on model performance. Our findings highlight the superior performance of CNN-Spectrogram and CNN-LSTM models while identifying the strengths and limitations of data augmentation. This work establishes foundational benchmarks and provides actionable insights for advancing dialectal NLP in Luxembourgish and other low-resource languages.
  </div>

    *  <font size="4"> <b> 11:20 - 11:40: Automatic Validation of the Non-Validated Spanish Speech Data of Common Voice 17.0 </b> </font>  
  <span style="color:gray"> Hernández Mena, Carlos Daniel and Scalvini, Barbara and Lág, Dávid í </span>  
  <button onclick="toggleAbstract('abstract1')">Show Abstract</button>
  <div id="abstract1" class="abstract" style="display:none;">Mozilla Common Voice is a crowdsourced project that aims to create a public, multilingual dataset of voice recordings for training speech recognition models. In Common Voice, anyone can contribute by donating or validating recordings in various languages. However, despite the availability of many recordings in certain languages, a significant percentage remains unvalidated by users. This is the case for Spanish, where in version 17.0 of Common Voice, 75% of the 2,220 hours of recordings are unvalidated. In this work, we used the Whisper recognizer to automatically validate approximately 784 hours of recordings which are more than the 562 hours validated by users. To verify the accuracy of the validation, we developed a speech recognition model based on a version of NVIDIA-NeMo’s Parakeet, which does not have an official Spanish version. Our final model achieved a WER of less than 4% on the test and validation splits of Common Voice 17.0. Both the model and the speech corpus are publicly available on Hugging Face.</div>

  *  <font size="4"> <b> 11:40 - 12:00: OCR Error Post-Correction with LLMs in Historical Documents: No Free Lunches </b> </font>  
  <span style="color:gray"> Kanerva, Jenna and Ledins, Cassandra and Käpyaho, Siiri and Ginter, Filip </span>  
  <button onclick="toggleAbstract('abstract8')">Show Abstract</button>
  <div id="abstract8" class="abstract" style="display:none;">
    Optical Character Recognition (OCR) systems often introduce errors when transcribing historical documents, leaving room for post-correction to improve text quality. This study evaluates the use of open-weight LLMs for OCR error correction in historical English and Finnish datasets. We explore various strategies, including parameter optimization, quantization, segment length effects, and text continuation methods. Our results demonstrate that while modern LLMs show promise in reducing character error rates (CER) in English, a practically useful performance for Finnish was not reached. Our findings highlight the potential and limitations of LLMs in scaling OCR post-correction for large historical corpora.
  </div>

**12:00 - 13:10** Lunch

**13:10 - 13:40** Keynote III, 

**13:40 - 14:40** Oral talks III

**14:40 - 15:50** Poster session (incl. coffee break)

**15:50 - 16:50** Panel discussion with Jussi Karlgren, Joshua Wilbur, Danila Petrelli, Hafsteinn Einarsson, Beáta Megyesi

**16:50 - 17:00** Closing

<hr>
