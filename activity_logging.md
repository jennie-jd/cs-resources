## Activity logging

Future **To Do** items are marked in bold to remind myself.

_**July 31, 2024**_  
Another way to simplify sentence is to break down long sentences into shorter expressions with independent meanings.

_**July 30, 2024**_  
One way to simplfy a sentence is to exchange complex words into simple words.

_**July 29, 2024**_  
The task is to fine-tune a model to produce a simpler version of a complex sentence.

_**July 28, 2024**_  
Working on an exercise to use Open AI API.

_**July 27, 2024**_  
Machine translation can be more easily done nowadays with LLM's help.

_**July 26, 2024**_  
Learning about machine translation tasks this week.

_**July 24, 2024**_  
Chain of though prompting is even more powerful than few-shot prompting.

_**July 23, 2024**_  
But even with just Zero-shot prompting, if we tweak the wordings to give more guidance on contexts or styles, the model would perform better.

_**July 22, 2024**_  
Few-shot prompting give a few examples to help the model understand the pattern we are looking for, so it performs better than zero-shot prompting.

_**July 21, 2024**_  
Learning about prompt engineering, a different way to customize model usages than fine-tuning.

_**July 20, 2024**_  
Learning to use open AI API again. 

_**July 19, 2024**_  
A more expensive way is to fact-check after the texts have been generated. 

_**July 18, 2024**_  
Another way to improve accuracy is to fact-check during the reinforcement process, which is the layer after the pre-trained transformers layers. 

_**July 17, 2024**_  
RAG is also vulnerable to wrong information on the internet. If the retrieved results are fake, the model will not be able to return correct results either. 

_**July 16, 2024**_  
Retrieval Augmented Generation (RAG) means that the model issues a search query to the web, and then chooses which result to display - either the web-retrieved answer or one of the model-generated answers. There is still a chance for the model to "prefer" rendering the model generated answer, which may be incorrect.

_**July 15, 2024**_  
Because LLMs mainly generate results based on probability outputs, we don't know if they really understand the "meaning" of the generates texts. Therefore, there are fact-checking techniques being studied nowadays to improve the chance of correct answers, including RAG - Retrieval Augmented Generation.

_**July 14, 2024**_  
Reinforcement learning is not used in the pre-training of these LLMs, but is used in the fune-tuning / application layers.

_**July 13, 2024**_  
Learning about bidirectional models and their difference with autoregressive models.

_**July 12, 2024**_  
As an example, the encoder-decoder framework is utilized for tasks such as machine translation, where the encoder processes the input sequence (source language) and converts it into a fixed-length context vector, which the decoder then uses to generate the output sequence (target language). This approach, along with the attention mechanism, was foundational in enhancing performance in text summarization, image captioning, and speech recognition.

_**July 11, 2024**_  
Encoder decoder is a framework used to apply NN to sequence generation tasks.

_**July 10, 2024**_  
Fined tuned BERT models can do sequence classification, sequence pair classification, and token classification.

_**July 9, 2024**_  
BERT can be fined-tuned to do classification tasks too.

_**July 8, 2024**_  
Fine-tuning BERT involves giving it specific training examples in Q&A format, so it learns this pattern.

_**July 7, 2024**_  
Learning about fining tuning BERT models.

_**July 6, 2024**_  
Attention is the key invention that leads to transformer models working so well.

_**July 5, 2024**_  
Attention is designed to let the contexts pull words towards them, so the words' vector representations also encode the contexts.

_**July 3, 2024**_  
First step is to learn about the attention mechanism in transformer models.

_**July 2, 2024**_  
Continue to learn about the transformer model this week. The paper was first published by Google researchers.

_**July 1, 2024**_  
Learning about HMM hidden markov model for parts of speeh tagging.

_**June 30, 2024**_  
Learning about parts of speech this week.

_**June 29, 2024**_  
RNN networks can "memorize" histories by keeping a part of the history in the parameters, but they are also prone to not being able to forget irrelavant histories.

_**June 27, 2024**_  
The models are downloaded from hugging face.

_**June 26, 2024**_  
Learning about pre-trained transformer models this week!

_**June 25, 2024**_  
Trained some RNN models with pytorch.

_**June 24, 2024**_  
It's impressive and surprising to me that libraries like pytorch has enabled everyone to train large neural network models.Google Colab allows users to use NVIDIA GPUs to run the extremely large models (but it has rate limits). I believe that as technology advances, more tools and libraries will be built, GPUs will become cheaper, and average people will have access to a variety of appliations to create things on their own - movies, music, personal utility tools and so on.

_**June 23, 2024**_  
Learning pytorch's nn.Module for defining neural networks.

_**June 21, 2024**_  
Learning pytorch for the first time, which seems powerful but somewhat difficult to grasp at first.

