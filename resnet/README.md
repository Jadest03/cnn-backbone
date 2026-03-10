# ResNet 구현
**바로 실행**: [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Jadest03/cv-paper-study/blob/main/resnet/resnet.ipynb)

## 개요
* **제목**: Deep Residual Learning for Image Recognition (ResNet)
* **원본 논문**: [Original Paper](https://arxiv.org/abs/1512.03385)
* **블로그(직접 작성)**: [ResNet 논문 리뷰](https://velog.io/@jjadestarr/Deep-Residual-Learning-for-Image-RecognitionResNet)

## 구현 환경
* **OS**: macOS
* **Language**: Python 3.x
* **Framework**: PyTorch
* **Dataset**: CIFAR-10

## 모델 구조
논문에서 제안한 ResNet-18을 구현하였고 이미지 데이터 셋의 구조에 맞게 resize하여 학습을 진행했습니다.

## 학습 결과
| Metric | Value |
| :--- | :--- |
| **Best Accuracy** | **88.5%** |
| **Final Loss** | 0.34 |
| **Epochs** | 20 |

## 실행 방법
1. 상단의 `Open In Colab` 링크를 클릭합니다.
2. Google Drive를 마운트합니다.
3. `모두 실행`을 실행하여 학습을 시작하거나, 제공된 가중치 파일을 로드하여 테스트할 수 있습니다.