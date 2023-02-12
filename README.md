# Kaggle_Dacon_repository
struct model using subclassing method

# notfication
- Original Subclassing module includes train datasets and checkpoint of model.
- However, due to size limit of Github, some files has been removed.
- Github size limit : 10M
- 9 files has been removed
    - [91M]     :   model_checkpoints/VGG16/53_0.5009.hdf5
    - [24M]     :   model_checkpoints/LeNet5/21_0.4171.hdf5
    - [251M]    :   model_checkpoints/GoogLeNet/22_0.9526.hdf5
    - [24M]     :   model_checkpoints/Ensemble/Submodel_checkpoint/LeNet5_01_0.2740.hdf5
    - [739M]    :   datasets/merged_dataset/merged_data.csv
    - [73M]     :   datasets/Digit_Recognizer/train.csv
    - [49M]     :   datasets/Digit_Recognizer/test.csv
    - [235K]    :   datasets/Digit_Recognizer/sample_submission.csv
    - [667M]    :   datasets/A-Z Handwritten Alphabets in .csv format/A_Z Handwritten Data.csv



------------------------------------------------------------------------

[Original Subclassing module]

- Subclassing
    - \_\_init_\_\.py
    - utils.py
    - models.py
    - load_trained_model.py
    - usage_example
        - example_vgg16.ipynb
        - example_lenet5.ipynb
        - example_googlenet.ipynb
        - example_ensemble.ipynb
    - model_checkpoints
        - VGG16
            - 53_0.5009.hdf5
        - LeNet5
            - 21_0.4171.hdf5
        - GoogLeNet
            - 22_0.9526.hdf5
        - Ensemble
            - Supmodel_checkpoint
                - ensemble_06_0.2691.hdf5
                - ensemble_05_0.2715.hdf5
            - Submodel_checkpoint
                - LeNet5_01_0.2740.hdf5
    - datasets
        - \_\_init_\_\.py
        - sampled_dataset.py
        - merged_dataset.py
        - sampled_dataset
            - sample_data.csv
        - merged_dataset
            - merged_data.csv
        - Digit_Recognizer
            - train.csv
            - test.csv
            - sample_submission.csv
        - A-Z Handwritten Alphabets in .csv format
            - A_Z Handwritten Data.csv

14 directories, 23 files

------------------------------------------------------------------------

[Modified Sublcassing module]


- Subclassing
    - \_\_init_\_\.py
    - utils.py
    - models.py
    - load_trained_model.py
    - usage_example
        - example_vgg16.ipynb
        - example_lenet5.ipynb
        - example_googlenet.ipynb
        - example_ensemble.ipynb
    - model_checkpoints
        - VGG16
        - LeNet5
        - GoogLeNet
        - Ensemble
            - Supmodel_checkpoint
                - ensemble_06_0.2691.hdf5
                - ensemble_05_0.2715.hdf5
            - Submodel_checkpoint
    - datasets
        - \_\_init_\_\.py
        - sampled_dataset.py
        - merged_dataset.py
        - sampled_dataset
            - sample_data.csv
        - merged_dataset
        - Digit_Recognizer
        - A-Z Handwritten Alphabets in .csv format

14 directories, 14 files
