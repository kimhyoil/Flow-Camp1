# Flow-Camp

###<소개>
###안녕하세요 여러분 이번 발표를 맡게된 ... 입니다
###발표내용의 흐름은 Tab3 -> Tab2 -> Tab순서로 진행됩니다.

###유엔 미래 보고서2020 에는 다음과 같은 내용이 있습니다
###'기술은 인류의 편의를 위해 끊임없이 발전할 것이다'
###그래서 우리는 여러 소셜 미디어에서 사용되는 해시태그를, 자동으로 생성해주는 (화면 가르키면서) 'HshTag Maker'를 개발했습니다.
###지금 우리의 시스템에는 인스타그램의 해시태그를 기반으로 데이터를 구축했지만, 다른 미디어로의 확장은 손쉽게 가능 할 것으로 판단합니다

###자세한 설명은 시현을 통해서 설명해드리겠습니다.
###보시다시피 ui는 전반적으로 ios를 따릅니다.

###(Tab3) - Tensorflow의 Object Detection을 이용하여, 이미지를 분석하고 이에 적합한 해시태그를 생성(해시태그 읽어주기)
###1. 사진 추가 및 변경
###2. 해시태그 수정 및 삭제
###3. 해시태그 복사 및 인스타 업로드
###확장 가능성: 사용자 개개인이 추가하고 삭제하는 해시태그를 학습시켜 성능 향상

###(Tab2) - 내장 데이터와 연동가능한 별개의 갤러리 생성
###1. 이미지 확대 및 슬라이드
###2. 사진 추가 및 삭제

###(Tab1) - ListView를 Custom하여, 휴대폰 데이터와 독립된 filesystem을 사용으며, 전화번호부가 요구하는 CRUD는 모두 구현 했습니다.
###1. 전화번호 추가(memo 작성 x, 전화번호에 번호만 입력가능, 포커스 자동이동, 자동 '-' 생성)
###2. 전화번호 수정(기본 이미지로 변경, memo 추가, 
###3. 전화번호 삭제(일부러 어렵게(아이폰UI), 실수로 지우는 불상사)
###4. 전화번호 검색 및 정렬
###% 가상머신에서 시현하는 것으로 이해해 실제 전화, 문자 내용 구현x
