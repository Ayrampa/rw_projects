# Medicago Salt Tolerance

This Jupyter notebook is devoted to the Srlk-gene nucleotide polymorphism analysis. Previously (in the PhD thesis) perennial Medicago accessions were taken in the sequencing experiments and were simultaneously evaluated for salt tolerance in a greenhouse. 

The data is imported as `df` and contains revealed nucleotide polymorphism of the Srlk-gene, root, stem length, and vitality of the plants.

In the thesis, the data were analyzed with Statistica™. Here we re-study the data with the sklearn python library.

In addition to the principal component analysis, we incorporate Random Forest Classifier to predict the ability of Medicago plants to survive under salt stress (`Vitality` feature) and identification important alleles.
