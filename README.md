# Foursquare-Location-Matching
DSAI2022 Final Project Submission, Kaggle-Foursquare-Location-Matching
Includes my 1dcnn_method (0.787) and lgb_method (0.829).

## Final Score 【0.845】
![image](https://user-images.githubusercontent.com/41388159/172056174-14a50da5-e970-40dc-bd6e-73fcdf7c15ee.png)


## Re-implement performance 

### Catboost (0.845)
> fine-tuned this [Kaggle Notebook](https://www.kaggle.com/code/nlztrk/public-0-836-catboost-fast-fe-22-features)

1. import `catboost-0.845.ipynb` to Kaggle Notebook
2. add competition dataset
3. add https://www.kaggle.com/datasets/nlztrk/4sq-catboost-models to dataset
4. run-all and submit

![image](https://user-images.githubusercontent.com/41388159/172057025-7acd8806-0157-4055-962d-17af62bb1730.png)



### LGB (0.834)
> fine-tuned this [Kaggle Notebook](https://www.kaggle.com/code/guoyonfan/binary-lgb-baseline-0-834)

1. import `lgb-0-834.ipynb` to Kaggle Notebook
2. add competition dataset
3. add [[https://www.kaggle.com/datasets/nlztrk/4sq-catboost-models](https://www.kaggle.com/datasets/guoyonfan/binary-lgb-baseline)](https://www.kaggle.com/datasets/guoyonfan/binary-lgb-baseline) to dataset
4. run-all and submit
![image](https://user-images.githubusercontent.com/41388159/172057102-bde569a5-2765-476e-a431-83479494baa6.png)


### My-Lgb, ensamble (0.829), single-model (0.828)
#### Training
1. run `prepare-lgb-training-data.ipynb` get training_data
2. add training_data above and run `my-lgbm-training.ipynb` get models

#### Inference Ensamble (0.829)
1. Add the following dataset then run `my-lgb-testing-0.829.ipynb`
  - https://www.kaggle.com/datasets/axotcc/lgb-new-train
  - https://www.kaggle.com/datasets/axotcc/lgbgetall1all008
  - https://www.kaggle.com/datasets/axotcc/lgbmnestimators1600
  - https://www.kaggle.com/datasets/axotcc/lgbmversion2
  - https://www.kaggle.com/datasets/axotcc/my-lgb-model
![image](https://user-images.githubusercontent.com/41388159/172057070-2830d6cd-6c87-427d-87a4-c02166ad354e.png)


### My-1DCNN 0.787
#### Training
1. run `prepare-idcnn-training-data.ipynb` get training_data
2. add training_data above and run `my-1dcnn-training.ipynb` get models

#### Inference
1. Add following dataset then run `my-1dcnn-testing-0.787`
  - https://www.kaggle.com/datasets/axotcc/base-cnn-model
  - https://www.kaggle.com/datasets/axotcc/base-qt

![image](https://user-images.githubusercontent.com/41388159/172057331-1ccd62db-94f4-4ef5-9c56-d0531a64eaed.png)


