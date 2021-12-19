# 딥러닝 1조 스터디 프로젝트 & git 코드 공유 repository

___

팀원: 고선욱, 장현영, 유상준
___

___

## 주제

생육 기간 예측 경진대회
___



## 배경

4차산업혁명의 시대를 맞아 농업의 분야에서도 AI  기술이 널리 사용되고 있습니다. 

또한 스마트팜, IT  기술을 동원하여 더욱 효율적인 작물 재배가 가능해지고 있습니다.

작물의 효율적인 생육을 위한 가장 최적의 환경을 도출한다면 식물 재배에 큰 도움이 될 것입니다.
___


## 데이터 소개

**1. train_dataset [Folder]**

예시) DAT00 ~ DAT01 (1일 차이) / DAT00 ~ DAT02 (2일 차이)

**2. test_dataset [Folder]**

idx : 테스트 데이터 인덱스값

before_file_path : 이전 사진 이미지 파일명

after_file_path : 이후 사진 이미지 파일명

**3. sample_submission.csv**

idx : test_data.csv의 index와 매칭

time_delta : test_data.csv에서의 before_file_path에 해당하는 이미지부터 after_file_path에 해당하는 이미지까지 식물의 생육기간을 예측

___

___
