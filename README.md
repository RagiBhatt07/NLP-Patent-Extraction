
# ✅                                                  Patent Extraction

##                              Prepare Knowledge Graphs based on term extraction in Patents under Healthcare Domain

- Group Members:
    - BHATT Ragi
    - HACHEM Racha

---

## Methodology: The notebook is sectioned with the following topics.

- Term Extraction: try different methodologies to extract terms from patents, see what method gives the best terms.
- Prepare the Gold Corpus
- Train the Spacy Model
- Annotate with Prodigy
- Evaluate the model performance
- Plot Discussions


## ✅ Conclusion:

In conclusion, for the term extraction, we use patent_terms from our regex function which proved valuable, with some notable successes and challenges. The use of pre-trained Spacy provided a solid foundation for our model, but the performance score decreased after persistent annotations with Prodigy. However, after further annotation rounds, we improved the score to around 64%, which was a significant improvement. Unfortunately, in subsequent rounds, we observed a decline in performance, with the score dropping to 46% when we trained the NER model after correction despite our best efforts to correct the model.

However, with NER Teach the score improved to 73%.  The main challenge with annotations was domain-specific knowledge. With better insights into the domain, maybe a more meaningful term synthesis could have been worked upon.

Overall, we learned that proper annotation is crucial in achieving accurate and consistent results, and we should invest more time in improving the quality of our annotations. Additionally, we were able to build knowledge graphs with comparatively lesser outliers than the methods used earlier mentioned in the notebook, so this is almost a fully connected knowledge graph.

![image](https://github.com/RagiBhatt07/NLP-Patent-Extraction/assets/124009502/3059a610-7e27-495e-b907-5ef09c27682f)

