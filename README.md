# w13_autudrv-mldl


강사님 연구 약력

제어로직 심화 : ESC

알고리즘 관련된 과제,
교수님이 미래자동차공학과 소속, 로봇은 자동차쪽 


- 리서치 서머리
 1. 자율주행차량의 센서 데이터 처리 및 융합기술 
   - 주행 가능한 영역 확보
   - 센서 코디네이션 및 켈리브레이션
   - 맷랩 로스 많이 써서 
   - 스피드 커버쳐 곡률에 따른 속도 프로파일 - ROS 이용한 구현
   - 카메이커라는 차량용 툴, 카심 등등 툴 사용 - 실제 차량을 이용해 센서데이터를 취득할 수 없으므로 컴퓨터 환경에서 가상환경
   - 차량 동역학 수학 모델링이 들어가 있어요, 100%정확하지 않더라도 수학 모델링 되어있고
   - 제어 로직 설계되어있어 -> 하드웨어 리얼타임 보장된 하드웨어에 
   - 버드아이뷰 관점(위에서 보는 지도 관점)에서 차선 및 차량 정보 처리
   - 
  2. 강사님의 관심
   - 도시환경 및 주변환경 러버스트 한 토대에서 제어하는 연구 
   
- 자율주행 왜 해야되냐???
 1. 서해대교 29중 추돌사고 - 안전을 위해서
 2. 유다시티 - 구글차를 만드신분, 스텐포드 교수님 - 구글 웨이모, 판매용이 아닌 서비스 
 3. 앤드류 - 지금은 바이두 자율주행차, 원래 스텐포드 교수님 : 자율주행차 피로보틱스
 
- 로보틱스 리서치
 - 퍼셉션
 - 맵핑 : 인지를 위해서, 어디에 어떤 차량이 존재하며,HD맵  -> 고정밀 지도 ,GPS단위 정보로 지원 해줌
 - 로컬라이제이션 : 단순히 GPS 거리정보 오미터 이상임 - 오도메트리, 데드 레커닝 어느정보로 가고있는지, 항공에서 많이 쓰던 경로추정 괭장히 정밀한 gps정보가 보장된
   - 카메라 정보는 어떻게 로칼라이제이션?
   - 측위(로컬라이제이션) 제일 어려워 센서처리 센서융합 
 - 하이브리드 어프로치 : 엔드 투 엔드가 아닌 각각의 요소에서 필요한부분만 딥러닝, 딥러닝과 고전 룰베이스 코드와의 적절한 조합
 - 차량은 주로 인지 및 디텍션에 딥러닝을 쓰고, 하드웨어가 어렵기때문에 아직 연구만 하고 있어요
 - 
 ===============================================
-세부 기술별개발 전력
 - 강모델 필터 : 
 - 약모델 필터 : 
 - 측위 : 로컬라이제이션에 이용 단순히 GPS뿐 아니라 라이더 레이더 모든 센서를 통합.
 - 패스 플래닝 ,전역경로계획
 
 ======================================
 - 라이더 1체널 이용 검출 
  - 터틀봇3 만들어서 실내로봇에 센세이션을 일으키고 있음 모바일플랫폼은 실내로봇 터틀봇 대표적
  - 자율주행 택배  등등 사용 가능 (RBCAR 5천만원, 
  - 연구실 현대차에서 제공한 차량
  - 센서 
    - 모빌아이 : 이스라엘 교수님창업 만도에서 패키징해 내보냄 주변 차량정보, 4대 차량정보 나오고 차선정보, 도로 표지판 속도표지판 다 나옴
    - 리얼센스 : 뎁스카메라 IR 장착
    - 스테레오 카메라 : 
    - 레이더 : 델파이사의 ESR
    - 1 체널 라이더 
    - RP라이다 1체널 360도 검출
    - 중국의 RS-Lidar 16/32
    - 데이터 취득을 위해 벡터사의 제품 Data Acquisition & 
    - 차량은 기본적으로 CAN통신을 하는데, 이때 필요한 장비,
    - 제어기를 위해 필요한 ECU, ECU를 대체하는 장비라고 보시면 됩니다. 
  -인지의 3분류 "디텍션/분류/트랙킹"  
    - 카메라, 레이더, 라이다 카메라도 100%는 없어요 도로상에는 복잡한 장애물이 없지롱 레이더의 검출능력과 라이더의 검출능력을 융합해서 만들어야하는거쥬
    - 카메라에 분류와 트레킹 디텍션은 딥러닝 많이 쓰지~
    - 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
