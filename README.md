this is a repo for natural-language-processing-exercises


## Goals

- Use Text Classification to assign tags or categories to text according to its content.

    - Some applications are sentiment analysis, topic labeling, spam detection, and intent detection.

    - Similar to topic modeling, but is supervised learning, so the set of possible classes are known/defined in advance.

- Use Topic Modeling to discover the abstract “topics” that occur in a collection of documents.

    - Latent Dirichlet Allocation (LDA) is a commonly used algorithm.

    - Similar to text classification but is unsupervised, like clustering, so the set of possible topics are unknown prior. The topics are defined as part of generating the topic models.

## General Process

1. Processing & Understanding Text
2. Feature Engineering & Text Representation
3. Supervised Learning Models for Text Data
4. Unsupervised Learning Models for Text Data
5. Advanced Topics


## Vocabulary

- **Entities**: Identify the type of entity extracted, such as a person, place or organization using Named Entity.
- **Stemming**: Reduce words to their root, or stem. For example, 'running','runs', and 'runned' become 'run'.
- **Lemmatization**: Return the base or dictionary form of a word, which is the lemma. For example 'better' becomes 'good' and 'walking' becomes 'walk'. Lemmatization trys to use context to choose the lemma (truncated form), where stemming just chops down to the root form of the word.
- **Tokenization**: Breaking text up into linguistic units such as words or n-grams.
- **Corpus**: Set of documents, dataset, sample, etc.
Document: A single observation, like the body of an email.
- **Sentence**: What it sounds like. Sometimes, you want to treat each sentence as a separate document and sometimes you want to merge all the sentences together to be a single document.