---
layout: post
author: seungpilpark
notification: true
title: "Devops 문화 정착에 실패했던 경험담"
description: Devops 문화 정착에 실패했던 경험담을 남기는 글.
image: 'https://user-images.githubusercontent.com/13447690/65383664-8b43a100-dd53-11e9-9c86-bb74bc0f3306.png'
categories: 
- essay
date: 2019-09-20 09:05:00
tags:
- devops
- agile
introduction: Devops 문화 정착에 실패했던 경험담을 남기는 글.
twitter_text: Devops 문화 정착에 실패했던 경험담을 남기는 글.
---

직업이 DEVOPS 아키텍트이다 보니 MSA 를 전환을 시도하거나, 애자일 방법론을 도입하려는 기업을 많이 접해왔다. 그런 곳에 투입되거나 간접적으로 연관되어 내 할일을 하면서, 조직이 어떻게 실패하게 되고 성공하게 되는지 많이 봐왔다.

좋은 이야기는 아니지만, "애자일 성공하는 필수 공식" 같은 글을 쓰는 것 보다 경험에서 나온 스토리를 담담하게 이야기하는 걸 해보고 싶었다. 임원이나 리더 입장이 아니라 일개 엔지니어의 포지션에서 바라보았기 때문에 글의 시야가 좁고 편협할 수 있겟다.

# 조직간의 문제가 실패의 원인이 됬던 경험

4년전의 일이다. 전자문서 관련 중견 기업이 솔루션을 퍼블릭 서비스로 만들고자 했고, 나는 이 회사의 클라우드 기반 서비스 구축이나 Subscription 결제 모델 등 기술지원으로 함께 하였었다.

### 회사에서 가장 잘하는 사람들을 모았으니 무조건 성공이야

시작 조건이 무척 좋은 팀이었다. 돈도 많았고, 임원들의 지원아래 회사에서 가장 경험있고 잘하는 사람들을 모아 팀을 꾸렸다. 이 팀은 기존 업무에서 완전히 분리되었다.

경험 많은 개발자 출신 팀장은 매우 의욕적인 사람이었다. 비록 서비스 사업에 대한 방법론이나 아키텍처가 막 태동하던 시기여서 우아하진 못했지만, 기존 SI 개발하던 방식대로 추진해도 프로젝트가 잘만 굴러갔다. 기획 잘 나오고, 디자인 잘 나오고 개발 잘했다. 맨파워가 있었기 때문에 정해진 일정에 순조롭게 마무리 하였다.

일정에 무리없이 프로젝트가 진행되어 가고 기존 솔루션으로 납품하던 고객들에게서 긍정적인 반응이 쏟아져 나왔다. 서비스가 나오면 꼭 써보고 싶다는 고객사 반응이 이어졌고, 임원들이 고무되기 시작했다. 국내 서비스를 런칭하기도 전에 글로벌 서비스 이야기를 하기 시작하였다. 프로젝트 인원들도 같이 동조되어 모이기만 하면 행복한 미래를 이야기했다. 런칭이 임박하여서는 전세계를 평정한 것처럼 자신감이 가득했다.

### 상황의 변화

결재를 제외한 베타 서비스를 출시하였다. 당연히 초기에는 이런저런 피드백들이 나왔다. 피드백들을 수렴하며 조직이 점점 변했다. 아무도 가르쳐 주지 않은 길이었지만 오로지 맨파워로 극복해 나가며 서비스 운영 조직으로 만들고자 팀이 노력했다. 조금씩이지만 가입자도 늘어나고 있었다. 나는 그맘때쯤 지원을 종료하였는데, 꾸준히 연락을 하던 팀장의 말로는 몇 달 후 서비스를 접었다고 헸다. 깜짝 놀랐다. 이야기를 들어보니, 팀장님께서는 다음과 같은 이야기를 하셨다.

