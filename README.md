# PupilTracker-OpenCV-
### 뇌졸중 , 안구진탕증을 진단하기위한 적외선 pupil tracking

### ▼하드웨어 장비
<img src ="https://user-images.githubusercontent.com/25413894/111255497-874bc300-865a-11eb-8967-b252a43c5f8c.jpg" width="200">
라즈베리파이3 , ELP-USB100W05MT-KRL36적외선카메라 2대

### ▼이미지 전처리 과정

<img src ="https://user-images.githubusercontent.com/25413894/111254953-7ea6bd00-8659-11eb-9299-be0fd3b935c0.png" width="200">


### ▼Gray Scake 적용 , GaussiarBlur 필터 적용 , 적응형 이진화 적용(Adaptive Binarization)
<img src ="https://user-images.githubusercontent.com/25413894/111254964-81a1ad80-8659-11eb-9f6e-0a7063e8b60d.png">

### ▼이진화를 통해 동공만 추출
<img src ="https://user-images.githubusercontent.com/25413894/111254965-81a1ad80-8659-11eb-9a9a-455c7c3cc4b8.png">

### ▼동공을 Contour 
<img src ="https://user-images.githubusercontent.com/25413894/111254966-823a4400-8659-11eb-8add-86c894be9b9d.png">


