## 2. Python으로 조작한 MODI 모듈의 응답 속도



### 1.1 시험 환경
    - 노트북과 MODI 모듈에 대한 USB 연결을 진행


### 1.2 시험 방법
    - 노트북에서 MODI를 제어하는 Python 모듈(Pymodi)을 import한 뒤 bundle initialize 진행
    - 측정 시료 5개(gyro 모듈, button 모듈, dial 모듈, ir 모듈, ultrasonic 모듈)에서 데이터를 1개씩 받아오는 코드를 실행
    - 데이터를 받아오는 속도를 측정
    


### 1.3 확인 항목
    - Python을 통해 제어를 진행한 시료(MODI 모듈)의 응답 속도가 10ms 이하일 것.



### 1.4 시험 결과
    - 측정 시료 5개(gyro 모듈, button 모듈, dial 모듈, ir 모듈, ultrasonic 모듈) 모두 응답속도 10ms 미만