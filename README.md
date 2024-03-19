# awesome-llm-sparsity

Collection of papers, algorithms, and other resources that show how sparsity emerges in LLMs, and how it can be utilized to reduce training and inference time

**Taxonomy**
![Sparsity Taxonomy](https://github.com/ariellubonja/awesome-llm-sparsity/blob/main/sparsity-taxonomy.png)
<small><i>Original image sourced from [Sparsity in transformers: A systematic literature review](https://www.sciencedirect.com/science/article/pii/S092523122400239X)</i></small>

### Table of Contents 
- [Emergent Sparsity](#Emergent-Sparsity)
- [Training for Sparsity](#training-to-be-sparse)
- [Review Papers](#review-papers)

## Emergent Sparsity
<div id="Emergent-Sparsity"></div> 

| Paper | Summary | Code | Date |
|:------|:-------|:----:|:----:|
|[The Lazy Neuron Phenomenon: On Emergence of Activation Sparsity in Transformers](https://arxiv.org/pdf/2210.06313.pdf) @ Google | Activation maps (between two Feed-Forward layers) of Transformers are surprisingly sparse: 90%+, regardless of task. This increases with model size. Paper proposes why this happens and the Top-K Transformer. | ∅ | June-23
|[ReLU Strikes Back: Exploiting Activation Sparsity in Large Language Models](https://arxiv.org/pdf/2310.04564.pdf) @ Apple | Using ReLU instead of GeLU or SiLU leads to increased activation sparsity throughout the LLM, with minimal impact on performance. Also shortly discusses caching/reusing weights across tokens, since they change slowly with token $t$.  | ∅ | Oct-23
<br/>


## Training to be Sparse
<div id="training-to-be-sparse"></div>


| Paper | Summary | Code | Date |
|:------|:-------|:----:|:----:|
|[Learn To be Efficient: Build Structured Sparsity in Large Language Models](https://arxiv.org/pdf/2402.06126.pdf) @ UIUC, CMU | TBA | ∅ | Feb-24
|[Generating Long Sequences with Sparse Transformers](https://arxiv.org/pdf/1904.10509.pdf) @ OpenAI | TBA | ∅ | Apr-19
<br/>


## Review Papers
<div id="review-papers"></div>

| Paper | Date |
|:----|  :----: |
|[Sparsity in transformers: A systematic literature review](https://www.sciencedirect.com/science/article/pii/S092523122400239X)| Aug-23
|[Efficient Transformers: A Survey](https://dl.acm.org/doi/pdf/10.1145/3530811) @ Google Research | Dec-22
<br/>


## Awesome Related Repos

[Awesome-Efficient-LLM](https://github.com/horseee/Awesome-Efficient-LLM)

[Awesome-LLM-Inference](https://github.com/DefTruth/Awesome-LLM-Inference)

<br/><br/><br/>

Thanks to [horseee](https://github.com/horseee/Awesome-Efficient-LLM/blob/main/README.md?plain=1) for the table!

