## 5. MODI Python API 제공 개수



### 1.1 시험 환경
    - 노트북과 MODI 모듈에 대한 USB 연결을 진행


### 1.2 시험 방법
    - 노트북에서 MODI를 제어하는 Python 모듈(Pymodi)을 import한 뒤 bundle initialize 진행
    - 12개 모듈이 정상적으로 Initialize 되는지 확인
    - Setup 모듈 1종(Network 모듈)
    - Input 모듈 7종(Dial 모듈, Button 모듈, Environment 모듈, Gyro 모듈, Ir 모듈, Mic 모듈, Ultrasonic 모듈)
    - Output 모듈 4종(Display 모듈, Led 모듈, Speaker 모듈, Motor 모듈)
    - Pymodi Github(https://github.com/LUXROBO/pymodi/tree/feature/add-py39-support/modi/module) 내 12종의 모듈 제어를 위한 API 존재 여부 확인
    


### 1.3 확인 항목
    - 12종의 MODI 모듈 제어를 위한 Python API가 제공될 것



### 1.4 시험 결과
    - 12종의 MODI 모듈 제어를 위한 Python API 확인