# CHANGELOG

이 저장소의 갱신 이력. 데이터가 추가·수정될 때마다 여기에 한 줄씩 쌓인다.

## 커밋 컨벤션

| 접두어 | 용도 | 예 |
|---|---|---|
| `log:` | 새 질문·정정·재적용 기록 추가 | `log: A03 reapplied (mock-task-a)` |
| `fix:` | 기존 기록의 오류 수정 (수정 사유를 본문에 명시) | `fix: Q3 date 08-03 → 08-04 (file metadata)` |
| `docs:` | 문서·페이지 개선 (데이터 불변) | `docs: index chart tooltip` |

데이터 행을 삭제하는 커밋은 만들지 않는다. 틀린 기록도 `fix:`로 정정 이력을 남기며 고친다 — 이 저장소의 주제가 바로 그것이기 때문이다.

## 이력

### 2026-08-13 — v3 최초 발행
- 통신(2026-04) + 반도체(2026-08) 2개 도메인 통합본 발행
- questions.csv 47행 / corrections.csv 19행
- corrections.csv에 `reapplication_type` 컬럼 신설 (self / self-partial / output / none — 정의: docs/methodology.md 3장)
- index.html 발행 — 모든 수치는 CSV에서 로드 시점 계산
- 편집 규칙 적용: 회사명 'A사' 치환 + 생활 정보 3곳 대괄호 마스킹 (docs/methodology.md 6장)

## 예정 (기록되면 위로 올라간다)

- [ ] 모의과제 A 실전 풀이 → A01~A04 재적용 측정
- [ ] 신규 영역(LTA 세부·낸드/eSSD·base die 경제학·고객사 구매 행태) 진입 시 L1→L3 소요 기록
- [ ] 8/20 채용 공고·JD 확인 → 3차 소스 기반 전형 정보 재검증
