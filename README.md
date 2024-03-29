# Using Self-Generated Data to Improve LLM Hallucination Identification Performance

## Abstract
Large Language Models (LLMs) have become a very powerful tool with a variety of capabilities.
However, it often suffers from hallucination, where the generated results are untruthful, subjective, and diverge from the original text. 

To increase the hallucination identification performance for LLMs, we used llama-2-7b-chat’s inherent knowledge to generate a dataset with questions and two answers for each question, one hallucinated and one un-hallucinated. 

We then used the generated dataset to fine-tune the original model, enhancing its capability to identify the un-hallucinated answer. To evaluate our model, we used two datasets: TruthfulQA and HaluEval. 

In both benchmarks, our finetuned model was able to outperform the base model in terms of classifying hallucinated and un-hallucinated answers. The key contribution of our project is that we were able to achieve a better hallucination identification performance without any external knowledge, which is very
cost-effective. 
Our method shows that finetuning with the model’s inherent knowledge could be a very effective way to combat hallucination for LLMs. 
