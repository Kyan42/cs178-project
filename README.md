# Allele Variant Pathogenicity Classifier

## Team: ChiK-fiL-a (Group 84)
Members: Colon Kwon, Keyon Jazayeri, Lex Truong

Professor Berg
CS178
University of California, Irvine

### Overview
Our project predicts the pathogenicity, or the "ability to cause disease," of allele variants. Given a variant, our binary classifier predicts if it is benign or pathogenic.

[Presentation Slides](https://docs.google.com/presentation/d/121mQG-m-s66KWJ24cenoSG_wep6AFmS4Tft9HPx6PT0/edit?usp=sharing)

### Dataset
To create a high-quality labeled dataset, we integrate two curated variant databases:

- **Humsavar** - UniProt human missense variants
- **dbNSFP 5.3a** - functional prediction and conservation scores

We train on each variant's *chromosome*, *position*, and *mutatated nucleotide*, along with several computed *pathogenicity prediction scores* to predict its pathogenicity. These prediction scores include SIFT, PolyPhen-2, CADD, REVEL, and others.

[More Info on our Datasets and Features](https://docs.google.com/document/d/1Ve1fyprCpVqA8yluqmOKTQsCM4DboclaBZ660_Pp-a8/edit?usp=sharing)

### Classifier
After starting with a simple/random model to get a baseline accuracy for our data, we will test multiple types of models with different hyperparameters. These models include naive Bayes, decision trees, random forests, and XGBoost.

**Which will be the best one???**
