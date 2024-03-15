## 2일차 학습
- 빅데이터 학습

### 빅데이터 학습

#### 데이터 분석 기초 (계속)

##### pandas 학습 (계속)

1. Pandas 내용 통합(merge, concat)
  
    ![내용통합](https://raw.githubusercontent.com/simwh123/bigdata-analysis-2024/main/images/ba002.png)
2. pivot 테이블 
 
    ![피벗테이블](https://raw.githubusercontent.com/simwh123/bigdata-analysis-2024/main/images/ba003.png)

#### Pandas 2.0 이상 문제확인
- 두 데이터를 합치기위한 append() 함수가 없어짐
  - https://pandas.pydata.org/docs/whatsnew/v2.0.0.html
- pd.concat() 함수로 대체
 
    ![pd.concat](https://raw.githubusercontent.com/simwh123/bigdata-analysis-2024/main/images/ba004.png)

#### NumPy 학습
NumPy는 행렬처리 수치 계산을 손쉽게 할 수 있도록 도와주는 계산관련 라이브러리
SCipy는 과학쪽에 특화된 계산관련 라이브러리
- DF에서 수치적으로 처리할 게 있으면 numpy로 변경한 다음, 계산 처리한 뒤 다시 DF로 변경

### Matplotlib / Seaborn
Matplotlib, Seaborn은 데이터 시각화 라이브러리
Matplotlib 기본, Searborn은 Matlotlib 확장버전

#### ChromDriver
- 웹브라우저 제어 라이브러리
- 크롬드라이버 필수
    1. [현재 크롬 버전 확인](chrome://settings/help)
    2. [다운로드](https://googlechromelabs.github.io/chrome-for-testing/)
    3. 시스템 속성 > 환경변수 경로 등록
    4. 셀리니움 연동


