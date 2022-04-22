All the code contained within is for Group 11's final project on human activity recognition using sensor data.

The "351_project" notebook is for the actual code. It is configured to run for ONE model. To switch which model is currently being run, select the correct model builder function in code cell 8, and pass it to the keras tuner in code cell 9. If the model is a CNN, the CNN reshape flag should be enabled in code cell 7.

The "test" notebook is a throwaway script used for examining the results of the hyperparameter tuning trials.

When hyperparameter tuning is done, it will generate a folder called "untitled_project" containing data from all the trials. When switching to a different model, this file must be deleted or renamed, otherwise keras tuner will try to use the parameters from the previous run to build the new model.

"sdata.csv" is the subset of the data used for the project. The cleaned_data directory contains all of the data.