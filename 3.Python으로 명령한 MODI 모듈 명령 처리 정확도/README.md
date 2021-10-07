## 3. Python으로 명령한 MODI 모듈 명령 처리 정확도



### 1.1 시험 환경
    - 노트북과 MODI 모듈에 대한 USB 연결을 진행


### 1.2 시험 방법
    - 노트북에서 MODI를 제어하는 Python 모듈(Pymodi)을 import한 뒤 bundle initialize 진행
    - 측정 시료 5개(gyro 모듈, button 모듈, dial 모듈, ir 모듈, ultrasonic 모듈)에 Python을 통해 데이터를 10회 이상 송/수신 하는 코드를 실행
    - Python 코드대로 데이터 누락 없이 정확한 데이터를 송/수신 하는지 확인
    


### 1.3 확인 항목
    - Led 모듈: Python 코드로 명령한 색과 동일한 색으로 Led 모듈이 점등될 것
    - Button 모듈: Python 코드를 실행한 상태에서 버튼을 클릭할 때마다 노트북에 클릭됨을 알리는 메시지가 표시될 것
    - Dial 모듈: Python 코드를 실행한 상태에서 Dial을 좌, 우로 돌릴 때마다 해당하는 다이얼의 위치가 노트북에 'Low', 'High'로 표시될 것
    - Motor 모듈: Python 코드로 명령한 대로 모터가 움직이고 멈춤을 반복할 것
    - Display 모듈: Python 코드로 생성하여 노트북에 표시되는 숫자와 디스플레이 모듈에 표시되는 숫자가 동일하게 표시될 것



### 1.4 시험 결과
    - 측정 시료 5개(gyro 모듈, button 모듈, dial 모듈, ir 모듈, ultrasonic 모듈) 모두 10회 이상 데이터 송/수신 시 누락 및 잘못된 데이터 없음