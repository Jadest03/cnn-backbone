# MobileNet_v1 Implementation
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Jadest03/cv-paper-study/blob/main/mobilenet_v1/MobileNet_v1_CIFAR.ipynb)

## 1. 개요 (Overview)
이 프로젝트는 **MobileNet_v1**논문을 읽고 PyTorch를 사용하여 **MobileNet** 모델을 구현하고, CIFAR-10 데이터셋으로 학습하였습니다.
공부 중 작성하여 틀린 부분이 있을 수 있습니다.

* **Title**: MobileNets: Efficient Convolutional Neural Networks for Mobile Vision Applications
* **Link**: [Original Paper](https://arxiv.org/pdf/1704.04861)
* **Blog Review**: [MobileNet 정리 블로그](https://velog.io/@jjadestarr/MobileNets-Efficient-Convolutional-Neural-Networks-for-Mobile-VisionApplications)

## 2. 구현 환경 (Environment)
* **OS**: macOS
* **Language**: Python 3.x
* **Framework**: PyTorch
* **Dataset**: CIFAR-10

## 3. 학습 결과 (Results)
100 Epoch 학습을 진행하였고 다음과 같은 성능을 달성하였습니다.

| Metric | Value |
| :--- | :--- |
| **Best Accuracy** | **91.27** |
| **Final Loss** | 0.0956 |
| **Epochs** | 100 |

## 4. 실행 방법 (Usage)
1. 상단의 `Open In Colab` 링크를 클릭합니다.
2. Google Drive를 마운트합니다.
3. `모두 실행`을 실행하여 학습을 시작하거나, 제공된 가중치 파일을 로드하여 테스트할 수 있습니다.