# Profile Website

ERP MM(구매/자재) 컨설턴트 커리어/프로젝트 포트폴리오 사이트입니다.

## 구성

- `index.html` — 홈
- `career.html` — Concept 1: 커리어 타임라인 (학력 + 경력)
- `projects.html` — Concept 2: ERP 컨설팅 프로젝트 목록
- `projects/aj-networks.html` — AJ네트웍스 ERP 시스템 구축 (2023.03 ~ 2024.07)
- `projects/harim-group.html` — 하림그룹 ERP 구축 (2024.08 ~ 2026.01)
- `projects/harim-pi.html` — 하림산업/펫푸드 PI 컨설팅 (2026.05 ~ 2026.07)
- `projects/template-new-project.html` — 새 프로젝트 추가 시 사용하는 템플릿
- `assets/css/style.css` — 전체 공통 스타일

## 새 프로젝트 추가하기

새 프로젝트를 진행하게 되면, 아래 정보를 Claude에게 전달하면 됩니다. (직접 코드를 수정할 필요 없음)

- 고객사명, 프로젝트명, 기간, 역할, 담당 모듈
- 고객사 사업 특성
- 주요 수행 업무
- 핵심 성과 (있다면)

`projects/template-new-project.html`은 참고용 구조입니다.

## 배포

GitHub Pages로 배포되어 있으며, 별도 빌드 과정 없이 정적 HTML로 동작합니다.
