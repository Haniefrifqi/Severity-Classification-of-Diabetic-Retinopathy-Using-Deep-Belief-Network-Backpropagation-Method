# Severity-Classification-of-Diabetic-Retinopathy-Using-Deep-Belief-Network-Backpropagation-Method

The background of this research is that Diabetic Retinopathy (DR) is a
disease that builds up blood sugar concentration in the eye. Examination of the
severity of DR disease manually by an ophthalmologist can provide diagnostic
results that seem subjective and inaccurate. The purpose of this research is to
implement a system based on digital image processing and deep learning to detect
the severity of DR. The benefit of this research output is that it can be used as a
reference by ophthalmologists to produce a more accurate examination of DR
disease.
This research uses cropping, re-size, Contrast Limited Adaptive Histogram
Equalization, and Non-Local Means Denoising methods in the pre-processing
stage, then the segmentation stage uses the closing morphology and adaptive
thresholding methods. The resampling stage uses the ADASYN method, while the
classification stage uses the Deep Belief Network-Backpropagation (DBNBackpropagation) method. This study uses data from the MESSIDOR dataset and
Indian Diabetic Retinopathy image Dataset (IDRiD).
This system is able to produce performance on the IDRiD dataset with an
accuracy of 49,51%, a precision of 52%, a recall of 50%, and an F1-score of 47%,
while the MESSIDOR dataset is able to produce an accuracy performance of 47%,
a precision of 45 %, recall by 47%, and F1-score by 45%. The resulting
performance is still low due to the small amount of data used in the deep learning
system and the complexity of the detection of DR disease object objects in the
dataset images used.

The result when using IDRiD dataset:
![image](https://user-images.githubusercontent.com/92786679/141990887-4cf5bf09-73dd-4081-b9e8-4e328d822b18.png)

