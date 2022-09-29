# breast-cancer-prediction
2021 SLDL final project

Invasive breast carcinoma with extensive intraductal component (EIC) may result in an incomplete surgical resection, and thus increase risk of local recurrence.
Pre-operative prediction of EIC-positive tumor can help breast surgeon make a surgical plan, and then improve surgical outcome.

### Dataset ###
2772 mamogram images from Kaohsiung Medical University

We use the nrrd file to get the position of the tumor and cut it off. Then, resize images to 1000*1000 pixel as our input data.

### Augmentation ###
Rotation & flip were added due to extreme class imbalance.
