# EEG-Emotion-Recognition-using-DGCNN

Recognizing emotional states from electroencephalogram, or Electroencephalogram (EEG), signal
data is challenging due to its large dimension and intricate spatial dependencies. This paper illustrates a
novel approach to Electroencephalogram (EEG) data analysis in emotion recognition tasks that employ
Dynamic Graph Convolutional Neural Networks (DGCNN). Our novel architecture takes advantage of
the inherent graph structure of Electroencephalogram (EEG) electrodes to effectively capture spatial
relationships and dependencies. Our approach used a refined DGCNN model to process and classify
the data into four primary emotional states- Happy, Sad, Fear, and Neutral, we configured the DGCNN
with 20 input features per electrode, optimized across 62 electrodes, and utilized multi-layered graph
convolutions. The model achieved an overall classification accuracy of 97%, with similarly high macro
and weighted average scores for precision, recall, and F1-score, demonstrating its resilience and accuracy
