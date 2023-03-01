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

| Datasets | Covid    | Non-Covid   |
| :---:    | :---:    | :---:       |
| CT-scans | 7593     | 6893        |
| X-Rays   | 3616     | 10200       |


| Datasets | Mask Images   | 
| :---:    | :---:         |
| I        | 1200          |
| II       | 1564          |

# Methodology 
![This is the methodology](/images/flow_chart_covid.jpg)

The overall methodology is given in Fig. 1. For classification and segmentation, we used two
different approaches. We employed an uncertainity aware transfer learning approach for classification. We utilized the U-net framework for segmentation.

# Classification 

To detect the presence of COVID-19, the suggested framework only relies on the information
content of X-rays and CT images. In this report, we evaluate two best pretrained networks on
the ImageNet data set and import and adjust them for COVID-19 identification. ResNet50 and
InceptionResNetV2 are the names of these networks.
![This is for classification](/images/transfer_learning_class.png)

# Segmentation

The general approach to semantically segmenting pictures is to develop a structure that collects
features through consecutive convolutions and outputs a segmentation map.
U-NET was created with the intention of comprehending and segmenting medical images. It
is a significant architecture in the medical imaging automation society and has a wide range of
applications in the sector. In this part, we go through the network’s core technological aspects and
how they contribute to successful outcomes.

![This is segmentation](/images/segmentation_covid.png)

# Results

I have done rigourous research on the results part, I have compared my model performance with the other state of the art models. My model outperformed all the models that I have considered on the above mentioned datasets. For more info on results, you can check the report included in the repo. 


