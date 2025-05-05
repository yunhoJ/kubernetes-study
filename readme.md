# Kubernetes Study

## 1. Pod 생성 및 환경변수 실습
- Pod API 버전: v1
- Pod 리소스 종류: Pod
- Pod 이름: hello-app
- Pod 네임스페이스: default
- 컨테이너 이름: hello-app
- 컨테이너 이미지: hello-app:1.0
- 컨테이너 포트: 8080
- 환경 변수: POD_NAME, POD_IP, POD_NAMESPACE, POD_NODE_NAME, POD_NODE_IP, STUDENT_NAME, GREETING

### 실습 내용
1. Pod 생성 YAML 파일 작성
2. 환경변수를 통한 Pod 메타데이터 전달
3. Pod 생성 및 상태 확인
4. Pod 로그 확인
5. Pod 내부 환경변수 확인

## 2. ReplicaSet 실습
- ReplicaSet API 버전: apps/v1
- ReplicaSet 이름: blue-replica-set, myapp-replica-set
- ReplicaSet replicas: 3
- 컨테이너 이미지: 
  - blue-app:1.0
  - my-app:2.0-unhealthy

### 실습 내용
1. ReplicaSet YAML 파일 작성
2. ReplicaSet을 통한 Pod 복제본 관리
3. Pod Template 설정
4. 레이블과 셀렉터를 통한 Pod 관리
5. 리소스 요청 및 제한 설정
6. 롤백 시나리오 실습

### 주요 학습 내용
- Kubernetes 기본 개념 이해
- YAML 파일을 통한 리소스 선언적 관리
- Pod와 ReplicaSet의 관계
- 환경변수를 통한 설정 관리
- 컨테이너 리소스 관리
- 고가용성을 위한 복제본 관리
