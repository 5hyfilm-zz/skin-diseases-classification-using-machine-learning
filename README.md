# JSTP #22 Skin Diseases Classification Using Machine Learning
This was JSTP #22 project about using machine learning to classify most 10 skin diseases in Thailand but I get only 4 skin diseases in [PJ6103_DATA](https://github.com/EvilPickle-PCSHSPT/PJ61403_DATA)

## [PJ6103_DATA](https://github.com/EvilPickle-PCSHSPT/PJ61403_DATA)

**Non-dangerous skin diseases**
These classes no need to consult a doctor.

- Atopic Dermatitis [ad]
- Normal [nm]

**Dangerous skin diseases**
These classes no need to consult a doctor.
- Psoriasis [ps]
- Seborrhoeic Keratosis [sk]

## Process
Train CNN model by using [HAM10000](https://dataverse.harvard.edu/dataset.xhtml?persistentId=doi:10.7910/DVN/DBW86T) and transfer weights to [PJ6103_DATA](https://github.com/EvilPickle-PCSHSPT/PJ61403_DATA) then ensemble the best 3 models for the best result.

## About work
- For [JSTP work](https://github.com/filmerxyz/JSTP22_SkinDiseaseClassificationUsingMachineLearning/tree/master/JSTP_work)
- For [Best work](https://github.com/filmerxyz/JSTP22_SkinDiseaseClassificationUsingMachineLearning/tree/master/PJ61403_work)


## Usage
* Clone this [respository](https://github.com/filmerxyz/JSTP22_SkinDiseaseClassificationUsingMachineLearning)

* Terminal: `git clone https://github.com/filmerxyz/JSTP22_SkinDiseaseClassificationUsingMachineLearning`

* Jupyter Notebook: `!https://github.com/filmerxyz/JSTP22_SkinDiseaseClassificationUsingMachineLearning`

## Results
### Confusion Matrix and Classification Report
<img src=https://github.com/filmerxyz/JSTP22_SkinDiseaseClassificationUsingMachineLearning/blob/master/image/cm.png>

![](https://github.com/filmerxyz/JSTP22_SkinDiseaseClassificationUsingMachineLearning/blob/master/image/report.png)

<p>
    <img src=https://github.com/filmerxyz/JSTP22_SkinDiseaseClassificationUsingMachineLearning/blob/master/image/ad.png width="200" height="200">
    <img src=https://github.com/filmerxyz/JSTP22_SkinDiseaseClassificationUsingMachineLearning/blob/master/image/ad.png width="200" height="200">
    <img src=https://github.com/filmerxyz/JSTP22_SkinDiseaseClassificationUsingMachineLearning/blob/master/image/ad.png width="200" height="200">
    <img src=https://github.com/filmerxyz/JSTP22_SkinDiseaseClassificationUsingMachineLearning/blob/master/image/ad.png width="200" height="200">

</p>

## Caution
Some line of code are wrong because I changed some filenames and I did not update those filenames, so if you want to run code you need to update some line of code.
