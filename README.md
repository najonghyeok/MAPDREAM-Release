# MAPDREAM 설치 파일

설치 파일만 올리는 곳입니다. 아래 **받기**를 누르면 바로 다운로드됩니다.

| 프로그램 | 대상 | 최신 버전 | 받기 |
|---|---|---|---|
| **MAPDREAM** | AutoCAD 2021 ~ 2027 | 2026-11-10 | [⬇ 설치 파일 (EXE)](https://github.com/najonghyeok/MAPDREAM-Release/releases/download/mapdream-v2026.11.10/MAPDREAM_Setup_20261110.exe) · [⬇ zip](https://github.com/najonghyeok/MAPDREAM-Release/releases/download/mapdream-v2026.11.10/MAPDREAM_20261110.zip) · [바뀐 점](https://github.com/najonghyeok/MAPDREAM-Release/releases/tag/mapdream-v2026.11.10) |
| **MAPDREAM BIM** | Revit 2024 · 2026, Navisworks Manage 2026 | 2026-11-10 | [⬇ 설치 파일 (EXE)](https://github.com/najonghyeok/MAPDREAM-Release/releases/download/bim-v2026.11.10/MAPDREAM_BIM_Setup_20261110.exe) · [⬇ zip](https://github.com/najonghyeok/MAPDREAM-Release/releases/download/bim-v2026.11.10/MAPDREAM_BIM_20261110.zip) · [바뀐 점](https://github.com/najonghyeok/MAPDREAM-Release/releases/tag/bim-v2026.11.10) |

이전 버전은 [Releases](https://github.com/najonghyeok/MAPDREAM-Release/releases)에 있습니다.

## MAPDREAM (AutoCAD) 설치

AutoCAD 2027 등을 처음 설치했다면 한 번 켰다 끈 뒤에 설치하세요.

### 방법 1: 설치 파일 (EXE, 추천)

1. `MAPDREAM_Setup_날짜.exe`를 실행합니다. (관리자 권한 필요 없음)
2. 설치할 AutoCAD 버전을 고릅니다. 이 PC에 없는 버전은 "(설치 안 됨)"으로 나오고 고를 수 없습니다.
3. [설치]를 누르면 `C:\MAPDREAM`에 설치되고 AutoCAD 등록(자동 로드, 신뢰 경로, 지원 경로)까지 자동으로 됩니다.
4. AutoCAD를 켜고 `MD_KEYS` → **[MAPDREAM 단축키 넣기]** 로 단축키를 넣습니다. (새 명령이 생기면 이것도 다시)

- AutoCAD가 켜져 있으면 끄라는 안내가 나옵니다. 끈 뒤 [확인]을 누르세요.
- Windows가 "PC 보호" 창을 띄우면 [추가 정보] → [실행]을 누르세요. (서명 없는 프로그램이라 나오는 안내)
- 지우려면 Windows **[설정 → 앱]** 에서 **MAPDREAM** 을 제거합니다.

### 방법 2: zip

1. AutoCAD를 모두 닫습니다.
2. zip을 `C:` 드라이브 바로 아래에 풉니다. (예전 MAPDREAM 폴더가 있으면 덮어쓰기)
3. `MAPDREAM` 폴더의 `설치.bat`을 실행합니다.
4. AutoCAD를 켜고 `MD_KEYS` → **[MAPDREAM 단축키 넣기]** 로 단축키를 넣습니다.

- 지우려면 `제거.bat`을 실행한 뒤 폴더를 지웁니다.

명령 설명은 AutoCAD에서 `MD_HELP` 를 입력하세요.

## MAPDREAM BIM (Revit · Navisworks) 설치

1. Revit, Navisworks를 모두 닫습니다.
2. zip을 아무 곳에 풉니다.
3. `MAPDREAM_BIM` 폴더의 `설치.bat`을 실행합니다. (깔린 Revit 2024 / 2026, Navisworks Manage 2026을 찾아 설치)
4. Revit을 켜면 **MAPDREAM BIM** 탭이 생깁니다.

## 문제가 있을 때

**Issues** 탭에 남겨 주세요.
