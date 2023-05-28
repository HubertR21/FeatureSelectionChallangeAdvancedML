# FeatureSelectionChallangeAdvancedML
The implementation of the project for Advanced Machine Learning classes during the Data Science course at MiNI, WUT.

## Authors

[Hubert Ruczyński](https://github.com/HubertR21)

[Adrian Stańdo](https://github.com/adrianstando)

## Repository description
`Model_training_cache`, `Model_training_files`, and `cached_results` contain the files gereated during the `Model_training.Rmd` execution. Saving of those files let's us speed up the process of building the `Model_training.html` files

The `data` folder contains the validation datasets preprocessed with feature selection scripts.

The `outcomes` folder contains the ourcomes in the form of txt files, which contain either a posterior probabilities or the binary labels of the classes.

The `preprocessed_freq_001`, `preprocessed_freq_01_MI`, and `preprocessed_raw` folders contain the files with the preprocessed (FS) data used in the `Model_training.Rmd`.

The `Model_training.Rmd` file performs a training of the models with the use of AutoML package the [forester](https://github.com/ModelOriented/forester).

The `Model_training.html` is a rendered and calculated version of the `Model_training.Rmd` file.

The `preprocessing.ipynb` file peforms feature selection with Python language.

The `preprocess_submission.ipynb` file performs preprocessing of the validation dataset for the best preprocessing method.
