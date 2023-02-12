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


[Original Subclassing module]

[ 320]  Subclassing
├── [3.4K]  utils.py
├── [ 30K]  models.py
├── [1.7K]  load_trained_model.py
├── [  50]  ____init____.py
├── [ 192]  usage_example
│   ├── [255K]  example_vgg16.ipynb
│   ├── [124K]  example_lenet5.ipynb
│   ├── [544K]  example_googlenet.ipynb
│   └── [ 77K]  example_ensemble.ipynb
├── [ 224]  model_checkpoints
│   ├── [  96]  VGG16
│   │   └── [ 91M]  53_0.5009.hdf5
│   ├── [  96]  LeNet5
│   │   └── [ 24M]  21_0.4171.hdf5
│   ├── [  96]  GoogLeNet
│   │   └── [251M]  22_0.9526.hdf5
│   └── [ 128]  Ensemble
│       ├── [ 128]  Supmodel_checkpoint
│       │   ├── [175K]  ensemble_06_0.2691.hdf5
│       │   └── [175K]  ensemble_05_0.2715.hdf5
│       └── [  96]  Submodel_checkpoint
│           └── [ 24M]  LeNet5_01_0.2740.hdf5
└── [ 320]  datasets
    ├── [ 119]  sampled_dataset.py
    ├── [ 105]  merged_dataset.py
    ├── [  50]  ____init____.py
    ├── [  96]  sampled_dataset
    │   └── [8.9M]  sample_data.csv
    ├── [  96]  merged_dataset
    │   └── [739M]  merged_data.csv
    ├── [ 160]  Digit_Recognizer
    │   ├── [ 73M]  train.csv
    │   ├── [ 49M]  test.csv
    │   └── [235K]  sample_submission.csv
    └── [  96]  A-Z Handwritten Alphabets in .csv format
        └── [667M]  A_Z Handwritten Data.csv

14 directories, 23 files

------------------------------------------------------------------------

[Modified Sublcassing module]

[ 320]  Subclassing
├── [3.4K]  utils.py
├── [ 30K]  models.py
├── [1.7K]  load_trained_model.py
├── [  50]  __init__.py
├── [ 192]  usage_example
│   ├── [255K]  example_vgg16.ipynb
│   ├── [124K]  example_lenet5.ipynb
│   ├── [544K]  example_googlenet.ipynb
│   └── [ 77K]  example_ensemble.ipynb
├── [ 224]  model_checkpoints
│   ├── [  96]  VGG16
│   ├── [  96]  LeNet5
│   ├── [  64]  GoogLeNet
│   └── [ 160]  Ensemble
│       ├── [ 128]  Supmodel_checkpoint
│       │   ├── [175K]  ensemble_06_0.2691.hdf5
│       │   └── [175K]  ensemble_05_0.2715.hdf5
│       └── [  96]  Submodel_checkpoint
└── [ 320]  datasets
    ├── [ 119]  sampled_dataset.py
    ├── [ 105]  merged_dataset.py
    ├── [  50]  __init__.py
    ├── [  96]  sampled_dataset
    │   └── [8.9M]  sample_data.csv
    ├── [  64]  merged_dataset
    ├── [  64]  Digit_Recognizer
    └── [  64]  A-Z Handwritten Alphabets in .csv format

14 directories, 14 files