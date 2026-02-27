---
title: Call for Papers
layout: page-fullwidth
order: 0
permalink: /cfp/
header:
  image_fullwidth: "generic-gradient.png"
---

**5th Conference on Automated Knowledge Base Construction (AKBC)**<br>
TBD 2026<br>
Homepage: [http://www.akbc.ws](http://akbc.ws)<br>
Email: [info@akbc.ws](mailto:info@akbc.ws)<br>

### Key dates

- TBD

All deadlines are 11.59 pm UTC -12h ("anywhere on Earth").

### Knowledge Base Construction

Knowledge gathering, representation, and reasoning are among the fundamental challenges of artificial intelligence. Large-scale repositories of knowledge about entities, relations, and their abstractions are known as "knowledge bases". Most major technology companies now have substantial efforts in knowledge base construction. Related scholarly work spans many research areas, including machine learning, natural language processing, computer vision, information integration, databases, search, data mining, knowledge representation, human computation, human-computer interfaces, and fairness. The AKBC conference serves as a research forum for gathering all these areas, in both academia and industry.

### Call for Papers

We invite the submission of papers describing previously unpublished research, including new methodology, datasets, evaluations, surveys, reproduced results, negative results, and visionary positions.

Topics of interest include, but are not limited to:

- Natural language processing, information extraction, extraction of entities, relations, and events, semantic parsing, coreference, machine reading, entailment, web mining, multilingual NLP.
- Information integration, entity resolution, schema & ontology alignment, text and structure alignment, federated KBs, Semantic Web.
- Machine learning, supervised, unsupervised, lightly-supervised and distantly-supervised learning, deep learning, symbolic learning, multimodal learning, embeddings of knowledge.
- Search, question-answering, reasoning, knowledge base completion, queries on mixtures of structured and unstructured data; querying under uncertainty.
- Multi-modal knowledge bases: structured data, text, images, video, audio.
- Human-computer interaction, crowdsourcing, interactive learning.
- Fairness, accountability, transparency, misinformation, multiple viewpoints, uncertainty.
- Databases, probabilistic databases, distributed databases, database cleaning, scalable computation, distributed computation, dynamic data, online adaptation of knowledge.
- Systems, languages and toolkits, demonstrations of existing knowledge bases.
- Evaluation of AKBC, datasets, evaluation methodology.

### Invited Talks

Invited speakers will be announced soon.

### Workshops

In addition to the conference program, we will have a collection of workshops on focused topics.

### Organizers

{% for organizer in site.data.organizers %}

<div class="row">
<div class="small-3 large-3 columns">
{{ organizer.position }}<br>
</div>
<div class="small-9 large-9 columns">
<a href="{{ organizer.url }}">{{ organizer.name }}</a>, {{ organizer.location }}<br>
</div>
</div>
{% endfor %}

### Area Chairs

<div class="row">
<div class="columns">
{% for area-chair in site.data.area-chairs %}
<a href="{{ area-chair.url }}">{{ area-chair.name }}</a>, {{ area-chair.location }}<br>
{% endfor %}
</div>
</div>

<br>
**Questions? Please mail: [info@akbc.ws](info@akbc.ws)**
<br>
