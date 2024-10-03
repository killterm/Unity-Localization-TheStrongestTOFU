# Unity-Localization-TheStrongestTOFU

The Strongest TOFU 한국어 패치

- 게임 데이터의 저작권은 모두 개발사 혹은 배급사에 있습니다.
  - 이 패치는 개발사 혹은 배급사의 요청에 의해 언제든 삭제될 수 있습니다.
- 텍스트만 기계 번역했습니다.
  - 출발어: 일본어
- 게임 내 설정 언어: English

## 게임

- [스팀 상점 페이지](https://store.steampowered.com/app/2408680/The_Strongest_TOFU/)
- Build ID: `15882640`

## 사용법

1. [최신 Release](https://github.com/killterm/Unity-Localization-TheStrongestTOFU/releases)를 게임 설치 경로에 다운로드
2. 압축 해제
   - `${게임 경로}/tofu_Data` 디렉토리 덮어쓰기

## Checksum

아래 명령의 결과값이 `True`여야 함.

```ps1
(Get-FileHash -Algorithm MD5 "tofu_Data.zip").Hash -eq "A913F82A6F868069E7AD69B8B7820206"
```
