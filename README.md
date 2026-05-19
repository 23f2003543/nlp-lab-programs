# 📚 NLP Lab Programs

> **VTU 6 Semester Natural Language Processing Laboratory Programs**

A comprehensive collection of NLP implementations demonstrating core concepts from tokenization to machine translation.

---

## 📋 Programs Overview

| # | Program | Topic | Description |
|---|---------|-------|-------------|
| **1** | Text Preprocessing | NLP Fundamentals | Tokenization, Filtration, Stop Word Removal, Stemming |
| **2** | N-gram Modeling | Probability Distribution | Unigrams, Bigrams, Trigrams Analysis |
| **3** | Minimum Edit Distance | String Similarity | Levenshtein Distance Implementation |
| **4** | Parsing Techniques | Syntax Analysis | Top-Down & Bottom-Up Parsers |
| **5** | Naive Bayes Classifier | Text Classification | Movie Review Genre Classification |
| **6** | Information Retrieval | Corpus Analysis | Brown, Inaugural, Reuters, UDHR Corpora |
| **7** | WordNet Applications | Lexical Database | Synonyms & Antonyms Extraction |
| **8** | Machine Translation | Seq2Seq Models | Low-Resource Language Translation |

---

## 🎯 Key Concepts Covered

### 1️⃣ Text Preprocessing
```
Raw Text → Tokenization → Filtration → Stop Word Removal → Stemming
```
**Key Operations:**
- ✅ Word Tokenization
- ✅ Script Validation
- ✅ English Character Filtering
- ✅ Stop Word Removal (NLTK)
- ✅ Porter Stemming

### 2️⃣ N-gram Models
Analyzes probability distributions across sentences:
- **Unigrams (1-gram)**: P(word)
- **Bigrams (2-gram)**: P(word₂|word₁)
- **Trigrams (3-gram)**: P(word₃|word₁,word₂)

### 3️⃣ Minimum Edit Distance (Levenshtein)
Dynamic Programming approach to measure string similarity:
- **Substitution** (kitten → sitten)
- **Insertion** (kitten → kittens)
- **Deletion** (kitten → kiten)

### 4️⃣ Parsing Techniques
Context-Free Grammar Implementation:
- **Top-Down Parser**: Recursive descent parsing
- **Bottom-Up Parser**: Shift-reduce parsing

### 5️⃣ Naive Bayes Classification
Probabilistic classifier with Add-1 smoothing:
- Training on labeled documents
- Computing prior and likelihood probabilities
- Classification of new documents

### 6️⃣ Information Retrieval
Corpus Analysis and Processing:
- **Brown Corpus**: Tagged POS collection
- **Inaugural Corpus**: Presidential speeches
- **Reuters Corpus**: News categorization
- **UDHR Corpus**: Universal Declaration of Human Rights

**Advanced Features:**
- Conditional Frequency Distributions
- Tagged Corpora Analysis
- Word Tokenization & POS Tagging
- Custom Corpora Creation

### 7️⃣ WordNet Integration
Lexical Database for English:
- **Synonyms**: Multiple word alternatives
- **Antonyms**: Opposite meanings
- **Synsets**: Groups of cognitive synonyms
- **Lemmas**: Base word forms

### 8️⃣ Machine Translation (Seq2Seq)
Neural machine translation for low-resource languages:
- **Encoder-Decoder Architecture**: LSTM-based
- **Data Augmentation**: Back-translation techniques
- **Tokenization & Padding**: Sequence preparation
- **Translation**: Real-time inference

---

## 🧠 NLP Facts & Insights

<table>
<tr>
<td>

### 💡 Fact #1: Evolution of NLP
NLP has evolved through three major eras:
- **Symbolic Era (1950s-1980s)**: Rule-based systems
- **Statistical Era (1990s-2000s)**: Machine learning approaches
- **Neural Era (2010s-present)**: Deep learning & Transformers

</td>
<td>

### 💡 Fact #2: Language Complexity
Natural language has unique challenges:
- **Ambiguity**: "bank" (financial/river)
- **Context Dependency**: Pronouns and references
- **Idioms**: "raining cats and dogs"
- **Morphological Variation**: "run", "runs", "running"

</td>
</tr>
<tr>
<td>

### 💡 Fact #3: Tokenization Importance
Tokenization is crucial because:
- **90% accuracy improvement** in many NLP tasks
- Different strategies for different languages
- Affects downstream performance significantly
- Critical for languages without spaces (Chinese, Japanese)

</td>
<td>

### 💡 Fact #4: The Curse of Dimensionality
In NLP:
- **Vocabulary size**: 100K+ words in standard English
- **N-gram combinations**: Exponentially grow with n
- **Solution**: Dimensionality reduction & embeddings
- **Impact**: Word2Vec, GloVe, FastText emergence

