---
layout: default
title: RESOURCEFUL-2025
---
{% if jekyll.environment  == "production" %}
        {% assign basepath = "." %}
        {%else%}
        {% assign basepath = "" %}
        {% endif %}

# Accepted papers (in random order)

## Talks

  *  <font size="4"> <b> Automatic Validation of the Non-Validated Spanish Speech Data of Common Voice 17.0 </b> </font>  
  <span style="color:gray"> Hernández Mena, Carlos Daniel and Scalvini, Barbara and Lág, Dávid í </span>  
  <button onclick="toggleAbstract('abstract1')">Show Abstract</button>
  <div id="abstract1" class="abstract" style="display:none;">Mozilla Common Voice is a crowdsourced project that aims to create a public, multilingual dataset of voice recordings for training speech recognition models. In Common Voice, anyone can contribute by donating or validating recordings in various languages. However, despite the availability of many recordings in certain languages, a significant percentage remains unvalidated by users. This is the case for Spanish, where in version 17.0 of Common Voice, 75% of the 2,220 hours of recordings are unvalidated. In this work, we used the Whisper recognizer to automatically validate approximately 784 hours of recordings which are more than the 562 hours validated by users. To verify the accuracy of the validation, we developed a speech recognition model based on a version of NVIDIA-NeMo’s Parakeet, which does not have an official Spanish version. Our final model achieved a WER of less than 4% on the test and validation splits of Common Voice 17.0. Both the model and the speech corpus are publicly available on Hugging Face.</div>

  *  <font size="4"> <b> FoQA: A Faroese Question-Answering Dataset </b> </font>  
  <span style="color:gray"> Simonsen, Annika and Nielsen, Dan Saattrup and Einarsson, Hafsteinn </span>  
  <button onclick="toggleAbstract('abstract2')">Show Abstract</button>
  <div id="abstract2" class="abstract" style="display:none;">We present FoQA, a Faroese extractive question-answering (QA) dataset with 2,000 samples, created using a semi-automated approach combining Large Language Models (LLMs) and human validation. The dataset was generated from Faroese Wikipedia articles using GPT-4-turbo for initial QA generation, followed by question rephrasing to increase complexity and native speaker validation to ensure quality. We provide baseline performance metrics for FoQA across multiple models, including LLMs and BERT, demonstrating its effectiveness in evaluating Faroese QA performance. The dataset is released in three versions: a validated set of 2,000 samples, a complete set of all 10,001 generated samples, and a set of 2,395 rejected samples for error analysis.</div>

  *  <font size="4"> <b> Annotating Attitude in Swedish Political Tweets </b> </font>  
  <span style="color:gray"> Lindahl, Anna </span>  
  <button onclick="toggleAbstract('abstract4')">Show Abstract</button>
  <div id="abstract4" class="abstract" style="display:none;">There is a lack of Swedish datasets annotated for emotional and argumentative language. This work therefore presents an annotation procedure and a dataset of Swedish political tweets. The tweets are annotated for positive and negative attitude. Challenges with this type of annotation is identified and described. The evaluation shows that the annotators do not agree on where to annotate spans, but that they agree on labels. This is demonstrated with a new implementation of the agreement coefficient Krippendorff's unitized alpha.</div>

  *  <font size="4"> <b> Voices of Luxembourg: Tackling Dialect Diversity in a Low-Resource Setting </b> </font>  
  <span style="color:gray"> Hosseini-Kivanani, Nina and Schommer, Christoph and Gilles, Peter </span>  
  <button onclick="toggleAbstract('abstract5')">Show Abstract</button>
  <div id="abstract5" class="abstract" style="display:none;">
    Dialect classification is essential for preserving linguistic diversity, particularly in low-resource languages such as Luxembourgish. This study introduces one of the first systematic approaches to classifying Luxembourgish dialects, addressing phonetic, prosodic, and lexical variations across four major regions. We benchmarked multiple models, including state-of-the-art pre-trained speech models like Wav2Vec2, XLSR-Wav2Vec2, and Whisper, alongside traditional approaches such as Random Forest and CNN-LSTM. To overcome data limitations, we applied targeted data augmentation strategies and analyzed their impact on model performance. Our findings highlight the superior performance of CNN-Spectrogram and CNN-LSTM models while identifying the strengths and limitations of data augmentation. This work establishes foundational benchmarks and provides actionable insights for advancing dialectal NLP in Luxembourgish and other low-resource languages.
  </div>

  *  <font size="4"> <b> The Application of Corpus-Based Language Distance Measurement to the Diatopic Variation Study (on the Material of the Old Novgorodian Birchbark Letters) </b> </font>  
  <span style="color:gray"> Afanasev, Ilia and Lyashevskaya, Olga </span>  
  <button onclick="toggleAbstract('abstract6')">Show Abstract</button>
  <div id="abstract6" class="abstract" style="display:none;">
    The paper presents a computer-assisted exploration of a set of texts, where qualitative analysis complements the linguistically-aware vector-based language distance measurements, interpreting them through close reading and thus proving or disproving their conclusions. It proposes using a method designed for small raw corpora to explore the individual, chronological, and gender-based differences within an extinct single territorial lect, known only by a scarce collection of documents. The material under consideration is the Novgorodian birchbark letters, a set of rather small manuscripts (not a single one is more than 1000 tokens) that are witnesses of the Old Novgorodian lect, spoken on the territories of modern Novgorod and Staraya Russa at the first half of the first millennium CE. The study shows the existence of chronological variation, a mild degree of individual variation, and almost absent gender-based differences. Possible prospects of the study include its application to the newly discovered birchbark letters and using an outgroup for more precise measurements.
  </div>

  *  <font size="4"> <b> Multi-label Scandinavian Language Identification (SLIDE) </b> </font>  
  <span style="color:gray"> Fedorova, Mariia and Frydenberg, Jonas Sebulon and Handford, Victoria and Langø, Victoria Ovedie Chruickshank and Willoch, Solveig Helene and Midtgaard, Marthe Løken and Scherrer, Yves and Mæhlum, Petter and Samuel, David </span>  
  <button onclick="toggleAbstract('abstract7')">Show Abstract</button>
  <div id="abstract7" class="abstract" style="display:none;">
    Identifying closely related languages at sentence level is difficult, in particular because it is often impossible to assign a sentence to a single language. In this paper, we focus on multi-label sentence-level Scandinavian language identification (LID) for Danish, Norwegian Bokmål, Norwegian Nynorsk, and Swedish. We present the Scandinavian Language Identification and Evaluation, SLIDE, a manually curated multi-label evaluation dataset and a suite of LID models with varying speed–accuracy tradeoffs. We demonstrate that the ability to identify multiple languages simultaneously is necessary for any accurate LID method, and present a novel approach to training such multi-label LID models.
  </div>

  *  <font size="4"> <b> OCR Error Post-Correction with LLMs in Historical Documents: No Free Lunches </b> </font>  
  <span style="color:gray"> Kanerva, Jenna and Ledins, Cassandra and Käpyaho, Siiri and Ginter, Filip </span>  
  <button onclick="toggleAbstract('abstract8')">Show Abstract</button>
  <div id="abstract8" class="abstract" style="display:none;">
    Optical Character Recognition (OCR) systems often introduce errors when transcribing historical documents, leaving room for post-correction to improve text quality. This study evaluates the use of open-weight LLMs for OCR error correction in historical English and Finnish datasets. We explore various strategies, including parameter optimization, quantization, segment length effects, and text continuation methods. Our results demonstrate that while modern LLMs show promise in reducing character error rates (CER) in English, a practically useful performance for Finnish was not reached. Our findings highlight the potential and limitations of LLMs in scaling OCR post-correction for large historical corpora.
  </div>


