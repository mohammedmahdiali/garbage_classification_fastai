# garbage_classification_fastai
#### Garbage Classification:
* Create appropriate __DataLoaders__ -> __dls.dataloaders(path)__
* Create a __Learner__ -> __cnn_learner(dls, metrics=[error_rate, accuracy])__
* Call a fit method -> __learn.fine_tune(n)__
* Make predictions or view results -> __learn.predict()__
