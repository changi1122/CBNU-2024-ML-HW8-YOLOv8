# 24-1 기계학습 YOLOv8 실습

## 개요
3개의 클래스에 대해서 100장 이상의 사진을 모으고, 이를 YOLOv8 모델에 학습 시켜 동영상에서 객체를 추적하는 실습을 하였습니다. 추적할 객체로 까치와 비둘기, 표지판으로 정해 교내에서 직접 사진을 찍고, 라벨링 후 YOLO 모델에 학습시켰습니다. 다음으로 촬영한 동영상에서 객체를 추적한 뒤 plot하여 동영상으로 출력해보았습니다.

주피터노트북 : [https://github.com/changi1122/CBNU-2024-ML-HW8-YOLOv8/blob/master/yolo%20tracking.ipynb](https://github.com/changi1122/CBNU-2024-ML-HW8-YOLOv8/blob/master/yolo%20tracking.ipynb)

추적 결과 영상 : [https://github.com/changi1122/CBNU-2024-ML-HW8-YOLOv8/tree/master/videos_tracking](https://github.com/changi1122/CBNU-2024-ML-HW8-YOLOv8/tree/master/videos_tracking)

## 데이터 수집
### 추적할 객체 설정
| 까치  | 비둘기 | 주차금지 표지판 |
| --- | --- | -------- |
| <img src="https://github.com/changi1122/CBNU-2024-ML-HW8-YOLOv8/blob/master/images/image01.png"> |   <img src="https://github.com/changi1122/CBNU-2024-ML-HW8-YOLOv8/blob/master/images/image02.png">  |      <img src="https://github.com/changi1122/CBNU-2024-ML-HW8-YOLOv8/blob/master/images/image03.png">    |



### 데이터 수집 및 라벨링
<img src="https://github.com/changi1122/CBNU-2024-ML-HW8-YOLOv8/blob/master/images/image04.png">
<img src="https://github.com/changi1122/CBNU-2024-ML-HW8-YOLOv8/blob/master/images/image05.png">
<img src="https://github.com/changi1122/CBNU-2024-ML-HW8-YOLOv8/blob/master/images/image07.png">



## 추적 결과
<img src="https://github.com/changi1122/CBNU-2024-ML-HW8-YOLOv8/blob/master/images/image08.png">
<img src="https://github.com/changi1122/CBNU-2024-ML-HW8-YOLOv8/blob/master/images/image09.png">
<img src="https://github.com/changi1122/CBNU-2024-ML-HW8-YOLOv8/blob/master/images/image10.png">
<img src="https://github.com/changi1122/CBNU-2024-ML-HW8-YOLOv8/blob/master/images/image11.png">
