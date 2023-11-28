# Research_Project (Msc Data Science & Applied Analytics)
"The Impact of Home Advantage in Sports: A Comprehensive Multi-Disciplinary Study" 

Summary: 

This scientific research project investigated the complex phenomenon of home advantage (HA) in sports, aiming to enhance our current understanding of its multifaceted nature. The study began by comprehensively reviewing existing literature on HA, spanning various sports, and considering factors such as team dynamics, scheduling, environmental influences, and gender disparities. Notably, this research bridges gaps in current knowledge by analysing HA in different sports contexts, exploring the impact of balanced vs. unbalanced scheduling, evaluating the role of a sport's inherent nature, and examining the influence of environmental factors on performance outcomes. HA was reported in each of the disciplines under inspection. Variations in the recorded HA magnitude between these disciplines was also found to be statistically significant.

The study also delved into the realm of predictive modelling using machine learning (ML) techniques, specifically focusing on HA in football. It extends the existing ML-driven sports prediction modelling studies by employing both traditional methods and modern deep learning techniques, ensuring a comprehensive evaluation of predictive capabilities. The XGBoost and recurrent neural network prediction models achieved the greatest overall accuracy, each scoring 64% in its prediction of home team win probability. 

More context: 

Python served as the primary programming language for this study, facilitating data manipulation, model building, and statistical analysis. Essential libraries like NumPy, Pandas, and Sci-kit-learn were instrumental in handling data frames, preprocessing data, performing classification tasks, and evaluating models. Visualization tools such as Matplotlib and Seaborn were crucial for visualizing data through scatter plots and confusion matrices, aiding in data distribution understanding and model evaluation.

The initial statistical analysis of this study involved computing Home Advantage (HA) scores and HA magnitude scores for six datasets using two distinct methods: 'method 1' based on a point system for win/draw/loss outcomes and 'method 2' calculating wins over total games (Pollard, 1986; Goumas, 2013).

T-tests were employed to evaluate the significance of differences in HA magnitudes between various sporting disciplines. This parametric test allowed for comparisons between pairs of sporting disciplines, aligning with established guidelines for hypothesis testing. The Tukey's Honestly Significant Difference (HSD) test was used as a post hoc analysis to thoroughly explore differences in HA scores among multiple sporting disciplines, effectively controlling the experiment-wise error rate and revealing specific group pairs with statistically significant differences 

Upon successful training of ML prediction models, confusion matrices were utilized to offer a detailed breakdown of the model's predictions, highlighting correct predictions and types of errors (true positives, true negatives, false positives, and false negatives). This comprehensive view aided in understanding the model's strengths and weaknesses. Additionally, several scoring metrics, including F1 score, precision, and recall, were incorporated to assess and compare model performance. These metrics allowed for comparisons between traditional and deep learning models, particularly useful in scenarios with imbalanced classes, providing insights into how well each model handles such datasets (references in Bishop and Nasrabadi, 2006; Dasgupta, 2018).

If you have any further questions surrounding the context or implementation of this research project, please feel free to reach out !
