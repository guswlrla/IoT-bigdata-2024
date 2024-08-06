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
    - [BeautifulSoup](https://github.com/guswlrla/IoT-bigdata-2024/blob/main/day02/bda04_beautifulsoup_basic.ipynb)
    - [Selenium](https://github.com/guswlrla/IoT-bigdata-2024/blob/main/day02/bda05_selenium_basic.ipynb)
- 빅데이터 실습
    - [스타벅스입지분석]()

## :white_check_mark: 3일차
### 1. 빅데이터 기초학습
- 스타벅스 입지분석 실습 계속
    - 지난주 최종으로 만든 데이터 csv파일 다시 로드
    - [스타벅스입지분석](https://github.com/guswlrla/IoT-bigdata-2024/blob/main/day03/bda07_starbucks_analysis.ipynb)

### 2. 빅데이터 활용방안
- 수집방법, 데이터전처리, 분석/시각화 알맞은 방법을 쓰는지 선별
- 단순 빅데이터 분석방법은 깃헙에서 참조만 해도 많은 것을 찾아볼 수 있음

### 3. 빅데이터 분석가의 작업순
- 수집, 저장 동시 - 크롤링, OpenAPI, DB, 엑셀 다운로드
- 데이터전처리(★) - 자동화 어려움, 분석 일정 50% 차지
- 분석을 통해 EDA/통계기반 분석, 머신러닝, 딥러닝 활용
- 시각화 - 경영진이 확인하고 비지니스, 결정에 도움을 줌

### 4. 일반적인 빅데이터 분석 예시
- 코로나 사태로 외국인 관광객수 변경 추세
- 인스타그램 크롤링으로 제주도 핫플레이스 시각화
- 스타벅스 입지분석
- 다나와 크롤링으로 인기있는 무선청소기 순위 분석

### 5. 머신러닝, 딥러닝이 들어가면 예측, 예상
- 이전에도 예측, 예상을 기존의 EDA 방식으로 사용했음
- 머신러닝, 딥러닝이 예측값의 정확도가 훨씬 높기에 사용

## :white_check_mark: 4일차
