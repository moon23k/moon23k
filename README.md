## <img src="https://emojis.slackmojis.com/emojis/images/1531849430/4246/blob-sunglasses.gif?1531849430" width="30"/> Hello World
&nbsp; Hi there! I'm **moon**, somebody who's focusing on solving problems through artificial intelligence. AI has many subcategories, of which I find Natural Language Processing the most interesting. By profession, I'm a **NLP Machine Learning Engineer**. As an engineer, I aim to develop a model that can communicate naturally with people. So the codes in all my repos will contain the progress towards the goal. In addition to the codes in my git repos, reviews of the papers and personal research on artificial intelligence techniques are recorded on my <a href="">notion page</a>. If you would like to contact me, please contact me at the email address in the left information field.

<br>

## 👨🏻‍🔬 Experiments
&nbsp; AI has a lot of variables, which means that different results can be derived depending on the settings of various variables. Therefore, many experiments from various viewpoints are required to obtain good results. Below is a series of experiments that introduce different approaches on three representative NLP tasks. Each is **Neural Machine Translation**, **Abstractive Text Summarization** and **Dialogue Generation**.

<br>

**Neural Machine Translation**
> Machine translation is the process of converting Source Text into Target Text using a computer. Source Text and Target Text are in different languages. The hegemony of machine translation was Rule-Based at the earliest, followed by SMT, and now NMT has been established. NMT aims to derive more accurate and natural translation results using Neural Networks. Below are experiments of various Neural Network Architectures for this purpose.

* <a href="https://github.com/moon23k/NMT_BERT">How much performance will be improved if a large-scale pre-training model is applied to a NMT Task?</a>
* <a href="https://github.com/moon23k/NMT_KoBERT">Compare BERT-base, BERT-MultiLingual and KoBERT models on Korean-English NMT Task</a>
* <a href="https://github.com/moon23k/NMT_GAN">How can application of GAN through Reinforcement Learning technique improve translation quality?</a>

<br>

**Abstract Text Summarization**
> Text Summarization summarizes long text into short sentences through Neural Networks, and the task has Extractive and Abstractive methods. Extractive Summarization selects key sentences from original text to make summary, whereas Abstractive Summarization creates a new summary sentence through the model's decoder. The experiments below mainly deal with Abstractive summary tasks.


* <a href="https://github.com/moon23k/Hier_Basics">Will the hierarchical structure help model to properly understand long sentences?</a>
* <a href="https://github.com/moon23k/Recursive_Transformer">How helpful is the recurrent structure on Transformer for dealing with long sentences?</a>
* <a href="https://github.com/moon23k/Hier_BERT">How helpful can a large-scale pre-training model and hierarchical structure be to improve performance?</a>
* <a href="https://github.com/moon23k/SUM_GAN">How can application of GAN through reinforcement learning technique improve Summarization Task?</a>
* <a href="https://github.com/moon23k/SUM_NMT">Implementation of a model that handles the two tasks of translation and summarization at once</a>

<br>

**Dialogue Generation**
> In general, the dialog generation model tends to give general and repetitive answers independent of the flow of the conversation. This is because it is helpful to generate generic and repetitive answers in a way to reduce the loss in the learning process. Below is a set of experiments to address this and generate a more natural answer.

* <a href="https://github.com/moon23k/Chat_BERT">Application BERT on Dialogue Generation Model would help the model to generate more natural utterance?</a>
* <a href="https://github.com/moon23k/C2_Bot">Can application of GAN throgh Policy Graident Technique be helpful to give Characteristic on Dialogue Generation Model?</a>
* <a href="https://github.com/moon23k/C3_Bot">Can Hierarchical Model Structure and GAN make Coherent Characteristic Chatbot?</a>

<br>

## ⚓ Anchor Codes
&nbsp; Recently, research on AI has been actively conducted, is currently in progress, and there will be more in the future. Accordingly, many new architectures and techniques are proposed. Therefore, a baseline is needed to objectively evaluate performance while applying a new method to existing tasks. I call this baseline code anchor code, and set the three most basic and frequently used architectures in NLP as anchors. Each is **Sequence-to-Sequence**, **Attention Architecture** and **Transformer**. The anchor codes for each representative task of NLP is as follows.

* <a href="https://github.com/moon23k/NMT_Basics">Anchor Codes on **Neural Machine Translation**</a>
* <a href="https://github.com/moon23k/Sum_Basics">Anchor Codes on **Abstractive Text Summarization**</a>
* <a href="https://github.com/moon23k/Chat_Basics">Anchor Codes on **Dialogue Generation**</a>

<br>

## 📄 Ablation Studies
&nbsp; AI models show different results depending on the architecture and different techniques. Even a small change can make a big difference, so building an ability to control the change is necessary. Of course, this requires a lot of experiments, and below are the experiments.

&nbsp; &nbsp; • &nbsp;<a href="https://github.com/moon23k/Transformer_Ablation">Ablation Studies on **Transformer Architectures**</a> &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; • &nbsp;<a href="https://github.com/moon23k/BERTs_Ablation">Ablation studies on **BERT based models**</a>

&nbsp; &nbsp; • &nbsp;<a href="https://github.com/moon23k/Enc_Dec_Ablation">Ablation studies on **Encoders and Decoders**</a> &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; • &nbsp;<a href="https://github.com/moon23k/PipeLines">Ablation studies on **Module PipeLines**</a>

&nbsp; &nbsp; • &nbsp;<a href="https://github.com/moon23k/Scheduler_Ablation">Ablation Studies on **Learning Rate Schedulers**</a> &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; • &nbsp;<a href="https://github.com/moon23k/Model_Lightenings">Ablation Studies on **Model Lightening Methods**</a>

<br>

## 💾 Data
&nbsp; AI model learns from large amounts of data. Therefore, high-quality bulk data is essential for building a good model. Below is a series of Data-Related Experiments. And the Experiements include from simply fetching and processing data, to further research such as Tokenization and Data Augmentation .

* <a href="https://github.com/moon23k/NLP_datasets">Download and Process</a>
* <a href="https://github.com/moon23k/Tokenzier_Ablations">Tokenizer Ablations</a>
* <a href="https://github.com/moon23k/Data_Augmentation">Data Augmentation</a>
