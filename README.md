# top

</p>
<h1 align="center"> Topic Modeling on News Articles </h1>
<h3 align="center"> AlmaBetter Verfied Project - <a href="https://www.almabetter.com/"> AlmaBetter School </a> </h5>


![ea-topic-modeling-hero](https://user-images.githubusercontent.com/109129303/178749324-19ba9ec2-2e47-4fed-9221-825e49e1e0dc.jpg)

<p>Data and Problem Statement:

The dataset contains a set of news articles for each major segment consisting of business, entertainment, politics, sports and technology. In this project task is to identify major themes/topics across a collection of  news articles. using probabulistic model such as Latent Dirichlet Allocation (LDA) to find out the patterns and themes in between topics</p>

<h2> :floppy_disk: Project Files Description</h2>

<p>This Project includes 3 executable files, 1 text files , 1 directories as follows:</p>
<h4>Executable Files:</h4>
<ul>

 <li><b>Topic_Modeling_on_News_Articles1__spacy.ipynb</b> - Includes all information on basic topic modeling through LDA and using spacy </li>
  <li><b>Topic_Modeling_on_News_Articles__Using_NLTK_Gensim.ipynb</b> - Includes the information of basic implementation of TF-IDf and LDA throgh using nltk and genism </li>
  
 <li><b>LDA_Topic_Modelling (1).ipynb</b> - Includes information on how LDA is performing by giving probability score on sample documen by using TF-IDF and Bag of words and its performance on unseen document </li>
</ul>

<h4>Output Files:</h4>
<ul>
  <li><b>result.txt</b> - Contains probabulitic scores on sample and unseen document .</li>
  
  </ul>


<h4>Source Directories:</h4>
<ul>
  <li><b>Dataset</b> - Includes dataset for topic modeling of news aricles in csv format.</li>
  
</ul>


</ul>

![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)

<h2> :book: Tokenization </h2>

<p> Tokenization is the first step in any NLP pipeline. It has an important effect on the rest of your pipeline. A tokenizer breaks unstructured data and natural language text into chunks of information that can be considered as discrete elements. The token occurrences in a document can be used directly as a vector representing that document. 

This immediately turns an unstructured string (text document) into a numerical data structure suitable for machine learning. They can also be used directly by a computer to trigger useful actions and responses. Or they might be used in a machine learning pipeline as features that trigger more complex decisions or behavior.

<h2> :book: Lemitization </h2>

<p> Lemmatization is a text normalization technique used in Natural Language Processing (NLP). It has been studied for a very long time and lemmatization algorithms have been made since the 1960s.

Essentially, lemmatization is a technique that switches any kind of a word to its base root mode. Lemmatization is responsible for grouping different inflected forms of words into the root form, having the same meaning.

![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)

<h2> :book: TF-IDF </h2>

<p> TF-IDF stands for “Term Frequency — Inverse Document Frequency”. This is a technique to quantify words in a set of documents. We generally compute a score for each word to signify its importance in the document and corpus. This method is a widely used technique in Information Retrieval and Text Mining.

If I give you a sentence for example “This building is so tall”. It's easy for us to understand the sentence as we know the semantics of the words and the sentence. But how can any program (eg: python) interpret this sentence? It is easier for any programming language to understand textual data in the form of numerical value. So, for this reason, we need to vectorize all of the text so that it is better represented.

By vectorizing the documents we can further perform multiple tasks such as finding the relevant documents, ranking, clustering, etc. This exact technique is used when you perform a google search (now they are updated to newer transformer techniques). The web pages are called documents and the search text with which you search is called a query. The search engine maintains a fixed representation of all the documents. When you search with a query, the search engine will find the relevance of the query with all of the documents, ranks them in the order of relevance and shows you the top k documents. All of this process is done using the vectorized form of query and documents.

Now coming back to our TF-IDF,

TF-IDF = Term Frequency (TF) * Inverse Document Frequency (IDF)



<h2> :book: Bag of Words </h2>

<p> Bag of words is a Natural Language Processing technique of text modelling. In technical terms, we can say that it is a method of feature extraction with text data. This approach is a simple and flexible way of extracting features from documents.

A bag of words is a representation of text that describes the occurrence of words within a document. We just keep track of word counts and disregard the grammatical details and the word order. It is called a “bag” of words because any information about the order or structure of words in the document is discarded. The model is only concerned with whether known words occur in the document, not where in the document.

One of the biggest problems with text is that it is messy and unstructured, and machine learning algorithms prefer structured, well defined fixed-length inputs and by using the Bag-of-Words technique we can convert variable-length texts into a fixed-length vector.

Also, at a much granular level, the machine learning models work with numerical data rather than textual data. So to be more specific, by using the bag-of-words (BoW) technique, we convert a text into its equivalent vector of numbers.




![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)

<p>The order of execution of the program files is as follows:</p>


<p><b>1) LDA_Topic_Modelling (1).ipynb</b></p>
<p> This file must be executed, to define how LDA works and its performance one sample document and unseen document and its probabulitic scores on both the documents using Bag of words and TF-IDf


  
  ![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)
  
  <h2 id="credits"> :scroll: Credits</h2>

< Manoj Korukonda > | Avid Learner | Data Scientist | Machine Learning Engineer | Deep Learning enthusiast

<p> <i> Contact me for Data Science Project Collaborations</i></p>


[![LinkedIn Badge](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/manoj-korukonda/)
[![GitHub Badge](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Manoj-Korukonda)


![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)

<h2> :books: References</h2>
<ul>
  <li><p>'Topic Modelling with LSA and LDA'. [Online].</p>
      <p>Available: https://www.kaggle.com/code/rcushen/topic-modelling-with-lsa-and-lda
  </li>
  
  <li><p>'Tokenization'. [Online].</p>
      <p>Available: https://neptune.ai/blog/tokenization-in-nlp
  </li>
   <li><p>'Lemitization'. [Online].</p>
      <p>Available: https://www.engati.com/glossary/lemmatization#:~:text=REQUEST%20A%20DEMO-,What%20is%20Lemmatization%20in%20NLP%3F,to%20its%20base%20root%20mode.
  </li>
  <li><p>'TF-IDf '. [Online].</p>
      <p>Available:https://www.capitalone.com/tech/machine-learning/understanding-tf-idf/ /</p>
  </li>
  <li><p>'
  A Gentle Introduction to Topic Modelling, Latent Semantic Analysis and Latent Dirichlet Allocation'. [Youtube].</p>
      <p>Available:https://www.youtube.com/watch?v=mNkeRh2__E8&list=LL&index=8</p>
  </li>
  
  
</ul>

![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)
</p>
  </li>
  
</ul>

![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)
   
