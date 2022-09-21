
# Plant Disease Classification using with Knowledge Distillation and Transfer Learning

Plant leaves disease detection is the concern nowadays, disease can cause the huge loss in the agriculture field. In this project multiclass classification has applied. Total three approches has applied to do this classification first is with Transfer Learning models, second is with custom CNN and third is with knowledge Distillation concept. With first two methods CNN was giving good accuracy but model size is really huge. In real scenariao this type of solutions are applied in Mobile applications, IoT devices or web applications. To get proper performance with these application model size should be small as much as possible. 

In this project i have applied Knowledge Distillation concept with custom CNN and Transfer Learning models, here CNN is with best accuracy but with this experiment we are not using full parameters as we need to make model light in terms of size. As a result model size decrease around 30-40%. 

### These project is done with Google Colab pro +

## Required Packages 

Install 

```bash
  pip install tensorflow , mlflow, matplotlib
  
```

## File Descriptions

There are two folders in this project one Knoledge Distillation and another one is Transfer Learning

Knoledge Distillation folder is having three files: 
- One is having experiment code with Resnet152 + CNN
- Second is with Densenet121 + CNN
- Third is with VGG16 + CNN

Transfer Learning Folder is having one file:
- mainmodels.ipynb is having all Transfer Learning Model code and custom CNN with MLFlow analysis code.

Other Files:
- testing.ipynb is having code to analyse the model perfromance with all performance metrics such as Recall, F1_score, Precision, Specificity, Confusion Matrix etc.

- CNN_testing.ipynb is for custom CNN model analysis and performance metrics.





## Dataset

Plant Leaves Disease Images Taken From :

Data is having 39 distinct classes, I am only applying this experiment on 38 classes. Not using Backgrond images folder.

https://data.mendeley.com/datasets/tywbtsjrjv/1