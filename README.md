# Project2_S_Review
<img width="739" alt="스크린샷 2021-06-07 오후 3 48 19" src="https://user-images.githubusercontent.com/79897429/120971628-d449bc00-c7a7-11eb-93d6-1261ba55a741.png">

## Project_Flow
#### 01.과제정의 
- 비즈니스 이슈
- 데이터 과제화
- 핵심 가술
- 핵심 아이디어

#### 02. 데이터 수집 및 전처리
- 데이터 수집 및 저장
- 데이터 전처리

#### 03. 모델링
- BERT를 활용한 분석
- 워드클라우드를 활용한 분석
- 감성사전을 활용한 분석

#### 04. 분석결과 활용
- Interactive Dashboard 시각화


# 왜 이 프로젝트를 진행하게 되었는지?
빅데이터 분석이란 다양한 소스에서 다양한 크기(테라바이트 - 제타바이트)의 정형, 반정형 및 비정형 데이터를 포함하는 매우 방대하고 다양한 데이터 세트에 대해 고급 분석 기술을 사용하는 것입니다.
빅데이터 분석을 통해 분석가, 연구자 및 비즈니스 사용자는 이전에는 액세스나 사용이 불가능했던 데이터를 사용하여 보다 나은 의사결정을 보다 빠르게 내릴 수 있습니다. 
기업들은 텍스트 분석, 머신 러닝, 예측 분석, 데이터 마이닝, 통계 및 자연어 처리 등의 고급 분석 기술을 사용함으로써 이전에는 사용되지 않던 데이터 소스에서 독립적으로 또는 기존의 엔터프라이즈 데이터와 함께 새로운 인사이트를 얻을 수 있습니다. 
이에따라 현재 우리가 생활하면서 가장 접근성이 가까우면서도 트렌드의 가장 민감하며 기본적인 고객솔루션의 중요성등등을 종합적으로 분석한뒤 커피전문점의 고객리뷰를 통한 솔루션을 만드는 것을 목표로 프로젝트를 진행하게 되었습니다.

# 비즈니스 이슈
현재 커피전문점 업계 경쟁이 치열해지고 있으며 현재의 시장점유율을 유지하기 위해 고객 만족도를 관리/개선하고 새로운 트렌드에 맞추어 영업중인 매장의 서비스를 개선할 필요가 있다고 판단 하였습니다.

# 비정형 데이터를 신뢰성 있는 정형 데이터로 생성
평점은 주는 사람마다 주관적인 기준이 들어가며, 리뷰없이 평점만 줄 시 매장이 어떤점을 개선해야하는지 알기 힘듭니다. 이에따라 텍스트마이닝,감정분석으로 평점이 아닌 리뷰들을 분석하여 실질적인 솔루션을 발생 시킬수 
있도록 리뷰들을 분석해서 의미있는 인사이트를 찾을 수 있습니다.

# 핵심 기술 
bs4,selenium : 웹 스크랩핑을 위해 bs4와 selenium을 통하여 대표사이트들의 리뷰를 스크랩핑을 진행하였습니다.
konlp,wordcloud : konlp를 통한 품사별 임베딩을 진행하고 wordcloud를 통해 리뷰들을 통하여 확인 될 수 있는 키워드들을 가시적인 결과물로 시각화를 진행하였습니다.
koBert : 양방향 대응방식으로 기존 모델대비 양방향에 배치되어있는 단어들의 문맥적 의미를 포함하여 파악한뒤 정제된 데이터를 통해 단순 고객평점이 아닌 리뷰를 바탕으로 한 고객의 실질적인 평가를 확인합니다.
Tableau : 리뷰데이터를 통한 감성사전을 제작한 데이터를 통해서 감성지수를 매장별로 파악한후 Tableau를 통한 시각화 진행.


# 마치며
비정형 데이터를 정형화하며 인사이트를 도출 하는 과정에서 과거에는 불가능하던 연산을 기술의 산물을 통하여 정형화 하며 의미있는 데이터로 만드는 과정에 대하여 대단히 흥미로웠으며 추후 모자르던 부분들에 대한 보안과 시시각각 변화하는 기술들을 융합하여 더 나은 인사이트를 발굴하도록 노력하고자 합니다.
