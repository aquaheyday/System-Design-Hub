# 🏗️ Designs

이 디렉토리는 시스템 디자인 연습 및 실제 설계 사례를 기록하는 공간입니다.  
각 폴더는 하나의 시스템 또는 서비스 단위로 구성되며, 다음과 같은 흐름으로 정리합니다:

- 요구사항 정의 (Requirements)
- 아키텍처 설계 (Architecture)
- 데이터 모델링 (Data Modeling - 필요 시)
- 주요 트레이드오프 분석 (Trade-offs)
- 다이어그램 (Diagrams)

---

## 📂 폴더 구성 예시

| 폴더명 | 설명 | 링크 |
|---|---|---|
| messaging-system | 메시징 시스템 설계 | [messaging-system/](./messaging-system/) |
| social-network | 소셜 네트워크 시스템 설계 | [social-network/](./social-network/) |

---

## 📌 설계 문서 구성 가이드

각 시스템 폴더 안에는 다음 파일들이 포함됩니다:

| 파일명 | 설명 |
|---|---|
| requirements.md | 요구사항 정의 (기능적/비기능적 요구사항 포함) |
| architecture.md | 아키텍처 구성 및 주요 컴포넌트 설명 |
| trade-offs.md | 설계 과정에서 고려한 선택지 및 트레이드오프 정리 |
| diagrams/ | 다이어그램 저장 폴더 |
| notes.md | 설계하면서 배운 점, 추가 학습 필요사항 정리 |

---

## 💡 설계 시 참고할 가이드라인
- 요구사항은 **기능적 + 비기능적 요구사항**을 모두 작성
- 아키텍처는 **고수준 구성도** + **주요 컴포넌트 설명** 포함
- 트레이드오프는 **기술 선택 이유** + **포기한 대안과 이유** 정리
- diagrams/ 폴더에 draw.io 다이어그램 보관 (원본+PNG)

---

## 📚 참고할 템플릿
- [design-template.md](../templates/design-template.md)
- [checklist.md](../templates/checklist.md)
- [review-guide.md](../templates/review-guide.md)