팀은 최선을 다했지만 임원들이 바라는 폭발적인 그 막연한 대박의 기대감이 너무 컸다. 팀을 유지하기 위해 쓰고 있는 돈이 비싸다는 이야기가 돌던 중에, 때마침 블록체인 호재가 터졌다. 여기저기 블록체인 한다고 나서기만 하면 대박을 쳤다. 블록체인 전자문서 사업을 한다고 온 회사의 관심이 집중되었다. 회사가 미래를 보지도 못하고 팀을 해제하는 결정을 하고 말았다고 하셨다.

### 캐시카우 역할을 하는 인원에 대한 존중이 없었다

당시 서비스 팀을 먹여살리기 위한 캐시카우는 솔루션 팀들이었다. 인원 구성도 솔루션 팀이 훨씬 많았다. 서비스 팀과 솔루션 제품팀의 분리가 상당히 오래 지속 되었었다. 내가 느낄 적 당시 솔루션 팀이 서비스 팀을 바라보는 시선은 그냥 자기들이 벌어다 준 돈 먹어가는 미운 녀석들 이었다. 지금 와서 생각해 보면 서비스 팀의 태도에 문제가 있었던 것 같다.

변덕이 심한 회사 조직이야 늘 듣는 이야기이니 그럴 수 있다. 그렇지만 그 회사 대표님께서 그렇게 피도 눈물도 없는 분도 아니었다 (엄청 똑똑하신 분인데). 그만한 중견기업을 키우신 분이 그런 결정을 한 데에는 그간 지켜본 전체적인 회사 분위기 등 복합적인 요인이 작용했을 것이다. 

서비스 팀에 우수한 인재들이 모였다. 자기들끼리 매일 으쌰으쌰 기분좋게 일한다. 매일 새로운 시도를 하고, 행복해 보인다. 매출이 제로인데도 임원들이 항상 관심있게 바라봐준다. 그럴 때일수록 서비스 팀의 팀원들은 겸손했어야 했다. 물론 겸손한 분들이었지만 겸손한 걸 넘어서서 다른 팀들에게 더 잘했어야 한다고 본다. 우리가 당신들이 돈을 열심히 벌어다 준 덕에 프로젝트를 진행할 수 있다고 감사하다고 하고, 밥도 사고 술도 사고, 다른 팀 고충도 듣고 머라도 하나 도와줄려고 노력도 하며 관계를 유지하는 데 더 노력했어야 했다.

그 팀의 팀장님께서는 나에게 자기가 정치에서 밀렸다고 하셨다. 내 생각은 좀 달랐다. 나는 그 일로 성장하는 팀이 나머지 팀에게 긍정적인 영향을 꾸준히 미치고 있지 못하면 이내 고립되고 오래 가지 못한다는 걸 배웠다.

서비스 팀 분들은 일부는 원래 업무로 돌아갔고, 일부는 다시 적응하지 못하고 회사를 나갔다고 하셨다.

# 준비되지 않은 리소스로 인해 실패했던 경험

2년 전의 일이다. 소속 회사 대표의 소개로, 기업 세미나에서 알게 된 고객사 대표를 소개받아 MSA 컨설턴트 일을 하러 간 적이 있었다. 회사의 상태는 매우 심각했으며, 한편으로는 매우 대단한 회사였다.

학원이나 병원등을 가보면 투박한 딱딱한 테트리스 모양의 상태바들이 늘어서있는 웹솔루션을 떠올릴 수 있을 것이다. 이 회사의 주력 상품이 그것이었다. 공장에서 로트추적 관리를 하는 솔루션이었는데, 센서기반 IOT 물류 추적을 떠올리면 안된다. 사무실에서 자재 매입, 출고, 영업 등등 수작업 기입하고 바코드를 발급하고, 현장에서는 착착 바코드 붙여가며 생산 몇개, 포장 몇개 식으로 기입하는 솔루션이다. PHP 로 만들어졌다.

그런데 테이블 수가 엄청나다. 초창기에 고객사 대표 혼자서 독학으로 만들어 낸 제품이다. 그만큼 현장 이해도가 타의 추종을 불허하신다. 제품의 질 따위는 상관없이 영업력으로 공장주들을 압도하였다. 회사가 순식간에 커졌고, 개발자를 모집했다.

