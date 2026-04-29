---
layout: default
title: "Horizon Summary: 2026-04-29 (VI)"
date: 2026-04-29
lang: vi
---

> From 607 items, 2 important content pieces were selected

---

1. [Lightweight and Production-Ready PDF Visual Element Parsing](#item-1) ⭐️ 7.0/10
2. [PDF-WuKong: A Large Multimodal Model for Efficient Long PDF Reading with End-to-End Sparse Sampling](#item-2) ⭐️ 7.0/10

---

<a id="item-1"></a>
## [Lightweight and Production-Ready PDF Visual Element Parsing](https://arxiv.org/abs/2604.23276) ⭐️ 7.0/10

A new lightweight PDF parsing framework has been released that accurately detects visual elements (figures, tables, forms) and associates captions, achieving over 96% detection accuracy and 93% caption association accuracy on benchmarks. This framework is production-ready and reduces latency by over 2x compared to state-of-the-art parsers, making it ideal for multimodal RAG systems and document understanding tasks in enterprise settings. The framework combines spatial heuristics, layout analysis, and semantic similarity for caption association. It significantly outperforms existing parsers and large vision-language models on the MMDocRAG benchmark while being lightweight enough for deployment.

rss · ArXiv cs.AI · Apr 28, 04:00

**Background**: PDF documents often contain complex visual elements like figures, tables, and forms that are critical for document understanding and multimodal retrieval-augmented generation (RAG). Existing parsers frequently miss these elements or extract non-informative artifacts such as watermarks and logos, degrading downstream tasks.

**Tags**: `#pdf parsing`, `#visual element extraction`, `#document understanding`, `#multimodal rag`, `#production ready`

---

<a id="item-2"></a>
## [PDF-WuKong: A Large Multimodal Model for Efficient Long PDF Reading with End-to-End Sparse Sampling](https://arxiv.org/abs/2410.05970) ⭐️ 7.0/10

Researchers introduce PDF-WuKong, a multimodal large language model that uses sparse sampling to efficiently handle long PDF documents with interleaved text and images, achieving 8.6% higher F1 than proprietary models on document QA. This model addresses the pain point of processing long PDFs, which is common in academic and office settings. Its efficiency and accuracy could enable practical document QA tools, benefiting Vietnamese offices that frequently handle lengthy reports and contracts. PDF-WuKong uses a sparse sampler to select the most relevant paragraphs or diagrams for user queries, reducing computational load. It is trained on PaperPDF, a dataset of 1.1 million QA pairs from English and Chinese academic papers.

rss · ArXiv cs.AI · Apr 28, 04:00

**Background**: Multimodal document understanding involves processing both text and images in documents. Existing LLMs often struggle with long PDFs due to high computational cost. Sparse sampling is a technique that selects only key information, improving efficiency.

**Tags**: `#pdf`, `#multimodal`, `#document-qa`, `#sparse-sampling`, `#llm`

---