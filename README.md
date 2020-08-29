# PreprocessingResnet34
The functions used for pre-processing are in the "preprocessing_functions" file. Those functions are applied in each image depending in the desired experiment.

The training and testing step is in the "Training_and_testing" file. The data uploaded must be data pre-processed either with histogram equlization or color mapping or both.

The Dataset directory needs to have the following structure:

Dataset:

---Training:

------Covid

------NoCovid

----Validation:

------Covid

------NoCovid


Addtional can add a "Test" set