제품의 질로 성장한 것이 아니라 현장 이해도와 영업의 힘으로 성장했다. 관성이란 것이 있기 때문에, 회사의 성장 방향도 자꾸 그 쪽으로 치우친다. 얼마 못가서 DB 프로시셔와 PHP 스파게티 코드로 인해 유지 보수 비용이 순이익을 침범하기 시작했다.

당시의 소스코드를 기억해 보자면 이러했다.

```
if (영진공업 or 길동공업 or 세정공업)
  if (자재입고)
     do 원료투입
     ## 2016-xx-xx 영진공업 요청으로 원료 투입시 예비 원료 계산 추가
     if(영진공업)
       do 예비 원료 계산
     else
       do ....
       ## 2017-xx-xx 길동공업 요청으로 불량 예측 필드 추가
       if(길동공업)
          do ...
       else
         ...
```

이런 상황이 50 군데가 넘는 공장을 대상으로 끝도 없이 if else 행렬이었다. 이런 와중에 고객사 대표께서 애자일 강의를 듣고 몇가지 서적, 기사에 매료되어 "우리도 이렇게 하면 Cool 하겠다" 하며 컨설팅을 시작하게 되었다.

### 준비되지 않은 리더십

내가 당시 경험이 좀 더 있었더라면 절대 하지 않았을 행동을 이때 많이 하였다. 그 대표의 성향은 음식을 찍어 먹으라고 포크 하나를 알려주면 포크로 음식도 찍어먹고 리모콘도 찍어 먹으려 하는 사람이었다. 하나를 알려주면 모든 것에 다 적용하려는 "밀어붙여" 타입이었다. 애자일을 공부하여 컨설팅 해 드렸더니 다음과 같은 방법으로 직원들을 괴롭혔다.

- 화이트보드/포스트잇 활용 문화 정착
- 스크럼, 칸반 등 개념 검토 및 현황조사
- 개발팀 교육용 자료 제작 및 교육 실시
- 애자일 툴 업체 섭외 및 도입 회의

영업,회계,개발 예외없이 일괄적으로 동참하도록 지시가 떨어졌다. 소속 대표에게 상황을 말했더니 깜짝 놀라시며 당분간 말을 아끼며 아무것도 하지 말라 하였다. 조용히 상황을 지켜보았다. 의외로 큰 반발없이 회의도 하고 교육 일정도 세우고 스크럼도 하고 있었다. 알고보니 고객사 대표가 예전에도 비슷한 상황을 만들었었고, 흐지부지 끝났던 터라 이번에도 그려러니 하며 폭풍이 지나가길 기다리고 있다고 하더라. 별 의미없는 행위만 계속되었다.

보다 못해서 제안을 하나 하였다. 당시 스파게티 코드로 인한 유지보수 스트레스로 인해 개발자들이 퇴사율이 매우 심했다. 그만큼 입사자도 많았다. 그럴 수 밖에 없는 것이, 아무 발전없이 if else 따라가며 한땀한땀 업무 맞추기가 무슨 낙이 있나 싶다. 퇴사자들이 이해가 갔다. 이 상황을 개선 할 겸, 아직 준비되지 않은 상황에서 시도하는 무의미한 애자일 보다 BPMN 프로세스를 알려드리며 복잡하게 꼬인 프로세스들을 도식화 하는 것을 제안하였다.

이 제안은 어느정도 성공하였다. 확실히 느리지만 꼬인 코드들이 가시화 되며 Policy 를 적용해 나갈 수 있었다. 그러자 이 대표님은 회사의 모든 업무를 BPMN 으로 처리해야 겠다며 나섰지만 직원들의 무시로 현실화 되지는 못하였다.

### 준비되지 않은 직원

BPMN 도식화 작업과 함께 개발자들이 기존의 유지보수 업무와 함께 수행해야 했기 때문에 업무 버든에 걸려 매우 힘든 상황이었다. 하지만 이 작업은 회사의 생존이 달린 문제이기 때문에 완료해야만 하는 작업이었다.

