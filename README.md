# LASSO-MLPNet for stellar atmospheric parameters estimation

This repo contains the code and trained models for our paper *Estimating Atmospheric Parameters from LAMOST Low-Resolution Spectra with Low SNR*.

### Requirements

-pandas

-numpy

-scikit-learn(>=0.15)



### Experimental data:

-training data and test data:
```
Preprocessed_spectra_data.npy
```

-training label and test label：
```
Label_APOGEE_payne_LASP.npy
```


-estimation catalog
```
LASSO-MLPNet.csv
```



### Usage

- Training a new model:

  ```shell
  Jupyter Notebook LASSO_MLPNet.ipynb
  ```

### Citation

- If you found this code useful please cite our paper: 
- 
