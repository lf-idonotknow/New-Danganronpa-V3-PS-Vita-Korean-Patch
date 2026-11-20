# 뉴 단간론파 V3 한국어 패치

《뉴 단간론파 V3 모두의 살인 신학기》 **PS Vita 일본판**의 비공식 한국어 패치입니다. 타이틀 번호는 **PCSG00936**이며, **공식 업데이트 1.03**이 설치되어 있어야 합니다.

**[0.8.0 패치 받기](https://github.com/lf-idonotknow/New-Danganronpa-V3-PS-Vita-Korean-Patch/releases/download/v0.8.0/New-Danganronpa-V3-PS-Vita-Korean-Patch-0.8.0-win-x64.zip)** · [릴리스 페이지](https://github.com/lf-idonotknow/New-Danganronpa-V3-PS-Vita-Korean-Patch/releases/tag/v0.8.0)

## 한글화 내용

- 본편과 학급재판의 대사, 선택지
- 메뉴, 전자수첩, 도움말, 재판 미니게임 문구
- 캐릭터 이름표와 일부 게임 화면 이미지의 일본어 글자

## 설치하기 전에

- **공통** · Windows 64비트 PC, 인터넷 연결, 본인이 보유한 PS Vita 일본판과 공식 업데이트 1.03이 필요합니다. PC에 **15GB 정도**, 패치를 설치할 드라이브에 **5GB 정도**의 빈 공간을 확보해 주세요.
- **PC에 설치할 구성 요소** · **Visual C++ v14 x64**를 설치하세요. 패치를 만드는 도구를 실행하는 데 필요합니다. [Microsoft 공식 설치 파일](https://aka.ms/vc14/vc_redist.x64.exe)
- **Vita3K로 플레이하시는 분** · Windows용 Vita3K를 준비하세요. 처음 사용한다면 펌웨어와 글꼴을 설치해야 합니다. [Vita3K 공식 시작 안내](https://vita3k.org/quickstart.html)
- **실제 비타로 플레이하시는 분** · 파일을 옮기는 앱 **VitaShell**, 패치를 게임에서 읽게 해 주는 **rePatch**, PC와 비타를 연결할 **데이터 전송용 USB 케이블**이 필요합니다. 암호화된 원본을 읽을 때는 **NoNpDrm**으로 만든 본인 게임의 라이선스 사본과 PC의 **Visual C++ 2012 Update 4 x64**가 필요합니다. Microsoft 다운로드 목록에서 `vcredist_x64.exe`를 고르세요. [VitaShell](https://github.com/TheOfficialFloW/VitaShell) · [rePatch](https://github.com/dots-tb/rePatch-reDux0) · [NoNpDrm](https://github.com/TheOfficialFloW/NoNpDrm) · [Microsoft 공식 다운로드](https://www.microsoft.com/en-us/download/details.aspx?id=30679)

위의 **0.8.0 패치 받기**로 ZIP을 받으세요. ZIP 파일을 마우스 오른쪽 버튼으로 누르고 **모두 압축 풀기**를 고른 뒤, 풀린 폴더에서 **DanganronpaV3KoreanPatch.exe**를 여세요. 같은 폴더에 있는 `patch-data.zip`은 그대로 두세요.

설치기는 필요한 도구를 인터넷에서 자동으로 받습니다. 암호화된 원본을 읽는 과정인 복호화도 설치기가 PC에서 처리합니다.

## Vita3K 에뮬레이터에 설치하기

1. Vita3K에 가지고 계신 **일본판 게임과 공식 업데이트 1.03**을 설치하세요.
2. Vita3K 왼쪽 위 **Open(열기) → Open Emulated Storage Path(저장 폴더 열기)**를 누릅니다. 파일 탐색기는 열어 두고 **Vita3K를 완전히 종료**하세요.
3. 패치 설치기에서 **Vita3K 에뮬레이터**를 선택하세요. **찾아보기**를 눌러 방금 연 폴더를 고릅니다. `ux0`와 `vs0`가 나란히 보이는 곳입니다.
4. **Vita3K에 설치**를 누르세요. 설치가 완료되면 Vita3K를 다시 열고 게임을 실행하세요.

## PS Vita 실기에 USB로 설치하기

1. 비타에 **일본판 게임과 공식 업데이트 1.03**을 설치하세요. rePatch와 NoNpDrm을 사용하도록 설정한 비타에서 게임을 한 번 실행한 뒤 완전히 닫으세요.
2. **VitaShell**을 열고 비타의 **START** 버튼을 누르세요. **SELECT button**은 **USB**로, **USB device**는 게임이 설치된 저장소로 고릅니다.
3. 설정을 닫고 USB 케이블로 비타와 PC를 연결하세요. VitaShell에서 **SELECT**를 누르면 PC에 USB 드라이브가 나타납니다.
4. 패치 설치기에서 **PS Vita 실기 (USB)**를 선택하고 **찾아보기**를 누르세요. 비타를 연결했을 때 새로 생긴 **USB 드라이브 자체**(예: `E:` 드라이브)를 선택한 뒤 **비타에 설치**를 누르세요. Windows 설정에 따라 그 안의 `app` 폴더는 숨겨져 있을 수 있습니다.
5. 설치가 완료되면 VitaShell의 USB 연결을 종료하고 게임을 실행하세요. 패치는 비타의 `ux0:rePatch/PCSG00936`에 들어갑니다.

### PC에서 수동 설치용 폴더 만들기

1. PC에 원본 백업을 준비하세요. 백업 폴더 바로 아래에 `app/PCSG00936`과 `patch/PCSG00936`을 함께 둡니다. 암호화된 원본이라면 비타에 있는 `nonpdrm/license/app/PCSG00936` 폴더도 같은 위치 구조로 복사하세요.
2. 설치기에서 **수동 설치용 폴더 만들기**를 고르세요. 원본 백업 폴더와 결과를 저장할 PC 폴더를 선택하고 **패치 폴더 만들기**를 누릅니다.
3. 완성된 `rePatch` 폴더를 비타의 게임 저장소 `ux0:` 첫 화면에 복사하세요. 이미 `rePatch`가 있으면 두 폴더를 합치면 됩니다.

## 설치가 안 될 때

- **패치 데이터가 없다고 하면** · 압축을 푼 폴더에 실행 파일과 `patch-data.zip`이 함께 있는지 확인하세요.
- **DLL 파일이 없다고 하면** · 위에 안내한 Visual C++ 구성 요소를 설치하거나 복구한 뒤 설치기를 다시 여세요.
- **게임을 찾지 못하면** · 일본판 `PCSG00936`에 업데이트 `1.03`이 설치되어 있는지 확인하세요. 실기에서는 VitaShell의 USB 연결과 **USB device** 설정도 확인하세요.
- **라이선스 또는 복호화 오류가 나오면** · NoNpDrm이 활성화된 비타에서 게임을 한 번 실행하세요. PC 백업을 선택했다면 `nonpdrm/license/app/PCSG00936` 폴더도 복사했는지 확인하세요. `PFS-DLL-C0000135`가 표시되면 위의 Visual C++ 2012 Update 4 x64를 설치하거나 복구하세요.

## 패치 제거

- **PS Vita 실기** · 게임을 닫은 뒤 `ux0:rePatch/PCSG00936` 폴더를 PC로 옮기면 일본어로 돌아갑니다.
- **Vita3K** · 저장 데이터를 백업한 뒤 일본판과 업데이트 1.03을 다시 설치하세요. 설치기가 교체한 파일은 Windows 탐색기에서 `%LOCALAPPDATA%\DanganronpaV3KoreanPatch`에 들어가면 확인할 수 있습니다.

## 제보

[오류·번역 제보](https://github.com/lf-idonotknow/New-Danganronpa-V3-PS-Vita-Korean-Patch/issues/new/choose)에 사용 환경, 챕터와 장면, 오류 메시지를 적어 주세요. 화면 사진을 첨부하실 수 있습니다. 게임 원본과 개인 라이선스 파일은 개인 PC에 보관해 주세요.

[단간론파 1·2 Reload 한국어 패치](https://github.com/lf-idonotknow/Danganronpa-12-Reload-PS-Vita-Korean-Patch)
