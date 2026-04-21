# exp16
AIM

To explore and apply Natural Language Processing (NLP) techniques in Python using the NLTK library, focusing on text preprocessing methods such as tokenization, stop-word removal, stemming, lemmatization, part-of-speech tagging, and word frequency analysis.

THEORY

Natural Language Processing (NLP) is a branch of artificial intelligence that enables computers to analyze, understand, and interpret human language. Before performing analysis, text data must be preprocessed to make it structured and meaningful. This involves breaking text into smaller components (tokenization), eliminating commonly used but insignificant words (stop words), reducing words to their base or root form (stemming and lemmatization), identifying grammatical categories (part-of-speech tagging), and studying the frequency of words.

The NLTK (Natural Language Toolkit) library in Python offers a wide range of tools and datasets to efficiently perform these tasks. Due to its flexibility and ease of use, it is widely applied in areas such as text mining, sentiment analysis, and language modeling.

FUNCTIONS (ONE-LINE EXPLANATIONS)
nltk.download() – Retrieves and installs required NLP datasets and resources
word_tokenize() – Breaks text into individual words or tokens
sent_tokenize() – Divides text into sentences
stopwords.words() – Provides a list of common words to be removed from text
PorterStemmer() – Applies stemming to reduce words to their root form
stem() – Converts a word into its stemmed version
WordNetLemmatizer() – Transforms words into their base dictionary form
lemmatize() – Returns the meaningful root form of a word
pos_tag() – Assigns grammatical labels (such as noun, verb, etc.) to words
FreqDist() – Computes the frequency distribution of words in text
most_common() – Displays the most frequently occurring words along with their counts
CONCLUSION

In this study, various NLP techniques were successfully implemented using the NLTK library in Python. The process of text preprocessing—including tokenization, stop-word removal, stemming, lemmatization, part-of-speech tagging, and frequency analysis—was understood and applied. These techniques play a vital role in preparing textual data for advanced tasks in text mining and language processing.
