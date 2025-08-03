# amsterdam-guesser
This is a repository created for submission purposes as Individual Assignment for Applied AI Research Seminar course.


1. Folder 'modelling_output':
   
Contains the results of the modelling stage (modelling.ipynb), that is:
- Models:

  a) Original dataset based on ResNet50,
  
  b) Reduced & augmented dataset based on ResNet50,
  
  c) Reduced & augmented dataset based on EfficientNet.
  
- Test images and labels (reduced & augmented dataset),
  
- Predicted labels (reduced & augmented dataset):
  
  a) Based on ResNet50,
  
  b) Based on EfficientNet.
  
- Label encoder (reduced & augmented dataset).

2. Folder 'notebooks':

Contains the notebooks used for this project, that is:

- Preprocessing (combining image metadata with dataset containing polygons representing Amsterdam neighborhoods' boundaries, data visualization, image preprocessing),
  
- Modelling (training and testing all-three models),
  
- Model evaluation (Results visualiza2on and discussion).
  
3. Folder 'predictions_example':
   
Contains the predictions examples (both correct and incorrect) of the model of reduced & augmented dataset based on EfficientNet. Examples were created in model_evaluation.ipynb.

5. Folder 'to_read':
Contains all files that need to be read in the notebooks. This includes:

- Pre-trained model weights (ResNet50 and EfficientNet),
  
- Metadata and Amsterdam neighborhoods’ boundaries,
  
- Modelling results (neighborhood accuracies and result metrics).
