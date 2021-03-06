# 하이퍼레저 기반의 의약품 위변조 플랫폼 구축

## 프로젝트 소개
암호 화폐로 이슈가 되어 부작용에 대한 우려가 많이 대두 되고 있는 블록체인 기술은 암호 화폐를 포함하는 대신 공동의 목표를 제공함으로써 부작용의 대명사가 되는 암호 화폐를 제거하고 문서의 송수신이라는 목적 달성을 위해 참여함으로써 보안기술의 완성이 가능함
따라서 오픈소스 블록체인 플랫폼을 활용한 N:M 문서유통 서비스 구축을 통하여 아래의 효과를 달성할 수 있음
・의약품 위변조 방지, 의약품 확인 서비스
・안전한 의약품 복용 가능한 환경 구축

## 개발 배경 및 필요성
의약품의 유통기한 이후 회수하고 있으나 실적은 저조하여 소비자에게 위해 의약품이 다수 유통될 가능성이 있음
- 이를 해결하기 위하여 식약처 및 정부에서는 제조업자 감시, 수입업자 감시, 의약품 품목갱신등의 제도 정비를 추진하고 있음
- 제도 뿐 만 아니라 의약품 추적으로 통해 처방부터 회수까지 관리를 통해 위해 의약품으로 부터의 환자 보호와 변조된 의약품을 확인 할 수 있도록 하는 의약품 안전관리 서비스 필요

## 주요 기능
### S/W 주요 기능
블록체인 플랫폼 : 리눅스 재단의 주관하에 이루어진 하이퍼레저 기반의 블록체인 오픈소스 플랫폼을 이용하여 개발한다.
의약품 고유정보 생성 : 마이닝을 통하여 고유 해시값을 생성한다. 이를 통하여 의약품은 해시값으로 구별될 수 있다.

### H/W 주요 기능
의약품 이미지 정보와 고유 해시값 매핑 : 데이터베이스 안에 있는 이미지 정보를 고유 의약품 해시값과 매핑하도록 한다.
의약품 이미지 정보의 전송 : 소형 카메라(예: 휴대폰 카메라)를 활용하여 의약품 정보(이미지 정보)를 고유 해시값과 매핑하기 위해 서버에 전송하도록 한다.

## 적용 기술
   ㅇ 리눅스 서버: 도커(Docker)
   ㅇ 블록체인 플랫폼: 하이퍼레저 패브릭
   ㅇ 모바일 서비스: 안드로이드 어플리케이션
   ㅇ 데이터베이스: MySQL
  
