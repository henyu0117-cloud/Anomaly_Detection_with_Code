# 이상치 탐지 논문 요약 및 코드 실습 
딥러닝 기반 이상치 탐지에 관한 논문 요약 및 코드 실습을 다루고 있습니다.
오류가 있을 수 있으므로, 정확한 내용은 원본 논문과 공식 코드를 참고하시길 바랍니다.  
This repository contains paper summaries and code implementations on anomaly detection.  
Please note that some parts may contain errors. For accurate information, refer to the original papers and official implementations.  

  
## Anomaly Detection Texonomy    
* Classical Approach
  * 히스토그램을 이용한 결함 탐지
    * otsu 알고리즘
  * GLCM을 이용한 결함 탐지
  * Local Binary Pattern을 이용한 결함 탐지
  * 자기상관(Autocorrelation)을 이용한 결함 탐지
  * 구조 기반 결함 탐지
    * Canny 알고리즘을 이용한 엣지 추출
    * Morphology 연산
    * Zhang-Suen 알고리즘을 이용한 skeleton 추출
  * 필터 기반 결함 탐지
    * Sobel 필터, Laplacian 필터
    * 푸리에 변환 후 필터링을 통하 이상치 탐지
   
* Deep learning Approach
  * Unsupervised learning
    * Student-Teacher Architecture
    * One-Class Classification
    * Distribution Map
    * Memory Bank
    * Autoencoder
    * GAN
    * Transformer
    * Diffusion Model
  * Supervised learning
  * Few-shot anomaly detection
  * Noisy anomaly detection
  * 3D Anomaly Detection


## Survey papers  
$\cdot$ Visual-Based Defect Detection and Classification Approaches for Industrial Applications—A SURVEY [[paper]](https://www.mdpi.com/1424-8220/20/5/1459)  
$\cdot$ Deep Industrial Image Anomaly Detection: A survey [[paper]](https://arxiv.org/abs/2301.11514)  


## Paper Review
### Unsupervised learning
### 1. Student-Teacher Architecture  

1. Uninformed students: Student-teacher anomaly detection with discriminative latent embeddings
[[paper]](https://arxiv.org/pdf/2011.11108)
[[summary]](https://sogsog.tistory.com/53)
[[colab]](https://github.com/henyu0117-cloud/ADcode/blob/73c10ec7655f557f17329f655e292914acb30104/1%20Student-Teacher%20Architecture/Multiresolution%20Knowledge%20Distillation%20for%20Anomaly%20Detection.ipynb)  

2. Multiresolution knowledge distillation for anomaly detection 
[[paper]](https://arxiv.org/pdf/2011.11108)
[[summary]](https://sogsog.tistory.com/53)
[[code]](https://github.com/henyu0117-cloud/ADcode/blob/73c10ec7655f557f17329f655e292914acb30104/1%20Student-Teacher%20Architecture/Multiresolution%20Knowledge%20Distillation%20for%20Anomaly%20Detection.ipynb)  

4. Student-teacher feature pyramid matching for anomaly detection  

5. Anomaly detection via reverse distillation from one-class embedding  

### 2. One-Class Classification  
$\cdot$ Patch svdd: Patch-level svdd for anomaly detection and segmentation  
$\cdot$ Panda: Adapting pretrained features for anomaly detection and segmentation  
$\cdot$ Deep nearest neighbor anomaly detection  
$\cdot$ Learning and evaluating representations for deep one-class classification  
$\cdot$ Cutpaste: Self-supervised learning for anomaly detection and localization  
$\cdot$ Contrastive Predictive Coding for Anomaly Detection  
$\cdot$ Support vector data description  
$\cdot$ Explainable deep one-class classification  
$\cdot$ Mean-shifted contrastive loss for anomaly detection  
$\cdot$ Representation learning with contrastive predictive coding  
$\cdot$ Grad-CAM: Visual Explanations from Deep Networks via Gradient-Based Localization  
$\cdot$ Attention guided anomaly localization in images  
  
### 3. Distribution Map  

### 4. Memory Bank  

### 5. Autoencoder  

### 6. GAN

### 7. Transformer  

### 8. Diffusion Model  

### Supervised Learning

### Few-Shot Anomaly Detection  

### Noisy Anomaly Detection  

### 3D Anomaly Detection

### Anomaly Synthesis  

## Reference
$\cdot$ Visual-Based Defect Detection and Classification Approaches for Industrial Applications—A SURVEY [[paper]](https://www.mdpi.com/1424-8220/20/5/1459)  
$\cdot$ Deep Industrial Image Anomaly Detection: A survey [[paper]](https://arxiv.org/abs/2301.11514)  


