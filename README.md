# Abstractive-and-Extractive-Text-Summarization

Text summerization is the task of generating a short or a summarized description of a large text. For large documents, the summarization goal is to extract either the most information by either extracting the important sentences, or abstractly describe the most important sentences such that it looks more intuitive[1]. The first technique is called extractive summarization and the second one is called abstractive summarization. This project aims to provide a comparative analysis between extractive and abstractive summarizations using predetermined  approaches. For extractive approach, the approaches to be used are the Frequency-driven Approaches such as Word Probability. For the abstractive summarization, a deep learning based approach can be used such as the GRU based encoder-decoder, LSTM based encoder-decoder and Bidirectional LSTM structure with applying the Attention mechanism. There are many datasets on which the previously mentioned approaches can be implemented. These datasets are the Document Understanding Conference (DUC) dataset, the TIPSTER Text Summarization Evaluation Conference (SUMMAC), the Legal Case Reports Data Set and Amazon Food Reviews. `For the scope of this project, the Amazon Food Reviews dataset will be used for implementation and evaluation. For evaluating each approach, the  Recall Oriented Understudy for Gisting Evaluation (ROUGE) is to be used as a key measure to compare all the implemented approaches[2].`

# Content

1.   Extractive Summarization using word frequency count.
2.   Dataset preprocessing.
3.   Abstractive summarization with Attention mechanism (using GRU, LSTM, Bi-directional LSTM) and Evaluation. 
4.   Conclusion.  

# Main prerequisites for the summarization task
- Python == 3.X
- Keras == 2.3.1
- Tensorflow == 2.2.0 
- Spacy == 2.2.4


# References

- [1] Allahyari, M., Pouriyeh, S., Assefi, M., Safaei, S., Trippe, E. D., Gutierrez, J. B., & Kochut, K. (2017). Text summarization techniques: a brief survey. arXiv preprint arXiv:1707.02268. 
- [2] Nikolov, N. I., Pfeiffer, M., & Hahnloser, R. H. (2018). Data-driven summarization of scientific articles. arXiv preprint arXiv:1804.08875.
- [3] Lin, C. Y. (2004, July). Rouge: A package for automatic evaluation of summaries. In Text summarization branches out (pp. 74-81).
- [4] Britz, D., Goldie, A., Luong, M. T., & Le, Q. (2017). Massive exploration of neural machine translation architectures. arXiv preprint arXiv:1703.03906.


