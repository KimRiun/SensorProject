# SensorProject

![image](https://user-images.githubusercontent.com/56223389/110943909-187f1900-837f-11eb-8981-6fdbe22c6ad7.png)

### 무인 온도 측정 및 명부 작성 프로젝트
프로젝트 제작 동기: 코로나19로 인해 강의실에서 매번 수기로 작성하는 명부와 체온측정을 온라인으로 작성 및 관리하고자 함
필요한 장비: 아두이노, 라즈베리 파이, 적외선 온도 센서, 3색 LED, LCD, 부저
개발 언어: Python3, C 언어

### 작동 과정
1. 라즈베리파이의 터미널 창에 학번과 이름을 입력한다.
2. 아두이노에 장착된 적외선 온도 센서에 손목을 가까이 가져다댄다.
3. 아두이노에 연결된 3색 led에서 체온 범위에 따라 색이 빛난다.(고온-빨강, 정상-초록, 미열-노랑) 
4. 아두이노가 측정한 온도 정보를 라즈베리파이로 보낸다(아두이노와 라즈베리파이는 USB 케이블로 연결됨)
5. 라즈베리 파이에 장착된 LCD에서 체온, 정상여부를 띄운다.
6. 고열인 경우 라즈베리 파이에 장착된 부저(소리 출력 장치)에서 간단한 멜로디를 출력한다.
7. 라즈베리 파이의 터미널 창에 사용자 학번, 이름, 체온을 띄운다.
8. 사용자 학번, 이름, 체온을 .txt 파일에 저장한다.
