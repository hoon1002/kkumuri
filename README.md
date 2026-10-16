# 꾸물이

**화면 위에 사는 작은 다마고치** — 맥 Dock과 윈도우 작업 표시줄 위에서 픽셀 펫을 키워요.

[![꾸물이 광고 영상](assets/poster.jpg)](https://hoon1002.github.io/kkumuri/#video)

- 펫 79종, 종마다 다른 성격·걸음걸이·말버릇
- 친구 방: 초대 코드 하나로 맥·윈도우 친구의 펫이 내 화면에 놀러 와요
- 스스로 크는 꾸물이(4.3): 배고프면 밥그릇에서 먹고, 심심하면 혼자 놀고, 그날 기분에 따라 가끔 고집도 부려요
- 새 놀이 냠냠 받기·잡아 봐라, 꾸미기(염색 12색), 함께 집중, 꾸물 일기

소개 페이지: https://hoon1002.github.io/kkumuri/

## 받기 (무료판 4.3.0)

| | 파일 | 필요한 것 |
| --- | --- | --- |
| 맥 | [Kkumuri-4.3.0-mac-free.zip](https://github.com/hoon1002/kkumuri/releases/download/v4.3.0/Kkumuri-4.3.0-mac-free.zip) (3MB) | macOS 14 이상 |
| 윈도우 | [Kkumuri-4.3.0-windows-free.zip](https://github.com/hoon1002/kkumuri/releases/download/v4.3.0/Kkumuri-4.3.0-windows-free.zip) (39MB) | Windows 10·11 (64비트) |

모든 판은 [Releases](https://github.com/hoon1002/kkumuri/releases)에 있어요. 무료판은 꾸미기(꾸물이 플러스)가 잠겨 있고, 매일 하나씩 무료로 써 볼 수 있어요. 게임과 79종 수집, 친구 방은 모두 무료예요.

## 처음 열 때

개인이 만든 앱이라 Apple·Microsoft 인증서가 없어서 처음 한 번 경고가 떠요.

- **맥**: ZIP을 풀고 `꾸물이.app`을 응용 프로그램 폴더로 옮겨요. 처음 열 때 "확인되지 않은 개발자" 창이 뜨면 **시스템 설정 > 개인정보 보호 및 보안** 맨 아래의 **그래도 열기**를 눌러요.
- **윈도우**: ZIP을 풀고 `Kkumuri.exe`를 실행해요. "Windows의 PC 보호" 창이 뜨면 **추가 정보 → 실행**을 눌러요.

## 받은 파일이 맞는지 확인하기

받은 ZIP의 SHA-256 지문이 아래와 같으면, 이 페이지에서 올린 파일 그대로예요. 다르면 열지 말고 지워 주세요.

```
d395c37d9836327cd816216ecf9c925570853f3a8642cb1644ddc004dd27ad97  Kkumuri-4.3.0-mac-free.zip
f73fa3fd9a10598bb1a7b8183f20af0b2d0094b575d3852f75c68d165b0ab815  Kkumuri-4.3.0-windows-free.zip
```

- 맥 터미널: `shasum -a 256 Kkumuri-4.3.0-mac-free.zip`
- 윈도우 명령 프롬프트: `certutil -hashfile Kkumuri-4.3.0-windows-free.zip SHA256`

## 개인정보

혼자 키울 때는 인터넷으로 아무것도 보내지 않아요. 친구 방에 들어갔을 때만 표시 이름, 대표 펫 모습, 채팅이 서버를 거쳐 친구에게 전해지고, 서버는 채팅을 저장하지 않아요. 광고·분석·추적은 없어요. 자세한 내용은 [개인정보 처리방침](PRIVACY.md).

## 포트폴리오

- [꾸물이 포트폴리오 (PDF, 9쪽)](assets/Kkumuri-portfolio.pdf)
- 기획·결정·실사용 테스트는 직접, 구현은 AI 코딩 에이전트(Claude Code)와 함께 했어요.

이 저장소에는 소개와 배포 파일만 있어요. 소스 코드는 비공개로 관리해요. 문의와 버그 신고는 [Issues](https://github.com/hoon1002/kkumuri/issues)에 남겨 주세요.
