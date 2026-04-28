# Proposal Workspace 사용 안내

## 목적
`proposal_workspace`는 공공기관 RFP를 사업계획서 초안으로 전환하기 위한 Markdown 기반 작업공간이다.

## 빠른 시작
1. `09_rfp_extraction_template.md`에 RFP 핵심정보를 먼저 정리한다.
2. `07_requirement_coverage_table.md`에 요구사항 ID를 등록한다.
3. `10_outline_planning_template.md`로 절/배점/담당자를 계획한다.
4. `04_section_card_template.md`와 `section_cards/*_template.md`로 절별 카드를 만든다.
5. `05_generation_prompt_template.md`로 절 초안을 생성하고 `drafts/`에 저장한다.
6. `06_review_prompt_template.md`로 검토·수정 후 `final/`로 병합한다.

## 폴더 구조
- `section_cards/`: 절 유형별 전용 템플릿
- `drafts/`: 절별 초안 저장소
- `final/`: 제출 직전 최종본

## 운영 원칙
- 요구사항 ID를 중심으로 추적한다.
- 절별 분량은 A4 0.5~1쪽을 기본으로 한다.
- 과장표현 및 금지문형은 `02_style_rules.md`를 따른다.
