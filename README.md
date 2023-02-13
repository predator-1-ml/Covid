# Covid Classification and Opacification using Transfer Learning

The application of computer vision technology to detect and classify this virus from a chest
X-ray picture can be a very valuable addition to the less sensitive traditional method of detecting COVID-19, namely reverse transcription polymerase chain reaction (RT-PCR).
This automated technique has the potential to improve on current COVID-19 treatment methods while also alleviating the scarcity of skilled physicians in rural areas. Again, segmenting diseased regions from a chest X-ray picture can aid medical practitioners in gaining insight into the afflicted area. So, in this research, we employed a deep learning-based transfer learning
approach for CT-scan and X-ray image classification, and a U-Net architecture for segmentation to segment the afflicted region. On the available X-ray dataset, 99.7% classification
accuracy was obtained, 99.4% on the available CT-scan dataset, and 87% average accuracy
from the segmentation process.

# Datasets

We have utilized different datasets for classification and segmentation. For classification, we
have used both Covid and Non-Covid pictures of X-ray and CT-scans. We used 13816 images
for X-ray, consisting of 3616 Covid-19 and 10200 Non-Covid images. We also used 14500 images
for CT-scans, consisting of 7593 Covid-19 and 6893 Non-Covid images.For segmentation, we have
used 2 datasets.Both the datasets consists of CT-scans along with their infection masks. In the
first dataset, it consists of 1200 images with the infection mask. In the second dataset, it consists
of 1564 CT-scans along with their infection masks.

# Methodology 


