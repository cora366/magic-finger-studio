# Knowledge

이 폴더는 **Magic Finger Studio**의 공식 지식(Knowledge Base)을 저장하는 공간입니다.

맞춤형 GPT(Magic Finger Builder)가 참고하는 기준 문서를 보관합니다.

---

## 목적

- 프로젝트의 공식 기준 문서 관리
- GPT Knowledge 파일 관리
- 검토 완료된 문서만 저장
- 프로젝트의 일관성 유지

---

## 저장 대상

- 프로젝트 비전
- 프로젝트 규칙
- 개발 워크플로
- UI/UX 설계
- 제스처 설계
- 프롬프트 라이브러리
- 교육 과정
- AI 기능 설계
- 코드 작성 규칙
- 공식 용어집

---

## 권장 구조

knowledge/

├── 00_Project/
│   ├── 01_Project_Vision.md
│   ├── 02_Project_Rules.md
│   ├── 03_Project_Roadmap.md
│   └── 04_Release_Notes.md
│
├── 10_Education/
│   ├── 11_Curriculum.md
│   ├── 12_Tutorial_Flow.md
│   ├── 13_Prompt_Library.md
│   └── 14_Teaching_Guide.md
│
├── 20_UI/
│   ├── 21_UI_Design.md
│   ├── 22_Gesture_Design.md
│   ├── 23_Code_Editor_UX.md
│   └── 24_Progress_UI.md
│
├── 30_AI/
│   ├── 31_AI_Code_Helper.md
│   ├── 32_AI_Feedback.md
│   └── 33_AI_Prompt_Rules.md
│
├── 40_Development/
│   ├── 41_HTML_Coding_Rules.md
│   ├── 42_File_Structure.md
│   ├── 43_Naming_Rules.md
│   └── 44_Development_Workflow.md
│
└── 90_Ideas/
    ├── 91_Idea_Log.md
    └── 92_Future_Features.md

---

## Knowledge 승격 규칙

모든 문서는 아래 단계를 거쳐 Knowledge에 등록합니다.

Draft

↓

ideas/

↓

Working

↓

docs/

↓

Review

↓

테스트 및 검토

↓

Knowledge

↓

knowledge/

---

## 관리 원칙

- Knowledge에는 검토가 완료된 문서만 저장합니다.
- 하나의 문서는 하나의 주제만 다룹니다.
- 파일명은 snake_case를 사용합니다.
- 변경 사항은 Release Notes에 기록합니다.
- GPT는 Knowledge 문서를 프로젝트의 공식 기준으로 사용합니다.

---

## Magic Finger Studio 원칙

Ideas는 아이디어를 기록하는 공간입니다.

Docs는 작업 중인 문서를 관리하는 공간입니다.

Knowledge는 프로젝트의 공식 문서를 관리하는 공간입니다.

항상 **Ideas → Docs → Knowledge** 순서로 문서를 발전시키는 것을 원칙으로 합니다.
