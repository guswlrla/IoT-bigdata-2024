# IoT-bigdata-2024
:page_with_curl:IoT 개발자과정 빅데이터분석 및 인공지능 학습 리포지토리:book:

## :white_check_mark: 1일차
### 1. 빅데이터 분석 및 AI
- 빅데이터를 사용하여 사회전반적인 문제, 현상, 원인, 해결점 등을 찾아가는 분석방법
- 사회전반에 모든 곳에서 사용
    - ex. 쿠팡 20대 중반 여성이 선호하는(트랜드) 화장품
        - 쿠팡 20대 중반 여성 - 회원정보를 검색
        - 회원들이 검색한 내용중 화장품을 조회
        - 그 중에서 가장 많이 검색된 화장품 통계
        - 20대 중반 여성 회원이 로그인
        - 첫화면에 검색된 화장품 1~3위를 디스플레이

### 2. 빅데이터?
- 빅데이터(Big Data) : 디지털환경에서 발생하는 대규모 정형 또는 비정형데이터
- 3V - Volume(크기, 규모), Variety(다양성), Velocity(속도)
- 5V - 3V + Veracity(진실성), Value(가치)
- 7V - 5V + Validity(정확성), Volatility(휘발성 : 데이터가 얼마나 오래 저장, 사용되는가)

### 3.  데이터?
- 정보를 수집자료 자체, 값, 총계 + 가치(Value) = 정보(Information)

### 4. 빅데이터 분석 순서 
- 생성 -> 수집 -> 저장 -> 분석 -> 표현
    - 생성 : IoT 센싱값, (쇼핑몰, 포털) 빅데이터 플랫폼을 통해서 생성
    - 수집 : MQTT로 DB에 저장, 빅데이터 플랫폼(하둡, 카프파...)에서 수집, 네트워크까지 포함
    - 저장 : 수집과 거의 동일, DB에 저장 (카프카, 데이터마이닝, NoSQL)
    - 분석 : 통계적 분석, 탐색적 분석(EDA), 머신러닝, 딥러닝, 자연어처리, 이미지프로세싱, 분석툴(Spark, Tableau, MS PowerBI) 사용
    - 표현 : 인사이트 도출(시각화, 그리드)

### 5. 데이터 분석 기초
- 파이썬 : 외 R, 자바, C# 등 다른 언어로도 분석가능. 단, 파이썬이 가장 쉽기에 많이 사용
- 데이터분석에 들어가는 라이브러리(모듈)부터 학습
    - 데이터처리 - Numpy(수치해석, 계산), Pandas(데이터처리), Scipy(과학계산) ...
    - 시각화 - Folium(지도), Matplotlib(차트), Seaborn(Matplotlib 고급화) ...
    - 엑셀 - openpyxl(엑셀 처리)
    - 크롤링 - Selenium(웹크롤링 자동화), BeautifulSoup(웹페이지 정제)
    - 머신러닝/딥러닝 - Scikit-Learn(가장 간단한 머신러닝), MS CNTK, Theano, Keras(최고의 딥러닝), TensorFlow(제일 유명, Keras포함), PyTorch(페이스북)

### 6. 빅데이터 학습
- 실습자료, 파이썬 기본(패스), 빅데이터 분석 기초학습 
    - [numpy](https://github.com/guswlrla/IoT-bigdata-2024/blob/main/day01/bda01_numpy_basic.ipynb)
    - [pandas](https://github.com/guswlrla/IoT-bigdata-2024/blob/main/day01/bda02_pandas_basic.ipynb)
    - [matplotlib](https://github.com/guswlrla/IoT-bigdata-2024/blob/main/day01/bda03_matplotlib_basic.ipynb)

## :white_check_mark: 2일차
### 1. 빅데이터 기초학습 
- 크롤링 관련
- 셀레니움 + 뷰티풀수프 같이 진행
    - [BeautifulSoup]()
    - [Selenium]()
- 빅데이터 실습
    - [스타벅스입지분석]()