# Model Info
```
- nnet_type=ResNet34L
- pooling_type=TSP
- embedding_dim=256
- loss_type=amsoftmax
- scale=30.0
- margin=0.2
```


# Results
```
-----------------------------------------------------------------------------
| Training Set  | Test Set  | System                               | EER(%) |
-----------------------------------------------------------------------------
| Vox2.Dev      | Vox1-T    | ResNet34 + AM-Softmax + TSP + Cosine | 1.627  |
| Vox2.Dev      | Vox1-H    | ResNet34 + AM-Softmax + TSP + Cosine | 2.858  |
| Vox2.Dev      | Vox1-E    | ResNet34 + AM-Softmax + TSP + Cosine | 1.688  |
| Vox2.Dev      | SITW.D    | ResNet34 + AM-Softmax + TSP + Cosine | 3.119  |
| Vox2.Dev      | SITW.E    | ResNet34 + AM-Softmax + TSP + Cosine | 3.253  |
-----------------------------------------------------------------------------
```
