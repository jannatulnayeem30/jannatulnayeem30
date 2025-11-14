Disease diagnosis through medical image analysis
using various transfer learning models and neural networks
have made significant progress in recent years. However, Medical
Image datasets are highly imbalanced due to the minimal number
of cases of rare diseases. As a result of this imbalance, pre￾trained CNN models perform poorly in detecting rare diseases
in supervised classification tasks. Classes with a high number
of data samples dominate in conventional supervised learning
setup. Therefore, our research focused on trying to minimize the
effect of this class imbalance. We proposed a hybrid architecture
which put together supervised learning and few-shot learning.
For common class detection, we used a pretrained MobileNetV2 as the base model of the classical supervised learning. For
Rare classes, a few shot learning model, Relation Network was
responsible for detecting rare disease classes. Our proposed
hybrid architecture achieved an average of 90% F1 score on
the rare classes.
