# fruitdataset
Fruit Dataset - 163 images of 15 classes of fruits.

Images:
 - fuits.zip: original color images
 - fruitsContour.zip: binary images with countour of each fruit
 - filename-class.csv: CSV file with fruit filename and its respective class (kind of fruit)

Features (ARFF file format):
 - Fourier.arff: Fourier transform computed from X and Y coordinates of the fruit contour
 - RGBcomFundo.arff: statistical descriptors from RGB information -- with background
 - RGBsemFundo.arff: statistical descriptors from RGB information -- without background
 - RGBcomFundo_Fourier.arff: combination of 'Fourier.arff' and 'RGBcomFundo.arff' features
 - RGBsemFundo_Fourier.arff: combination of 'Fourier.arff' and 'RGBsemFundo.arff' features
 - PEx-Image-features.arff: PEx-Image image features -- see PExImage-Features.pdf
 

Papers:

[1] Priscila A. Macanhã, Danilo Medeiros Eler, Rogério E. Garcia, Wilson E. Marcilio Junior (2017).
Handwritten Feature Descriptor Methods Applied to Fruit Classification.
In Proceedings of the 14th International Conference on Information Technology: New Generations, pages 699-705.
DOI https://doi.org/10.1007/978-3-319-54978-1_87
https://link.springer.com/chapter/10.1007/978-3-319-54978-1_87

[2] Marcela Nishida, Danilo Medeiros Eler, Almir O. Artero, Maurício A. Dias (2015).
Comparison of feature spaces in fruit recognition.
In Proceedings of the XI Workshop de Visão Computacional, pages 71–76.
http://iris.sel.eesc.usp.br/wvc/Anais_2015/Proceedings_WVC2015.pdf

[3] Priscila A. Macanhã, Wilson E. Marcilio Junior, Danilo Medeiros Eler, Rogério E. Garcia, Ronaldo C. M. Correia (2015).
New Approaches of Feature Extraction from Fruits to Augmented Reality Systems.
In Proceedings of the XII Workshop de Realidade Virtual e Aumentada, pages 42-47.
https://github.com/daniloeler/wrva2015_anais

