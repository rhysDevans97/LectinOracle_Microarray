# LectinOracle

[LectinOracle_Microarray.ipynb](https://colab.research.google.com/drive/1Tk67xxra3W1fc4kJDQ5TLlpWUQaBEgGw)
Input amino acid sequence and specify to either use ESM1b modelling or flex; the former requires a high RAM GPU. The notebook also requires connecting to your GDrive and using a hosted GPU runtime.

Contains code and all necessary files to train and use LectinOracle models described in Lundstrøm et al., 2021.

LectinOracle is a deep learning-based model to predict the interaction of proteins and complex carbohydrates (glycans) based on their sequences, making it potent and easily generalizable. We used a pre-trained transformer-based architecture for analyzing the protein part and a graph convolutional neural network for analyzing the glycan sequences.

Abstract:
Ranging from bacterial cell adhesion over viral cell entry to human innate immunity, glycan-binding proteins or lectins abound in nature. Widely used as staining and characterization reagents in cell biology, and crucial for understanding the interactions in biological systems, lectins are a focal point of study in glycobiology. Yet the sheer breadth and depth of specificity for diverse oligosaccharide motifs has made studying lectins a largely piecemeal approach, with few options to generalize. Here, we present LectinOracle, a model combining transformer-based representations for proteins and graph convolutional neural networks for glycans to predict their interaction. Using a curated dataset of 564,647 unique protein-glycan interactions, we show that LectinOracle predictions agree with literature-annotated specificities for a wide range of lectins. We further identify clusters of lectins with related binding specificity that are not clustered based on sequence similarity. Using a range of specialized glycan arrays, we show that LectinOracle predictions generalize to new glycans and lectins, with qualitative and quantitative agreement with experimental data. We further demonstrate that LectinOracle can analyze whole lectomes and their role in host-microbe interactions. We envision that the herein presented platform will advance both the study of lectins and their role in (glyco)biology. 