그 와중에 대표가 그간 배운 애자일, MSA 개념을 가지고 열심히 사업수주를 하러 다녔나 보다. 작은 정부지원 프로젝트를 따냈다. 정부 지원 프로젝트이니 무조건 수행해야 하지 않겠는가. 매우 안타깝게도 기존 개발인력을 분리하여 MSA 수행팀을 만들었다. 대표 입장에서는 축하할 일이지만 직원들 입장에서는 내 존재 자체가 재앙이며, 대표에게 자꾸 바람을 넣는 못된 사기꾼 처럼 보였을 것이다. 매우 불편하였고 그만두고 싶은 마음이 컸다. 심적 부담도 컸다. 그래도 도망치지 않고 MSA 과제는 마무리 하고 가고 싶었다.

쫒기듯이 배정된 프로젝트 룸으로 향했다. MSA 전환 팀에는 나이가 어린 친구들이 배정되었다. 영리한 친구들이었기에, 내가 Spring Cloud 와 Angular 코드 틀을 잡고 가이드 코딩을 해 나가면 금방 배워가며 빈 곳을 채워나갔다. 이 회사에서 컨설팅 하면서 제대로 생산적인 활동을 한 의미있는 시간이었다. 서로 많이 배워가며 진행하였다. 

조용히 마음 맞는 사람들끼리 결과물을 내고 있으려니, 대표가 역시 자신이 옳았다고 생각을 하였는지 모든 레거시 시스템을 MSA 로 전환하기 위해 이리저리 돌아다니며 밑밥을 깔고 다니기 시작했다. 집중하고 있는 시기에 프로젝트에 끼어들어 이런저런 업무지시를 내리기 시작했다. 이제 막 성과를 보이기 시작하는 것을 차분히 원숙해 질 때까지 기다려야 할 때인데, 조만간 기껏 해 놓은것도 스러질 게 예상이 되었다. 때마침 나의 계약이 만료되었지만 연장하지 않고 조용히 본사로 복귀하였다. 

### 좌절감이 퇴사로

함께 MSA 전환 팀에 있던 어린 친구들은 아직도 연락하고 지낸다. 그 이후 그 친구들이 말하길, 계속되는 푸쉬로 인해 에너지가 완전히 바닥이 났고, 무엇보다 다른 조직에서 저들이 대체 돈만 까먹고 뭘 하나 하는 무관심에 큰 좌절감에 휩싸였다고 한다. 열악한 환경에서도 싹튼 떡잎들은 그렇게 회사를 퇴사하고 현재는 알만한 중견 스타트업에서 매출에 큰 기여를 하고 있다.

글을 쓰던 중 문득 궁금하여 그 회사의 홈페이지에 들어가 보았다. 제법 멋지고 감각적인 화면이 뜬다.  최신 기술로 점철된 완벽한 솔루션을 제공하는 것 처럼 보인다. 제품 카테고리와 문서를 받아 보았다. 내용과 업무 프로세스가 옛날과 다를 바 없다. 본질적인 문제를 그대로 안고 가는 것이 틀림없다.  

큰 조직에서 일할때는 조직화 된 시스템도 있고 변화를 버텨낼 체력도 있었지만, 상대적으로 작은 조직에서 유달리 개발 문화 변화가 힘든 것 같다. 성공했던 기억보다 실패했던 경험이 더 가슴아프다. 실패했던 팀들이 매출이 없다고 괄시 받던 모습들이 나에게도 트라우마가 되어 가급적 어느 조직을 가더라도 제대로 밥벌이는 하고 살려고 노력한다.

인력풀은 그대로 유지한 채로 모두들 무언가 마법에 걸린 것 처럼 업무도 열심히 하고 실력도 쑥쑥 늘고 하는 일은 벌어지지 않는 걸 경험했다. 과도기에는 그만큼 기존 업무의 완충 인력이 더 들어가기 때문이다. 소프트웨어 활동도 결국 돈을 벌고자 하는 것인데, 개발 문화 혁신은 당장 돈을 벌지 못하고 돈이 더 들어간다. 리더의 입장에서는 조직의 존속을 생각해야 하므로 밸런스를 잡는게 더 어려울 수 있을거라 생각된다.


