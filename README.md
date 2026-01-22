This project compares:
- **Discriminative model:** Logistic Regression (classification)
- **Generative model:** Simple GAN (image generation)

Both models are trained on the **MNIST dataset**

Preprocessing:
- **Logistic Regression:** images flattened to 784 features and normalized to **[0,1]**
- **GAN:** images scaled to **[-1,1]** to match the generator’s `tanh` output
  
## Files in this Repository
- Assignment 1 - Foundations Reflection.ipynb
Written report (2–3 pages) including:
  - Introduction, methods, results, reflection, and conclusion
