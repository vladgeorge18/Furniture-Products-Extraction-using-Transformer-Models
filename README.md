# **Extracting and Grouping Furniture Products Using Transformer Models**

## **Overview**  
This project uses **transformer models** to extract furniture product names from e-commerce websites and group URLs by product similarity. It employs:  

- **DistilRoBERTa** and **DistilBERT** for Named Entity Recognition (NER).  
- **all-mpnet-base-v2** for generating sentence embeddings and grouping similar products.  
- **Selenium** and **BeautifulSoup** for web scraping.  

The solution demonstrates how **NLP techniques** can enhance product extraction and clustering, providing valuable insights for retail applications.

---

## **Features**  
- **Product Name Extraction**: Identifies furniture products from web content using **DistilRoBERTa** and **DistilBERT** NER models.  
- **URL Grouping by Similarity**: Clusters URLs based on similar products using **cosine similarity** on sentence embeddings.  
- **Web Scraping Pipeline**: Collects data from dynamic web pages using **Selenium** and **BeautifulSoup**.  
- **Efficient Models**: Lightweight and performant models (**DistilRoBERTa**, **DistilBERT**, **all-mpnet-base-v2**) tailored for fast computation.  

---
