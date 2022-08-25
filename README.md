<h1> Skin Diseases Detection </h1>
 
It's a project for learning how to use images, processing and using them in deep learning. This model is ready to classificate 7 types of skin diseases by using convolutional neural networks.

<img src="https://github.com/mkowalsky97/Skin_Cancer_Detection/blob/main/imgs/samples.png" width="600"/>

<h2> Tools </h2>

  - *Python v. 3.10.1*
  - *TensorFlow v. 2.9.1*
  - *Keras*
  - *Jupyter Notebook*

<h2> More about the project </h2>

1. The database used: [HAM1000 - read more](https://dataverse.harvard.edu/dataset.xhtml?persistentId=doi:10.7910/DVN/DBW86T)
2. Dataframe with all informations: 

<img src="https://github.com/mkowalsky97/Skin_Cancer_Detection/blob/main/imgs/dataframe.png" width="600"/>

3. Some data visualisation:

<div>
<img src="https://github.com/mkowalsky97/Skin_Cancer_Detection/blob/main/imgs/diseases.png" width="335"/>
<img src="https://github.com/mkowalsky97/Skin_Cancer_Detection/blob/main/imgs/gender.png" width="250"/>
</div>
<img src="https://github.com/mkowalsky97/Skin_Cancer_Detection/blob/main/imgs/age.png" width="600"/>
<img src="https://github.com/mkowalsky97/Skin_Cancer_Detection/blob/main/imgs/localisation.png" width="600"/>
<img src="https://github.com/mkowalsky97/Skin_Cancer_Detection/blob/main/imgs/age-dis.png" width="600"/>

4. The dataset was imbalanced, so after *RandomOverSampler*:

<img src="https://github.com/mkowalsky97/Skin_Cancer_Detection/blob/main/imgs/oversampling.png" width="600"/>

5. CNN model structure:

<img src="https://github.com/mkowalsky97/Skin_Cancer_Detection/blob/main/imgs/model.png" width="400"/>

6. Validation during the fitting, where **epochs = 15** and **batch = 47**:

<img src="https://github.com/mkowalsky97/Skin_Cancer_Detection/blob/main/imgs/loss.png" width="400"/>
<img src="https://github.com/mkowalsky97/Skin_Cancer_Detection/blob/main/imgs/acc.png" width="400"/>

7. Testing results: 

<img src="https://github.com/mkowalsky97/Skin_Cancer_Detection/blob/main/imgs/report.png" width="400"/>
<img src="https://github.com/mkowalsky97/Skin_Cancer_Detection/blob/main/imgs/matrix.png" width="400"/>

<h2>
   Conclusions
</h2>

**around 97% accuracy of the model**

<h2>
   License
</h2>

[MIT License](https://github.com/mkowalsky97/Skin_Cancer_Detection/blob/main/LICENSE.txt)
