# π¦ Ultrasound_Image_Classifications

## π Discription

> open sourceλ‘ μ κ³΅λλ ultrasound dataλ€μ μ΄μ©ν΄μ classification νλ λͺ¨λΈμ κ΅¬μ±ν΄λ³Ό μμ 

## π Datasets

### busi dataset structure

```
βββ train
β   βββ normal
β   βββ malignant
β   βββ benign
βββ test
β   βββ normal
β   βββ malignant
β   βββ benign
βββ all
β   βββ normal
β   βββ malignant
β   βββ benign
```

## π notebooks

### - busi_classifier
```
# version_0915 
  κΈ°λ³Έμ μΈ 3 classλ₯Ό predictionνλ μ½λ
  : basic classification (with timm or torchvision)
  : metrics (Acc, ROC curve, AUC, Classfication reports, Confusion Matrix)
  : k-fold validation (StratifiedKFold,..)
```
