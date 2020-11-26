# Embeddings
## A study on Word Embeddings

The concept of words as vectors was an ingenius concept ([introduced in 2013](https://arxiv.org/pdf/1301.3781.pdf) by Mikolov et.al. 
During the time of its conception, it blew open the possibilities and raised the bar of NLP. Through this repository and the ([accompanying  Weights and Biases report](https://arxiv.org/pdf/1301.3781.pdf), we have segmented the concept thoroughly and in a such a way that all idelogical intuitions formed in transition of reading the report pave way for a better understanding of the underlying mathematics involved. We have also included a hands-on coding tutorial explaining each relevant steps invovled. 

Through this report, we have explained two core concepts in Word2Vec;
* Continuous Bag of Words 
CBOW is essentially the concept of a group of context words giving the relevant center word as its output
![CBOW implementation](https://paper-attachments.dropbox.com/s_17EC4A7AA5E35C6AE91C949F7159817F453BFBF2E26C091F630CA492C2D4B3AA_1605758538826_CBOW.gif)

* Skip-Gram 
In Skip-gram, we have a singular center word giving out relevant context words as its output. 

![Skip Implementation](https://paper-attachments.dropbox.com/s_17EC4A7AA5E35C6AE91C949F7159817F453BFBF2E26C091F630CA492C2D4B3AA_1605759408916_Skip.gif)

For both architectures, softmax loss is used to generate gradients used in training the Center word embeddings and the context word
embeddings. 

## Data Used
To assess and compare the prowess of the aforementioned techniques, two corporas were used;
* Self made small set of sentences not covering a general topic
* ([A relatively bigger paragraph based on Marie Curie and her achievements](https://www.testprepreview.com/modules/reading1.htm)

## Results 
Our intention was to see how these two architectures fare when fed with different types of data. Below are a few visualizations we got as results

