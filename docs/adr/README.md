# ADR (Architecture Decision Records)

"왜 A 대신 B를 선택했는가"를 기록합니다. 한 번 기록한 ADR은 수정하지 않고, 결정이 바뀌면 새 ADR을 작성해 이전 ADR을 대체(Superseded)합니다.

## 파일 규칙
- 파일명: `NNNN-제목.md` (예: `0001-llm-openai-compatible-api.md`)
- 구성: 상태(제안/승인/대체됨) · 맥락 · 결정 · 결과(장단점)

## 목록

| 번호 | 제목 | 상태 |
|---|---|---|
| [0001](0001-storage-roles.md) | 저장소 역할 분담: Postgres 원장 · Qdrant 벡터 · Neo4j 그래프 | 승인 |
| [0002](0002-monorepo-service-split.md) | 모노레포 + 서비스 분리 | 승인 |
| [0003](0003-canonical-article-id.md) | 조문 정식 키와 결정론적 청크 ID | 승인 |
