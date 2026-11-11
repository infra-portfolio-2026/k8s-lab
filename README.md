# k8s-lab

웹, API, MySQL 3계층 서비스를 kind 클러스터에 올려 본 Kubernetes 실습 환경입니다.

## 주요 내용

- `kind-config.yaml`: 로컬 클러스터와 포트 매핑
- `k8s/`: Deployment, Service, PVC, HPA(CPU 50%, 1~5개), VPA(권고 모드), metrics-server 패치
- `docker-compose.yml`: 같은 구성을 Compose로 작성해 비교

## 기술

Kubernetes · kind · HPA · VPA · Docker Compose · MySQL · Node.js

DB 비밀번호는 실습용 값입니다.


> 블라인드 채용 제출용 사본입니다. 이름·기관명·비밀값은 치환하거나 제외했고, 커밋 기록은 새로 만들었습니다. 치환된 식별자 때문에 그대로 빌드되지 않을 수 있습니다.
