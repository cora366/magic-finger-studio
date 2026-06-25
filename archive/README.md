# Archive

이 폴더는 **Magic Finger Studio**의 이전 버전과 보관용 자료를 저장하는 공간입니다.

---

## 목적

* 이전 버전 보관
* 실험 프로젝트 백업
* 폐기된 기능 관리
* 참고용 코드 저장
* 프로젝트 변경 이력 유지

---

## 저장 대상

* 이전 버전 HTML
* 테스트 프로젝트
* 실험 코드
* 삭제 예정 기능
* 이전 UI 디자인
* 이전 프롬프트
* 임시 백업 파일

---

## 권장 구조

```text
archive/

├── v1/
│   ├── MagicFinger_v1.html
│   ├── README.md
│   └── release_note.md
│
├── deprecated/
│   ├── old_ui/
│   ├── old_gestures/
│   └── old_prompts/
│
├── backup/
│   ├── docs/
│   ├── tutorial/
│   └── examples/
│
└── experimental/
    ├── test_canvas/
    ├── ai_experiments/
    └── prototype/
```

---

## 관리 원칙

### Archive에는 삭제 대신 보관합니다.

삭제가 필요한 자료도 바로 제거하지 않고 Archive로 이동하여 보관합니다.

---

## 이동 대상

다음 자료는 Archive로 이동합니다.

* 사용하지 않는 기능
* 이전 UI
* 테스트 코드
* 실패한 프로토타입
* 구버전 튜토리얼
* 오래된 예제

---

## 버전 관리

예시

### v1.0

* 첫 번째 Air Canvas

### v2.0

* Hover 기능 추가 전 버전

### v3.0

* Gesture 개편 전 버전

---

## 운영 원칙

Archive는 프로젝트의 역사입니다.

프로젝트를 되돌리거나 과거 구현 방식을 참고해야 할 경우 Archive를 활용합니다.

가능한 한 삭제보다 보관을 우선합니다.

---

## Magic Finger Studio 개발 흐름

```text
Ideas
   ↓
Docs
   ↓
Tutorial
   ↓
Examples
   ↓
Final
   ↓
Release

       ↓

    Archive
```

Archive는 프로젝트의 안정성과 지속적인 개선을 위한 백업 저장소이며, 모든 주요 변경 사항은 필요 시 이곳에서 다시 확인할 수 있습니다.

