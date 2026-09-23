 # Generative AI with Large Language Models - Coursera Course

## 1. 🎯 About the Course
This course provides a practical and technical introduction to Generative AI and Large Language Models, going beyond simply using tools such as ChatGPT.

The course explains how modern LLM systems are developed throughout their lifecycle—from data gathering and model selection to pre-training, fine-tuning, evaluation, optimization, deployment, and integration into real-world applications.

A major strength of the course is that it connects theoretical concepts with practical implementation and business use cases. The course includes hands-on labs involving tasks such as dialogue summarization, model fine-tuning, and reinforcement-learning-based improvement.

## 👨‍🏫 Who Teaches the Course?
The course is taught by four AWS practitioners:
**Antje Barth** — Principal Developer Advocate, Generative AI, Amazon Web Services (AWS)
**Chris Fregly** — Principal Solutions Architect, Generative AI, AWS
**Shelbee Eigenbrode** — Principal Solutions Architect, Generative AI, AWS
**Mike Chambers** — Developer Advocate for Generative AI at AWS.
**Concept → Architecture → Practical Example → Lab → Evaluation → Real-world Application**

# 📘 Week 1 — Generative AI Use Cases, Project Lifecycle & Model Pre-training
During Week 1, I learn the **fundamentals of Generative AI and Large Language Models, along with how an LLM project is planned and trained**.

Key topics covered
🔹Generative AI & Large Language Models
• Understand what Generative AI and LLMs are
• Explore common LLM tasks and real-world use cases
• Understand how LLMs generate text

🔹Transformer Architecture
• Learn the basics of Transformers
• Understand how attention mechanisms enable Transformers to process language
• Understand why Transformers became fundamental to modern LLMs

🔹Text Generation
• Learn how Transformer-based models generate text
• Understand generation parameters and how they influence outputs

🔹Prompt Engineering
• Learn how prompts influence LLM responses
• Understand different approaches to designing effective prompts
• Experiment with model generation settings

🔹Generative AI Project Lifecycle
• Understand the end-to-end lifecycle of an LLM project
• From data gathering → model selection → training → evaluation → deployment

🔹LLM Pre-training
• Understand how large language models are pre-trained
• Explore computational requirements and challenges
• Learn about scaling laws and compute-optimal models
• Understand domain-specific pre-training and adaptation

🔹Hands-on Lab
• Build a Generative AI use case for dialogue summarization

