# Principal_Component_Analysis
Image Compression - Implemented Principal Component Analysis to compress images

Principal Component Analysis is a popular dimensionality reduction technique which condenses information from a large set of variables into fewer variables by applying some sort of transformation onto them.

The transformation is applied in such a way that linearly correlated variables get transformed into uncorrelated variables.

Correlation tells us that there is a redundancy of information and if this redundancy can be reduced, then information can be compressed.

The direction of projection is determined using eigenvalues and eigenvectors.

The first few transformed features termed as Principal Components (PCs) are rich in information (explains most of the variance), whereas the last features contain mostly noise with negligible information in them.

We retain the first few principal components, thus reducing the number of variables significantly with minimal loss of information.
