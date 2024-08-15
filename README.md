# Co-Author Network Analysis and the Impact of Large Language Models (LLMs) on Research Domains - Academic Project for EECS 6414

## Project Overview

This project focuses on analyzing the interactions between researchers who frequently publish on Arxiv, specifically those related to Large Language Models (LLMs). The study examines how co-authorship networks are formed between authors affiliated with both industry and academia, highlighting trends in publication patterns and the growing influence of LLMs across various research domains. 

## Motivation

The rapid rise of LLMs, such as GPT-4 and LLaMA, has significantly impacted research beyond traditional computer science. This project aims to uncover the underlying collaborative dynamics and publication trends within these transformative areas. By exploring the Arxiv dataset, this analysis provides insights into how LLMs are shaping the future of research across disciplines like computer science, statistics, and more.

## Research Questions

- What trends can be inferred from Co-Authorship Networks?
- How are industry-academia collaboration networks formed?
- How are institutions collaborating on LLM research?
- Which topics and authors are driving the growth of LLM research?
- What does the publication trend look like over time?

## Dataset

The dataset used for this analysis is derived from Arxiv, covering approximately 2.4 million entries across 8 primary disciplines with 61 sub-arxivs. The analysis focuses on data from 2018 to 2023, particularly in the fields of computer science and statistics, refined to include papers related to LLMs. Metadata points include Arxiv ID, author list, title, abstract, submission date, and subject categories.

## Methodology

### Data Preprocessing

1. **Keyword-Based Refinement:** Keywords like "language model," "GPT-4," "BERT," etc., were used to filter relevant publications.
2. **Subset Creation:** The dataset was divided into academic and industry-affiliated papers, facilitating a dual analysis of these groups.
3. **Network Construction:** Co-authorship networks were created for both subsets using tools like Python, NetworkX, and Gephi.

### Network Analysis

- **Node & Edge Addition:** Nodes represent individual authors, and edges represent co-authorship relationships.
- **Refinement:** The network was refined by removing isolated nodes and focusing on the most relevant components.
- **Visualization:** Interactive graphs were generated to represent the networks, illustrating the collaborative relationships.

## Findings

The analysis revealed significant trends in academic and industry collaborations, with a noticeable increase in LLM-related publications over the past few years. Academic institutions have shown consistent activity, while industry researchers are increasingly contributing to the field. The co-authorship networks provided insights into the structure and dynamics of these collaborations, identifying key contributors and influential papers.

## Conclusion

This project provides a comprehensive understanding of how LLMs are influencing research collaborations and publication trends. By analyzing the co-authorship networks, the study offers valuable insights into the evolving landscape of interdisciplinary research driven by LLMs.
