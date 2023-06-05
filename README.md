# Logistic Regression Tutorial👨🏼‍🏫

In this tutorial, I implement Logistic Regression with Python. I build a Logistic Regression classifier to predict a tumour as malignant or benign. I train a binary classification model using Logistic Regression. The variable I’m going to be predicting can have one of the 2 values: 0 or 1.

**✏️Terminology.**

Before we start with the analysis, it is important to understand what exactly we are trying to predict and what the information provided. “Benign” refers to a type of medical condition that is not cancerous or dangerous as opposed to “Malign”. The dataset contains 9 independent variables, each of them is a feature that is typically used in breast cancer analysis. 

- Clump thickness is a measure of the thickness of the cells in a tumor. Benign cells tend to be grouped in mono-layers, while cancerous cells tend to be in multiple layers.
- Uniformity of cell size and uniformity of cell shape are two characteristics that can be used to describe the appearance of cells under a microscope. Here we are checking the degree to which the cells in a sample are similar in size and shape.
- Marginal adhesion is the degree to which cells in a tissue sample adhere, or stick, to one another at the edges of the sample. Loss of adhesion might be a sign of malignancy.
- Single epithelial cell size is the size of individual cells in an epithelial tissue sample. Epithelial tissue is a type of tissue that covers the surface of the body and lines internal organs and structures. It is made up of cells that are tightly packed together and held in place by specialized junctions.
- Bare nuclei refers to cells in a tissue sample that are missing their cell membranes and cytoplasm, leaving only the nucleus visible.
- Bland chromatin is the appearance of the genetic material (chromatin) in the nucleus of a cell under a microscope. Chromatin is made up of DNA and proteins, and it contains the genetic information that controls the cell’s functions. When the chromatin in a cell’s nucleus is compact and uniform in appearance, it is said to be “bland.”
- Normal nucleoli are small, spherical structures found within the nucleus of a cell. They are composed of DNA, RNA, and proteins and are responsible for synthesizing ribosomes, which are the cellular structures that produce proteins. Nucleoli are usually visible under a microscope and can vary in size and appearance depending on the stage of the cell cycle and the cell’s function. In normal, healthy cells, nucleoli are usually small and have a distinct, well-defined border.
- Mitosis is the process of cell division that occurs in all living organisms. During mitosis, a single cell divides into two daughter cells, each of which contains a copy of the parent cell’s DNA. The process of mitosis is essential for the growth and repair of tissues and the production of new cells.
- Class contains the values 2 or 4 (‘malignant’ = 4 or ‘benign’ = 2).

**📚References.**

- https://www.kaggle.com/datasets/marshuu/breast-cancer.
- Johns Hopkins University, 2023, Glossary of Breast Cancer Terms, <https://pathology.jhu.edu/breast/glossary>.
- Sarkar, S K, Nag, A, 2017, Identifying Patients at Risk of Breast Cancer through Decision Trees, viewed 15 January, 2023, <https://www.researchgate.net/publication/325868350_Identifying_Patients_at_Risk_of_Breast_Cancer_through_Decision_Trees>.




