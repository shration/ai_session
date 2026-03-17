# M몰 AI 활용 세션 커리큘럼

현대카드 M몰 팀의 AI 업무 활용 능력 향상을 위한 사내 세션 자료입니다.  
MD·마케팅·운영·개발·기획 파트가 함께 참여하며, 매주 30분씩 실무에 바로 쓸 수 있는 내용으로 진행합니다.

---

## 파일 구조

```
├── index.html              # 전체 커리큘럼 인덱스 (자동 렌더링)
├── sessions.json           # 세션 데이터 (업데이트 시 이 파일만 수정)
├── session_01_common.html  # 세션 01 · 공통 — AI 도구 비교 체험
├── session_02_md_planning.html  # 세션 M2 · MD — 기획전 테마·구성 기획
└── README.md
```

---

## 새 세션 추가 방법

1. 새 세션 HTML 파일을 저장소에 업로드
2. `sessions.json`에서 해당 세션 두 줄만 수정

```json
"status": "upcoming"  →  "status": "done"
"file": ""            →  "file": "session_03_common.html"
```

3. 커밋 — `index.html`은 수정 불필요

---

## 세션 구성

| 구분 | 세션 수 | 내용 |
|------|---------|------|
| 공통 | 5 | AI 도구 비교·프롬프트 기초·문서 자동화·이미지 생성·리서치 |
| MD | 4 | 소싱 리서치·기획전 기획·상품 카피·비주얼 제작 |
| 마케팅 | 4 | 프로모션 카피·SNS 자동화·세그먼트 기획·성과 분석 |
| 운영 | 4 | VOC 분석·QA 자동화·FAQ 작성·이슈 보고서 |
| 개발·기획 | 5 | PRD 작성·UX 리서치·목업 생성·추천 기획·데이터 분석 |

---

## 활용 AI 도구

유료 도구도 활용하되, 가급적 무료 플랜으로 실습 가능한 범위를 기준으로 진행합니다.

`Claude` `ChatGPT` `Gemini` `NotebookLM` `Stitch` `Perplexity` `Canva AI` `Obsidian`
