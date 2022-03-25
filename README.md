**The python code can't be uploaded because of data authority issue**

# 2020 Seoul Big Data Campus Contest
- Period for the preliminary : 2020.09.20 ~ 10.14
- Mentoring period for qualifying candidates: 2020.10.30
- Period for the finals: 2020.10.23 ~ 2020.11.16

## Why did we analyze the data?
- There are many complaints from Seoul citizens that there is no personal mobility parking lot.
  - (ref: Seoul City Hall Complaint Website)
- In 2020 Korea, The market for shared electric mobility is growing bigger and bigger.
  - (ref: Korea Transport Institute)
- So, We want to help the policymakers to choose a proper parking lot for personal mobility by using data analysis.
- What is personal mobility?
  - <img src="https://user-images.githubusercontent.com/102137580/160078259-e01e4f1f-b7ad-449d-8ec7-5b011a85eaa4.png" width="200">


  - This is personal mobility. Especially we used the "kickboard" data for analysis. 


## Analysis Process Description

**1. Preliminary investigation**
- We read the paper about shared electric kickboards and categorized users according to their purpose.
  - Paper : Empirical analysis of the factors affecting the satisfaction and behavior of individuals using shared electric kickboards. -A Case study of Seoul- (Daeun Ahn, Gongju University, 2020)
  1. Commuting type 
  2. Individual lifestyle type
  <img src="https://user-images.githubusercontent.com/102137580/160080753-01c43066-e5cf-4de5-a2bd-321abcef261a.png" width="500">
 

**2. Data Preprocessing**
- 서울시 빅데이터 캠퍼스 데이터
- 

**3. Exploratory Data Analysis**
- 필터링
- 

**4. Conclusion**
- We proposed the parking lot where the following.
- 

## What I did felt
- 처음으로 팀장으로써 팀원들과 함께 분석했지만, 팀원으로 있을때는 몰랐던 팀장의 고충을 느낄 수 있었다.
- 좀 더 구체적으로 써야지~<br/>
- 그리고 현직자 멘토링 데이라는 것도 있어서 공모전 제출작에 대한 피드백도 많이 받을 수 있어서 좋았다. -> 멘토링 이후 분석을 좀 더 깊게 분석을 했다.
- 오히려 예선보다 본선에 진출해서 분석을 더 열심히 한 느낌~!
- 시상식 자리에서는 다른 팀들의 분석과정도 볼 수 있어서 많은 걸 보고 들었다. 다음에 1등 팀이 쓴 EM 알고리즘도 써보고 싶다.
- 내가 발표를 잘 못한다는 것을 깨달았던 공모전! 발표력을 기르자~
- 데이터 분석가는 사회의 불편한 점을 알고, 데이터를 통해 그 문제를 해결할 수 있는 방향을 찾아 사람들에게 알려주는 스토리 텔러인 것 같다는 생각을 했다.

## Need to improvement
- 일단, 팀원들이 기본적인 "모델링"에 관한 개념이 없어서 EDA과정만 진행했는데, 개인적으로는 조금 아쉬웠다.
- 모델링 과정을 추가했으면 좀 더 정책결정권자들에게 도움이 되는 분석이 되지 않았을까하는 생각
  - 팀원들에게 하나부터 열까지 가르치면서 진행할 수 있는 시간이 없었다. (+중간고사 기간) :(
- 따릉이 보관소, 자전거 보관소 등 고려
  > 처음에는 서울 시내에 있는 자전거 보관소를 고려하자고 팀원들에게 말했지만, 팀원들이 자전거와 퍼스널 모빌리티의 사용자들 성향이 다르다는 의견이 있어 자전거 보관소를 고려하지 않았다. 하지만, 본선에서 심사위원들의 질의응답 시간에 기존에 있는 자전거 보관소 & 따릉이 보관소 데이터를 활용했으면 더 좋았을 것이라는 말에 나는 "퍼스널 모빌리티는 사용자들이 라스트 마일, 즉 최종 목적지까지 가는 가장 마지막 이동 수단이기 때문에 자전거라는 이동수단과 사용패턴이 달라 고려하지 않았다."라고 대답했다. 이 말에 또 다른 심사위원은 그래도 고려해보지.. 라고 말씀하시는 분 도 계셨고, 어떤 심사위원은 내 말에 동의하면서 실제로 따릉이는 출퇴근 수단으로 많이 쓰여서 퍼스널 모빌리티와는 결이 다르다고 말해주신 분도 계셨다. (이 때 얼마나 고마웠던지..) Q&A 시간 때 이렇게 심사위원들끼리 이야기해서 사실 이 프로젝트에서 따릉이 보관소나 자전거 보관소를 고려했어야 하는 지 아직도 잘 모르겠다.
