| Dataset size | #Labels | features | SVM kernel | SVM class weight | SVM max_iter | Others | f1_score average setting | train f1_score | test f1_score  | Notes |
|:----:|:----:|----|----|----|:----:|-----|:----:|:----:|:-----:|-------|
| 61/278 | 4 | VGG16 on imagenet | linear | balanced | 25 | - | weighted | 0.569 | 0.277 | |
| 61/278 | 4 | VGG16 on imagenet | linear | balanced | 50 | - | weighted | 0.649 | 0.327 | |
| 61/278 | 4 | VGG16 on imagenet | linear | balanced | 75 |- | weighted | 0.709 | 0.365 | INDEX_1 |
| 61/278 | 4 |VGG16 on imagenet | linear | balanced | 100 |- | weighted | 0.805 | 0.323 | BAD accuracy: 0.087 |
| 61/278 | 4 |VGG16 face | linear | balanced | 150 |- | weighted | 0.563 | 0.352 | INDEX_4 |
| 99/278 | 4 | VGG16 face | linear | balanced | 125 |- | weighted | 0.647 | 0.350 | INDEX_5 |
| 123/278 | 4 | VGG16 Face | linear | balanced | 75 | - | weighted | 0.596 | 0.404 | INDEX_6|


INDEX_1

```
Training
Naive accuracy 4341/6221
Naive accuracy type 0 3042/4282
Naive accuracy type 1 376/483
Naive accuracy type 2 600/1057
Naive accuracy type 3 323/399

f1-score: 0.7093706008788654

Model saved.

==============================
Test accuracy:
Naive accuracy 851/2149
Naive accuracy type 0 593/883
Naive accuracy type 1 61/300
Naive accuracy type 2 158/632
Naive accuracy type 3 39/334

f1-score: 0.3651511145196964

accuracy by actor: 29/89
accuracy by actor type 0: 24/31
accuracy by actor type 1: 0/7
accuracy by actor type 2: 4/25
accuracy by actor type 3: 1/26
```

INDEX_2

```
Naive accuracy 3570/6594
Naive accuracy type 0 2707/4380
Naive accuracy type 1 217/575
Naive accuracy type 2 475/1192
Naive accuracy type 3 171/447

f1-score: 0.5626642159064329

Model saved.

==============================
Test accuracy:
Naive accuracy 821/2219
Naive accuracy type 0 552/941
Naive accuracy type 1 59/300
Naive accuracy type 2 190/632
Naive accuracy type 3 20/346

f1-score: 0.35167418657681093

accuracy by actor: 25/93
accuracy by actor type 0: 21/34
accuracy by actor type 1: 0/7
accuracy by actor type 2: 3/25
accuracy by actor type 3: 1/27
```

INDEX_3

```
max_iter = 200
Naive accuracy 4349/6594
Naive accuracy type 0 3980/6019
Naive accuracy type 1 369/575

f1-score: 0.7335661357133348

Model saved.

==============================
Test accuracy:
Naive accuracy 1294/2219
Naive accuracy type 0 1099/1919
Naive accuracy type 1 195/300

f1-score: 0.6487542207565516

accuracy by actor: 56/93
accuracy by actor type 0: 51/86
accuracy by actor type 1: 5/7
```

INDEX_4

```
Naive accuracy 5174/6594
Naive accuracy type 0 4829/6019
Naive accuracy type 1 345/575

f1-score: 0.8243108619726961

Model saved.

==============================
Test accuracy:
Naive accuracy 1512/2219
Naive accuracy type 0 1396/1919
Naive accuracy type 1 116/300

f1-score: 0.7234667058961475

accuracy by actor: 72/93
accuracy by actor type 0: 70/86
accuracy by actor type 1: 2/7
```

```
random f1 score: 0.2516468817633159
all good f1 score: 0.25256016793971514
weighted random f1 score: 0.297151904227101
```

INDEX_5

```
Naive accuracy 6919/10467
Naive accuracy type 0 5116/7355
Naive accuracy type 1 562/836
Naive accuracy type 2 623/1386
Naive accuracy type 3 618/890

f1-score: 0.6740328201506157

Model saved.

==============================
Test accuracy:
Naive accuracy 1273/3445
Naive accuracy type 0 903/1498
Naive accuracy type 1 99/300
Naive accuracy type 2 171/1058
Naive accuracy type 3 100/589

f1-score: 0.350148885425095

accuracy by actor: 60/140
accuracy by actor type 0: 56/57
accuracy by actor type 1: 0/7
accuracy by actor type 2: 0/36
accuracy by actor type 3: 4/40
```

INDEX_6

```
Naive accuracy 7930/13210
Naive accuracy type 0 6645/8909
Naive accuracy type 1 369/1084
Naive accuracy type 2 475/2009
Naive accuracy type 3 441/1208

f1-score: 0.5955322768434901

Model saved.

==============================
Test accuracy:
Naive accuracy 1860/4194
Naive accuracy type 0 1586/2171
Naive accuracy type 1 41/334
Naive accuracy type 2 156/1071
Naive accuracy type 3 77/618

f1-score: 0.403943558796438

accuracy by actor: 87/174
accuracy by actor type 0: 84/85
accuracy by actor type 1: 1/9
accuracy by actor type 2: 0/37
accuracy by actor type 3: 2/43
```