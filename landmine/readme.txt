LandmineData.mat contains two 1-by-29 cell arrays "feature" and "label". Each cell of the cell arrays corresponds to one task, index consistent with that in the MTL paper. Each cell of "feature" is an N_m-by-9 data matrix, where N_m is the number of samples for task m, m=1,...,29, i.e., each sample is described by a 9-dimensional feature vector, stored in the corresponding row of the data matrix. Each cell of "label" is an N_m-dimensional binary vector.



Description vue ici:
https://arxiv.org/pdf/1312.2606.pdf

Tasks 1 − 15 correspond to regions that are relatively highly foliated, while the other 14 tasks correspond
to regions that are bare earth or desert.