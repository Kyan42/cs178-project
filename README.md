# Allele Variant Pathogenicity Classifier

## Team: ChiK-fiL-a (Group 84)
Members: Colon Kwon, Keyon Jazayeri, Lex Truong

Professor Berg
CS178
University of California, Irvine

### Overview
Our project predicts the pathogenicity, or the "ability to cause disease," of allele variants. Given a variant, our multiclass classifier predicts if it is benign, likely benign, pathogenic, or likely pathogenic.

### Dataset
To create a high-quality labeled dataset, we integrate two curated variant databases:

- [**ClinVar**](https://ftp.ncbi.nih.gov/pub/clinvar/tab_delimited/) – clinically interpreted variants
- **ncVarDB** – manually curated benign and pathogenic non-coding variants

We focus on each variant's *chromosome*, *start* and *end* position, and *mutatated allele* to predict its pathogenicity.

### Classifier
After starting with a simple/random model to get a baseline accuracy for our data, we will test multiple types of models with different hyperparameters. These models include naiive Bayes, decision trees, random forests, and neural networks.

**What will be the best one???**

[Presentation Slides](https://docs.google.com/presentation/d/121mQG-m-s66KWJ24cenoSG_wep6AFmS4Tft9HPx6PT0/edit?usp=sharing)
[More Info on our Datasets](https://docs.google.com/document/d/16ZdtEIUICCZ9heCVjdewYdsU7RZDKKe8NwaXwbGBDEA/edit?usp=sharing)