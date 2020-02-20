# Digital Health Hackathon 2019

### 2019. 09. 21 (Sat) Team Building Day
18:30-19:00 참가자 등록  
19:00-20:00 오리엔테이션  
20:00-22:00 팀 빌딩 행사  
  
### 2019. 10. 12 (Sat) Hackathon Day 1
18:00-18:30 참가팀 등록  
18:30-19:00 개회  
19:00-19:30 팀별 개발 환경 세팅  
19:30 팀별 활동 시작  
20:00-22:00 멘토링 세션  
22:00-23:00 야식 제공 이벤트  
23:00- 팀별 활동  
  
### 2019. 10. 13 (Sun) Hackathon Day 2
08:00-09:00 아침 식사  
9:00-12:00 팀 부스 설치  
12:00-13:00 점심 식사  
13:00-14:00 팀 별 데모 행사  
14:00-17:00 최종 발표  
17:00-18:00 시상 및 폐회  

### Classify Model 

증상분류 모델은 base model은 xgboost 모델을 사용하였으며 
Bayesian optimization을 통해 optimize 된 모델을 찾은 뒤 다른 모델과 앙상블을 하여 최종 모델을 선정했습니다.
주요 모델의 Accuracy는 다음과 같습니다.

Model                                    | Accuracy        |
---------------------------------------- | :-------------: | 
xgboost                                  | 81.2            | 
xgboost using Bayesian optimize          | 89.2            | 
optimize xgboost and ensemble            | 92.4            | 
