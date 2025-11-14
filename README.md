It is known that in Image classification problem classes with a high number
of data samples dominate in conventional supervised learning
setup. Therefore, Our research focused on trying to minimize the
effect of class imbalance exists in Chest-Xray datasets.Medical
Image datasets are highly imbalanced due to the minimal number
of cases of rare diseases. For that reason, We proposed a hybrid architecture
which put together supervised learning and few-shot learning.
For common class detection, we used a pretrained MobileNetV2 as the base model of the classical supervised learning. For
Rare classes, a few shot learning model, Relation Network was
responsible for detecting rare disease classes. Our proposed
hybrid pipeline achieved an average of 90% F1 score on
the rare classes.
