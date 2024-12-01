# CMPE255 Short Story

# Research Paper
https://arxiv.org/pdf/2408.02752

# Medium Article
https://medium.com/@anthonyvn/exploring-visual-data-mining-through-diffusion-models-a-revolutionary-approach-c0196195ccb4

# Presentation
https://docs.google.com/presentation/d/1rKfwMV2EdQcwqqICWX0YoeChgbJXz6cotiXelmPuXgI/edit?usp=sharing

# Video 
https://youtu.be/oqkLRK9YCQE

# Abstract
This paper demonstrates how to use generative models trained
for image synthesis as tools for visual data mining. Our insight is that
since contemporary generative models learn an accurate representation
of their training data, we can use them to summarize the data by mining
for visual patterns. Concretely, we show that after finetuning conditional
diffusion models to synthesize images from a specific dataset, we can use
these models to define a typicality measure on that dataset. This measure
assesses how typical visual elements are for different data labels, such as
geographic location, time stamps, semantic labels, or even the presence of
a disease. This analysis-by-synthesis approach to data mining has two key
advantages. First, it scales much better than traditional correspondence-
based approaches since it does not require explicitly comparing all pairs of
arXiv:2408.02752v1 [cs.CV] 20 Jul 2024
2 I. Siglidis et al.
visual elements. Second, while most previous works on visual data mining
focus on a single dataset, our approach works on diverse datasets in
terms of content and scale, including a historical car dataset, a historical
face dataset, a large worldwide street-view dataset, and an even larger
scene dataset. Furthermore, our approach allows for translating visual
elements across class labels and analyzing consistent changes.
