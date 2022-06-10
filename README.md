![main](https://user-images.githubusercontent.com/50396533/172968927-fe87c266-13f5-4720-aead-96ca55660c21.png)

# 부스트캠프 AI Tech 3기의 Github에 오신 것을 환영합니다
'지속가능한 개발자'를 양성하는 개발자 교육 프로그램, 부스트캠프에 오신 것을 환영합니다.

부스트캠프는 네이버가 설립한 비영리 교육재단 [네이버 커넥트재단]에서 소프트웨어 교육을 통해 개인의 지속적인 성장과 발전을 돕고, 누구에게나 배움의 기회가 열리는 세상을 만들기 위해 운영하는 프로그램입니다.

이곳에서는 단순한 '지식과 스킬'이 아니라, 빠른 IT의 변화 속에서 지속적으로 성장할 수 있는 '좋은 개발자의 경험과 습관'을 가진 지속 가능한 개발자 양성을 목표로 교육이 진행됩니다. 개인이 아니라 팀 협업을 통해 배우고 현실에 존재하는 문제를 해결하며 다함께 성장하는 학습 커뮤니티를 지향합니다.

부스트캠프 AI Tech 3기에 참여한 학생(캠퍼)들의 최종 프로젝트 결과가 궁금하다면 [여기](https://github.com/boostcampaitech3/Overview/blob/main/Final_Project_List.md)에서 확인할 수 있습니다.

### [AI Tech 3기 교육 소개]
부스트캠프 AI Tech에서는 '비즈니스 가치를 창출하는 AI 엔지니어'를 목표로 핵심 교육 콘텐츠, 다양한 학습 경험, 멘토링을 제공합니다. 1000여 명의 지원자 중에서, 1)AI에 강한 호기심과 실험정신을 가지고 있으며, 이를 바탕으로 자기 주도적으로 성장하고 싶으신 분, 2)끝을 보는 '덕질'의 성향을 AI 엔지니어로의 성장에 십분 발휘하고 싶으신 분을 240명 선발하여 교육을 진행했습니다.

가장 큰 특징은 AI 기초와 모델링 중심으로 구성된 타 교육 프로그램과는 다르게, 본인의 선택에 따라 CV(Computer Vision), NLP(Natural Language Processing), RecSys(Recommendation System) 중에 하나를 선택하여 심화 이론 및 심화 프로젝트 각 2개를 진행하며 해당 트랙의 AI Production의 END-to-END 전과정을 학습합니다.

* 기간 : 2022년 1월 17일 ~ 2022년 6월 15일, 5개월 (100일간 풀타임)
* 구성 : Level 1(6주, AI Basics) + Level 2(10주, AI Modeling) + Level 3(4주, End to End)
* 트랙별 학습(Level 2) : CV, NLP, RecSys 중에 하나의 트랙을 정하여 AI Production의 END-to-END를 학습함

![path_of_growth](https://user-images.githubusercontent.com/50396533/172974887-dd8a71b0-7241-4eba-a0da-263132529a4c.PNG)

### [프로젝트 개요]


* __공통__

이름|검색키워드|설명|평가방법
----|----|----|----
이미지분류|level1-image-classification|인물 사진에서 사람이 마스크를 쓰고 있는지, 쓰지 않았는지, 정확히 쓴 것이 맞는 지, 자동으로 가려낼 수 있는 모델을 구현합니다. |F1, accuracy


* __컴퓨터 비전 (Computer Vision)__

이름|검색키워드|설명|평가방법
----|----|----|----
객체 영역 구분|level2-object-detection|쓰레기가 찍힌 사진들 속에서 물체를 분류하는 모델을 만듭니다. |mAP
데이터 제작|level2-data-annotation_cv|실무에서 활용되는 AI 프로젝트 과정의 전반적인 이해와 함께 피드백 사이클을 통해 점진적으로 모델 성능을 개선합니다. |F1
객체 검출|level2-semantic-segmentation|위 프로젝트에서 분류된 결과를 기반으로 쓰레기를 구분하여 분리수거를 할 수 있는 모델을 구현합니다. |mIoU


* __자연어 처리 (Natural Language Processiong)__

이름|검색키워드|설명|평가방법
----|----|----|----
한국어 언어 모델 학습 및 다중과제 튜닝|level2-klue|자연어 문장에서 단어간의 관계를 추론하여 정보를 요약하고, 중요한 성분을 파악하는 모델을 구현합니다. 이를 통해 질문에 답변하는 AI를 만들 수 있습니다. |Micro_f1
데이터 제작|level2-data-annotation_nlp|실무에서 활용되는 AI 프로젝트 과정의 전반적인 이해와 함께 피드백 사이클을 통해 점진적으로 모델 성능을 개선합니다. |-
기계독해|level2-mrc|질문 데이터 없이 지식 정보만을 학습하여 다양한 질문에 답변하는 AI를 구현합니다. 어떤 질문이 입력될지 알 수 없어 어려우며, retriver와 reader 두 모델을 직접 구현해야 합니다. |EM

* __추천 시스템 (Recommendation System)__

이름|검색키워드|설명|평가방법
----|----|----|----
영화 추천|level2-movie-recommendation|사용자의 영화 시청 이력 데이터를 바탕으로 사용자가 다음에 시청할 영화 및 좋아할 영화를 예측하는 모델을 구현합니다. 추천 시스템 트랙의 경우 별도의 데이터 제작 과정이 없고, 데이터 제작이 해당 프로젝트에 녹여져 진행되었습니다. |Recall@10
DKT(Deep Knowledge Tracing)|level2-dkt|학생별 문제 풀이 데이터를 이용하여 아직 풀지 않은 미래의 문제에 대해 맞았는지 틀렸는지 분류하는 모델을 구현합니다. |AUROC

### [팀별 레포 목록]
* 최종프로젝트 리스트 : https://github.com/boostcampaitech3/Overview/blob/main/Final_Project_List.md
* 컴퓨터 비전(CV) : https://github.com/boostcampaitech3/Overview/blob/main/repoList_teamDetail_CV.md
* 자연어 처리(NLP) : https://github.com/boostcampaitech3/Overview/blob/main/repoList_teamDetail_NLP.md

### [기타]
* 부스트캠프 홈페이지 : https://boostcamp.connect.or.kr/
* 문의 : boostcamp_ai@connect.or.kr
