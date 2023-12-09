# CS184A-Final-Project
This repository includes the different notebooks and code for my final project.

The different notebooks all need to ran in Kaggle's environment, with the dataset for the Kaggle competition (Kaggle. https://kaggle.com/competitions/UBC-OCEAN).

The data exploration notebook is the one I used to examine and visualize the data (it is mostly composed from publicly available Kaggle notebooks, which I cited in that file).

The experiment notebooks (the files ending with "experimnet.ipynb" or "experiments.ipynb") are the ones I used to test models with different combinations of hyperparameters, and record their cross-validation accuracies. I did not include the output files from this notebook, but instead included the CSV files which I transferred the cross-validation accuracies into (I formatted these in a way that is more clear to understand).

Finally, the final testing notebooks (the files ending with "final-model.ipynb") are the ones in which I trained and tested the best model of each of the three convolutional neural network architectures with which I experimented. These split the given training dataset into a training and testing sets (85% for training and 15% for testing), train the model, test it, display the training and testing accuracies, and plot the accuracies and loss over the training epochs.

To run any of these notebooks, please create a new Kaggle notebook and import them. Then, go to the data tab, click the add data button, choose the competition datasets option, and then choose the "UBC Ovarian Cancer Subtype Classification and Outlier Detection (UBC-OCEAN)" dataset (Bashashati el. al., 2023). If the dataset does not appear, you will need to join the competition by heading to the competition main page (the one I linked below in the citation for the competition). Follow the steps from there (such as accepting the competition rules), and then you should be able to use the dataset. When you imported the notebook and selected the correct dataset, you should be able to run the notebook (with a GPU or a TPU or you wish, to make it run significantly faster).

For any further questions (or issues with running any of the notebooks), please reach out to me.


Citation for the Kaggle competition:
Ali Bashashati, Hossein Farahani, OTTA Consortium, Anthony Karnezis, Ardalan Akbari, Sirim Kim, Ashley Chow, Sohier Dane, Allen Zhang, Maryam Asadi. (2023). UBC Ovarian Cancer Subtype Classification and Outlier Detection (UBC-OCEAN). Kaggle. https://kaggle.com/competitions/UBC-OCEAN