## Posters

  *  <font size="4"> <b> WikiQA-IS: Assisted Benchmark Generation and Automated Evaluation of Icelandic Cultural Knowledge in LLMs </b> </font>  
  <span style="color:gray"> Arnardóttir, Þórunn and Bjartur Einarsson, Elías and Ingvarsson Juto, Garðar and Páll Helgason, Þorvaldur and Einarsson, Hafsteinn </span>  
  <button onclick="toggleAbstract('abstract3')">Show Abstract</button>
  <div id="abstract3" class="abstract" style="display:none;">This paper presents WikiQA-IS, a novel question-answering dataset focusing on Icelandic culture and history, along with an automated pipeline for dataset generation and evaluation. Leveraging GPT-4 to create questions and answers based on Icelandic Wikipedia articles and news sources, we produced a high-quality corpus of 2,000 question-answer pairs. We introduce an automatic evaluation method using GPT-4o as a judge, which shows strong agreement with human evaluations. Our benchmark reveals varying performances across different language models, with closed-source models generally outperforming open-weights alternatives. This work contributes a resource for evaluating language models' knowledge of Icelandic culture and offers a replicable framework for creating similar datasets in other cultural contexts.</div>

  *  <font size="4"> <b> Universal Dependencies Treebank for Uzbek </b> </font>  
  <span style="color:gray"> Akhundjanova, Arofat and Talamo, Luigi </span>  
  <button onclick="toggleAbstract('abstract9')">Show Abstract</button>
  <div id="abstract9" class="abstract" style="display:none;">We present the first Universal Dependencies treebank for Uzbek, a low-resource language from the Turkic family. The treebank contains 500 sentences (5850 tokens) sourced from the news and fiction genres and it is annotated for lemmas, part-of-speech (POS) tags, morphological features, and dependency relations. We describe our methodology for building the treebank, which consists of a mix of manual and automatic annotation and discuss some constructions of the Uzbek language that pose challenges to the UD framework.</div>

  *  <font size="4"> <b> DUDU: A Treebank for Ottoman Turkish in UD Style </b> </font>  
  <span style="color:gray"> Yılandiloğlu, Enes and Siewert, Janine </span>  
  <button onclick="toggleAbstract('abstract10')">Show Abstract</button>
  <div id="abstract10" class="abstract" style="display:none;">This paper introduces a recently released Ottoman Turkish (ota) treebank in Universal Dependencies (UD) style, DUDU. The DUDU Treebank consists of 1,064 automatically annotated and manually corrected sentences. The texts were manually collected from various academic or literary sources available on the Internet. Following preprocessing, the sentences were annotated using a MaCHAMP-based neural network model utilizing the large language model (LLM) architecture and manually corrected. The treebank became publicly available with the 2.14 release, and future steps involve expanding the treebank with more data and refining the annotation scheme. The treebank is the first and only treebank that utilizes the IJMES transliteration alphabet. The treebank not only gives insight on Ottoman Turkish lexically, morphologically, and syntactically, but also provides a small but robust test set for future computational models for Ottoman Turkish.</div>

  *  <font size="4"> <b> A Simple Audio and Text Collection-Annotation Tool Targeted to Brazilian Indigenous Language Native Speakers </b> </font>  
  <span style="color:gray"> Polleti, Gustavo Padilha and Cozman, Fabio and Gerardi, Fabricio </span>  
  <button onclick="toggleAbstract('abstract11')">Show Abstract</button>
  <div id="abstract11" class="abstract" style="display:none;">In this paper we present an audio and text annotation tool for native speakers, with a particular focus on Brazilian indigenous languages. Our tool simplifies the process of language resource annotation and employs gamefication techniques typically found in language learning games. Then we describe the annotation tool and present preliminary results for the Bororo language. We discuss the limitations of our tool, highlighting ethical and practical implementation concerns.</div>

  *  <font size="4"> <b> Fine-Tuning Cross-Lingual LLMs for POS Tagging in Code-Switched Contexts </b> </font>  
  <span style="color:gray"> Absar, Shayaan </span>  
  <button onclick="toggleAbstract('abstract12')">Show Abstract</button>
  <div id="abstract12" class="abstract" style="display:none;">Code-switching (CS) involves speakers switching between two (or potentially more) languages during conversation and is a common phenomenon in bilingual communities. The majority of NLP research has been devoted to mono-lingual language modelling. Consequentially, most models perform poorly on code-switched data. This paper investigates the effectiveness of Cross-Lingual Large Language Models on the task of POS (Part-of-Speech) tagging in code-switched contexts, once they have undergone a fine-tuning process. The models are trained on code-switched combinations of Indian languages and English. This paper also seeks to investigate whether fine-tuned models are able to generalise and POS tag code-switched combinations that were not a part of the fine-tuning dataset. Additionally, this paper presents a new metric, the S-index (Switching-Index), for measuring the level of code-switching within an utterance.</div>

  *  <font size="4"> <b> First Steps in Benchmarking Latvian in Large Language Models </b> </font>  
  <span style="color:gray"> Skadina, Inguna and Bakanovs, Bruno and Darģis, Roberts </span>  
  <button onclick="toggleAbstract('abstract13')">Show Abstract</button>
  <div id="abstract13" class="abstract" style="display:none;">The performance of multilingual large language models (LLMs) in low-resource languages, such as Latvian, has been under-explored. In this paper, we investigate the capabilities of several open and commercial LLMs in the Latvian language understanding tasks. We evaluate these models across several well-known benchmarks, such as the Choice of Plausible Alternatives (COPA) and Measuring Massive Multitask Language Understanding (MMLU), which were adapted into Latvian using machine translation. Our results highlight significant variability in model performance, emphasizing the challenges of extending LLMs to low-resource languages. We also analyze the effect of post-editing on machine-translated datasets, observing notable improvements in model accuracy, particularly with BERT-based architectures. We also assess open-source LLMs using the Belebele dataset, showcasing competitive performance from open-weight models when compared to proprietary systems. This study reveals key insights into the limitations of current LLMs in low-resource settings and provides datasets for future benchmarking efforts.</div>

  *  <font size="4"> <b> On the Usage of Semantics, Syntax, and Morphology for Noun Classification in IsiZulu </b> </font>  
  <span style="color:gray"> Sayed, Imaan and Mahlaza, Zola and van der Leek, Alexander and Mopp, Jonathan and Keet, C. Maria </span>  
  <button onclick="toggleAbstract('abstract14')">Show Abstract</button>
  <div id="abstract14" class="abstract" style="display:none;">There is limited work aimed at solving the core task of noun classification for Nguni languages. The task focuses on identifying the semantic categorisation of each noun and plays a crucial role in the ability to form semantically and morphologically valid sentences. The work by Byamugisha (2022) was the first to tackle the problem for a related, but non-Nguni, language. While there have been efforts to replicate it for a Nguni language, there has been no effort focused on comparing the technique used in the original work vs. contemporary neural methods or a number of traditional machine learning classification techniques that do not rely on human-guided knowledge to the same extent. We reproduce Byamugisha (2022)’s work with different configurations to account for differences in access to datasets and resources, compare the approach with a pre-trained transformer-based model, and traditional machine learning models that relyon less human-guided knowledge. The newly created data-driven models outperform the knowledge-infused models, with the best performing models achieving an F1 score of 0.97.</div>

  *  <font size="4"> <b> VerbCraft: Morphologically-Aware Armenian Text Generation Using LLMs in Low-Resource Settings </b> </font>  
  <span style="color:gray"> Avetisyan, Hayastan and Broneske, David </span>  
  <button onclick="toggleAbstract('abstract15')">Show Abstract</button>
  <div id="abstract15" class="abstract" style="display:none;">Understanding and generating morphologically complex verb forms is a critical challenge in Natural Language Processing (NLP), particularly for low-resource languages like Armenian. Armenian's verb morphology encodes multiple layers of grammatical information, such as tense, aspect, mood, voice, person, and number, requiring nuanced computational modeling. We introduce VerbCraft, a novel neural model that integrates explicit morphological classifiers into the mBART-50 architecture. VerbCraft achieves a BLEU score of 0.4899 on test data, compared to the baseline's 0.9975, reflecting its focus on prioritizing morphological precision over fluency. With over 99\% accuracy in aspect and voice predictions and robust performance on rare and irregular verb forms, VerbCraft addresses data scarcity through synthetic data generation with human-in-the-loop validation. Beyond Armenian, it offers a scalable framework for morphologically rich, low-resource languages, paving the way for linguistically informed NLP systems and advancing language preservation efforts.</div>

  *  <font size="4"> <b> Post-OCR Correction of Historical German Periodicals using LLMs </b> </font>  
  <span style="color:gray"> Danilova, Vera and Aangenendt, Gijs </span>  
  <button onclick="toggleAbstract('abstract16')">Show Abstract</button>
  <div id="abstract16" class="abstract" style="display:none;">
    Optical Character Recognition (OCR) is critical for accurate access to historical corpora, providing a foundation for processing pipelines and the reliable interpretation of historical texts. Despite advances, the quality of OCR in historical documents remains limited, often requiring post-OCR correction to address residual errors. Building on recent progress with instruction-tuned Llama 2 models applied to English historical newspapers, we examine the potential of German Llama 2 and Mistral models for post-OCR correction of German medical historical periodicals. We perform instruction tuning using two configurations of training data, augmenting our small annotated dataset with two German datasets from the same time period. The results demonstrate that German Mistral enhances the raw OCR output, achieving a lower average word error rate (WER). However, the average character error rate (CER) either decreases or remains unchanged across all models considered. We perform an analysis of performance within the error groups and provide an interpretation of the results.
  </div>

  *  <font size="4"> <b> From Words to Action: A National Initiative to Overcome Data Scarcity for the Slovene LLM </b> </font>  
  <span style="color:gray"> Holdt, Špela Arhar and Antloga, Špela and Munda, Tina and Pori, Eva and Krek, Simon </span>  
  <button onclick="toggleAbstract('abstract17')">Show Abstract</button>
  <div id="abstract17" class="abstract" style="display:none;">
    Large Language Models (LLMs) have demonstrated significant potential in natural language processing, but they depend on vast, diverse datasets, creating challenges for languages with limited resources. The paper presents a national initiative that addresses these challenges for Slovene. We outline strategies for large-scale text collection, including the creation of an online platform to engage the broader public in contributing texts and a communication campaign promoting openly accessible and transparently developed LLMs.
  </div>

  *  <font size="4"> <b> Assessing the Similarity of Cross-Lingual Seq2Seq Sentence Embeddings Using Low-Resource Spectral Clustering </b> </font>  
  <span style="color:gray"> Moll, Nelson and Rabbani, Tahseen </span>  
  <button onclick="toggleAbstract('abstract18')">Show Abstract</button>
  <div id="abstract18" class="abstract" style="display:none;">
    In this work, we study the cross-lingual distance of machine translations through alignment of seq2seq representations over small corpora. First, we use the M2M100 model to collect sentence-level representations of The Book of Revelation in several languages. We then perform unsupervised manifold alignment (spectral clustering) between these collections of embeddings. As verses between translations are not necessarily aligned, our procedure falls under the challenging, but more realistic non-correspondence regime. The cost function associated with each alignment is used to rank the relative (machine) similarity of one language to another. We then perform correspondent alignment over another cluster of languages, this time using FLORES+ parallel NLLB model embeddings. Our experiments demonstrate that the representations of closely-related languages group closely, and are cheap to align (requiring <1000 sentences) via our strategy.
  </div>

  *  <font size="4"> <b> "I Need More Context and an English Translation": Analysing How LLMs Identify Personal Information in Komi, Polish, and English </b> </font>  
  <span style="color:gray"> Ilinykh, Nikolai and Szawerna, Maria Irena </span>  
  <button onclick="toggleAbstract('abstract19')">Show Abstract</button>
  <div id="abstract19" class="abstract" style="display:none;">
    Automatic identification of personal information (PI) is particularly difficult for languages with limited linguistic resources. Recently, large language models (LLMs) have been applied to various tasks involving low-resourced languages, but their capability to process PI in such contexts remains under-explored. In this paper we provide a qualitative analysis of the outputs from three LLMs prompted to identify PI in texts written in Komi (Permyak and Zyrian), Polish, and English. Our analysis highlights challenges in using pre-trained LLMs for PI identification in both low- and medium-resourced languages. It also motivates the need to develop LLMs that understand the differences in how PI is expressed across languages with varying levels of availability of linguistic resources.
  </div>

  *  <font size="4"> <b> Federated Meta-Learning for Low-Resource Translation of Kirundi </b> </font>  
  <span style="color:gray"> Sang, Kyle Rui and Rabbani, Tahseen and Zhou, Tianyi </span>  
  <button onclick="toggleAbstract('abstract20')">Show Abstract</button>
  <div id="abstract20" class="abstract" style="display:none;">
    In this work, we reframe multilingual neural machine translation (NMT) as a federated meta-learning problem and introduce a translation dataset for the low-resource Kirundi language. We aggregate machine translation models locally trained on varying (but related) source languages to produce a global meta-model that encodes abstract representations of key semantic structures relevant to the parent languages. We then use the Reptile algorithm and Optuna fine-tuning to fit the global model onto a target language. The target language may live outside the subset of parent languages (such as closely-related dialects or sibling languages), which is particularly useful for languages with limitedly available sentence pairs. We first develop a novel dataset of Kirundi-English sentence pairs curated from Biblical translation. We then demonstrate that a federated learning approach can produce a tiny 4.8M Kirundi translation model and a stronger NLLB-600M model which performs well on both our Biblical corpus and the FLORES-200 Kirundi corpus.
  </div>

  *  <font size="4"> <b> Second language Korean Universal Dependency treebank v1.2: Focus on Data Augmentation and Annotation Scheme Refinement </b> </font>  
  <span style="color:gray"> Sung, Hakyung and Shin, Gyu-Ho </span>  
  <button onclick="toggleAbstract('abstract21')">Show Abstract</button>
  <div id="abstract21" class="abstract" style="display:none;">
    We expand the second language (L2) Korean Universal Dependencies (UD) treebank with 5,454 manually annotated sentences. The annotation guidelines are also revised to better align with the UD framework. Using this enhanced treebank, we fine-tune three Korean language models—Stanza, spaCy, and Trankit—and evaluate their performance on in-domain and out-of-domain L2-Korean datasets. The results show that fine-tuning significantly improves their performance across various metrics, thus highlighting the importance of using well-tailored L2 datasets for fine-tuning first-language-based, general-purpose language models for the morphosyntactic analysis of L2 data.
  </div>

  *  <font size="4"> <b> Recommendations for Overcoming Linguistic Barriers in Healthcare: Challenges and Innovations in NLP for Haitian Creole </b> </font>  
  <span style="color:gray"> Mompelat, Ludovic </span>  
  <button onclick="toggleAbstract('abstract22')">Show Abstract</button>
  <div id="abstract22" class="abstract" style="display:none;">
    Haitian Creole, spoken by millions in Haiti and its diaspora, remains underrepresented in Natural Language Processing (NLP) research, limiting the availability of effective translation tools. In Miami, a significant Haitian Creole-speaking population faces healthcare disparities exacerbated by language barriers. Existing translation systems fail to address key challenges such as linguistic variation within the Creole language, frequent code-switching, and the lack of standardized medical terminology. This work proposes a structured methodology for the development of an AI-assisted translation and interpretation tool tailored for patient-provider communication in a medical setting. To achieve this, we propose a hybrid NLP approach that integrates fine-tuned Large Language Models (LLMs) with traditional machine translation methods. This combination ensures accurate, context-sensitive translation that adapts to both formal medical discourse and conversational registers while maintaining linguistic consistency. Additionally, we discuss data collection strategies, annotation challenges, and evaluation metrics necessary for building an ethically designed, scalable NLP system. By addressing these issues, this research provides a foundation for improving healthcare accessibility and linguistic equity for Haitian Creole speakers.
  </div>

  *  <font size="4"> <b> Interpreting the UAS and the LAS of the parsing of Old English with Universal Dependencies </b> </font>  
  <span style="color:gray"> Martin Arista, Javier and Elvira Ojanguren López, Ana and Domínguez Barragán, Sara </span>  
  <button onclick="toggleAbstract('abstract23')">Show Abstract</button>
  <div id="abstract23" class="abstract" style="display:none;">
    This paper interprets, from a linguistic point of view, the Unlabelled Attachment Score (UAS) and Labelled Attachment Score (LAS) metrics obtained in the Universal Dependencies parsing of Old English. The study assesses the performance of three distinct training methods based on the Natural Language Processing library spaCy: a baseline pipeline, a pretrained model, and a transformer-based model (MobileBERT). Using datasets ranging from 1,000 to 20,000 words, the best-performing model (pretrained model with 20,000 words) achieved 83.2% UAS and 74.2% LAS. The model performs better at identifying structural relations than at labeling specific dependency relations. There is a consistent 9 point gap between UAS and LAS accross the different structural levels, including the word, the phrase, the clause and the complex sentence. While the model shows high accuracy in morphologically marked local relations and morphological feature recognition (often over 90%), its accuracy is lower with long-distance dependencies and complex syntactic structures. Particularly problematic areas include non-projective dependencies, fixed expressions, copulative constructions, and double object constructions. The conclusion is reached that improving parsing accuracy will require larger training datasets and a fine-grained analysis of complex syntactic relations that is compatible with the strong performance reached in morphological feature recognition.
  </div>

  *  <font size="4"> <b> Beyond a Means to an End: A Case Study in Building Phonotactic Corpora for Central Australian Languages </b> </font>  
  <span style="color:gray"> Muradoglu, Saliha and Gray, James and Simpson, Jane Helen and Proctor, Michael and Harvey, Mark </span>  
  <button onclick="toggleAbstract('abstract24')">Show Abstract</button>
  <div id="abstract24" class="abstract" style="display:none;">
    Linguistic datasets are essential across fields: computational linguists use them for NLP development, theoretical linguists for statistical arguments supporting hypotheses about language, and documentary linguists for preserving examples and aiding grammatical descriptions. Transforming raw data (e.g., recordings or dictionaries) into structured forms (e.g., tables) requires non-trivial decisions within processing pipelines. This paper highlights the importance of these processes in understanding linguistic systems. Our contributions include: (1) an interactive dashboard for four central Australian languages with custom filters, and (2) demonstrating how data processing decisions influence measured outcomes.
  </div>

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
