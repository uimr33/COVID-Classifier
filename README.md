
# Coursework - Reproducing the claims in the paper using the given codebase and dataset 

Forked from https://github.com/abzargar/COVID-Classifier

### Citation to the original paper
    Zargari Khuzani, A., Heidari, M. & Shariati, S.A. COVID-Classifier: an automated machine learning 
    model to assist in the diagnosis of COVID-19 infection in chest X-ray images. 
    Sci Rep 11, 9887 (2021). https://doi.org/10.1038/s41598-021-88807-2
### Link to the original paper’s repo
    https://github.com/abzargar/COVID-Classifier
### Dependencies
    * scikit-image
    * scikit-learn
    * opencv-python
    * seaborn
    * keras
    * tensorflow
    * ipython
    * pydot
### Data download instruction
    Used dataset is available in this path: 
    https://github.com/abzargar/COVID-Classifier/tree/master/dataset

### Preprocessing
```
    preprocess_images.py 
    # Run for each (normal, covid, pneumonia)
```
        
```
    extract_features.py
    #Saves the created feature pools as .mat files
```    
        
```
    evaluate_features.py
    #Run for each  (normal, covid, pneumonia)
```
        
### Training and Evaluation
```
    train_model.py
    # Training and Evaluation
```

### Table of results
    The claim in the paper was reproducible. 
    Details of the results are documented in the project submission. 