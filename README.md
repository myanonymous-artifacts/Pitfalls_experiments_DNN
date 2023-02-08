# Pitfalls in Experiments with DNN4SE: An Analysis of the State of the Practice

Software engineering techniques are increasingly relying on deep learning approaches to support many software engineering tasks, from bug triaging to code generation. To assess the efficacy of such techniques researchers typically perform controlled experiments. Conducting these experiments, however, is particularly challenging given the complexity of the space of variables involved, from specialized and intricate architectures and algorithms to a large number of training hyper-parameters and choices of evolving datasets, all compounded by how rapidly the machine learning technology is advancing, and the inherent sources of randomness in the training process. In this work we conduct a mapping study, examining 194 experiments with techniques that rely on deep neural networks appearing in 55 papers published in premier software engineering venues to provide a characterization of the state-of-the-practice, pinpointing experiments common trends and pitfalls. Our study reveals that most of the experiments, including those that have received ACM artifact badges, have fundamental limitations that raise doubts about the reliability of their findings. More specifically, we find: 1) weak analyses to determine that there is a true relationship between independent and dependent variables (87% of the experiments), 2) limited control over the space of DNN relevant variables, which can render a relationship between dependent variables and treatments that may not be causal but rather correlational (100% of the experiments), and 3) lack of specificity in terms of what are the DNN variables and their values utilized in the experiments (86% of the experiments) to define the treatments being applied, which makes it unclear whether the techniques designed are the ones being assessed, or how the sources of extraneous variation are controlled. We provide some practical recommendations to address these limitations.

# Contents of this Repository

There are 3 folders in this repository:

- 3_Analysis_of_papers. Contains 3 pdf files with the results of the analyses of papers presented in Section 3 of the paper, plus one file with additional analyses not included in the paper:

    *	3_1_Search_results: Data for Section 3.1 of the paper. This includes a summary of the results of the search and selection process and the list of papers retrieved from SCOPUS, along with the inclusion/exclusion criteria applied to each one.

    *	3_2_Papers_characterization: Data for Section 3.2 of the paper. It contains the information retrieved from each individual paper associated to the steps of the experimental process, for each experiment described in the papers.

    *	3_3_Papers_summary: Data for Section 3.3 of the paper. It includes a description of the characterization criteria, along with its application to the 194 experiments (per venue and overall). 

    *	Papers_per_experiment_type: Additional material (does not appear in the paper) containing a classification of experiments by type and the results of the characterization of the experiments per type.

- 4_Analysis_of_artifacts. Contains 2 pdf files with the results of the analysis of artifacts presented in Section 4 of the paper:

    * Characterization_badges. For those papers that earned an ACM artifact badge, this file includes the information retrieved from the paper, and the information that the artifact adds to the one in the paper.

    * Summary_discrepancies. A summary of the discrepancies found between papers and artifacts.

-	5_Implications. Contains 1 pdf file with the results of the analysis of validity presented in Section 5 of the paper:

    * Validity_analysis. The raw data corresponding to Fig. 3 in the paper is provided, along with the detailed values for each experiment.

