# Welcome to chat GPT2
This is the code with which I fine tuned OpenAI's GPT2(which is made for text completion) to a chatting model. The model seems to be very good for a 124M parameter model in general knowledge. Intended purpose of the model: To create a powerful, easy to use and reliable model to be run on a consumer level graphics card (or maybe even a CPU). This model vastly outperforms GPT2 and many other similar parameter models.

#### To use the model. click this huggingface link: https://huggingface.co/Arjun-G-Ravi/chat-GPT2


### Model Description

```
license: mit
dataset: MuskumPillerum/General-Knowledge
base_model: gpt2
Finetuned epochs: 50
Finetune loss: 0.06
```


# Comparision with GPT2
  GPT2 is a text generation AI and is not meant for question answering purposes. The following comparison is meant to show how good the fine tuned model is, in comparison to the base model.

**1. Who is the king of the jungle?**
```
GPT2: Who is the king of the jungle? And where is the king?'

'Babe: It is in the hills, called the forest.'

They both said something I hadn't seen before

They say the king is in his

```
```
chat-GPT2: Read the question and give an honest answer. Your answers should not include any unethical, racist, sexist, dangerous, or illegal content. If the question is wrong, or does not make sense, accept it instead of giving the wrong answer.
Question: Who is the king of the jungle?
Answer: Lion is the king of the jungle.

```

**2. What is AI?**
```
GPT2: What is AI? Can it be done? How does it function? These are all incredibly important questions, and they've been answered in great detail, but if we want to get to what really matters, we can't just assume the answer in order

```
```
chat-GPT2: Read the question and give an honest answer. Your answers should not include any unethical, racist, sexist, dangerous, or illegal content. If the question is wrong, or does not make sense, accept it instead of giving the wrong answer. 
Question: What is AI?
Answer: AI is a branch of computer science that focuses on creating intelligent machines that are capable of performing tasks that would typically require human intelligence, such as visual perception, speech recognition, decision-making, and language translation.\n

```

**3. What is the difference between acid and a base?**
```
GPT2: What is the difference between an acid and a base?


The simplest distinction among these two structures has been between acids and bases. Acid is the water equivalent to a base — the water that enters a bottle, or the acid stored on it, or the base that is added to the glass.

```
```
chat-GPT2: Read the question and give an honest answer. Your answers should not include any unethical, racist, sexist, dangerous, or illegal content. If the question is wrong, or does not make sense, accept it instead of giving the wrong answer. 
Question: What is the difference between an acid and a base? 
Answer: An acid is a molecule or ion that donates a proton (H+) in a chemical reaction, while a base is a molecule or ion that accepts a proton (H+) in a chemical reaction. Acids have a pH lower than 7, while bases have a pH higher than 7.\n
```
