# artificially-correct-hackathon
Submission for Artificially Correct Hackathon 2021.

**Task: Identifying sentences susceptible to machine translation bias**

**Team: Aleksandra Konovalova, Lukas Felser, Laura König**

Machine Translation is not perfect, and it can make mistakes in translations. However, if we could identify sentences that are more susceptible to a bias, we could prevent some of them happening.

Full description can be found here:
https://dcsaunders.github.io/ac_hackathon
Or here:
https://www.goethe.de/prj/one/en/aco/ver/hac/cha.html#i7094315

The idea was to create solution that could be potentially language-independent. We tested several approaches:
- Logistic Regression (sklearn)
- NER and dependency trees (spacy)
- pretrained Word Embeddings (gensim, just a quick look)
