# MFML_Bayesian_KNN
You will find here the code associate to Report of ‘A Bayesian reassessment ofnearest–neighbour classification’ Repositories.
Authors: Andra Chiorcea and Zhengyang Lan
Professor: Dr Rémi Bardenet 
Original authors: Lionel Cucala, Jean-Michel Marin, Christian P. Robert and D.M. Titterington

The file MFML.ipynb is the main part, it includes the methods form this paper that we have implemented.
At first, it's the error rate by cross validation leave one out of original KNN with different k.
I also define a class to simplify the computation of neighbour, potential function, etc.

It also containes the method written in 6.1, you should run that after running the first three boxes.
Run Plot_Maxlikelihood_potts_model function to get the plot of likelihood and the value of max likelihood for Potts model.
Next run Plot_Maxlikelihood_boltzmann_model function to get the plot of likelihood and the value of max likelihood for Boltzmann model.



For the file KNN_radio.ipynb is about the method I proposed with chapter 6.2. We can call it KNN radio method.
It shows the average error rate by cross validation leave one out of KNN radio method and the time it takes to compute, in comparison with the Original KNN.

For all the .ipynb file, you can open see the result directly in github. If you want to run it, you can open it with Colab online or download it then open it with jupyter notebook.


