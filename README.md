# cse556-assignment-1-solved
**TO GET THIS SOLUTION VISIT:** [CSE556 Assignment 1 Solved](https://www.ankitcodinghub.com/product/cse-556-natural-language-processing-assignment-1-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;127149&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;2&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (2 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CSE556 Assignment 1 Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 138px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            5/5 - (2 votes)    </div>
    </div>
General Instructions:

● Every assignment has to be attempted by 4 people. At least one part has to be done by one team member. All members need to have a working understanding of the entire code

● Create a single .py/ipynb file for generating the final outputs that are required for submittables. Clearly indicate which cell/python method corresponds to which task/subtask. Outputs will be checked from this inference file only.

● Only one person has to submit the zip file containing all the above-mentioned files, along with the report as a PDF. It will be named A1_&lt;Grp No&gt;.zip The person having the alphabetically smallest name should submit.

Tasks: The assignment consists of 2 tasks:

1. Implement tokenization using BytePair encoding.

2. Create a Bigram Language Model (LM), and modify the standard implementation of Bigram LM to generate emotion-oriented sentences

Dataset: It can be downloaded from the link. The folder consists of the files corpus.txt and labels.txt. This is a subset of the twitter emotion dataset available on Hugging Face (link). The file corpus.txt consists of text samples, 1 sample per line. The file labels.txt consists of the corresponding emotion labels. Please use only this corpus for tasks 1 and 2.

____________________________________________________________________________________

Implement FROM SCRATCH a tokenizer based on the BytePair encoding algorithm (link). You are only allowed to use standard Python libraries and objects (lists, arrays, dictionaries, and collections library). Use of existing frameworks (such as nltk, HuggingFace, Spacy, TextBlob) is not allowed.

Specifically, you are required to create a Tokenizer class in python, which implements the following methods:

● learn_vocablury(), which takes as parameter the corpus number of merges and learns the split rules and frequencies; and

● tokenize(), which takes as input a sample and tokenizes it based on the learnt rules.

Evaluation:

Submit .txt files for each of the following:

Refer to the following folder (link) for a demo about how to submit the .txt files (refer to files tokens.txt, merge_rules.txt and tokenized_samples.txt)

____________________________________________________________________________________

1. Implement a Bigram Language Model from scratch. You are only allowed to use standard Python methods and the NumPy library for implementation.

Specifically, create a class called BigramLM, which has a methods for learning the bigram model from the dataset, and stores the learned LM and other supporting methods

2. Implement the following two smoothing algorithms in the BigramLM class: Laplace and Kneser-Ney smoothing. Compare the probabilities obtained from both and give an

3. Download the following file: utils.py. Use the function emotion_scores() to get the emotion scores of a sample sentence. Using these emotion scores, modify the standard probability of the bigram model 𝑃(𝑤𝑖|𝑤𝑖−1) = (𝑐𝑜𝑢𝑛𝑡(𝑤𝑖)/𝑐𝑜𝑢𝑛𝑡(𝑤𝑖−1)) + β

calculation,β and at the unigram, bigram or sampleβlevel. Using this modification, you where is the emotion component. Note that this can be included in any part of the

need to generate emotion-oriented samples (generate samples corresponding to a

4. Extrinsic evaluation:

a. Generate 50 samples for each of the 6 emotions for which you can get scores. Store these outputs in .txt files for each emotion using the file name format gen_&lt;emotion&gt;.txt. These generated samples will be used for extrinsic

b. Carry out extrinsic evaluation with the original corpus as your training data, and the generated samples as your testing data (labels for the generated samples will be the emotion corresponding to which you generated each sample).

Train a SVC model from Scikit-Learn library (link), and use the TF-IDF vectorizer (link) for vectorizing the text samples. Conduct Grid Search (link) to find out the best parameters and use the best model obtained to test out the performance of

Evaluation:

1. Top 5 bigrams before smoothing and after each of the 2 selected smoothing techniques along with their probabilities BEFORE applying emotion component.

2. Reasoning for method used for including emotion component

3. 2 generated samples for each emotion, for a total of 12 generated samples

4. Accuracy and macro F1 scores obtained from extrinsic evaluation

5. For each emotion, pick 1 of the generated sample and reason why it is generated according to its corresponding emotion.

6. A credit statement reflecting the contribution of each member of the group for the assignment.
