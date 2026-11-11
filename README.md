# law-rag-platform

폐쇄망 환경에도 대응할 수 있는 **법령 지식베이스 RAG 플랫폼**입니다.
법제처 Open API의 공개 법령(신탁법, 자본시장법 등)과 해석례를 지식베이스로 사용합니다.

## 문서
- [PRD (제품 요구사항)](docs/prd.md)
- [ADR (아키텍처 결정 기록)](docs/adr/)

## 로드맵
| 단계 | 내용 |
|---|---|
| 0 | 기획(PRD) + AI 하네스 구축 |
| 1 | Docker Compose 기반 RAG MVP + 평가셋 |
| 2 | MCP 서버 / Claude Code 플러그인 |
| 3 | GitHub Actions CI + k3d + ArgoCD |
| 4 | Terraform 기반 AWS 인프라 |
| 5 | 평가 기반 개선 루프, 확장(GraphRAG 등) |

> 본 프로젝트는 학습 목적이며, 답변은 법률 자문이 아닙니다.
