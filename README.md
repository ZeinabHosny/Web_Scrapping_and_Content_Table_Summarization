#### the task is about:

- web scrapping 

- reading table of content from a pdf

- summarizing the table of content 

#### Table Of Content Summarization Steps ( sentence embedding method):
1. Reading the table of content.
2. Choosing only level one sentences to summarize.
3. Cleaning TOC sentences.
4. Summarizing each sentence in TOC:
    1. Splitting into words (Tokenization).
    2. Vectorizing each word using TF-Hub Universal sentence Encoder (embedding matrix).
    3. Applaying Kmeans clusturing to cluster the words into certain no. of clusters.
    4. Forming sentence summary from the words which are the nearst to clusteres centroids. from each cluster we take a words this word is the closest to the centroid. Then we join these words together to form the summarized sentence.
5. Printing the summary of TOC.


