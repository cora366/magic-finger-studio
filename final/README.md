# Final

이 폴더는 **Magic Finger Studio**의 최종 완성 프로젝트와 배포 가능한 결과물을 저장하는 공간입니다.

---

## 목적

* 최종 배포 버전 관리
* 교육에서 바로 사용할 수 있는 완성본 보관
* 안정화된 프로젝트 관리
* 버전별 릴리스 관리

---

## 저장 대상

* 최종 HTML 프로젝트
* 배포용 웹앱
* 완성된 교육 콘텐츠
* 발표용 데모
* 릴리스 버전

---

## 권장 구조

```text
final/

├── v1/
│   ├── MagicFinger_v1.html
│   ├── README.md
│   └── release_note.md
│
├── v2/
│   ├── MagicFinger_v2.html
│   ├── README.md
│   └── release_note.md
│
├── latest/
│   ├── MagicFinger.html
│   └── README.md
│
└── archive/
```

---

## 버전 관리 규칙

### Development

현재 개발 중인 버전

↓

### Beta

기능 테스트 완료

↓

### Release

교육 및 배포 가능한 버전

↓

### Archive

이전 버전 보관

---

## 배포 체크리스트

최종 프로젝트를 저장하기 전에 아래 항목을 확인합니다.

* HTML 정상 실행
* 모든 기능 동작 확인
* 오류(Console Error) 없음
* UI/UX 최종 검토
* 모바일 환경 확인
* 교육용 테스트 완료
* README 작성 완료
* Release Notes 작성 완료

---

## 파일명 규칙

권장 파일명

```text
MagicFinger_v1.html
MagicFinger_v2.html
MagicFinger_v3.html
```

최신 안정 버전은

```text
MagicFinger.html
```

로 유지합니다.

---

## Release Notes

각 버전에는 변경 사항을 기록합니다.

예시

### v1.0

* Air Canvas 구현
* MediaPipe Hands 적용
* PNG 저장 기능 추가

### v2.0

* Hover UI 추가
* Gesture 개선
* Pointer Mode 추가

### v3.0

* AI Code Helper
* STEP 추천 코드
* 코드 검색 기능

---

## 운영 원칙

* `final` 폴더에는 **완성되고 검증된 프로젝트만 저장**합니다.
* 실험용 코드는 `examples` 또는 `tutorial`에서 개발합니다.
* 안정화가 완료되면 `final`로 이동합니다.
* 이전 버전은 삭제하지 않고 `archive`에 보관합니다.

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
```

`final`은 프로젝트의 공식 배포본을 관리하는 공간이며, 교육 현장과 GitHub Pages 배포 시 기준이 되는 버전을 제공합니다.