</td>
</tr>
<tr>
<td>

### 💡 Fact #5: Stemming vs Lemmatization
| Aspect | Stemming | Lemmatization |
|--------|----------|--------------|
| **Speed** | Fast | Slower |
| **Accuracy** | Moderate | High |
| **Output** | May not be valid words | Always valid |
| **Use Case** | IR, rough processing | Fine-grained analysis |

</td>
<td>

### 💡 Fact #6: Transformer Revolution
**BERT (2018) & Beyond:**
- **18 layers** of bidirectional attention
- Trained on **3.3 billion words**
- **11 languages** supported
- **2.7 billion downloads** (2023)
- Foundation for GPT, T5, LLaMA models

</td>
</tr>
<tr>
<td>

### 💡 Fact #7: Sequence-to-Sequence Models
Introduced by **Sutskever et al. (2014)**:
- **Two LSTM networks**: Encoder + Decoder
- **Attention mechanism**: (2015) - breakthrough
- **Applications**: Machine translation, Q&A, summarization
- **Success Rate**: 70%+ BLEU score on WMT datasets

</td>
<td>

### 💡 Fact #8: Corpus Statistics
Popular NLP Corpora:
- **Brown Corpus**: 1M words, 15 categories
- **Wikipedia**: 6B words, 6M articles
- **Google Books**: 130B words, 4M books
- **Common Crawl**: 250B+ words, entire web snapshots

</td>
</tr>
<tr>
<td>

### 💡 Fact #9: Edit Distance Applications
Minimum Edit Distance is used in:
- **Spell Checking**: ~95% accuracy
- **DNA Sequencing**: Biological research
- **Plagiarism Detection**: Content similarity
- **Fuzzy Matching**: Record linkage in databases

</td>
<td>

### 💡 Fact #10: Naive Bayes Performance
Despite simplicity:
- **80-90% accuracy** on text classification
- **Fast training**: O(n) complexity
- **Real-world use**: Spam detection filters
- **Drawback**: Assumes feature independence

</td>
</tr>
</table>

---

## 🚀 Technologies & Libraries

### Core Libraries
- **NLTK**: Natural Language Toolkit (tokenization, POS tagging)
- **TensorFlow/Keras**: Deep learning framework
- **NumPy**: Numerical computing
- **Pandas**: Data manipulation

### Key Algorithms
- Porter Stemmer (morphological analysis)
- Tokenization (word/sentence split)
- Hidden Markov Models (POS tagging)
- Attention Mechanisms (sequence models)

---

## 📊 Program Statistics

```
Total Programs:        8
Total Lines of Code:   500+
Jupyter Notebooks:     1
Algorithms Covered:    10+
Libraries Used:        5+
Difficulty Level:      Beginner → Intermediate
```

---

## 🎓 Learning Outcomes

By completing these programs, you will understand:

✅ **Fundamentals**: Text preprocessing pipeline  
✅ **Probability**: N-gram models and distributions  
✅ **Similarity**: Edit distance algorithms  
✅ **Syntax**: Parsing techniques and grammars  
✅ **Classification**: Naive Bayes classifier  
✅ **Retrieval**: Corpus analysis and frequency  
✅ **Lexical**: WordNet and semantic relations  
✅ **Neural**: Seq2Seq architecture and translation  

---

## 📈 NLP Industry Applications

| Domain | Application |
|--------|-------------|
| 🏥 **Healthcare** | Clinical note analysis, medical coding |
| 💰 **Finance** | Sentiment analysis, risk assessment |
| 🛒 **E-commerce** | Product recommendation, reviews |
| 🔒 **Security** | Spam detection, content moderation |
| 📱 **Social Media** | Trend detection, fake news identification |
| 🗣️ **Voice Assistants** | Alexa, Siri, Google Assistant |
| 🌐 **Translation** | Google Translate, DeepL |
| 📧 **Email** | Auto-reply, priority inbox |

---

## 🔗 Resources

- **NLTK Book**: https://www.nltk.org/book/
- **Stanford NLP**: https://nlp.stanford.edu/
- **Hugging Face**: https://huggingface.co/
- **Paper Trail**: arXiv.org (cs.CL section)

---

## 📝 Program Execution

Each program is self-contained in the Jupyter notebook:

```python
# Run in Google Colab or Jupyter
# All dependencies are installed in cells
# Execute cells sequentially for best results
```

---

## 🎯 Future Enhancements

- [ ] Add transformer-based models
- [ ] Implement attention visualization
- [ ] Add benchmark datasets
- [ ] Create web interface for demos
- [ ] Add multilingual support

---

<div align="center">

### ⭐ If this repository helps you, please star it! ⭐

**Made with ❤️ for NLP Enthusiasts**

</div>
