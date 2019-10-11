how to run my program:
run kz882_HW4_main.ipynb


initial MAP: 0.20962153846010492

1. Divide this count by the number of words in the document
2. Use the logarithm of the term frequency

MAP: 0.23721519047239004

3. Use 1 if the term exists in the document and 0 if it does not
4. Use idf of articles for idf of requests (it doesn't make sense to calculate idf of requests since user could always ask the same questions and make the idf of requests biased)

MAP: 0.31309265293114613