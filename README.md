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
$\cdot$ Visual-Based Defect Detection and Classification Approaches for Industrial Applications-A SURVEY (2020) [[paper]](https://www.mdpi.com/1424-8220/20/5/1459)  
$\cdot$ Deep Industrial Image Anomaly Detection: A survey (2023) [[paper]](https://arxiv.org/abs/2301.11514)  


## Paper Review
### 1. Student-Teacher Architecture  

1. Uninformed students: Student-teacher anomaly detection with discriminative latent embeddings (2020)
[[paper]](https://arxiv.org/pdf/2011.11108)
[[summary]](https://sogsog.tistory.com/53)  

2. Multiresolution knowledge distillation for anomaly detection (2021)
[[paper]](https://arxiv.org/pdf/2011.11108)
[[summary]](https://sogsog.tistory.com/54)

3. Student-teacher feature pyramid matching for anomaly detection (2021) [[paper]](https://arxiv.org/pdf/2103.04257)
[[summary]](https://sogsog.tistory.com/55)  

4. Anomaly detection via reverse distillation from one-class embedding (2022)
[[paper]](https://arxiv.org/pdf/2201.10703)
[[summary]](https://sogsog.tistory.com/56)  


### 2. One-Class Classification  
$\cdot$ Support vector data description (2004)
[[paper]](https://link.springer.com/article/10.1023/B:MACH.0000008084.60811.49)
[[summary]](https://sogsog.tistory.com/57)  
$\cdot$ Deep nearest neighbor anomaly detection (2020)
[[paper]](https://arxiv.org/pdf/2002.10445)
[[summary]](https://sogsog.tistory.com/58)  
$\cdot$ Patch svdd: Patch-level svdd for anomaly detection and segmentation (2020)
[[paper]](https://arxiv.org/pdf/2006.16067)
[[summary]](https://sogsog.tistory.com/59)  
$\cdot$ Learning and evaluating representations for deep one-class classification (2020)  
$\cdot$ Explainable deep one-class classification (2020)  
$\cdot$ Attention guided anomaly localization in images (2020)  
$\cdot$ Panda: Adapting pretrained features for anomaly detection and segmentation (2021)  
$\cdot$ Cutpaste: Self-supervised learning for anomaly detection and localization (2021)  
$\cdot$ Contrastive Predictive Coding for Anomaly Detection (2021)  
$\cdot$ Mean-shifted contrastive loss for anomaly detection (2023)  


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
$\cdot$ Visual-Based Defect Detection and Classification Approaches for Industrial Applications-A SURVEY [[paper]](https://www.mdpi.com/1424-8220/20/5/1459)  
$\cdot$ Deep Industrial Image Anomaly Detection: A survey [[paper]](https://arxiv.org/abs/2301.11514)  


