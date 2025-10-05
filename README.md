# Similar Company Recommender (Healthcare Investment)

## Overview
In the fast-evolving field of healthcare investments, private equity firms face challenges in identifying high-potential companies. This project presents a **scalable, data-driven recommendation system** designed to streamline the sourcing process by suggesting companies similar to a target company of interest.

---

## Key Features
- Computes **company similarity** using **NLP techniques**, leveraging **BERT** and **OpenAI embeddings**.  
- Combines textual embeddings with additional company features for a **hybrid similarity measure**.  
- Implements **two modeling strategies**:  
  1. Unified textual input of all features.  
  2. Distinct handling of each feature type for hybrid similarity computation.  
- Uses **cosine similarity** for pairwise comparison and **FAISS** for efficient large-scale retrieval.  
- Applies **ranking algorithms** to refine recommendations based on relevance.  
- Integrates **domain-specific knowledge**, supporting both automated analysis and expert judgment.

---

## Tech Stack
- **NLP Models:** BERT, OpenAI Embeddings  
- **Similarity Search:** FAISS  
- **Data Processing:** Python, Pandas, NumPy  
- **Ranking Algorithms:** Custom scoring pipeline  

---

## Impact
The system provides a **robust tool for private equity professionals** to efficiently identify promising healthcare investments, enabling faster and more data-driven decision-making. The framework is adaptable and could be applied to other investment domains or industries requiring similarity-based recommendations.

---

## Usage
> ⚠️ Note: Due to confidentiality and company data restrictions, the dataset and full code cannot be publicly shared.

If you find this project interesting or would like to discuss the methodology, feel free to **reach out to me** — I’m happy to walk through the concepts, architecture, and lessons learned.

---

## Future Improvements
- Incorporate additional structured features like financial metrics and market data.  
- Experiment with **multi-modal embeddings** (text + numerical + categorical).  
- Add **explainability features** to highlight why companies are considered similar.
