# EECE570-Final-Project
code for EECE570 Final Report "Improving Fairness in Image Classification via Sketching Style Combination"

Ruichen Yao

84951482


## Overall Pipeline
![avatar](./img/method.png)
I convert the original input images into sketch style combined images instead of sketch images with only one style. Then I feed sketch style combined images to the following classification model for prediction. To further fairness improvement, I introduce a fairness loss function to mitigate the bias in the model.
