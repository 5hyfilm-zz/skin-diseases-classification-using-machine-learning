# JSTP #22 Skin Disease Classification Using Machine Learning

This was JSTP #22 project about using machine learning to classify most skin disease in Thailand but I get only 4 skin disease in [PJ6103_DATA](https://github.com/EvilPickle-PCSHSPT/PJ61403_DATA)

## [PJ6103_DATA](https://github.com/EvilPickle-PCSHSPT/PJ61403_DATA)

**Non-dangerous skin disease**

These classes no need to consult a doctor.

- Atopic Dermatitis [ad]
- Normal [nm]

**Dangerous skin disease**

These classes no need to consult a doctor.
- Psoriasis [ps]
- Seborrhoeic Keratosis [sk]

## Process

Train CNN model by using [HAM10000](https://dataverse.harvard.edu/dataset.xhtml?persistentId=doi:10.7910/DVN/DBW86T) and transfer weights to [PJ6103_DATA](https://github.com/EvilPickle-PCSHSPT/PJ61403_DATA) then ensemble the best 3 models for the best result.

Some line of code are wrong because I changed some filenames and I did not update those filenames, so if you want to run code you need to update some line of code

## Usage
* Clone this [respository](https://github.com/filmerxyz/JSTP22_SkinDiseaseClassificationUsingMachineLearning)

* Terminal: `git clone https://github.com/filmerxyz/JSTP22_SkinDiseaseClassificationUsingMachineLearning`

* Jupyter Notebook: `!https://github.com/filmerxyz/JSTP22_SkinDiseaseClassificationUsingMachineLearning`
