---
permalink: /
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I am a Machine Learning Engineer at [Therap (BD) Ltd.](https://www.therapbd.com/), where I build and evaluate LLM systems: retrieval-augmented support chatbots, LLM-as-judge evaluation pipelines, and faithfulness checks for LLM-generated charts. I received my BSc in Computer Science and Engineering from the University of Dhaka in 2025.

I am interested in knowing when we can rely on what an AI system produces. For me this means evaluating LLMs reliably, checking their outputs against the sources they draw on, and understanding how well they reason about code. I am also interested in learning from graphs and hypergraphs, where much of the information lies in how groups of items are connected.

## Research interests

- Evaluation and reliability of LLM systems
- Graph and hypergraph representation learning
- Grounded retrieval-augmented generation
- LLM reasoning about code

## Research

**Overlap-Aware Sub-hypergraph Pattern Frequencies for Hypergraph-Level Classification**
<span class="pub-authors">**Nafiul Hasan Anik**, Nazira Jesmin Lina, Md Tanvir Alam, Md. Fahim Arefin</span>
<span class="pub-venue">*arXiv preprint*, 2026 · [[arXiv]](https://arxiv.org/abs/2610.33514) [[code]](https://github.com/NafiHasan/overlap-fhgm)</span>

We extend frequent sub-hypergraph mining with overlap labels and represent each hypergraph by the relative frequencies of its mined patterns. Under a fully inductive protocol on DHG-Bench, the method exceeds the best published mean Macro-F1 on 5 of 6 datasets. I led the feature design, experiments, and ablations.

**Can LLMs Judge Code Without Execution? Predicting Correctness of Submissions from Problem Descriptions and Source Code**
<span class="pub-authors">Nazira Jesmin Lina, Syed Mumtahin Mahmud, **Nafiul Hasan Anik**, Md Mosaddek Khan, Md. Fahim Arefin</span>
<span class="pub-venue">*Under review*, ACL Rolling Review, 2026</span>

We study whether LLMs can predict online-judge verdicts from a problem description and source code alone, comparing prompted frontier models with smaller open-weight models fine-tuned with QLoRA. Models are more reliable on verdicts with visible source-level evidence than on failures that depend on execution. I ran the baseline prompting experiments, fine-tuned the smaller models, and analyzed errors by verdict class.

## Professional Experience

**Machine Learning Engineer**, Therap (BD) Ltd., Dhaka (Apr 2025 – present)

- **LLM-as-judge evaluation of a support chatbot:** LLM-simulated users hold multi-turn conversations with the chatbot, sharing details only when asked. A judge model then scores each answer for correctness and completeness. I used it to compare 4 chatbot backends on 87 curated questions.
- **Retrieval-augmented support chatbot:** hybrid dense and keyword retrieval over a ~239K-record knowledge base, with query paraphrasing, reranking, and a validator that diagnoses failed answers and triggers a matching regeneration strategy. I also built the ingestion pipeline that cleans, chunks, and indexes the knowledge base, with LLM-generated concept phrases and incremental sync.
- **Faithfulness evaluation of LLM-generated charts:** checks whether charts an LLM generates (e.g. Vega-Lite, matplotlib) accurately reflect large nested XML health records. The ground truth is cross-checked between a rule-based parser and an LLM extractor.
- **RAG benchmarking and fine-tuning:** benchmarked RAG pipelines from single-passage to multi-hop and book-length QA; fine-tuned Gemma 3 with LoRA and BERT-family encoders.

## Education

**Bachelor of Science [2020 – 2025]**<br>
Department of Computer Science and Engineering, University of Dhaka, Bangladesh<br>
CGPA: **3.49/4.00**

## Achievements

- **ICPC Asia Dhaka Regional 2023:** [19th](https://icpc.global/ICPCID/VIASLG13GQUT) of 200+ teams
- **Online judges:** [Codeforces](https://codeforces.com/profile/N_Crypted) Expert (max rating 1719, 1000+ problems solved); [CodeChef](https://www.codechef.com/users/n_crypted) 5-star (max rating 2012)
- **Meta Hacker Cup 2024:** ranked [1094](https://www.facebook.com/codingcompetitions/hacker-cup/2024/certificate/578273137109641) of 5000+ participants worldwide in Round 2
- **SUST Inter-University Programming Contest 2023:** 15th of 120+ teams
- **Code Samurai 2024 (BJIT):** 11th in the inter-university hackathon
