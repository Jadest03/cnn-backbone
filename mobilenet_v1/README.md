# MobileNet_v1 구현
**바로 실행**: [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Jadest03/cv-paper-study/blob/main/mobilenet_v1/MobileNet_v1_CIFAR.ipynb)

## 개요
* **제목**: MobileNets: Efficient Convolutional Neural Networks for Mobile Vision Applications
* **원본 논문**: [Original Paper](https://arxiv.org/pdf/1704.04861)
* **블로그(직접 작성)**: [MobileNet_v1 논문 리뷰](https://velog.io/@jjadestarr/MobileNets-Efficient-Convolutional-Neural-Networks-for-Mobile-VisionApplications)

## 구현 환경
* **OS**: macOS
* **Language**: Python 3.x
* **Framework**: PyTorch
* **Dataset**: CIFAR-10

## 모델 구조
MobileNet v1 모델은 비교적 가볍기 때문에 논문에서 제시한 Architecture을 그대로 따랐습니다.  
단, CIFAR-10 Dataset을 사용하여 초기에 이미지를 Resize하였습니다.  

## 학습 결과
| Metric | Value |
| :--- | :--- |
| **Best Accuracy** | **91.27** |
| **Final Loss** | 0.0956 |
| **Epochs** | 100 |

## 실행 방법
1. 상단의 `Open In Colab` 링크를 클릭합니다.
2. Google Drive를 마운트합니다.
3. `모두 실행`을 실행하여 학습을 시작하거나, 제공된 가중치 파일을 로드하여 테스트할 수 있습니다.