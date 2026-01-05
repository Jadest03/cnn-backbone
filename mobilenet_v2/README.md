# MobileNet_V2 구현
**바로 실행**: [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Jadest03/cv-paper-study/blob/main/mobilenet_v2/MobileNet_V2_CIFAR10.ipynb)

## 개요
* **제목**: MobileNetV2: Inverted Residuals and Linear Bottlenecks
* **원본 논문**: [Original Paper](https://arxiv.org/pdf/1801.04381)
* **블로그(직접 작성)**: [MobileNet_V2 논문 리뷰](https://velog.io/@jjadestarr/MobileNetV2-Inverted-Residuals-and-Linear-Bottlenecks)

## 구현 환경
* **OS**: macOS
* **Language**: Python 3.x
* **Framework**: PyTorch
* **Dataset**: CIFAR-10

## 학습 결과
| Metric | Value |
| :--- | :--- |
| **Best Accuracy** | **89.20** |
| **Final Loss** | 0.3551 |
| **Epochs** | 30 |

## 실행 방법
1. 상단의 `Open In Colab` 링크를 클릭합니다.
2. Google Drive를 마운트합니다.
3. `모두 실행`을 실행하여 학습을 시작하거나, 제공된 가중치 파일을 로드하여 테스트할 수 있습니다.