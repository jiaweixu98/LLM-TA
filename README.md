# LLM-TA: LLM-Enhanced Thematic Analysis Pipeline

Code for the paper **"LLM-TA: An LLM-Enhanced Thematic Analysis Pipeline for Transcripts from Parents of Children with Congenital Heart Disease"** (Accepted by GenAI4Health Workshop at AAAI 2025).

## Getting Started

```bash
git clone https://github.com/jiaweixu98/LLM-TA.git
```
To reuse the code, you need to provide your LLM API key. Refer to the [LangChain official documentation](https://python.langchain.com/docs/integrations/chat/) for setup instructions.  

**Note:** The transcripts are not included in this repository. You can use your own data and modify the prompt to fit your context.  

### Notebooks  

- **`0_shot.ipynb`**: Contains our proposed method and evaluation code in a direct input/output setting.  
- **`1_shot.ipynb`**: Contains our proposed method and evaluation code with one exemplar provided.  
- **`reflexion.ipynb`**: Contains our proposed method and evaluation code using the Reflexion strategy.  

### Baselines  

The `baselines/` directory includes two baselines from:  

> De Paoli, S. (2024). Performing an inductive thematic analysis of semi-structured interviews with a large language model: An exploration and provocation on the limits of the approach. *Social Science Computer Review, 42(4)*, 997–1019.  

### Citation  

If you find this paper useful, please cite our paper:  

> **[ArXiv XXXX]**
