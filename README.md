# Gradient Descent Clustering with Regularization to Recover Communities in Transformed Attributed Networks(GDCRinTAN).

### Author: Soroosh Shalileh
Head of Artificial Intelligence in Cognitive Science Laboratory (AICS);//
Research Fellow at Center for Language and Brain, HSE University, Moscow, Rf.//
PhD in Computer Science.

**Abstract.**

Community detection in attributed networks aims to recover clusters in which the within-community nodes are as interconnected and as homogeneous as possible, while the between-communities nodes are as disconnected and as heterogeneous as possible. The current research proposes a straightforward data-driven model with an integrated regularization term to recover communities. For further improvement of the quality of detected communities we also propose a softmaxed-scaled-dot-product to transform the data spaces into cluster-friendlier data spaces. We adopt the gradient descent optimization strategy to optimize our proposed clustering objective function. We compare the performance of the proposed method using both real-world and synthetic data sets with three state-of-art algorithms. Our results showed that the proposed method obtains promising result.


To use the GDCRinTAN, first clone to this repository; next, in the directory where the main.py is located, run the following command:


    python main.py --algorithm_name="gdcm_fn_e" --init="random" --run=1 --data_name="hvr" --update_rule="vgdc_reg" --verbose=1 --pp="mm-ms" --p_value=2. --step_size=0.1 --n_init=10 --n_repeats=10 --max_iter=10 


Currently only pandas dataframes are accepted and the must be located in ./Datasets/FN/ directory, unless a user modifies it.



The paper is under the review in ASONAM 2024.

    





