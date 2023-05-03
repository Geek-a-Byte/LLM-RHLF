# fairGPT
raw idea: a conversational bot which will work as an automated detector of unfair/privacy-risky clauses in online terms of service 

- GPT [Generative pre-trained transformer]

## dataset
- https://github.com/corticai/claudette
- The clauses are broken up into 9 categories as per described below. The fairness is measured on a scale of 1 - 4 (Fair: 1, Potentially Unfair: 2, Clearly Unfair: 3, Unclassified: 4)

![414e33_7eabace3b393446dac6e8654b595f5f7~mv2 (1)](https://user-images.githubusercontent.com/59027621/236007632-1400bf42-adb6-4b23-94f5-686d59cef10f.png)

## necessary papers
- [ ] https://arxiv.org/abs/1706.03762
- [ ] https://arxiv.org/pdf/1805.01217v2.pdf
- [ ] https://www.corticai.com/post/machine-learning-nlp-applications-contract-clauses-legal-review
- [ ] https://link.springer.com/article/10.1007/s10506-019-09243-2

## constraints
- [ ] should be able to have large amount of data as input
- [ ] the model should be constantly learning from the conversations
