## <img src="https://emojis.slackmojis.com/emojis/images/1531849430/4246/blob-sunglasses.gif?1531849430" width="30"/> Hello World
&nbsp; Hi there! I'm **moon**, somebody who's focusing on solving problems through artificial intelligence. AI has many subcategories, of which I find Natural Language Processing the most interesting. By profession, I'm a **NLP Machine Learning Engineer**. As an engineer, I aim to develop a model that can communicate naturally with people. So the codes in all my repos will contain the progress towards the goal. In addition to the codes in my git repos, reviews of the papers and personal research on artificial intelligence techniques are recorded on my <a href="https://shy-vole-f74.notion.site/Hello-I-m-moon-e1ecc2e40b32405e997713cfb44e4f3c">notion page</a>. If you would like to contact me, please contact me at the email address in the left information field.

<br>

## 👨🏻‍🔬 Experiments
&nbsp; AI has a lot of variables, which means that various variable settings can make different results. Therefore, many experiments from various viewpoints are required to obtain good results. Below is a series of experiments that introduce different approaches on three representative NLP tasks. Each is **Neural Machine Translation**, **Dialogue Generation**, and **Abstractive Summarization**.

<br>

**Neural Machine Translation**
> Machine translation is the task of converting Text from Source Language into Target Language using a computer processing. The hegemony of machine translation was Rule-Based at the earliest, followed by SMT, and now NMT has been established. NMT aims to derive more accurate and natural translation results using Neural Networks. Below are experiments of various Neural Network Architectures for this purpose.

&emsp; • &hairsp; <a href="https://github.com/moon23k/NMT_BERT">How to utilize **BERT** on Machine Translation</a>
&emsp; &emsp; &emsp; &emsp; &emsp; &nbsp;
• &hairsp; <a href="https://github.com/moon23k/NMT_Back">Improve Performance via **Back Translation**</a>

&emsp; • &hairsp; <a href="https://github.com/moon23k/NMT_GEN">**Generative Training Studies** for Machine Translation</a>
&emsp; &emsp;
• &hairsp; <a href="https://github.com/moon23k/NMT_GAN">Generate better Translation via **SeqGAN**</a>

<br>

**Dialogue Generation**
> Dialogue Generation is a task to generate a response to a previous utterance, just like humans do in a conversational situation. However, it is very difficult for the model to understand the flow of the conversation and return appropriate answers. Below is a set of experiments to generate more natural responses like humans do.

&emsp;  • &hairsp; <a href="https://github.com/moon23k/Dialog_SemEnt">Simple Implementation of **SemEnt & DRESS**</a>
&emsp; &emsp; &emsp; &ensp;
• &hairsp; <a href="https://github.com/moon23k/Dialog_FluEnt">**F**irst **l**etter in **u**tterance & **Ent**ropy based Generative Training</a>

&emsp;  • &hairsp; <a href="https://github.com/moon23k/Dialog_Char">**Characteristic Dialgue Generation** via **SeqGAN**</a>
&emsp; &emsp;
• &hairsp; <a href="https://github.com/moon23k/Dialog_MultiTurn">**Multi-Turn** Dialgue Generation Study</a>

<br>

**Abstract Summarization**
> Summarization Task summarizes long text into short sentences through Neural Networks, and the task can be devided into Extractive and Abstractive methods. Extractive Summarization selects key sentences from original text to make summary, whereas Abstractive Summarization creates a new summary sentence through the model's decoder. The experiments below mainly deal with Abstractive summary tasks.

&emsp; • &hairsp; <a href="https://github.com/moon23k/Sum_BERT">How to Utilize **BERT** on Summarization</a> 
&emsp; &emsp; &emsp;
• &hairsp; <a href="https://github.com/moon23k/Sum_HAT">Compare **Hier & Flat** Architectures on Summarization</a>

&emsp; • &hairsp; <a href="https://github.com/moon23k/Sum_GAN">Generate Better Summaries via **SeqGAN**</a>
&emsp; &emsp; &thinsp;
• &hairsp; <a href="https://github.com/moon23k/Sum_SALT">**S**emantic **A**nd **L**ength based Generative **T**raining</a>

<br>

## ⚓ Anchor Codes
&nbsp; AI research has been actively conducted, is currently in progress, and there will be more and more in the future. As research becomes more diverse, a baseline for objective evaluation is essential. I set four baselines for the NLG Tasks and call them **anchor codes**, each is **LSTM**, **GRU with Attention Mechanism**, **Transformer**, and **T5**. The former three models are the basic Encoder-Decoder Models via LSTM, Attention Mechanism, and Transformer. Those three models acts as minimum performance thresholds for the same network-based architectures. And the last T5 model is pre-trained Encoder-Decoder model, which shows great performances in many language generation tasks. The T5 model works as performance threshold for pre-trained models.


&emsp; • &hairsp; <a href="https://github.com/moon23k/LSTM_Anchors">Anchor Code for **LSTM Encoder-Decoder**</a> 
&emsp; &emsp; &emsp; 
• &hairsp; <a href="https://github.com/moon23k/Attention_Anchors">Anchor Code for **GRU Encoder-Decoder with Attention**</a>

&emsp; • &hairsp; <a href="https://github.com/moon23k/Transformer_Anchors">Anchor Code for **Trasformer**</a> 
&emsp; &emsp; &emsp; &emsp; &emsp; &emsp; &emsp; &nbsp; &thinsp;
• &hairsp; <a href="https://github.com/moon23k/T5_Anchors">Anchor Code for **T5 Fine-Tuning**</a>

<br>

## 📄 Ablation Studies
&nbsp; AI models show different results depending on the architecture and different techniques. Even a small change can make a big difference, so building an ability to control the change is necessary. Of course, this requires a lot of experiments, and below are the experiments.

&emsp; • &hairsp; <a href="https://github.com/moon23k/Transformer_Arhcs">Ablation Studies on **Transformer Architectures**</a>
&emsp; &emsp; &emsp; &ensp;
• &hairsp; <a href="https://github.com/moon23k/PipeLines">Ablation studies on **Module PipeLines**</a> 

&emsp; • &hairsp; <a href="https://github.com/moon23k/Efficient_Training">Ablation Studies on **Efficient Training Strategies**</a> 
&emsp; &emsp; &emsp;
• &hairsp; <a href="https://github.com/moon23k/Efficient_Models">Ablation studies on **Efficient Models**</a>

<br>

## 💾 Data
&nbsp; Deep Learning model learns from large amounts of data. Therefore, high-quality bulk data is essential for building a good model. Below is a series of Data-Related Experiments. And the Experiements include from simply fetching and processing data, to further research such as Tokenization and Data Augmentation.

* <a href="https://github.com/moon23k/NLP_Datasets">**Download and Process** Datasets</a>
* <a href="https://github.com/moon23k/Tokenizations">**Tokenization** Strategies</a>
* <a href="https://github.com/moon23k/Data_Augmentation">**Data Augmentation**</a>
