# Precision Recall Keras
Precision and Recall GAN Evaluations using Manifolds


Implementation of the metrics from this paper:

https://arxiv.org/pdf/1904.06991v1.pdf

In Keras.

# Use

1. Place data in /data/ folder.
2. Import get_prec_and_recall function, or add to precision-recall.py.
3. Enter the folder names of the real and fake data respectively as parameters to the function.
4. Optionally: Set n, meaning number of samples to use.
5. Optionally: Set get_scores, if True this will return realism scores for fake samples.
6. Run function.
