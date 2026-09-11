# labs/gitops

GitOps의 기본 개념과 동작 방식을 실습하며 이해하기 위한 실험실.

Kubernetes에 애플리케이션을 직접 배포하는 방식에서 시작하여, 
Argo CD를 통해 Git을 SoT(Source of Truth)로 사용하는 배포 방식으로 전환하는 과정을 실습함.

### Architecture

```txt
Git
 ↓
Argo CD
 ↓
Kubernetes
```

### Phases

1. Kubernetes 수동 배포
2. Argo CD 설치
3. Git Repository 연결
4. Git 변경 및 Sync 확인
5. Drift 및 Self-Healing 실험