## Week -1 Generative AI with Large Language Model - Coursera Course Quiz Answers
![Alt Text](https://github.com/hritik1910/Generative_AI_with_Large_Language_Models--Coursera_Course/blob/main/Week-1_GenAI_with_LLM_Coursera_Course.jpg)
![Alt Text](https://github.com/hritik1910/Generative_AI_with_Large_Language_Models--Coursera_Course/blob/main/Week%201%20-%20Pre%20Training%20For%20Domain%20Adaption.png)

## **Weekly Quiz - Week - 1**
**Question 1**
Interacting with Large Language Models (LLMs) differs from traditional machine learning models. Working with LLMs involves natural language input, known as a  _____, resulting in output from the Large Language Model, known as the ______ .
Choose the answer that correctly fill in the blanks.

(A). prompt, completion
(B). prediction request, prediction response
(C). tunable request, completion
(D). prompt, fine-tuned LLM
**_Correct Ans_- (A)**

**Question 2**
Large Language Models (LLMs) are capable of performing multiple tasks supporting a variety of use cases.  Which of the following tasks supports the use case of converting code comments into executable code?

(A). Translation
(B). Invoke actions from text
(C). Text summarization
(D). Information Retrieval
**_Correct Ans_- (A)**

**Question 3**
What is the self-attention that powers the transformer architecture?

(A). A measure of how well a model can understand and generate human-like language.
(B). The ability of the transformer to analyze its own performance and make adjustments accordingly.
(C). A technique used to improve the generalization capabilities of a model by training it on diverse datasets.
(D). A mechanism that allows a model to focus on different parts of the input sequence during computation.
**_Correct Ans_- (D)**

**Question 4**
Which of the following stages are part of the generative AI model lifecycle mentioned in the course? (Select all that apply)

(A). Manipulating the model to align with specific project needs.
(B). Selecting a candidate model and potentially pre-training a custom model.
(C). Defining the problem and identifying relevant datasets.
(D). Performing regularization
(E). Deploying the model into the infrastructure and integrating it with the application.
**_Correct Ans_- (A), (B), (C) & (E)**

**Question 5**
"RNNs are better than Transformers for generative AI Tasks." 
Is this true or false?

(A). True
(B). False
**_Correct Ans_- (B)**

**Question 6**
Which transformer-based model architecture has the objective of guessing a masked token based on the previous sequence of tokens by building bidirectional representations of the input sequence.

(A). Autoregressive
(B). Sequence-to-sequence
(C). Autoencoder
**_Correct Ans_- (C)**

**Question 7**
Which transformer-based model architecture is well-suited to the task of text translation?

(A). Sequence-to-sequence
(B). Autoencoder
(C). Autoregressive
**_Correct Ans_- (A)**

**Question 8**
Do we always need to increase the model size to improve its performance?

(A). True
(B). False
**_Correct Ans_- (B)**

**Question 9**
Scaling laws for pre-training large language models consider several aspects to maximize performance of a model within a set of constraints and available scaling choices.  Select all alternatives that should be considered for scaling when performing model pre-training?

(A). Dataset size: Number of tokens
(B). Model size: Number of parameters
(C). Batch size: Number of samples per iteration 
(D). Compute budget: Compute constraints
**_Correct Ans_- (A), (B) & (D)**

**Question 10**
"You can combine data parallelism with model parallelism to train LLMs."
Is this true or false?

(A). True
(b). False
**_Correct Ans_- (A)**

# 📗 Week 2 — Fine-Tuning & Evaluating Large Language Models

**NOTE: Week 2 focuses on adapting existing pretrained LLMs for specific tasks rather than building a model completely from scratch.**

Key topics covered
🔹Instruction Fine-Tuning
• Understand how pretrained models can be trained to follow instructions
• Learn how fine-tuning changes a model's behavior

🔹Single-Task Fine-Tuning
• Adapt an LLM for a specific task
• Understand when task-specific fine-tuning is useful

🔹Multi-Task Instruction Fine-Tuning
• Learn how a model can be trained across multiple tasks
• Understand the benefits and trade-offs of multi-task training

🔹Model Evaluation
• Learn how LLM performance is measured
• Understand evaluation methodologies and model benchmarks
• Compare model performance across different tasks

🔹Parameter-Efficient Fine-Tuning (PEFT)
• Understand why updating every parameter of a large model can be expensive
• Learn techniques that reduce computational and memory requirements

🔹LoRA
• Learn Low-Rank Adaptation
• Understand how LoRA allows efficient model adaptation with fewer trainable parameters

🔹Soft Prompts
• Explore another parameter-efficient technique for adapting LLM behavior

🔹Hands-on Lab
• Fine-tune a Generative AI model for dialogue summarization

## Week -2 Generative AI with Large Language Model - Coursera Course Quiz Answers

**Fine Tuning On Single Task - On going Week 2 question**
Which of the following are true in respect to Catastrophic Forgetting? Select all that apply.

(A). Catastrophic forgetting only occurs in supervised learning tasks and is not a problem in unsupervised learning.
(B). Catastrophic forgetting is a common problem in machine learning, especially in deep learning models.
(C). One way to mitigate catastrophic forgetting is by using regularization techniques to limit the amount of change that can be made to the weights of the model during training.
(D). Catastrophic forgetting occurs when a machine learning model forgets previously learned information as it learns new information.
**_Correct Ans_- (B), (C) & (D)**

**Multi-task instruction fine tuning - On going Week 2 question**
What is the purpose of fine-tuning with prompt datasets?

(A). To decrease the accuracy of a pre-trained language model by introducing new prompts.
(B). To improve the performance and adaptability of a pre-trained language model for specific tasks.
(C). To increase the computational resources required for training a language model.
(D). To eliminate the need for instructions and prompts in training a language model.
**_Correct Ans_- (B)**

**Parameter efficient fine-tuning (PEFT) - On going Week 2 question**
"Parameter Efficient Fine-Tuning (PEFT) updates only a small subset of parameters. This helps prevent catastrophic forgetting." True or False?

(A). True
(B). False
**_Correct Ans_- (A)**

**PEFT techniques 2 soft prompts - On going Week 2 question**
Parameter Efficient Fine-Tuning (PEFT) methods specifically attempt to address some of the challenges of performing full fine-training. Which of the following options describe challenges that PEFT tries to overcome?

(A). Model performance
(B). Computational constraints
(C). Catastrophic forgetting
(D). Storage requirements
**_Correct Ans_- (B), (C) & (D)**

## Weekly Quiz - Week - 2
**Question 1**
Fill in the blanks: __________ involves using many prompt-completion examples as the labeled training dataset to continue training the model by updating its weights.  This is different from _________ where you provide prompt-completion examples during inference.

(A). Instruction fine-tuning, In-context learning
(B). In-context learning, Instruction fine-tuning 
(C). Pre-training, Instruction fine-tuning
(D). Prompt engineering, Pre-training
**_Correct Ans_- (A)**

**Question 2**
Fine-tuning a model on a single task can improve model performance specifically on that task; however, it can also degrade the performance of other tasks as a side effect.  This phenomenon is known as: 

(A). Model toxicity
(B). Catastrophic loss
(C). Catastrophic forgetting
(D). Instruction bias
**_Correct Ans_- (C)**

**Question 3**
Which evaluation metric below focuses on precision in matching generated output to the reference text and is used for text translation?

(A). ROUGE-1
(B). BLEU
(C). HELM
(D). ROUGE-2
**_Correct Ans_- (B)**

**Question 4**
Which of the following statements about multi-task finetuning is correct? Select all that apply:

(A). Multi-task finetuning can help prevent catastrophic forgetting.
(B). Performing multi-task finetuning may lead to slower inference.
(C). Multi-task finetuning requires separate models for each task being performed.
(D). FLAN-T5 was trained with multi-task finetuning.
**_Correct Ans_- (A) & (D)**

**Question 5**
"Smaller LLMs can struggle with one-shot and few-shot inference:" Is this true or false?

(A). True
(B). False
**_Correct Ans_- (A)**

**Question 6**
Which of the following are Parameter Efficient Fine-Tuning (PEFT) methods? Select all that apply.

(A). Selective
(B). Subtractive
(C). Additive
(D). Reparameterization
**_Correct Ans_- (A), (C) & (D)**

**Question 7**
Which of the following best describes how LoRA works?

(A). LoRA trains  a smaller, distilled version of the pre-trained LLM to reduce model size
(B). LoRA continues the original pre-training objective on new data to update the weights of the original model.
(C). LoRA decomposes weights into two smaller rank matrices and trains those instead of the full model weights.
(D). LoRA freezes all weights in the original model layers and introduces new components which are trained on new data.
**_Correct Ans_- (C)**

**Question 8**
What is a soft prompt in the context of LLMs (Large Language Models)?

(A). A set of trainable tokens that are added to a prompt and whose values are updated during additional training to improve performance on specific tasks.
(B). A strict and explicit input text that serves as a starting point for the model's generation.
(C). A technique to limit the creativity of the model and enforce specific output patterns.
(D). A method to control the model's behavior by adjusting the learning rate during training.
**_Correct Ans_- (A)**

**Question 9**
"Prompt Tuning is a technique used to adjust all hyperparameters of a language model." Is this true or false?

(A). True
(B). False
**_Correct Ans_- (B)**

**Question 10**
"PEFT methods can reduce the memory needed for fine-tuning dramatically, sometimes to just 12-20% of the memory needed for full fine-tuning."
Is this true or false?

(A). True
(B). False
**_Correct Ans_- (A)**

## Week -3 Generative AI with Large Language Model - Coursera Course Quiz Answers

**Reinforcement Learning with Human Feedback (RLHF) - On going Week 3 question**
When using Reinforcement Learning with Human Feedback (RLHF) to align large language models with human preferences, what is the role of human labelers?

(A). To identify model weights that should be updated
(B). To compare the original LLM completions to the RLHF updated model completions and ensure they don't diverge too much.
(C). To score prompt completions, so that this score is used to train the reward model component of the RLHF process.
(D). To write prompts and completions from scratch that are used during fine-tuning with RLHF
**_Correct Ans_- (C)**

**RLHF - Reward Hacking - On going Week 3 question**
How can RLHF align the performance of large language models with human preferences? Select all that apply

(A). Inference is faster after RLHF, improving the user experience
(B). RLHF can enhance the interpretability of generated text
(C). RLHF increases the model's size by adding new parameters that represent human preferences
(D). RLHF can help reduce model toxicity and misinformation
**_Correct Ans_- (B) & (D)**

**Using the LLM in applications - On going Week 3 question**
How does Retrieval Augmented Generation (RAG) enhance generation-based models?

(A). By making external knowledge available to the model
(B). By applying reinforcement learning techniques to augment completions.
(C). By optimizing model architecture to generate factual completions.
(D). By increasing the training data size.
**_Correct Ans_- (A)**

## **Weekly Quiz - Week - 3**
**Question 1**
Which of the following are true in regards to Constitutional AI? Select all that apply.

(A). To obtain revised answers for possible harmful prompts, we need to go through a Critique and Revision process.
(B). For constitutional AI, it is necessary to provide human feedback to guide the revisions.
(C). In Constitutional AI, we train a model to choose between different responses.
(D). Red Teaming is the process of eliciting undesirable responses by interacting with a model.

# Ongoing Course. Very soon full details will be here.
