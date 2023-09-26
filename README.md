<br>

## ✋ Hello World
&nbsp; Hi there! I'm **moon**, somebody who's focusing on solving problems through artificial intelligence. AI has many subcategories, of which I find Natural Language Processing the most interesting. By profession, I'm a **NLP Machine Learning Engineer**. As an engineer, I aim to develop a model that can communicate naturally with people. So the codes in all my repos will contain the progress towards the goal. In addition to the codes in my git repos, reviews of the papers and personal research on artificial intelligence techniques are recorded on my <a href="https://shy-vole-f74.notion.site/Hello-I-m-moon-e1ecc2e40b32405e997713cfb44e4f3c">notion page</a>. If you would like to contact me, please contact me at the email address in the left information field.

<br><br> 


## 🤖 Model Design
> &nbsp; Model design is a crucial element in machine learning engineering. 
The choice of model architecture can significantly impact performance. 
A series of projects, concentrating on model architecture, are presented below to establish standards for the suitable model structures in three NLG tasks: Translation, Dialogue Generation, and Summarization.

| Title | Desc |
|---|---|
| [**• &hairsp; RNN Seq2Seq**](https://github.com/moon23k/RNN_Seq2Seq)                           | An analysis of model performance in Seq2seq models with the use of RNN, LSTM, and GRU |
| [**• &hairsp; RNN Seq2Seq with Attention**](https://github.com/moon23k/RNN_Seq2Seq_Attention)  | Compare Three Attention mechanism added Architectures on Three NLG tasks |
| [**• &hairsp; Transformer**](https://github.com/moon23k/Transformer)                           | Compare Custom Transformer and Pytorch Transformer |
| [**• &hairsp; Encoder Decoder Param Ratio**](https://github.com/moon23k/Param_Ratio)           | Explore How the ratio of Encoder & Decoder affects three NLG Tasks |
| [**• &hairsp; Transformer Variants**](https://github.com/moon23k/Transformer_Variants)         | Compare Standard Transformer, Recurrent Transformer, and Evolved Transformer |
| [**• &hairsp; PLM Fusion**](https://github.com/moon23k/PLM_Fusion)                             | Compare Two way of fusing PLM Encoder and Transformer Decoder |

<br><br> 


## ⏰ Toward Efficiency
> &nbsp; Large-scale models with numerous parameters tend to deliver better performance. Many recent research focus on training even larger models on extensive datasets to achieve superior results. 
However, deploying such large-scale models in typical computing environments can be restrictive. 
To address this issue, the following project introduces an efficient approach that maintains a certain level of performance while mitigating computational demands.

| Title | Desc |
|---|---|
| [**• &hairsp; Efficient Training**](https://github.com/moon23k/Eff_Training)  | Explore methods to efficiently utilize GPU memory during the learning process and compare the GPU usage and actual training results for each approach |
| [**• &hairsp; Efficient PLMs**](https://github.com/moon23k/Eff_PLMs)          | Compare BERT with three Lightweight PreTrained Language Models on performance and efficiency |
| [**• &hairsp; Param Efficient Fine-Tuning**](https://github.com/moon23k/PEFT) | Fine-tune Large-Scale PreTrained Models using the PEFT (Parameter Effective Fine-Tuning) approach and evaluate their performance and efficiency |

<br><br> 


## 🏃‍♂️ Training Methodology
> &nbsp; In the typical training process of a Seq2Seq model for Natural Language Generation, the issue of 'Exposure Bias' and the discrepancy between training and inference inevitably arises. 
The most ideal solution is to train the model on a large and diverse dataset, but in reality, this is a challenging endeavor. 
To overcome these constraints and enhance training effectiveness, several training strategies are proposed below.
Among these, **`Auxiliary Training`** and **`Scheduled Sampling`** aim to make the most of GPU parallel processing while facilitating complementary learning. 
On the other hand, **`Generative Training`** and **`SeqGAN Training`** may have lower training efficiency but serve as strategies to extract maximum performance in extremely data-restricted environments.

| Title | Desc |
|---|---|
| [**• &hairsp; Auxiliary Training**](https://github.com/moon23k/Aux_Training)       |  |
| [**• &hairsp; Scheduled Sampling**](https://github.com/moon23k/Scheduled_Sampling) |  |
| [**• &hairsp; Generative Training**](https://github.com/moon23k/GEN_Training)      |  |
| [**• &hairsp; SeqGAN Training**](https://github.com/moon23k/GAN_Training)          |  |

<br><br> 


## 🔄 Neural Machine Translation
> &nbsp; Machine translation is the task of converting Text from Source Language into Target Language using a computer processing. The hegemony of machine translation was Rule-Based at the earliest, followed by SMT, and now NMT has been established. NMT aims to derive more accurate and natural translation results using Neural Networks. Below are experiments of various Neural Network Architectures for this purpose.

| Title | Desc |
|---|---|
| [**• &hairsp; Back Translation**](https://github.com/moon23k/NMT_Back)                  | Examine how effective BackTranslation is when data is limited |
| [**• &hairsp; Multi-Lingual Translation**](https://github.com/moon23k/NMT_MultiLingual) | Compare the performance between a Multilingual Translation Model and Translation Models trained separately for each language pair |
| [**• &hairsp; NMT Blend**](https://github.com/moon23k/NMT_Blend)                        | Based on the previous projects, blend the most optimal architecture and training method. And verify the Performance |

<br><br> 


## 🗣️ Dialogue Generation
> &nbsp; Dialogue Generation is a task to generate a response to a previous utterance, just like humans do in a conversational situation. However, it is very difficult for the model to understand the flow of the conversation and return appropriate answers. Below are a set of experiments to generate more natural responses like humans do.

| Title | Desc |
|---|---|
| [**• &hairsp; Characteristic Dialogue Generation**](https://github.com/moon23k/Dialog_Char) | An experiment to infuse personality into the GPT model with only a small dataset using SeqGAN techniques |
| [**• &hairsp; Utilize SimEnt Technique**](https://github.com/moon23k/Dialog_SimEnt)         |  |
| [**• &hairsp; Multi-Turn Dialgue Generation**](https://github.com/moon23k/Dialig_MultiTurn) |  |
| [**• &hairsp; Dialogue Generation Blend**](https://github.com/moon23k/Dialig_Blend)         | Based on the previous projects, blend the most optimal architecture and training method. And verify the Performance |

<br><br> 


## 📝 Abstract Text Summarization
> &nbsp; Summarization Task summarizes long text into short sentences through Neural Networks, and the task can be devided into Extractive and Abstractive methods. Extractive Summarization selects key sentences from original text to make summary, whereas Abstractive Summarization creates a new summary sentence through the model's decoder. The experiments below mainly deal with Abstractive summary tasks.

| Title | Desc |
|---|---|
| [**• &hairsp; Hierarchical Encoder**](https://github.com/moon23k/Summ_HierEnc) | Implement Hierarchical Encoder to handle long input sequence & Compare performance with Standard Encoder |
| [**• &hairsp; Sparse Attention**](https://github.com/moon23k/Summ_Sparse)      | Implement and validate the utility of Sparse Attention in Text Summarization |
| [**• &hairsp; Summarizartion Blend**](https://github.com/moon23k/Summ_Blend)   | Based on the previous projects, blend the most optimal architecture and training method. And verify the Performance |

<br><br> 


## 💾 Data
> &nbsp; Deep Learning model learns from large amounts of data. Therefore, high-quality bulk data is essential for building a good model. Below is a series of Data-Related Experiments. And the Experiements include from simply fetching and processing data, to further research such as Tokenization and Data Augmentation.

| Title | Desc |
|---|---|
| [**• &hairsp; NLG Datasets**](https://github.com/moon23k/NLG_datasets)           | Load and Process Datasets for Natural Language Generation Tasks |
| [**• &hairsp; Tokenizations**](https://github.com/moon23k/Tokenizations)         | Investigate the impact of various tokenization methods on the model's performance |
| [**• &hairsp; Data Augmentation**](https://github.com/moon23k/Data_Augmentation) | Augment Data to overcome Data Shortage |

<br><br> 
