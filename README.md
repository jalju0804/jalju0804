# 이찬주

운영되고, 복구되고, 다음 사람에게 이어질 수 있는 시스템을 만드는 데 관심이 있습니다.

처음에는 좋은 소프트웨어를 만드는 일이 가장 중요하다고 생각했습니다. 그런데 학교와 창업팀에서 직접 서비스를 만들고 운영해보니, 진짜 어려운 문제는 “만든 뒤에도 계속 쓰이게 하는 것”에 더 가깝다는 걸 배웠습니다.

학교에서는 유용한 소프트웨어가 많이 만들어졌지만 오래 운영되지 못하는 경우가 많았습니다. 그래서 학생들이 직접 만들고, 운영하고, 사용하는 인프라가 있다면 더 좋은 소프트웨어가 다시 만들어지는 긍정적인 루프를 만들 수 있다고 생각했습니다. 그 문제의식이 [Aolda](https://github.com/orgs/Aolda)로 이어졌습니다.

창업 동아리에서 시작한 Witt에서는 아이디어를 인터뷰와 미팅으로 다듬고, 실제 결제를 받아보고, 클레임을 받고, 다시 개선하는 과정을 겪었습니다. 이때 기획서 속 니즈와 실제 사용자가 돈을 내며 말해주는 니즈는 다르다는 걸 배웠습니다. 사용자의 신뢰는 멋진 기능보다 결제, 알림, 배포, 로그처럼 지루하지만 정확해야 하는 디테일에서 나온다는 것도 배웠습니다.

이후 저는 기능을 더 붙이기 전에 먼저 이런 질문을 하게 됐습니다.

- 이 시스템은 누가 운영할 수 있는가?
- 장애가 나면 어디서부터 복구할 수 있는가?
- 특정 사람의 기억이나 습관에 의존하고 있지는 않은가?
- 다음 사람이 이어받아도 같은 판단을 할 수 있는가?

## 경험 한 줄 정리

- [Aolda](https://github.com/orgs/Aolda): 학생들이 직접 만들고 운영할 수 있는 클라우드 인프라와 ACC(Aolda Cloud Console)를 설계
- OpenStack / Ceph: 단순 구축보다 장애 모드, 백업, health check, quorum 검증 같은 복구 가능한 운영 기준을 더 중요하게 보게 된 경험
- Observability / Monitoring: 대시보드를 보기 좋은 화면이 아니라 배포 안정성, 장애 조사, 인수인계를 위한 피드백 루프로 다루었습니다.
- [Witt](https://witt.kr) / [Witt Store](https://store.witt.kr): 창업팀에서 실제 결제와 사용자 클레임을 겪으며 비즈니스와 사용자 신뢰를 제품 안에서 배웠습니다.
- AODS: GitHub, Kubernetes, 컨테이너 이미지, 검증 절차를 묶어 내부 배포 운영 흐름을 정리한 MVP

## 자주 다뤄온 도구

**Infrastructure / Cloud**

OpenStack, Ceph, Kubernetes, Amazon EKS, Docker

**DevOps / Platform**

GitHub Actions, ArgoCD, Argo Rollouts, Helm

**Observability**

Datadog, Prometheus, Grafana, Loki, Tempo, Alertmanager, OpenTelemetry

**Backend / Data**

Java, Spring Boot, QueryDSL, MariaDB, Redis

## Contact

- Email: [chanju0804@gmail.com](mailto:chanju0804@gmail.com)
