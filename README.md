
# 🧠 Generative AI Examples Collection

This repository contains four practical programs built using modern NLP and generative AI tools like Hugging Face Transformers, Sentence Transformers, LangChain, and Pydantic. Each example demonstrates a real-world use case.

---

## 🚀 Programs Included

---

### 1. 📊 Sentiment Analysis & Similarity Checker

- **Input:** Multiple sentences (separated by `|||`)  
- **Output:** Sentiment label and score per sentence, and similarity matrix (cosine similarity)  
- **Tools:** `transformers`, `sentence-transformers`

**Run using:**
```bash
python sentiment_similarity.py
```

---

### 2. 📝 Text Summarization

- **Input:** A long article, news report, or academic paragraph  
- **Output:** A concise summary of the input content using a pretrained transformer model  
- **Tools:** `transformers` (`facebook/bart-large-cnn`)

**Run using:**
```bash
python summarizer.py
```

---

### 3. 🌍 LangChain Travel Planner

- **Input:** User queries related to travel planning (e.g., "Suggest places in Paris", "What’s the weather in Tokyo?")  
- **Output:** Intelligent travel suggestions, mock flight/weather responses, or LLM-generated replies  
- **Tools:** `langchain`, `langchain_community`, `transformers`, `torch`

**Run using:**
```bash
python travel_assistant.py
```

---

### 4. ✅ Pydantic Data Validator

- **Input:** CLI-based form for entering product information (ID, name, price, date, optional rating)  
- **Output:** Validated JSON output or error messages if validation fails  
- **Tools:** `pydantic`, `datetime`

**Run using:**
```bash
python pydantic_product_entry.py
```
