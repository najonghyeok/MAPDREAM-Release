# MAPDREAM 설치 파일

설치 파일만 올리는 곳입니다. 아래 **받기**를 누르면 바로 다운로드됩니다.

| 프로그램 | 최신 버전 | 받기 |
|---|:---:|---|
| **MAPDREAM**<br><sub>AutoCAD 2021 ~ 2027</sub> | 2026&#8209;11&#8209;10 | [⬇&nbsp;설치&nbsp;파일&nbsp;(EXE)](https://github.com/najonghyeok/MAPDREAM-Release/releases/download/mapdream-v2026.11.10/MAPDREAM_Setup_20261110.exe) · [⬇&nbsp;zip](https://github.com/najonghyeok/MAPDREAM-Release/releases/download/mapdream-v2026.11.10/MAPDREAM_20261110.zip) · [바뀐&nbsp;점](https://github.com/najonghyeok/MAPDREAM-Release/releases/tag/mapdream-v2026.11.10) |
| **MAPDREAM&nbsp;BIM**<br><sub>Revit 2024 · 2026, Navisworks Manage 2026</sub> | 2026&#8209;11&#8209;10 | [⬇&nbsp;설치&nbsp;파일&nbsp;(EXE)](https://github.com/najonghyeok/MAPDREAM-Release/releases/download/bim-v2026.11.10/MAPDREAM_BIM_Setup_20261110.exe) · [⬇&nbsp;zip](https://github.com/najonghyeok/MAPDREAM-Release/releases/download/bim-v2026.11.10/MAPDREAM_BIM_20261110.zip) · [바뀐&nbsp;점](https://github.com/najonghyeok/MAPDREAM-Release/releases/tag/bim-v2026.11.10) |

이전 버전은 [Releases](https://github.com/najonghyeok/MAPDREAM-Release/releases)에 있습니다.

## MAPDREAM (AutoCAD) 설치

AutoCAD 2027 등을 처음 설치했다면 한 번 켰다 끈 뒤에 설치하세요.

### 방법 1: 설치 파일 (EXE, 추천)

1. `MAPDREAM_Setup_날짜.exe`를 실행합니다. (관리자 권한 필요 없음)
2. 환영 화면 다음 **작업 선택** 화면에서 고릅니다.
   - **설치 / 업데이트**: 고른 AutoCAD 버전에 최신 버전을 설치합니다. 이 PC에 없는 버전은 "(설치 안 됨)", 이미 설치된 버전은 "(설치됨 → 업데이트)"로 나옵니다.
   - **제거**: MAPDREAM이 설치된 AutoCAD 버전만 보여 주고, 체크한 버전만 지웁니다. (zip으로 설치한 것도 찾아서 지움)
     모든 버전을 지울 때는 **MAPDREAM 단축키도 지우기**(기본 체크)를 고를 수 있습니다. acad.pgp에 넣은 MAPDREAM 단축키를 백업한 뒤 지워서, 가려져 있던 원래 단축키(드림, AutoCAD 기본)가 다시 쓰이게 합니다.
3. 설치는 `C:\MAPDREAM`에 되고, AutoCAD 등록(자동 로드, 신뢰 경로, 지원 경로)까지 자동으로 됩니다.
4. AutoCAD를 켜고 `MD_KEYS` → **[MAPDREAM 단축키 넣기]** 로 단축키를 넣습니다. (새 명령이 생기면 이것도 다시)

- AutoCAD가 켜져 있으면 끄라는 안내가 나옵니다. 끈 뒤 [확인]을 누르세요.
- Windows가 "PC 보호" 창을 띄우면 [추가 정보] → [실행]을 누르세요. (서명 없는 프로그램이라 나오는 안내)
- 한 번에 전부 지우려면 Windows **[설정 → 앱]** 에서 **MAPDREAM** 을 제거해도 됩니다. (단축키도 지울지 물어봅니다)

### 방법 2: zip

1. AutoCAD를 모두 닫습니다.
2. zip을 `C:` 드라이브 바로 아래에 풉니다. (예전 MAPDREAM 폴더가 있으면 덮어쓰기)
3. `MAPDREAM` 폴더의 `설치.bat`을 실행합니다.
4. AutoCAD를 켜고 `MD_KEYS` → **[MAPDREAM 단축키 넣기]** 로 단축키를 넣습니다.

- 지우려면 `제거.bat`을 실행한 뒤 폴더를 지웁니다.

명령 설명은 AutoCAD에서 `MD_HELP` 를 입력하세요.

## MAPDREAM BIM (Revit · Navisworks) 설치

### 방법 1: 설치 파일 (EXE, 추천)

1. `MAPDREAM_BIM_Setup_날짜.exe`를 실행합니다. (관리자 권한 필요 없음)
2. 처음 화면에서 **[설치 / 업데이트]** 또는 **[제거]** 를 고릅니다.
   - **설치 / 업데이트**: 설치할 프로그램(Revit 2024 / Revit 2026 / Navisworks Manage 2026)을 고릅니다. 이 PC에 없는 프로그램은 "(설치 안 됨)"으로 나오고 고를 수 없습니다. 이미 설치된 것은 "(설치됨 → 업데이트)"로 나오고 최신 버전으로 바뀝니다.
   - **제거**: 이 PC에 설치된 것만 나오고, 체크한 것만 지웁니다.
3. Revit / Navisworks를 켜면 **MAPDREAM BIM** 탭이 생깁니다.

- Revit이나 Navisworks가 켜져 있으면 끄라는 안내가 나옵니다. 끈 뒤 [확인]을 누르세요.
- Windows가 "PC 보호" 창을 띄우면 [추가 정보] → [실행]을 누르세요. (서명 없는 프로그램이라 나오는 안내)
- 한 번에 전부 지우려면 Windows **[설정 → 앱]** 에서 **MAPDREAM BIM** 을 제거해도 됩니다.

### 방법 2: zip

1. Revit, Navisworks를 모두 닫습니다.
2. zip을 아무 곳에 풉니다.
3. `MAPDREAM_BIM` 폴더의 `설치.bat`을 실행합니다. (깔린 Revit 2024 / 2026, Navisworks Manage 2026을 모두 찾아 설치)
4. Revit / Navisworks를 켜면 **MAPDREAM BIM** 탭이 생깁니다.

- 예전 이름(THUGSO)으로 설치돼 있으면 두 방법 모두 자동으로 지웁니다.

## 문제가 있을 때

**Issues** 탭에 남겨 주세요.
