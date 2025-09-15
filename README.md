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
1. Support vector data description (2004)
[[paper]](https://link.springer.com/article/10.1023/B:MACH.0000008084.60811.49)
[[summary]](https://sogsog.tistory.com/57)  
2. Deep nearest neighbor anomaly detection (2020)
[[paper]](https://arxiv.org/pdf/2002.10445)
[[summary]](https://sogsog.tistory.com/58)  
3. Patch svdd: Patch-level svdd for anomaly detection and segmentation (2020)
[[paper]](https://arxiv.org/pdf/2006.16067)
[[summary]](https://sogsog.tistory.com/59)  
4. Learning and evaluating representations for deep one-class classification (2020)
[[paper]](https://arxiv.org/pdf/2011.02578)
[[summary]](https://sogsog.tistory.com/60)  
5. Explainable deep one-class classification (2020)
6. Attention guided anomaly localization in images (2020)
7. Panda: Adapting pretrained features for anomaly detection and segmentation (2021)
8. Cutpaste: Self-supervised learning for anomaly detection and localization (2021)


### 3. Distribution Map  
1. Variational Inference with Normalizing Flows (2015)
2. Modeling the distribution of normal data in pre-trained deep features for anomaly detection (2021)  
3. Same same but differnet: Semi-supervised defect detection with normalizing flows (2021)
4. Fully convolutional cross-scale-flows for image-based defect detection (2022)  

### 4. Memory Bank  
1. Sub-image anomaly detection with deep pyramid correspondences (2020)
2. Padim: a patch distribution modeling framework for anomaly detection and localization (2021)
3. Towards total recall in industrial anomaly detection (2022)


### 5. Autoencoder  
1. Iterative energy-based projection on a normal data manifold for anomaly localization (2019)
2. Encoding structure-texture relation with p-net for anomaly detection in retinal images (2020)
3. Towards visually explaining variational autoencoders (2020)
4. Improved anomaly detection by training an autoencoder with skip connections on images corrupted with stain-shaped noise (2021)
5. Divide-and-assemble: Learning block-wise memory for unsupervised anomaly detection (2021)
6. Draem-a discriminatively trained reconstruction embedding for surface anomaly detection (2021)
7. DSR–a dual subspace re-projection network for surface anomaly detection (2022)
8. Natural synthetic anomalies for self-supervised anomaly detection and localization (2022)
9. Self-supervised predictive convolutional attentive block for anomaly detection (2022)  


### 6. GAN
1. Learning semantic context from normal samples for unsupervised anomaly detection (2021)
2. Anoseg: Anomaly segmentation network using self-supervised learning (2021)
3. Omni-frequency channel-selection representations for unsupervised anomaly detection (2022)  


### 7. Transformer  
1. Vt-adl: A vision transformer network for image anomaly detection and localization (2021)  
2. Inpainting transformer for anomaly detection (2021)
3. A Unified Model for Multi-class Anomaly Detection (2022)
4. ADTR: Anomaly Detection Transformer with Feature Reconstruction (2022)  

### 8. Diffusion Model  
1. Anoddpm: Anomaly detection with denoising diffusion probabilistic models using simplex noise (2022)
2. Unsupervised visual defect detection with score-based generative model (2023)


### Supervised Learning

### Few-Shot Anomaly Detection  

### Noisy Anomaly Detection  

### 3D Anomaly Detection

### Anomaly Synthesis  

### Anomaly Detection with LLM and RAG

## Reference
$\cdot$ Visual-Based Defect Detection and Classification Approaches for Industrial Applications-A SURVEY [[paper]](https://www.mdpi.com/1424-8220/20/5/1459)  
$\cdot$ Deep Industrial Image Anomaly Detection: A survey [[paper]](https://arxiv.org/abs/2301.11514)  


