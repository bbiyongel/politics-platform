# politics-platform

Doc2Vec 모델 및 개체명 인식 기반 정치 기사 추천 웹 서비스

최근 선거 연령이 낮아짐에 따라 청소년 또한 투표를 할 수 있게 되었는데요, 그와 관련해서 저와 같이 정치에 대한 관심이 적거나 정치에 대해서 잘 모르는 친구들도 활발한 정치 참여를 하는 민주시민으로 자라날 수 있도록 도움을 주기 위해 Doc2Vec 모델 및 개체명 인식 기술을 활용하여 정치 기사 추천 웹 서비스를 개발해보았습니다. 프로그램 진행 과정은 다음과 같습니다.

1)  내가 잘 모르는 정치 이슈의 키워드를 입력하면 정치 기사들을 찾아Doc2Vec 모델을 활용해 중요한 정보를 요약해주고, 개체명 인식 기술을 활용하여 사건과 관련된 인물,  정당, 기관/집단, 장소 키워드를 제시해줍니다. 이를 통해 기존에는 잘 알지 못했던 이슈의 주요 정보를 한눈에 파악할 수 있습니다.

2) 순환신경망 감성 분석기를 이용해서 정치적 발언 및 정책의 내용을 기사 속에서 찾아 다양한 정치적 의견이 담긴 문구들을 제시합니다. 사용자가 공감이 가는 문구들을 선택하면 Doc2Vec 모델을 활용해 그와 관련된 정치적 성향의 기사들을 데이터베이스에서 찾아 추천해줍니다. 여기서 추천 대상의 기사들을 선택된 문구와 비슷한 정치적 의견을 대변하는 기사 뿐 아니라 반대되는 의견의 기사 또한 포함됩니다. 이러한 포괄적인 추천 시스템을 통해 사용자가 정치적 스펙트럼의 한 쪽에 치우치지 않은 넓은 안목으로 정치 이슈를 바라볼 수 있도록 도움을 줍니다.

한 번씩 봐주시면 감사하겠습니다.

웹서비스: https://politics-platform-web-sva4lzoc7q-an.a.run.app/
데모 영상: https://www.youtube.com/watch?v=QmhBJfef4ro
