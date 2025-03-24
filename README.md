# AI 웹소설 코치 (AIWC) 가이드

## 공개 저장소 안내

이 저장소는 AI 웹소설 코치(AIWC) 시스템의 소개와 기본 구조를 공유하는 공개 가이드입니다. AIWC는 자기계발서와 전문 지식을 창의적인 웹소설로 변환하는 체계적 방법론을 제공하며, Claude와의 창의적 협업을 통해 고품질 웹소설을 효율적으로 창작할 수 있도록 지원합니다.

### 유료 회원제 서비스 안내

AIWC의 완전한 시스템과 템플릿은 유료 회원제 서비스로 제공됩니다. 이 공개 저장소는 시스템의 기본 구조와 접근 방식을 이해하는 데 도움을 드리기 위한 가이드입니다.

- **교육 및 접근 방법**: AIWC 시스템에 대한 교육과 완전한 접근을 원하시면 [AIWC 교육 신청](https://getso.link/aiw-edu) 링크를 통해 문의해 주세요.
- **전체 저장소 접근**: 교육을 수료하신 분들에게는 전체 시스템이 포함된 비공개 저장소([https://github.com/leetaewon/AIWC/](https://github.com/leetaewon/AIWC/))에 대한 접근 권한이 제공됩니다.

---


## 프로젝트 소개

AI 웹소설 코치(AIWC)는 Anthropic의 AI 어시스턴트 Claude를 기반으로 하는 창의적 협업 시스템입니다. 단편적인 아이디어부터 체계화된 전문 지식까지, 다양한 출발점에서 매력적인 웹소설을 함께 만들어갑니다.

### 핵심 비전

"일방적인 분석이 아닌, 함께 만들어가는 대화형 창작 프로세스"

AIWC는 엄격한 가이드라인을 제공하는 도구가 아닌, 사용자의 창의성을 증폭시키는 협업 파트너입니다. Claude와의 자연스러운 대화를 통해 아이디어를 점진적으로 구체화하고, 질문과 대답을 주고받으며 이야기의 뼈대를 함께 구축합니다.

## 두 가지 창작 여정

### 아이디어 기반 시작 (Idea-to-Novel)
- 단편적인 아이디어나 개념에서 출발
- 브레인스토밍과 확장 과정을 통한 세계관/캐릭터 개발
- 대화를 통한 점진적 구체화와 발전
- 함께 상상하고 만들어가는 협업 과정

### 콘텐츠 변환 시작 (Content-to-Novel)
- 기존 콘텐츠(전문 지식, 교육 자료, 연구 등)에서 출발
- 핵심 가치와 원리의 창의적 재해석
- 사용자와의 대화를 통한 방향성 설정
- 원작의 가치를 보존하면서 매력적인 이야기로 변환

## 경량화된 문서 구조 및 접근법

AIWC 2.0은 효율적인 작업과 접근성 향상을 위해 핵심(core) 문서와 확장(extended) 문서로 분리된 경량화 구조를 채택했습니다. 이 접근법은 Claude의 컨텍스트 제한 내에서 최적의 성능을 발휘하도록 설계되었습니다.

### 핵심/확장 문서 시스템
- **핵심 문서**: 필수적인 정보만 포함한 경량 버전 (예: `2_1-aiwc-guide-master.md`)
- **확장 문서**: 심화 내용과 추가 예시를 포함한 상세 버전 (예: `2_1e-aiwc-guide-master.md`)
- **직관적 명명 규칙**: 확장 문서는 파일명에 'e' 접미사 추가

### 작업 단계별 문서 활용
창작 단계에 따라 필요한 최소한의 문서 세트를 활용하여 효율적으로 작업할 수 있습니다:
- **탐색 단계**: 마스터 가이드 + 탐색 템플릿
- **세계관 구축**: 마스터 가이드 + 장르/세계관 템플릿
- **캐릭터 설계**: 마스터 가이드 + 캐릭터 템플릿
- **파일럿 작성**: 마스터 가이드 + 회차 구성 템플릿

### 심화 정보 접근
작업 중 특정 영역에 대한 더 깊은 정보가 필요하다면:
- "이 주제에 대해 더 자세히 알고 싶습니다"
- "캐릭터 내적 갈등 설계에 대한 심화 기법이 궁금합니다"
- "세계관 차별화 전략에 대해 더 알려주세요"

## 저장소 구조

```
/AIWC
├── README.md                                 # 프로젝트 소개 문서
├── 1. 사용자 문서/
│   └── 1_1-aiwc-introduction.md              # 소개 및 빠른 시작 가이드
├── 2. 가이드 문서/
│   ├─◼︎ 2_0-project-instructions.md           #◼︎◼︎ 프로젝트 지침 문서 (템플릿)
│   ├─◼︎ 2_1-aiwc-guide-master.md              #◼︎◼︎ 마스터 가이드 (핵심)
│   ├── 2_1e-aiwc-guide-master.md             # 마스터 가이드 (확장)
│   ├─◼︎ 2_2-aiwc-guide-document.md            #◼︎◼︎ 문서 관리 가이드
│   ├── 2_2e1-document-philosophy.md          # 문서 철학 심화
│   ├── 2_2e2-naming-conventions.md           # 명명 규칙 상세
│   ├── 2_2e3-git-workflow.md                 # GitHub 워크플로우
│   ├── 2_2e4-quality-review.md               # 품질 관리 프로세스
│   ├─◼︎ 2_3-aiwc-guide-conversation.md        #◼︎◼︎ 대화 가이드 (핵심)
│   ├── 2_3e1-creative-dialogue.md            # 심층 대화 철학과 창의적 브레인스토밍 (확장)
│   ├── 2_3e2-modular-flow.md                 # 모듈식 대화 흐름과 전환 관리 (확장)
│   ├── 2_3e3-problem-solving.md              # 문제 해결과 심층 피드백 전략 (확장)
│   ├─◼︎ 2_4-aiwc-guide-quality.md             #◼︎◼︎ 품질 관리 가이드 (핵심)
│   ├── 2_4e1-quality-philosophy.md           # 품질 관리 철학과 접근법 심화
│   ├── 2_4e2-dialogue-process.md             # 대화형 품질 관리 프로세스 심화
│   ├── 2_4e3-core-elements.md                # 핵심 품질 요소 심화
│   ├── 2_4e4-stage-specific.md               # 단계별 품질 관리 심화
│   ├── 2_4e5-reader-focused.md               # 독자 중심 품질 평가 심화
│   ├── 2_4e6-ai-collaboration.md             # AI 활용 품질 관리 심화
│   ├── 2_4e7-problem-solving.md              # 문제 해결 및 품질 향상 심화
│   ├── 2_4e8-checklists.md                   # 상세 품질 확인 체크리스트
│   └─◼︎ 2_5-aiwc-guide-ai-collaboration.md    #◼︎◼︎ AI 협업 가이드
├── 3. 템플릿 문서/
│   ├─◼︎ 3_1-aiwc-template-exploration.md      #◼︎◼︎ 아이디어/콘텐츠 탐색 템플릿 (핵심)
│   ├── 3_1e1-genre-exploration.md            # 장르 탐색 심화 (확장)
│   ├── 3_1e2-systemization.md                # 시스템화 심화 (확장)
│   ├── 3_1e3-creative-dialogue.md            # 창의적 대화 기법 (확장)
│   ├── 3_1e4-world-differentiation.md        # 차별화 및 세계관 (확장)
│   ├─◼︎ 3_2-aiwc-template-genre-world.md      #◼︎◼︎ 장르별 세계관 설정 템플릿 (핵심)
│   ├── 3_2e1-genre-systems.md                # 장르별 시스템 심화
│   ├── 3_2e2-genre-fusion.md                 # 장르 믹스 및 융합 전략 심화
│   ├── 3_2e3-world-keywords.md               # 키워드 활용 및 차별화 심화
│   ├─◼︎ 3_3-aiwc-template-character.md        #◼︎◼︎ 캐릭터 설정 템플릿 (핵심)
│   ├── 3_3e1-character-depth.md              # 캐릭터 심층 구축
│   ├── 3_3e2-character-relationships.md      # 관계 역학 심화
│   ├── 3_3e3-character-growth.md             # 성장 과정 설계
│   ├── 3_3e4-character-examples.md           # 장르별 예시와 케이스 스터디 (필요시 추가)
│   ├── 3_3e5-genre-relationships.md          # 장르별 관계 패턴 (필요시 추가)
│   ├── 3_3e6-growth-examples.md              # 장르별 성장 사례 (필요시 추가)
│   ├─◼︎ 3_4-aiwc-template-series.md           #◼︎◼︎ 전체 연재 계획 템플릿 (핵심)
│   ├── 3_4e1-story-structure.md              # 스토리 구조 심화
│   ├── 3_4e2-character-journey.md            # 캐릭터 여정 심화
│   ├── 3_4e3-theme-development.md            # 테마와 핵심 가치 전개 심화
│   ├─◼︎ 3_5-aiwc-template-optimization.md     #◼︎◼︎ 연재 최적화 템플릿 (핵심)
│   ├── 3_5e1-platforms.md                    # 플랫폼별 상세 전략
│   ├── 3_5e2-marketing.md                    # 마케팅 및 프로모션 심화
│   ├── 3_5e3-reader-engagement.md            # 독자 참여 확장 전략
│   ├── 3_5e4-series-management.md            # 연재 관리 및 지속성 심화
│   ├─◼︎ 3_6-aiwc-template-chapter.md          #◼︎◼︎ 회차 구성 템플릿 (핵심)
│   ├── 3_6e1-approaches.md                   # 회차 설계 접근법과 파일럿 전략 심화
│   ├── 3_6e2-development.md                  # 회차별 구성 개발 심화
│   └── 3_6e3-optimization.md                 # 독자/품질 최적화 (타겟 독자, 창작 품질 향상, 차별화 전략, 문제 해결 등)
├── 4. 장르별 키워드 세트/
│   └── 다양한 장르별 키워드 세트 및 가이드
└── 기타 문서/
    └── 업그레이드 계획 및 분석 문서
```

## 시작하기

AIWC를 활용한 창작을 시작하려면:

1. 소개 문서 (`1_1-aiwc-introduction.md`)를 읽고 전체 개요를 파악합니다.
2. Claude에게 다음과 같이 시작을 알립니다:
   ```
   "안녕하세요, 웹소설을 만들고 싶습니다."
   ```
3. 아이디어 기반 접근 또는 콘텐츠 변환 접근 중 선택하여 대화를 이어갑니다.
4. 자연스러운 대화를 통해 창작을 진행합니다.
5. 필요에 따라 특정 영역의 심화 정보를 요청합니다.

자세한 가이드는 소개 문서를 참조하세요.

## 버전 정보

**현재 버전**: AIWC 2.0 (2025년 3월)

### 주요 업데이트 내용
- 대화 중심의 창의적 협업 모델로 전환
- 시간 제약 제거 및 유연한 프로세스 도입
- 아이디어와 콘텐츠 기반 접근법 모두 지원
- Claude 3.7 Sonnet의 향상된 기능 최적화
- 마케팅 및 피드백 분석 기능 추가
- 문서 구조 경량화 및 핵심/확장 분리 도입
- 작업 단계별 최적화된 문서 세트 제공

## 기여 가이드

AIWC 프로젝트에 기여하고 싶으시다면:

1. 이슈 제출: 문제점이나 개선 아이디어가 있으면 이슈를 등록해주세요.
2. 풀 리퀘스트: 수정 사항이나 새로운 기능을 제안하고 싶다면 풀 리퀘스트를 작성해주세요.
3. 피드백 공유: 사용 경험과 개선점을 저장소 이슈 트래커에 공유해주세요.

## 라이선스 및 저작권

이 프로젝트는 [라이선스 정보]에 따라 배포됩니다. 사용 및 배포에 관한 자세한 정보는 라이선스 문서를 참조하세요.

## 문의 및 지원

- 문제 해결 및 지원: 저장소 이슈 트래커를 이용해주세요.
- 기타 문의: [연락처 정보]로 문의하세요.

---

AI 웹소설 코치와 함께 당신의 창의적인 이야기를 만들어보세요!