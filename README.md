# Bigcontest2019
[오전반_3조 최종.pdf](https://github.com/schw240/Bigcontest2019/files/4957702/_3.pdf)
# 사용자, 카드사에게 최적의 헤택을 제공하는 카드 "FLOW"제시

> 빅콘테스트 ASAP 팀 : 팀장: 임시은, 팀원: 김한주(본인), 김선우, 박지우

<hr/>

### 1. 프로젝트 개요
![이노베이션](https://user-images.githubusercontent.com/54871612/102210768-f871c200-3f15-11eb-93e4-503444494a58.png)


### 2. 프로젝트 환경
* Colab
* Jupyter Notebook
* 구글드라이브를 활용해 모든 데이터셋, 코드 , 그래프를 통합관리

### 3. 기능구현
<hr/>
#### 1) 데이터 EDA

![15](https://user-images.githubusercontent.com/54871612/102211886-a2058300-3f17-11eb-953d-030368a0b549.png)
* 데이터 분석

![14](https://user-images.githubusercontent.com/54871612/102211885-a2058300-3f17-11eb-859d-77f4c0570a18.png)
* 데이터 별 공통 데이터를 찾아 기준으로 삼고 통합, 숫자형이 아닌 데이터들 숫자로 인코딩

![13](https://user-images.githubusercontent.com/54871612/102211881-a16cec80-3f17-11eb-9159-83cac2dc4859.png)
* 결측치 처리, 이상치는 Isolation Forest 알고리즘 사용하여 제거

![12](https://user-images.githubusercontent.com/54871612/102211880-a16cec80-3f17-11eb-8b09-690b512babdb.png)
* 데이터를 지역, 날짜 기준으로 통합

![11](https://user-images.githubusercontent.com/54871612/102211879-a0d45600-3f17-11eb-841d-9faa1a076888.png)
* 전처리 및 시각화

![6](https://user-images.githubusercontent.com/54871612/102212722-fbba7d00-3f18-11eb-9225-f650c978fab5.png)


#### 2) 분석한 데이터를 통해 비즈니스 아이디어인 "FLOW" 제시
* 기존 카드상품에는 미세먼지에 특화된 상품이 없었기에 AI 기반 최적의 혜택을 주는 카드 [FLOW]
![FLOW](https://user-images.githubusercontent.com/54871612/102212501-aed6a680-3f18-11eb-967d-76e625748714.png)

#### 3) 서비스 아키텍쳐 및 기술
![9](https://user-images.githubusercontent.com/54871612/102212577-cb72de80-3f18-11eb-8f35-d9e397e12a93.png)
* 각 데이터별로 예측을 통해서 최종적으로 유동인구를 예측하고 업종별 매출 증감률을 예측

![5](https://user-images.githubusercontent.com/54871612/102212795-1ab90f00-3f19-11eb-810a-f9a8c610e9d3.png)
* Word2vec를 이용하여 미세먼지 관련 키워드 분석

![4](https://user-images.githubusercontent.com/54871612/102212788-17be1e80-3f19-11eb-9657-e0bbb96a881c.png)
* SNS 데이터 Konlpy를 활용해 형태소 분석을 통해 미세먼지의 변화에 따른 단어 빈도수 체크

![3](https://user-images.githubusercontent.com/54871612/102212785-168cf180-3f19-11eb-9e42-f56156d2b2ec.png)
* Linear Regression, Decision Tree, Random Forest 활용하여 모델 예측

![2](https://user-images.githubusercontent.com/54871612/102212799-1bea3c00-3f19-11eb-9b9f-215c17d4d88a.png)
* 최종 결과

<hr/>
git을 활용한 프로젝트 관리 (git 에 push 할 때 주의할 점)​
✔️ git bash 접속해서 git pull을 먼저하기

✔️ master 권한으로 올리지 않기 → branch 생성해서 push 하기

✔️ branch 이름은 자신이 맡은 역할을 나타낼 수 있도록 만듦

오늘 calendar 작업을 했으면, branch 이름은 calendar

commit message에 날짜와 함께 작업 내용 상세하게 기록해주세요 😄

git branch 브랜치명 → branch 생성
git branch → 현재 접속 된 branch 확인
git checkout 브랜치명 → 해당하는 branch로 접속

git push origin 브랜치명
→ 접속된 `branch`로 push 하는 법 (저장소 이름인 'origin' 뒤에 branch 이름 써서 push 하기)
