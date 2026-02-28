# Project_IDS
Suricata와 Elasticsearch, Kibana를 활용한 실시간 네트워크 침입 탐지 시스템(IDS) 및 분석 자동화

# Key Features (주요 기능)
* 실시간 침입 탐지 (IDS): Suricata를 활용한 외부 위협 및 비정상 트래픽 탐지
* 로그 수집 자동화**: Filebeat를 통한 Suricata `eve.json` 로그의 실시간 Elasticsearch 전송
* 데이터 시각화: Kibana 대시보드를 구축하여 공격자의 IP, 유입 경로, 공격 유형을 한눈에 파악
* 효율적 분석 환경: 방대한 텍스트 로그를 시각화 데이터로 변환하여 분석 리소스 최적화

# Tech Stack (기술 스택)
* IDS: Suricata
* Logging: Filebeat
* Storage: Elasticsearch
* Visualization: Kibana
* Environment: Linux (Rocky 9)

# Project Results (실습 결과)
* ICMP Flooding 등 시뮬레이션 공격에 대한 실시간 탐지 확인
* 대시보드를 통한 공격 지표 시각화 및 대응 프로세스 수립 경험

---
© 2026 pu55. MIT License 적용.
