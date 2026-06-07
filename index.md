---
title: 10th Workshop on Automated Knowledge Base Construction
display_title: "10th Workshop on<br>Automated Knowledge Base Construction"
layout: page-fullwidth
header:
  image_fullwidth: "budapest.jpg"
permalink: /
---

Co-located with [EMNLP 2026](https://2026.emnlp.org/) in Budapest, Hungary &mdash; **October 28, 2026**.

While Large Language Models (LLMs) have revolutionized NLP, they remain prone to hallucinations, reasoning "mode-collapse" in open-ended generation, and a lack of factual provenance. The Automated Knowledge Base Construction (AKBC) workshop addresses a key missing piece of the generative era: structured knowledge. Knowledge Bases (KBs) serve as ground truth for fact verification, the semantic backbone for constrained decoding in generation, and as a resource behind Retrieval-Augmented Generation (RAG).

The workshop contributes to the growing momentum around integrating structured knowledge into generative models, both at training time and at inference time.

It follows a successful series of previous editions: as an independent conference in [2022](https://akbc.ws/2022), [2021](https://akbc.ws/2021), and [2020](https://akbc.ws/2020), as workshop in [2017 at NIPS](https://akbc.ws/2017), in [2016 at NAACL](https://akbc.ws/2016), in [2014 at NIPS](https://akbc.ws/2014), in [2013 at CIKM](https://akbc.ws/2013), in [2012 at NAACL](https://akbc.ws/2012), and in 2010 as a stand-alone event in Grenoble, France.

<a name="news"></a>

<a class="linkedin-callout" href="https://www.linkedin.com/company/akbc-workshop/" target="_blank" rel="noopener">
  <span class="linkedin-callout-icon iconfont"></span>
  <span class="linkedin-callout-text">
    <strong>Stay in the loop.</strong>
    Follow AKBC on LinkedIn for deadlines, speaker announcements, and shared task updates.
  </span>
  <span class="linkedin-callout-cta">Follow &rarr;</span>
</a>

## News

- May 28th, 2026: [Alon Halevy](https://en.wikipedia.org/wiki/Alon_Halevy) (Google) is confirmed as a keynote speaker
- May 27th, 2026: The workshop day is fixed to **October 28, 2026**
- May 21st, 2026: We are excited to announce [Heng Ji](https://siebelschool.illinois.edu/about/people/faculty/hengji) (UIUC) as a keynote speaker
- May 21st, 2026: We are excited to announce [Mausam](https://www.cse.iitd.ac.in/~mausam/) (IIT Delhi) as a keynote speaker
- April 27th, 2026: We receive news that the workshop will be held on October 28, 2026
- April 13th, 2026: The Web page of AKBC goes live

<a name="dates"></a>

## Important Dates

<table class="dates-table">
  <tbody>
    <tr><td>Direct submission (research + vision)</td><td><span class="date-pill">July 27, 2026</span></td></tr>
    <tr><td>Direct submission (shared task)</td><td><span class="date-pill">August 15, 2026</span></td></tr>
    <tr><td>ARR commitment (research)</td><td><span class="date-pill">August 25, 2026</span></td></tr>
    <tr><td>Notification of acceptance</td><td><span class="date-pill">September 1, 2026</span></td></tr>
    <tr><td>Camera ready due</td><td><span class="date-pill">September 10, 2026</span></td></tr>
    <tr><td>Workshop date</td><td><span class="date-pill date-pill-highlight">October 28, 2026</span></td></tr>
  </tbody>
</table>

<a name="cfp"></a>

## Call for Papers

The 10th Workshop on Automated Knowledge Base Construction (AKBC) returns in 2026, bringing together researchers and practitioners working on the construction, integration, and use of structured knowledge in the era of large language models (LLMs). As LLMs continue to transform NLP, challenges such as hallucinations, lack of provenance, and limited reasoning reliability highlight the need for robust, explicit, and usable knowledge representations.

AKBC provides a venue at the intersection of natural language processing, knowledge representation, databases, and machine learning, with a particular focus on how symbolic structure can ground, constrain, and enhance generative models.

We invite submissions on topics including, but not limited to:

#### Knowledge for Generative Models

- Knowledge-aware pretraining and fine-tuning
- Factuality, attribution, and verification in generation
- Neuro-symbolic methods and hybrid models
- Injecting and editing knowledge in LLMs

#### Building and Maintaining Knowledge

- Knowledge extraction and consolidation from text and multimodal data
- Knowledge graphs, ontologies, and schema alignment
- Knowledge base construction, completion, and continual updates

#### Retrieval and Reasoning

- Retrieval-augmented generation (RAG) with structured sources
- Graph-based and knowledge-intensive question answering
- Multi-hop reasoning and interaction with KBs

#### Vision Papers

- New roles for structured knowledge in generative models
- Knowledge-aware training objectives, pretraining, and fine-tuning
- New architectures for combining symbolic knowledge and generative models
- Benchmarks, evaluations, and research agendas for knowledge-grounded generation
- Position papers on the future of knowledge bases, reasoning, and trustworthy AI

### Submission Types

We welcome three types of submissions, reflecting both mature research results and forward-looking ideas at the intersection of structured knowledge and generative AI. All submissions have to follow the [EMNLP formatting instructions](https://2026.emnlp.org/calls/main_conference_papers/#paper-submission-details). All submissions are double-blind.

#### 1. Regular Research Papers ([ARR](https://openreview.net/group?id=EMNLP/2026/Workshop/AKBC_ARR_Commitment) or [direct submission](https://openreview.net/group?id=EMNLP/2026/Workshop/AKBC))

For original research contributions. We accept papers reviewed through the ACL Rolling Review (ARR); authors may submit to ARR and commit their papers to AKBC. Accepted papers will follow standard ACL/EMNLP reviewing policies. The page limit is 8 pages + references.

#### 2. Vision Papers ([direct submission](https://openreview.net/group?id=EMNLP/2026/Workshop/AKBC))

For bold ideas, emerging directions, and unifying perspectives. We particularly encourage papers that articulate new opportunities and challenges for knowledge base construction in the age of LLMs, and that help define promising research agendas for the field. The page limit is 4 pages + references.

#### 3. Shared Task Papers ([direct submission](https://openreview.net/group?id=EMNLP/2026/Workshop/LM-KBC_Shared_Task))

For system descriptions and analyses related to the [AKBC shared task]({{ site.baseurl }}/shared-task.html), co-located with the workshop. These submissions should describe participating systems, methodologies, and lessons learned from the challenge. The page limit is 4 pages + references.

#### Presentation Formats

Accepted papers will be presented as posters, with a selection invited for lightning talks. Remote participation is possible for both attendees and authors. Instead of presenting their poster physically, remote authors will upload heir poster to the workshop Web site. The workshop will also feature invited keynotes from leading researchers in academia and industry.

<a name="shared-task"></a>

## Shared Task

Large language models contain a substantial amount of factual knowledge. Turning that knowledge into reliable knowledge base entries, however, is much harder than answering a single factual question.

Given a subject *s* and a relation *r*, predict the complete set of correct object strings {o₁, o₂, …, oₖ}. Unlike standard factual QA, a subject may have zero, one, or many correct objects. The goal is to construct a complete and precise KB entry.

Further details are on the [shared task page]({{ site.baseurl }}/shared-task.html).

<a name="speakers"></a>

## Invited Speakers

<div class="speakers-grid">
{% for s in site.data.speakers %}
  <div class="speaker-card">
    <a href="{{ s.url }}"><img src="{{ site.baseurl }}/assets/img/{{ s.thumbnail }}" alt="{{ s.speaker }}"></a>
    <div class="speaker-name"><a href="{{ s.url }}">{{ s.speaker }}</a></div>
    <div class="speaker-affil">{{ s.institution }}</div>
  </div>
{% endfor %}
  <div class="speaker-card speaker-card-tba">
    <div class="speaker-tba-circle">TBA</div>
    <div class="speaker-name">More to be announced</div>
  </div>
</div>

<a name="organization"></a>

## Organization

### Organizing Committee

<ul class="organizers-list">
{% for o in site.data.organizers %}
  <li>{% if o.url %}<a href="{{ o.url }}">{{ o.name }}</a>{% else %}{{ o.name }}{% endif %}, {{ o.location }}</li>
{% endfor %}
</ul>

Contact us at [akbc2026@gmail.com](mailto:akbc2026@gmail.com) for workshop inquiries, or at [akbc2026-shared-task@googlegroups.com](mailto:akbc2026-shared-task@googlegroups.com) for shared task inquiries.

### Program Committee

<ul>
{% for p in site.data.pc %}
  <li>{% if p.url %}<a href="{{ p.url }}">{{ p.name }}</a>{% else %}{{ p.name }}{% endif %}{% if p.affiliation %} ({{ p.affiliation }}){% endif %}</li>
{% endfor %}
</ul>
