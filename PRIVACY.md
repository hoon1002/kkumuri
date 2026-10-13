# 꾸물이 개인정보 처리방침

시행일: 2026년 10월 11일

꾸물이는 계정을 만들지 않고, 광고·분석·추적 기능이 없습니다. 혼자 키울 때는 인터넷으로 아무것도 보내지 않습니다.

## 기기 안에만 저장하는 것
- 펫 이름, 키운 기록, 도감, 일기, 설정은 사용자의 기기 안에만 저장됩니다.
  (맥: `~/Library/Application Support/Kkumuri`, 윈도우: `%APPDATA%\Kkumuri`)
- 펫이 창 위에 올라서기 위해 열린 창의 위치와 크기만 읽고, 창의 제목이나 내용은 읽지 않습니다.
- 자리 비움과 배터리 상태는 펫의 반응을 위해 기기 안에서만 쓰고 저장하거나 보내지 않습니다.

## 친구 방을 쓸 때만 보내는 것
사용자가 친구 방에 들어갔을 때만, 같은 방의 친구에게 보여 주기 위해 아래 정보를 꾸물이 친구 방 서버를 거쳐 보냅니다.

- 사용자가 정한 표시 이름 (예: "지훈")
- 대표 펫의 모습 (종, 단계, 반짝 여부, 염색, 소품, 펫 이름)
- 상태 (접속 중, 자리 비움, 집중 중)와 맥·윈도우 구분
- 사용자가 보낸 채팅, 이모트, 쓰다듬기·간식 선물, 함께 집중 시작·멈춤
- 방 안에서 사용자를 구분하는 무작위 번호 (기기에서 만든 값이며 이름, 이메일, 기기 정보와 연결되지 않습니다)

서버는 위 정보를 방에 있는 사람에게 전달합니다. 꾸물이를 끄거나 컴퓨터가 잠들어도 방에 남아 있을 수 있도록, 방 멤버 목록(표시 이름, 대표 펫의 모습, 맥·윈도우 구분, 무작위 번호, 마지막 접속 시각)을 서버에 저장합니다. 이 기록은 사용자가 방에서 나가거나 방장이 내보내면 바로 지우고, 14일 동안 접속하지 않으면 자동으로 지웁니다.

채팅은 저장하지 않습니다. 늦게 들어온 친구를 위해 최근 대화 30개를 누군가 접속해 있는 동안 서버의 메모리에만 두고, 모두 접속을 끊으면 지웁니다. 서버는 Cloudflare Workers에서 동작하며, Cloudflare는 서비스 운영을 위해 접속 기록(IP 주소 등)을 잠시 처리할 수 있습니다. 서버는 너무 잦은 접속을 막으려고 IP 주소별 접속 횟수를 1분 동안만 세며, IP 주소를 저장하지 않습니다.

## 안전
- 거친 말은 받는 기기에서 기본으로 가려집니다 (설정에서 끌 수 있음).
- 친구를 차단하면 그 친구의 펫과 말풍선이 보이지 않습니다. 방장은 친구를 방에서 내보낼 수 있습니다.
- 대화를 신고하면 사용자의 메일 앱에 신고 내용이 채워진 메일이 열리고, 사용자가 직접 보냅니다.

## 그 밖에
- 맥 App Store판의 앱 안 구입은 Apple이 처리하며, 꾸물이는 결제 정보를 받거나 저장하지 않습니다.
- 사진·엽서 저장과 공유는 사용자가 직접 고른 곳에만 저장하고, 고른 앱으로만 보냅니다.
- 앱의 데이터를 지우면(설정의 데이터 초기화 또는 저장 폴더 삭제) 기기 안의 모든 기록이 사라집니다.

문의: hhoon1002@gmail.com

---

# Kkumuri Privacy Policy

Effective: October 11, 2026

Kkumuri has no accounts, ads, analytics, or tracking. When you play alone, it sends nothing over the internet.

## Stored only on your device
- Pet names, progress, the collection book, diary, and settings stay on your device
  (Mac: `~/Library/Application Support/Kkumuri`, Windows: `%APPDATA%\Kkumuri`).
- To let pets stand on windows, Kkumuri reads only the position and size of open windows, never their titles or contents.
- Idle time and battery status are used on your device only to make pets react, and are never stored or sent.

## Sent only when you use a Friend Room
Only while you are in a Friend Room, the following is relayed through the Kkumuri room server so that friends in the same room can see it:

- The display name you choose
- Your featured pet's appearance (species, stage, shiny, dye, accessory, pet name)
- Your status (online, away, focusing) and whether you use Mac or Windows
- Chat messages, emotes, pets/snack gifts, and shared focus start/stop that you send
- A random member ID generated on your device (not linked to your name, email, or device information)

The server forwards this to people in the room. So that you stay in the room when Kkumuri is closed or your computer sleeps, the server stores the room's member list (display name, featured pet appearance, Mac/Windows, random member ID, last seen time). This record is deleted as soon as you leave the room or the owner removes you, and automatically after 14 days without connecting.

Chat messages are not stored. The latest 30 messages are kept in memory only while someone is connected, so friends who join later can catch up, and are discarded when everyone disconnects. The server runs on Cloudflare Workers; Cloudflare may briefly process connection data (such as IP addresses) to operate the service. To block connection floods, the server counts connections per IP address over one minute; IP addresses are not stored.

## Safety
- Rude words are masked on the receiving device by default (can be turned off in Settings).
- Blocking a friend hides their pet and bubbles. The room owner can remove people from the room.
- Reporting a message opens your own mail app with the report filled in; you decide whether to send it.

## Other
- In-app purchases on the Mac App Store are processed by Apple. Kkumuri never receives or stores payment information.
- Photos and postcards are saved or shared only where you choose.
- Deleting the app's data (Settings > Reset, or removing its data folder) removes all records on your device.

Contact: hhoon1002@gmail.com
