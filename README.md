# recal_context
All stimulus location and responses, biases VE and VAE are in visual degrees.
0 is center, negative values are to the left, positive values are to the right.
For basic paradigm, see https://elifesciences.org/articles/47001, Figure 1 & Methods

N sub-dataset = 2
sub-dataset1: N subject = 21, larger dVA
sub-dataset2: N subject = 21, smaller dVA
*subjects are the same sample for both sub-datasets

1. Each dataset is a cell array of one or two sub-datasets.
The lowest level of array is the subject data.

2. Each subject data is a matrix and the first 8 columns are:

c1: AV trial V stimulus location

c2: AV trial A stimulus location

c3: A trial A stimulus location

c4: dVA: AV V - AV A (a.k.a, audio-visual discrepancy)

c5: AV trial response

c6: VE

c7: A trial response

c8: VAE

c9: AV trial confidence (%) 

c10: A trial confidence (%)
