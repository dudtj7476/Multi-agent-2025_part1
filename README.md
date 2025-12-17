# Korea Intelligent Automotive Parts Promotion Institute(KIAPI) Data
## <img width="2953" height="367" alt="Image" src="https://github.com/user-attachments/assets/be3b3af9-a0d4-4bc8-a3f2-fd788cb608cb" />
This work was supported by Institute of Information &amp; communications Technology Planning &amp; Evaluation (IITP) grant funded by the Korea government (MSIT) (No.2021-0- 01415, Development of multi-agent simulation &amp; test scenario generation SW for edge connected autonomous driving service verification. 

## Autonomous Driving Data

### Download Autonomous Driving

#### Data : [Download](http://192.168.11.47:5000/sharing/5TLQ29XYu)     
          
※ **자율주행차량의 주행 데이터는 2025년 8월에 실제 차량을 통해 계측한 데이터임**  
※ 차량에 장착된 센서 RAW 데이터(카메라, 라이다) 및 라이다 기반 객체 인지정보를 포함하고 있음

### 1. 개요  
### Autonomous vehicle  
  * 차종(차명) : 승용(현대 IONIQ electric)  
  * Radar, Lidar 2대, GPS, Camera, OBU 장치가 장착되어 있음
  
    <img src="https://github.com/Yunhyeongseok-kiapi/KIAPI_dataset/assets/85465084/98408c85-9d99-46f7-8550-357abb3a0c7e" width="612" height="350"> 

### 데이터 수집 리스트
#### 1) Autonomous vehicle  
  * 주행 데이터는 Ubuntu(Linux)의 ROS 환경 기반의 bag 포맷으로 계측을 진행하였음
  * 센서 데이터 및 차량에서 계측된 주행 데이터의 목록은 다음과 같음
  * 수집 데이터의 구조는 ROS에서 제공되는 구조와 자체 정의한 custom_msgs로 구성되어 있음
  * custom_msgs의 상세 구조는 과제 관련 2차년도 KIAPI 기술문서(엣지 인프라 및 자율주행차량 데이터 융복합 InterFace 구성 방안 설계서)에 정의되어 있음

    <img width="612" height="682" alt="화면 캡처 2025-12-17 150617" src="https://github.com/user-attachments/assets/29e4ecd1-453d-486f-b8f0-9b55962caba5" />

### 2. 데이터 수집 환경   
* 2025년 8월에 실제 자율주행차량을 통해 계측한 데이터  
  * 약 140km 주행에 관한 데이터로 약 2.2TB
  * Linux(Ubuntu) ROS환경에서 제공되는 bag 포맷으로 저장
  * 대구 실증도로를 비롯한 주변 도로를 주행하면서 계측을 진행
    
* <주행 환경>

  <img width="612" height="682" alt="화면 캡처 2025-12-17 152236" src="https://github.com/user-attachments/assets/0068230b-b482-48a7-86aa-ace60137463e" />
