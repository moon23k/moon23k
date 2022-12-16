## <img src="https://emojis.slackmojis.com/emojis/images/1531849430/4246/blob-sunglasses.gif?1531849430" width="30"/> Hello World
&nbsp; Hi there! I'm **moon**, somebody who's focusing on solving problems through artificial intelligence. AI has many subcategories, of which I find Natural Language Processing the most interesting. By profession, I'm a **NLP Machine Learning Engineer**. As an engineer, I aim to develop a model that can communicate naturally with people. So the codes in all my repos will contain the progress towards the goal. In addition to the codes in my git repos, reviews of the papers and personal research on artificial intelligence techniques are recorded on my <a href="https://shy-vole-f74.notion.site/Hello-I-m-moon-e1ecc2e40b32405e997713cfb44e4f3c">notion page</a>. If you would like to contact me, please contact me at the email address in the left information field.

<br>

## 👨🏻‍🔬 Experiments
&nbsp; AI has a lot of variables, which means that various variable settings can make different results. Therefore, many experiments from various viewpoints are required to obtain good results. Below is a series of experiments that introduce different approaches on three representative NLP tasks. Each is **Neural Machine Translation**, **Dialogue Generation**, and **Abstractive Summarization**.

<br>

**Neural Machine Translation**
> Machine translation is the process of converting Source Text into Target Text using a computer. Source Text and Target Text are in different languages. The hegemony of machine translation was Rule-Based at the earliest, followed by SMT, and now NMT has been established. NMT aims to derive more accurate and natural translation results using Neural Networks. Below are experiments of various Neural Network Architectures for this purpose.

&emsp; • &hairsp; <a href="https://github.com/moon23k/NMT_BERT">Improve Translation via **Back Translation**</a> 
&emsp; &emsp; &emsp; &emsp; &emsp; &emsp; &emsp; &hairsp;
• &hairsp; <a href="https://github.com/moon23k/NMT_BERT">Improve Translation via **SeqGAN**</a>

&emsp; • &hairsp; <a href="https://github.com/moon23k/NMT_BERT">Improve Translation via **Back Translation & SeqGAN**</a> 
&emsp; &emsp; &emsp; 
• &hairsp; <a href="https://github.com/moon23k/NMT_BERT">Improve Translation via **Fusing PLM**</a>

<br>

**Dialogue Generation**
> In general, the dialog generation model tends to give general and repetitive answers independent of the flow of the conversation. This is because it is helpful to generate generic and repetitive answers in a way to reduce the loss in the learning process. Below is a set of experiments to address this and generate a more natural answer.

&emsp;  • &hairsp; <a href="https://github.com/moon23k/NMT_BERT">Improve Dialgue Generation via **SeqGAN**</a> 
&emsp; &emsp; &emsp; &emsp; &emsp; &emsp; &emsp; 
• &hairsp; <a href="https://github.com/moon23k/NMT_BERT">Improve Dialgue Generation via **Dual SeqGAN**</a>

&emsp;  • &hairsp; <a href="https://github.com/moon23k/NMT_BERT">Improve **Multi-Turn** Dialgue Generation via **SeqGAN**</a> 
&emsp; &emsp; &emsp; 
• &hairsp; <a href="https://github.com/moon23k/NMT_BERT">Improve Dialgue Generation via **Fusing PLM**</a>

<br>

**Abstract Summarization**
> Summarization Task summarizes long text into short sentences through Neural Networks, and the task can be devided into Extractive and Abstractive methods. Extractive Summarization selects key sentences from original text to make summary, whereas Abstractive Summarization creates a new summary sentence through the model's decoder. The experiments below mainly deal with Abstractive summary tasks.

&emsp; • &hairsp; <a href="https://github.com/moon23k/NMT_BERT">**Summarize & Translate At Once**</a> 
&emsp; &emsp; &emsp; &emsp; 
• &hairsp; <a href="https://github.com/moon23k/NMT_BERT">Improve Summarization via **Fusing PLM in a Hierarchical Structure**</a>

&emsp; • &hairsp; <a href="https://github.com/moon23k/NMT_BERT">Improve Summarization via **SeqGAN**</a> 
&emsp; &emsp; &emsp;
• &hairsp; <a href="https://github.com/moon23k/NMT_BERT">Improve Summarization via **Fusing PLM for Long Sequence**</a>

<br>

## ⚓ Anchor Codes
&nbsp; AI research has been actively conducted, is currently in progress, and there will be more and more in the future. As research becomes more diverse, a baseline for objective evaluation is essential. I set four baselines for the NLG Tasks and call them **anchor codes**, each is **LSTM**, **GRU with Attention Mechanism**, **Transformer**, and **T5**. The former three models are the basic Encoder-Decoder Models via LSTM, Attention Mechanism, and Transformer. Those three models acts like minimum performance thresholds for the same network-based architectures. And the last T5 model is pre-trained Encoder-Decoder model, which shows sota performance in many language generation tasks. The T5 model works as maximum performance threshold for various NLG task specific models.


&emsp; • &hairsp; <a href="https://github.com/moon23k/NMT_Basics">Anchor Code for **LSTM Encoder-Decoder**</a> &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; • &hairsp; <a href="https://github.com/moon23k/Sum_Basics">Anchor Code for **GRU Encoder-Decoder with Attention**</a>

&emsp; • &hairsp; <a href="https://github.com/moon23k/Chat_Basics">Anchor Code for **Trasformer**</a> &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; • &hairsp; <a href="https://github.com/moon23k/Chat_Basics">Anchor Code for **T5 Fine-Tuning**</a>

<br>

## 📄 Ablation Studies
&nbsp; AI models show different results depending on the architecture and different techniques. Even a small change can make a big difference, so building an ability to control the change is necessary. Of course, this requires a lot of experiments, and below are the experiments.

&emsp; • &hairsp; <a href="https://github.com/moon23k/Transformer_Ablation">Ablation Studies on **Transformer Architectures**</a> &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; • &hairsp; <a href="https://github.com/moon23k/BERTs_Ablation">Ablation studies on **BERT based models**</a>

&emsp; • &hairsp; <a href="https://github.com/moon23k/Lightening_Ablation">Ablation Studies on **Model Lightening Methods**</a> &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; • &hairsp; <a href="https://github.com/moon23k/Pipeline_Ablation">Ablation studies on **Module PipeLines**</a> 

<br>

## 💾 Data
&nbsp; AI model learns from large amounts of data. Therefore, high-quality bulk data is essential for building a good model. Below is a series of Data-Related Experiments. And the Experiements include from simply fetching and processing data, to further research such as Tokenization and Data Augmentation .

* <a href="https://github.com/moon23k/NLP_datasets">**Download and Process** Datasets</a>
* <a href="https://github.com/moon23k/Tokenizer_Ablation">**Tokenizer** Ablation Studies</a>
* <a href="https://github.com/moon23k/Data_Augmentation">**Data Augmentation**</a>