_**June 19, 2024**_  
Learning the mathematic notations for multi-layer models.

_**June 18, 2024**_  
Learning again about perceptron models and neural network models for natural language training.

_**June 16, 2024**_  
Used vectorization of words to cluster target words paraphrases into different clusters. For example, "apple" can mean a fruit or a computing device. Made use of the sklearn library to run clustering algorithms.

_**June 14, 2024**_  
There are many goals for semantic models like word sense, hypernymy, compositionality, grounding, logical inference, context dependence, that are not satisfied by current techniques. These areas are being researched as of today.  
In other words, our language models still lack the ability to actually "understand" meanings or contexts.  
In my opinion, these issues may not be resolved for another many years or may not be resolved at all.

_**June 13, 2024**_  
Vector space models can be used to solve analogy problems.

_**June 12, 2024**_  
Learning about advanced vector space models this week.

_**June 11, 2024**_  
Develop similarity metrics (cosine, jaccard, dice, etc.) to evaluate which documents are similar, or which words are similar.

_**June 10, 2024**_  
It's necessary to normalize the matrix so that a word's frequencies do not influence its significance. The common approaches include PPMI and tf-idf transformations.

_**June 9, 2024**_  
Learned about word-by-document (term-document matrix) and word-by-word (term-content matrix) vectors

_**June 8, 2024**_  
Vestor space models - vectorization of words help to capture the similarity and contexts for words, which builds the foundation for language models

_**June 7, 2024**_  
Text processing like adding an ending special character helps to distinguish entry boundaries when we use n-gram models to perform classification tasks

_**June 6, 2024**_  
N-gram can be used for classification tasks by training multiple n-grams and looking for the lowest perplexity model when it comes to predictions.
Next comment: text processing like adding special character to distinguish boundaries help

_**June 5, 2024**_  
N-gram interpolation uses a weighted approach to mix different sized n-grams, i.e., using various n values.

_**June 4, 2024**_  
Trained n-gram models on some sample Shakespear texts. The predictions do resemble Shakespear, although they don't mean anything.

_**June 3, 2024**_  
Building helper functions today for predicting next char based on N-gram contexts :)

_**June 2, 2024**_  
Building blocks for N-gram models include context-character paring and probability calculations.

_**May 31, 2024**_  
Starting a small-size N-gram language model training.

_**May 29, 2024**_  
Learning about N-gram language models.

_**May 28, 2024**_  
Features need to be normalized before being fed to the trainig models.

_**May 27, 2024**_  
Testing SVM, Decision Trees, and Random Forest models :)

_**May 26, 2024**_  
Used sklearn to fit some Naive Bayes and Logistic Regression models :)

_**May 24, 2024**_  
Precision and recall are inversely related, so the optimization comes from a balance of them (the fscore).

_**May 23, 2024**_  
Precision, recall and fscore are used to evaluate training models.

_**May 20, 2024**_  
Training usually divides data into training, development and test datasets to find the best fit and avoid over-fitting.

_**May 19, 2024**_  
Training a simple classification model for "complex" versus "simple" words

_**May 17, 2024**_  
Hugging face is the "github" for ML and NLP, so I registered for a hugging face account to check it out

_**May 16, 2024**_  
Starting hw2 part 1 and refreshing memories of precision and recall

_**May 15, 2024**_  
Learned that Python is the most popular language for NLP, and different organizations have developed NLP packages like nltk, spaCy, stanza, and Transformers etc.

_**May 13, 2024**_  
Gradient descent is used in a wide range of real life applications

_**May 11, 2024**_  
Learning about gradient descent training

_**May 10, 2024**_  
Refreshing memories of logistic regression for language models

_**May 7, 2024**_  
Learning about the topic of tokenization for NLP

_**May 6, 2024**_  
Refreshing regex knowledge for NLP

_**May 5, 2024**_  
Refreshing memory of jupiter notebook and testing github copilot vs chatgpt
- chatgpt is cleaner to use and start new dialogues to get rid of prior conversation's influenced
- copilot is easier to use inline to ask questions and let it modify the codes directly
- neither is able to replace human because they don't interpret the exact instructions without human help
<br></br>

_**May 4, 2024**_  
Learning about sentiment analysis

_**May 3, 2024**_  
Starting NLP class at school

_**May 2, 2024**_  
Learning about multi-threading and event driven programming

_**May 1, 2024**_  
Started system design video 2

_**April 28, 2024**_  
Started system design video 1

_**April 17, 2024**_  
Opening git commit editor from terminal actually pops up vim  
**To Do** - learn vim; the shortcuts can be very helpful to productivity

_**April 16, 2024**_  
Learned about how to open git commit editor from terminal

_**April 12, 2024**_  
Learned about tkinter interface, sqlite database, git reset

_**April 7, 2024**_  
Working on the mini app of a self study tool
