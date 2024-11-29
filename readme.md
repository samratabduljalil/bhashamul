
# Bengali Regional IPA Transcription

This project aims to transcribe Bengali regional dialects into **IPA (International Phonetic Alphabet)** using state-of-the-art NLP models. The goal is to achieve accurate transcription by experimenting with various models and fine-tuning their hyperparameters.

---

## Models Evaluated

1. **Google ByT5 Small and  Base both**  
   - **Best performance** for Bengali regional IPA transcription.  
   - Fine-tuned using custom datasets with optimized hyperparameters.

2. **UMT5 Small and Base both**  
   - Tested for comparison but **underperformed** compared to ByT5 Small .

---

## Hyperparameter Tuning

To improve performance, the following hyperparameters were fine-tuned:

- **Epochs**: Optimal number of training epochs was determined for each model.  
- **warmup_steps** : 1000 give me the best result
- **Batch Size**: Tested with various sizes to balance training time and performance.

Each model configuration (**base** and **small**) was trained and evaluated in separate experiments for a detailed comparison.

---

## Results

- **Best Model**: Google **ByT5 Small ** provided the most accurate IPA transcriptions for Bengali regional dialects.  
- **Model Comparisons**: The **base** and **small** variants of each model were trained in separate runs, with results documented in individual files for clarity.

---



---

## How to Use
 
**Model link :** https://www.kaggle.com/datasets/samratabduljalil/bhashamul-01911


1. **Model Fine-Tuning**  
   Fine-tune your selected model (e.g., ByT5 Small ) using the provided training scripts and datasets.  
   Modify hyperparameters in the configuration file to experiment with optimal settings.

2. **Transcription**  
   Use the fine-tuned model for Bengali regional IPA transcription.  
   Scripts for preprocessing, training, and evaluation are included.

---

## Future Work

- **Dataset Expansion**: Add additional regional dialect samples for better generalization.  
- **Advanced Techniques**: Explore advanced models and methods to improve transcription accuracy further.  
- **Real-World Testing**: Evaluate performance using live speech data.  

---

**Contributions, suggestions, and feedback are welcome to make this project even better!**
