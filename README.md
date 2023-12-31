# CAN Data Processing
CAN 데이터가 저장된 log파일을 이용해 CAN데이터에서 필요한 부분의 데이터만 수집하여
데이터를 처리하고, 이를 시각화하는 작업

## 목차
* [코드 설명](#코드-설명)
* [Jypyter Notebook 내용 설명](#상세-설명)
## 코드 설명
#### can_process.ipynb
log파일을 읽어와, 필요한 데이터만 수집 처리하여 이를 시각화
#### String_to_JSON.ipynb
String 내용을 가져와 반복되는 패턴을 찾아 원하는 형식대로 바꾸고, 이를 JSON파일로 변환

## 상세 설명
1. re 라이브러리를 이용해 문자열을 정규표현식을 이용해 필요한 형태로 변환
2. 데이터 로드하기
3. 데이터 전처리 (날씨 변환, ID와 Data 분리)
4. 데이터 추출
5. 시각화

## 결과물
CAN 데이터에서 전처리 후 추출하여 시각화한 결과는 다음의 이미지와 같음.

<img src="/img/can_process_result.png" width="300" height="300">
