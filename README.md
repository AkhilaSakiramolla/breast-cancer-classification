# Breast cancer classification using K-Means

Here, we will use K-means clustering to try to diagnose breast cancer based solely on a Fine
Needle Aspiration (FNA), which as the name suggests, takes a very small tissue sample using a syringe.

To this end we will use the Wisconsin Diagnostic Breast Cancer dataset (https://pages.cs.wisc.edu/~olvi/uwmp/cancer.html#diag), containing information about 569
FNA breast samples. Then a clinician isolates individual
cells in each image, to obtain 30 characteristics (features), like size, shape, and texture. We will use these
30 features to cluster benign from malign FNA samples.
