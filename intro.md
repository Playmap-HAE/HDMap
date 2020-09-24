## PlayMap HD Map

- 소개:
PlayMap 정밀지도는 사용자 위치정보를 서버로 전송하여 해당위치 정밀지도 tile을 Geojson으로 응답하는 스트리밍 방식의 서비스입니다.
정밀지도 이미지는 tiling 단위로 제공되며 RAD-R 포맷으로 제공됩니다.

- 활용방법:
양산차에 서비스되는 지도 데이터로 자율주행자동차 연구개발에 사용할 수 있으며 자율주행 개발용 시뮬레이터에서 실제 도로환경을 구현할 수 있습니다.

- RAD-R 제공 컨텐츠

|**구분(Model)**|**객체**|**Private**|**Public**|
|------|---|---|---|
|Land Model (차선모델) |Road Link (도로 중심선 정보)|제공|제공|
| |Road Node (도로 속성 경계 정보)|제공|제공|
| |Lane Side (도로 표면 경계: 실선, 파선 등)|제공|제공|
| |Lane Link (차선 중심 3D 형상 정보)|제공|제공|
| |Core Matching (SD 매칭 정보)|제공|미제공|
|Localization Model (측위 모델)|Road Edge(도로 경계시설물: 벽, 연석, 가드레일등)|제공|제공|
| |Traffic Light (신호등 정보)|제공|미제공|
| |Road Facility (도로 시설: 육교, 톨게이트 등)|제공|미제공|
|Routing Model (탐색 모델)|Link(SD 형상/속성 정보)|제공|미제공|
||Node (SD 통행/회전 정보)|제공|미제공|


- 제공 지역
전국 자동차전용 고속도로, 도심 여의도

## Open Drive

- 가상주행 환경용 도로데이터입니다.
- HD Map을 시뮬레이션 용도의 포맷으로 제공합니다.

참고:http://www.opendrive.org/

## 신청방법

첨부파일을 다운로드 받은 후 아래 메일로 신청해주시면 심사 후 샘플 및 상세 문서를 회신드립니다.

playmap@hyundai-mnsoft.com



