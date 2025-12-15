# DenseNet 구현
**바로 실행**: [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Jadest03/cv-paper-study/blob/main/densenet/DenseNet_121_CIFAR.ipynb)

## 개요
* **제목**: Densely Connected Convolutional Networks(DenseNet)
* **원본 논문**: [Original Paper](https://arxiv.org/pdf/1608.06993v5)
* **블로그(직접 작성)**: [DenseNet 논문 리뷰](https://velog.io/@jjadestarr/Densely-Connected-Convolutional-NetworksDenseNet)

## 구현 환경
* **OS**: macOS
* **Language**: Python 3.x
* **Framework**: PyTorch
* **Dataset**: CIFAR-10

## 학습 결과
| Metric | Value |
| :--- | :--- |
| **Best Accuracy** | **89.88%** |
| **Final Loss** | 0.16 |
| **Epochs** | 20 |

## 실행 방법
1. 상단의 `Open In Colab` 링크를 클릭합니다.
2. Google Drive를 마운트합니다.
3. `모두 실행`을 실행하여 학습을 시작하거나, 제공된 가중치 파일을 로드하여 테스트할 수 있습니다.