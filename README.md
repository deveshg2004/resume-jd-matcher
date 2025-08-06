# 📄 Resume–Job Description Matcher

An NLP-based project that automatically matches resumes with job descriptions using sentence embeddings and cosine similarity.

---

## 💡 Project Highlights

- 🧠 **Built with:** [Sentence-Transformers](https://www.sbert.net/) (`all-MiniLM-L6-v2` model)  
- 📊 **Scoring:** Uses cosine similarity to rank resume matches in percentage format  
- ⚙️ **NLP Tasks:** Embedding generation, similarity scoring  
- ✅ **Use Case:** Helps recruiters or systems auto-match best candidate resumes for a given job  

---

## 🧪 Example Matches

| Resume   | Best JD Match | Match % |
|----------|----------------|---------|
| Resume A | JD 1           | ~98%    |
| Resume B | JD 2           | ~97%    |
| Resume C | JD 3           | ~99%    |

---

## 🛠️ Tech Stack

- Python  
- Sentence Transformers (`all-MiniLM-L6-v2`)  
- Pandas (for data formatting)  
- Cosine similarity (via `sentence-transformers.util`)

---

## 🚀 How It Works

1. Load pre-trained embedding model (`all-MiniLM-L6-v2`)  
2. Convert resume and JD texts to embeddings  
3. Compute cosine similarity matrix  
4. Display similarity scores (in %) and best matching JD for each resume  

---

## 👤 Author

**Devesh Gogia**  
GitHub: [@deveshg2004](https://github.com/deveshg2004)
Email: deveshgogia22@gmail.com
---


⭐ **If you like this project, consider giving it a star!**
