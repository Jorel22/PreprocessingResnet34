# PreprocessingResnet34
The functions used for pre-processing are in the "preprocessing_functions" file. Those functions are applied in each image depending in the desired experiment.
The training and testing step is in the "Training_and_testing" file. The data uploades must be data pre-processed either with histogram equlization or color mapping or both.
The root directory need to have the following structure:
Dataset:
-Taining:
  -Covid
  -NoCovid
Validation:
  -Covid
  -NoCovid
