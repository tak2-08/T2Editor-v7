# T2Editor v7 배포본 매니페스트

**상태: EOL (지원 종료) — 이 계열의 모든 판본**
판본 3건 · 출처 시점 2026-09-27 · 배포 API `https://dsclub.kr/api/t2editor/version/index.php?action=list`

릴리즈 노트에 실리는 배포 설명 전문을 옮긴 기록이다.

---

## 1. v7.0.0

- **상태: EOL**
- 배포일: 2025-12-14
- 저장소 표제: T2Editor 7.0.0
- 브랜치: `releases/v7.0.0` · 태그: `v7.0.0`
- ZIP: `7.0.0.zip` (1267402 bytes)
- sha256: `8b472e189af6b387c543b1ebfcde7c6ab5ccd357cc7abd369af6226ed31df206`
- 배포 시점 유효 라이선스: **2.0.0**
- 라이선스 원본 위치: 배포본 안 `readme.txt`
- readme.txt: 포함 (sha256 `79678ecb0a8bc335f2527d9f757e12ce0152062e6171ca66ffbda6582c65776a`)
- 배포 API 원본: <https://dsclub.kr/api/t2editor/version/index.php?action=download&version=7.0.0&file=0>

### 배포 설명

```text
1. 플러그인 별 독립 css 파일 사용 기능 추가- 기존 core.css, dark.css, 플러그인 js파일에 삽입되어있던 스타일들을 각 플러그인이름.css로 변경하여 유지보수성 향상 (t2editor/editor.lib.php, t2editor/css/core.css, t2editor/css/dark.css, t2editor/plugin/대부분 플러그인)- 플러그인 스타일 작성 시 T2Editor/plugin/plugin_name/plugin_name.css에 추가해두면 자동으로 editor.lib.php에 추가​

2. 이미지 플러그인 사용성 개선
- 디자인 개선
- 드래그를 통해 업로드 이미지 순서 변경 기능 추가
```

---

## 2. v7.0.1

- **상태: EOL**
- 배포일: 2025-12-16
- 저장소 표제: T2Editor 7.0.1
- 브랜치: `releases/v7.0.1` · 태그: `v7.0.1`
- ZIP: `7.0.1.zip` (1271270 bytes)
- sha256: `2dbe12705f58465005a675895da8a2b0857b02207596c75f82ed5a36cca59464`
- 배포 시점 유효 라이선스: **2.0.0**
- 라이선스 원본 위치: 배포본 안 `readme.txt`
- readme.txt: 포함 (sha256 `35b34eee7ecfd8528235e639d0ec0b0262ac247ee3d7d37a1c83af5a0347ea95`)
- 배포 API 원본: <https://dsclub.kr/api/t2editor/version/index.php?action=download&version=7.0.1&file=0>

### 배포 설명

```text
업데이트 중 제거된 텍스트&amp;텍스트 배경 색상 선택기 복구​
```

---

## 3. v7.0.2

- **상태: EOL**
- 배포일: 2025-12-19
- 저장소 표제: T2Editor 7.0.2
- 브랜치: `releases/v7.0.2` · 태그: `v7.0.2`
- ZIP: `7.0.2.zip` (1261702 bytes)
- sha256: `71f0a14bc13d1d220631a805db7341e07fae4f3ceeb11d26d75732e1656b22b5`
- 배포 시점 유효 라이선스: **2.0.0**
- 라이선스 원본 위치: 배포본 안 `readme.txt`
- readme.txt: 포함 (sha256 `a842f31b0e805e36b37931250166964ce0aa08618b34baf8e879ebe7caf3a59f`)
- 배포 API 원본: <https://dsclub.kr/api/t2editor/version/index.php?action=download&version=7.0.2&file=0>

### 배포 설명

```text
순차 css로드 기능에 오류가 발생하여 ios환경을 제외한 안드로이드 및 윈도우, 리눅스 브라우저에서 스타일이 적용되지 않던 문제를 해결하였습니다.
(t2editor/editor.lib.php) ​
```
