# Learn PaliGemma with Interactions

Interactive examples for understanding Google's PaliGemma vision-language model, plus a Colab notebook that runs the real models.

- **Interactive page:** https://latifakgun.github.io/learn-paligemma-with-interactions/
  SigLIP vs. CLIP, softmax overflow, the −10 bias, ViT patching, BatchNorm vs. LayerNorm, the input sequence, the Prefix-LM mask and `<loc>` tokens.
- **Notebook:** [`PaliGemma2_Ornek_Testleri.ipynb`](PaliGemma2_Ornek_Testleri.ipynb) · [Open in Colab](https://colab.research.google.com/github/latifakgun/learn-paligemma-with-interactions/blob/main/PaliGemma2_Ornek_Testleri.ipynb)
  SigLIP vs. CLIP on a real photo, captioning, VQA, detection and OCR at 224 vs. 448 pixels with PaliGemma 2 3B. Needs a T4 GPU and a Hugging Face token. The OCR section expects your own receipt photos (`fis1-3.jpeg`) and their transcriptions (`fis1-3.txt`); the author's receipts are not included.

The notebook is currently in Turkish; an English version is coming.

Based on Umar Jamil's [Coding a Multimodal (Vision) Language Model from scratch in PyTorch](https://www.youtube.com/watch?v=vAmKB7iPkWw) and the PaliGemma / PaliGemma 2 papers. Written by Latif Akgün as part of a Freya Research fellowship.
