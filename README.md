# 2023년도 2학기 무인이동체 융합프로젝트B (PBL) 
- 2023-2학기 세종대학교 일반대학원 ICT혁신인재양성사업 교과목
  - 세부프로젝트1: 적응적 예측을 통한 실시간 영상 압축 (이진영)
  - 세부프로젝트2: 환경 강인한 영상 기반 댑스 추정 (최유경)**
  - 세부프로젝트2: 인공지능 기반 날씨 예보 데이터 생산 (김세원)
  
## 수업정보
- 수업방식: 하이브리드 강의 

## 시험정보
- 중간고사: Take-home Exam 
- 기말고사: Take-home Exam

## 강의계획서
- 수업내용: 세부프로젝트2 - 환경 강인한 영상 기반 댑스 추정
- 수업시간: 화(19:00-21:30)
- 수업주차: 4주차, 5주차, 6주차, 7주차, 9주차
- 담당교수
  - 최유경(ykchoi@sejong.ac.kr)
- 담당조교(TA)
  - 이승현 (총괄), 김태주, 신정민, 홍주영

| 주차 | 수업내용 | 강의노트 | 코드 | 수업일 | 참고자료 | 과제 | 비고 | 
|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|
| 4 | 프로젝트 소개 | | | 2023.09.26 | [담당조교](https://github.com/sejongresearch/2023.Mobility.PBL.B/blob/main/Mentor.md) | | 오프라인 |
| 4 | 컴퓨터비전 <br> 입문 | [PDF](https://github.com/sejongresearch/2023.Mobility.PBL.B/blob/main/LectureNotes/%5B1%E1%84%8C%E1%85%A1%E1%86%BC%5D%20%E1%84%8F%E1%85%A5%E1%86%B7%E1%84%91%E1%85%B2%E1%84%90%E1%85%A5%E1%84%87%E1%85%B5%E1%84%8C%E1%85%A5%E1%86%AB%20%E1%84%8B%E1%85%B5%E1%86%B8%E1%84%86%E1%85%AE%E1%86%AB%20(2023).pdf) | | 2023.09.26 |  [이론영상](https://youtu.be/y_7ROFzkS7E) | | |
| 4 | 딥러닝과 <br> 신경망 | [PDF](https://github.com/sejongresearch/2023.Mobility.PBL.B/blob/main/LectureNotes/%5B2%E1%84%8C%E1%85%A1%E1%86%BC%5D%20%E1%84%83%E1%85%B5%E1%86%B8%E1%84%85%E1%85%A5%E1%84%82%E1%85%B5%E1%86%BC%E1%84%80%E1%85%AA%20%E1%84%89%E1%85%B5%E1%86%AB%E1%84%80%E1%85%A7%E1%86%BC%E1%84%86%E1%85%A1%E1%86%BC%20(2023).pdf) | | 2023.09.26 |  [이론영상](https://youtu.be/-CDG4fIJfe0) | | |
| 5 | 합성곱신경망 | [PDF](https://github.com/sejongresearch/2023.Mobility.PBL.B/blob/main/LectureNotes/%5B3%E1%84%8C%E1%85%A1%E1%86%BC%5D%20%E1%84%92%E1%85%A1%E1%86%B8%E1%84%89%E1%85%A5%E1%86%BC%E1%84%80%E1%85%A9%E1%86%B8%E1%84%89%E1%85%B5%E1%86%AB%E1%84%80%E1%85%A7%E1%86%BC%E1%84%86%E1%85%A1%E1%86%BC%20(2023).pdf) | MNIST([Keras](https://www.kaggle.com/code/yukyungchoi/2022-dl-w3p1/notebook), [Pytorch](https://www.kaggle.com/code/dobarri/03-mnist-cnn)) <br/> CIFAR10([Keras-CPU](https://www.kaggle.com/code/yukyungchoi/2022-dl-w3-project-cpu/notebook), [Keras-GPU](https://www.kaggle.com/code/yukyungchoi/2022-dl-w3-project-gpu/notebook),[Pytorch](https://www.kaggle.com/code/leeseunghyeon99/2023-1-dls-w3-cifar10-cnn)) | 2023.10.03 |  [이론영상](https://youtu.be/NmUknzJqYG4) <br/> 실습영상: <br> [MNIST(Pytorch)](https://youtu.be/Rr48AuqCdGE) <br/> [CIFAR10(Pytorch)](https://www.youtube.com/watch?v=nV5cU9IBG00)| | 오프라인 <br> 실습가능 |
| 5 | 딥러닝프로젝트와 <br> 하이퍼파라미터 | [PDF](https://github.com/sejongresearch/2023.Mobility.PBL.B/blob/main/LectureNotes/%5B4%E1%84%8C%E1%85%A1%E1%86%BC%5D%20%E1%84%83%E1%85%B5%E1%86%B8%E1%84%85%E1%85%A5%E1%84%82%E1%85%B5%E1%86%BC%E1%84%91%E1%85%B3%E1%84%85%E1%85%A9%E1%84%8C%E1%85%A6%E1%86%A8%E1%84%90%E1%85%B3%E1%84%8B%E1%85%AA%20%E1%84%92%E1%85%A1%E1%84%8B%E1%85%B5%E1%84%91%E1%85%A5%E1%84%91%E1%85%A1%E1%84%85%E1%85%A1%E1%84%86%E1%85%B5%E1%84%90%E1%85%A5%E1%84%90%E1%85%B2%E1%84%82%E1%85%B5%E1%86%BC%20(2023).pdf) |  합성데이터([Keras](https://www.kaggle.com/code/yukyungchoi/2022-dl-w4p1/notebook)) <br/> CIFAR10([Keras](https://www.kaggle.com/code/leeseunghyeon99/4-10-19011804-v3/notebook), [Pytorch](https://colab.research.google.com/drive/1W9gYZTByAP39BiDhrfRk76N6iMBgvres)) |  2023.10.03 | [이론영상](https://youtu.be/72IQrg8RgIo) <br> 실습영상 <br> [CIFAR10(Pytorch)](https://youtu.be/L6F3kWGZkfo)| [리더보드](https://www.kaggle.com/t/9a33a744a2594bcd84a0bc5b5c01b934) | 오프라인 <br> 실습가능 |
| 6 |  고급 <br> 합성곱신경망 | [PDF](https://github.com/sejongresearch/2023.Mobility.PBL.B/blob/main/LectureNotes/%5B5%E1%84%8C%E1%85%A1%E1%86%BC%5D%20%E1%84%80%E1%85%A9%E1%84%80%E1%85%B3%E1%86%B8%20%E1%84%92%E1%85%A1%E1%86%B8%E1%84%89%E1%85%A5%E1%86%BC%E1%84%80%E1%85%A9%E1%86%B8%E1%84%89%E1%85%B5%E1%86%AB%E1%84%80%E1%85%A7%E1%86%BC%E1%84%86%E1%85%A1%E1%86%BC%20(2023).pdf) | LeNet ([Keras](https://colab.research.google.com/drive/1W0ZAJ0WvSgD1Izw6EOA48LJ145Uon5Qj),  [Pytorch](https://www.kaggle.com/code/dobarri/7-lenet-implementation/notebook))<br/>AlexNet ([Keras](https://colab.research.google.com/drive/1rRo6OPn0jKXaqPV-5wRdk7V9k50f7Vf3), [Pytorch](https://www.kaggle.com/code/xown3197/alexnet-implementation-in-pytorch))<br/>VGGNet ([Keras](https://colab.research.google.com/drive/1DNJbNkn6s1-RZJNfv_RNTkyvmdzVtzYu), [Pytorch](https://www.kaggle.com/code/dobarri/9-vgg-pytorch/notebook)) <br/>GoogLeNet ([Keras](https://colab.research.google.com/drive/1Az7rIE9u6cNmvBjmbAcyVHtpbYZ1gpMu), [Pytorch](https://www.kaggle.com/code/leeseunghyeon99/2023-1-dls-w5-inception-googlenet-pytorch/notebook))<br/>ResNet ([Keras](https://colab.research.google.com/drive/1kdY1xymHt64R1hsklEjVc18CGVztqAwq), [Pytorch](https://www.kaggle.com/code/dobarri/12-resnet50-implementation-pytorch)) <br/> Pretrained_model ([Keras](https://colab.research.google.com/drive/16uqFF3-fXmbGIGhtt-NyqHdlGsSFCHhw), [Pytorch](https://www.kaggle.com/code/leeseunghyeon99/2023-1-dls-pretrained-resnet50-pytorch/notebook)) | 2023.10.10 | [이론영상](https://youtu.be/aCq10cpP3-4?list=PL1xKqHsVFgvl0mdO_n_Ppx3w_doigvwdd) <br/>   실습영상: <br>[LeNet(Pytorch)](https://youtu.be/0qZl6Sl4jVE) <br/> [AlexNet(Pytorch)](https://youtu.be/p8sCbxb2PMk) <br/>[VGGNet(Pytorch)](https://youtu.be/iomsSc6G35I) <br/>[GoogLeNet(Pytorch)](https://youtu.be/NtJun16913s) <br/>[ResNet(Pytorch)](https://youtu.be/ZfaQVvz-47w) <br/>[Pretrained_model(Pytorch)](https://youtu.be/AIygsdRy5i4)| | 오프라인 <br> 실습가능 |
| 6 | 전이학습 | [PDF](https://github.com/sejongresearch/2023.Mobility.PBL.B/blob/main/LectureNotes/%5B6%E1%84%8C%E1%85%A1%E1%86%BC%5D%20%E1%84%8C%E1%85%A5%E1%86%AB%E1%84%8B%E1%85%B5%E1%84%92%E1%85%A1%E1%86%A8%E1%84%89%E1%85%B3%E1%86%B8%20(2023).pdf) | 개고양이분류 ([Keras](https://www.kaggle.com/code/leeseunghyeon99/2023-1-dls-w6p1-dog-cat-keras), [Pytorch](https://www.kaggle.com/code/leeseunghyeon99/2023-1-dls-w6p1-dog-cat-pytorch)) <br/> 수화분류 ([Keras](https://www.kaggle.com/code/leeseunghyeon99/2023-1-dls-w6p2-keras), [Pytorch](https://www.kaggle.com/code/leeseunghyeon99/2023-1-dls-w6p2-pytorch))| 2023.10.10 |  [이론영상](https://youtu.be/bsraGcxKV88?list=PL1xKqHsVFgvl0mdO_n_Ppx3w_doigvwdd) <br>  실습영상: <br> [개고양이분류(Pytorch)](https://youtu.be/hcoDF-ztOrI) <br> [수화이미지분류(Pytorch)](https://youtu.be/d17A7h_dZR0) | [리더보드(1)](https://www.kaggle.com/t/effaffb18ada4a7dbce060c9cfbe06e2) <br/> [리더보드(2)](https://www.kaggle.com/t/c387f95465aa4da38c6ef686888f6d47) | 오프라인 <br> 실습가능 |
| 7 | 사물 탐지 | [PDF](https://github.com/sejongresearch/2023.Mobility.PBL.B/blob/main/LectureNotes/%5B7%E1%84%8C%E1%85%A1%E1%86%BC%5D%20%E1%84%89%E1%85%A1%E1%84%86%E1%85%AE%E1%86%AF%20%E1%84%90%E1%85%A1%E1%86%B7%E1%84%8C%E1%85%B5%20(2023).pdf) |  | 2023.10.17 | [영상](https://youtu.be/PH-4pg_z5uc?list=PL1xKqHsVFgvl0mdO_n_Ppx3w_doigvwdd) | [리더보드](https://www.kaggle.com/t/7fae31be19f5429f89a168f6a2ecc84c)|  오프라인 <br> 실습가능  |
| 8 | 중간 고사 | |   | 2023.10.24 |  | |   |
| 9 | 사물 탐지 <br> 보강 |  | | 2023.10.31 | | | 오프라인 |
