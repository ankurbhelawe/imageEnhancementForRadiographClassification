# imageEnhancementForRadiographClassification

This is a research oriented project to find out the effect of various image processing techniques on chest radiograph classification.

The dataset used was Paul Mooney's [Chest X-Ray dataset](https://www.kaggle.com/paultimothymooney/chest-xray-pneumonia). The goal was to classify the chest radiographs as having pneumonia or healthy.

## Results:

On the Paul Mooney Pneumonia dataset, a simple 2 layer, 1 epoch CNN was applied. Testing accuracy achieved was 78.7%. We retrained the same model with images after applying various image processing techniques on the data, and the results were thus:

| Image Processing Technique | Test Accuracy |
| --- | --- |
| NILL | 78.7% |
| Adaptive Equalisation | 62.48 |
| Histogram Equalisation | 62.49% |
| Laplace | 62.5% |
| Gradient Image | 66.39% |
| CLAHE | 81.41% |
| Close Image | 81.56% |
| Contraharmonic Mean | 85.1% |
| Contrast Stretching | 86.03% |
| Erosion | 86.54 |
| Open Image | 86.85% |
| Dilation | 87.19 |
