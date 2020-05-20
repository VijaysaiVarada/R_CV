# R_CV
simple cv , loov cv and k-fold cv implementation in R 
Implementation of lm with cv.
The split of test train is done randomly and the model performance will be unreliable if we train the model on random train split
This is haldled using cv in k fold cv the uncertainitity in split is haldled by running the model multiple times on different test train splits
and the mean cv is used to choose the best model 
