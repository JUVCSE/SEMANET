This paper proposes a novel approach, where a Snapshot Ensemble-based MultiHead
Attention-aided framework is used for the vehicle image classification task. A modi-
fied CBAM attention module with spatial and channel attention is added to the base
classifier Xception network to increase its learning ability. The final classification at
the test time is done using a Snapshot Ensemble-based strategy using the predictions
made by each of the individual snapshots. Our developed model has three primary
phases, each adding unique functions to the framework as a whole. First, the raw
input images are normalized and standardized before being converted into tensors
to begin the processing. Subsequently, the input image for training data undergoes
image rescaling and other data augmentation strategies, such as a horizontal flip. In
the first stage, we have added a Separable Convolutional 2D layer with the baseline
model. In the second stage, we have added a Multi-Head attention-aided modified
CBAM attention module with the first stage. Finally, in the third stage, the Global
Average Pooling 2D layer is employed in the classification module, facilitating precise
classification. Our model achieves robust classification performance through this com-
prehensive approach, effectively addressing the challenges posed by complex datasets.
