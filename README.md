# Data Analytics for Age-friendly Busan
"고령친화 도시 부산" 을 위한 데이터 분석 프로젝트.

## 개요
국제보건기구 WHO는 [Age-Friendly World](https://extranet.who.int/agefriendlyworld/age-friendly-cities-framework/) 프레임워크 내 8개의 상호연결된 도메인을 제안하였습니다. 도메인은 노인들의 건강과 참여에 대한 경계를 식별 및 언급하는데 도움을 줄 수 있습니다. 우리는 오픈 데이터 기반 로케이션 인텔리젼스 프레임워크를 제안함으로서 고령친화 도시 부산에 관련된 정책의 투명성과 정책품질의 향상을 추구합니다. 고령친화도시 부산의 정책적 방향은 5대 전략과 20대 과제, 110개의 세부사업으로 구성됩니다 [관련링크](http://afc.bswdi.re.kr/Main.do). 우리의 목표는 진행중/실시될 정책에 대하여 오픈 데이터와 함께 분석사례를 만들어 재사용 및 재생산이 가능하면서도 확장가능한 오픈소스 기반 분석 프레임워크와 그에 대한 사례를 개발하는 것입니다.

## 현재단계
현재 프레임워크는 오픈소스 기반 GIS도구를 이용하여 시니어 센터의 입지 분석 기능을 지원합니다. 
1. 최적화된 입지분석을 위한 데이터 분석 과정 ( 접근성(도보 이동시간), 시니어 센터 이용율, 고령인구 변화 )

## 향후 진행방향
우리의 목표는 상업적 프레임워크를 사용하는 것이 아닌, 오픈소스 기반 분석 프레임워크를 향상 개발하고 이에 대한 분석사례 개발을 목표합니다.
1. 입지분석을 위해 고려해야할 요인를 추가
2. 현재 도로 네트워크의 교차점별로 데이터가 집계되어 있음. 집계데이터에, 통계학 방법/기계학습/딥러닝/그래프 방법론 등을 적용
3. 입지분석을 위해 다양한 시각적인 지도, 차트 구현.

## 특징


## 기술적 요구사항
- 코드 간결화
- 부동산, 고도, 이동 거리에 따른 시간을 수치화 할 수 있는 방법 
  - ex) 이동 시간(y) = A이동거리(x) + B (A,B : 부동산, 고도)
- 인구 예측 수식 고도화
- 주석 필수

## 국내 참고자료
- 서울시 빅데이터분석 사례 
- 노인복지시설 현황 분석
- 국내외 논문

## 관련 용어
[로케이션 인텔리젼스](https://www.esri.com/en-us/location-intelligence)(LI: Location Intelligence): 지리공간 데이터(geospatial data)와 비지니스 데이터를 결합하여 새로운 인사이트(insight)를 발굴하는 과정을 의미합니다. 동일한 용어로 

시니어 센터/노인복지시설

## 참고사이트

[부산 경로당 광역지원센터](http://www.busansenior.or.kr/05centeredu/00.php)

[부산 노인종합복지관](http://www.youngsilver.or.kr/theme/grape/mobile/page/sub02.php)

[부산복지개발원](http://afc.bswdi.re.kr/Main.do)

[OSMnx 고도 정보 관련 메서드](https://osmnx.readthedocs.io/en/latest/osmnx.html#module-osmnx.elevation)

[부산시 표준공시지가 정보](http://openapi.nsdi.go.kr/nsdi/eios/ServiceDetail.do?svcSe=F&svcId=F013&provOrg=NIDO) 



## 팀원
2103952 김범준
