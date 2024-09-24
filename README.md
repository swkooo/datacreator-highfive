# Data Creator Camp_highfive
This is team repository of highfive team
- Member : 강동찬, 구서원, 김시영, 박도연, 정지송
- Notion : [notion link](https://www.notion.so/2024-1016cd3d264b802e8b79f32aa7dadf00)

## Projects
**인공지능은 사람의 마음을 이해할 수 있을까?**

Mission 1. 패션 스타일 이미지 분류
- 2024.09.30 ~
- 1-1. 주어진 이미지 데이터의 파일 명은 아래와 같은 형식이다. “{W/T}_{이미지ID}_{시대별}_{스타일별}_{성별}.jpg”이에 기반하여 “이미지ID” 수 기준으로 “성별 & 스타일” 통계치를 아래 표 형식으로 기입한다.
- 1-2. ResNet-18를 활용하여 “성별 & 스타일” 단위로 클래스 분류를 수행하고 Validation 데이터에 대한 정확도를 제시한다.

Mission 2. 패션 스타일 선호 여부 예측
- 2-1. 주어진 라벨링 데이터의 파일 명은 아래와 같은 형식이다.“{W/T}_{이미지ID}_{시대별}_{스타일별}_{성별}_{설문ID}.json”이에 기반하여 “설문ID” 수 기준으로 “성별 & 스타일” 통계치를 아래 표 형식으로 기입한다.
- 2-2. 2-1에서 구한 유효한 라벨링 데이터만 따로 분리하여 아래와 같이 100명 응답자의 “스타일 선호 정보표”를 구한다. 파일은 json 포맷으로 되어 있으며 json 필드 중, “응답자ID”는 “user>R_id”로 알 수 있고, “스타일 선호 여부”는 “item>survey>Q5”로 알 수 있다.

Mission 3. 패션 추천시스템 만들기(최종)
- 3-1. 추천 시스템의 기본인 협업 필터링 (Collaborative Filtering)은 크게 user-based filtering, item-based filtering 방식으로 나뉘어져 있다. 각각에 대해서 이해하고, 2-2에서 구해 본 응답자의 “스타일 선호 정보표”를 토대로 Validation 데이터 내 응답자의 “스타일 선호 여부 예측” 문제를 2가지 기법으로 어떻게 적용해 볼 수 있고, 서로 비교하여 어떤 장단점을 갖는지 설명한다.
- 3-2. 3-1에서 살펴 본 기법 중, item-based filtering을 직접 구현해본다. “이미지 간 유사도” (image2image)만을 활용하여 Validation 데이터 내 응답자의 “스타일 선호 여부 예측” 문제를 수행하고 성능을 측정한다.

## Data

2024 Data Creator Camp - 2024.09 ~ 2024.11.
