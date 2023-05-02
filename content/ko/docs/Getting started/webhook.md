---
title: "Webhook 연결"
linkTitle: "Webhook 연결"
weight: 6
---

## 디스코드 연결하기

DAO에서 프로포절 생성 시 Discord의 채널에 알림이 오도록 설정합니다. 이 사용법은 디스코드 웹 버전이 아닌 앱 버전을 기준으로 합니다.

1. 사용하는 디스코드 서버에서 우클릭을 하여 [서버설정-연동]으로 들어갑니다. 여기서 "웹후크만들기" 버튼을 선택합니다. (영어버전은 [Server setting-Integrations])

![](/docs/images/discord00.png)

2. 웹후크가 만들어지면 알림 메시지를 게재할 채널을 선택합니다. 이후 "웹후크 URL 복사" 버튼을 눌러 url을 복사해둡니다.

![](/docs/images/discord01.png)

3. ByFactory의 Setting 메뉴에서 Discord Webhook URL란에 생성한 url을 입력하고 연결을 해줍니다. 이후 신규 프로포절이 생성되면 연결된 디스코드 채널에 알림이 옵니다.

![](/docs/images/discord02.png)

## 슬랙 연결하기

DAO에서 프로포절 생성 시 Slack의 채널에 알림이 오도록 설정합니다.

1. [슬랙 api 페이지](https://api.slack.com/messaging/webhooks) 로 이동합니다. "Create your Slack app" 버튼을 클릭하여 앱 관리 페이지로 이동합니다.

![](/docs/images/slack00.png)

2. "Create an app" 창이 뜨면 "From scratch" 메뉴를 선택합니다. 이후 나오는 화면에서 `App Name`을 정해주시고 메시지를 받아볼 슬랙 워크스페이스를 선택합니다.

![](/docs/images/slack01.png)
![](/docs/images/slack02.png)

3. 생성한 "DAO-Webhook" 앱을 설정합니다. 여기서는 "Incoming Webhooks" 메뉴를 선택합니다.

![](/docs/images/slcak03.png)

4. Activate Incoming Webooks를 'off'에서 'on'으로 변경하고 "Add New Webhook to Workspace" 버튼을 선택합니다.

![](/docs/images/slack04.png)

5. 메시지를 받아볼 채널을 선택하고 Allow를 선택합니다. Webhook URL이 생성되었습니다. 이 주소를 카피해둡니다.

![](/docs/images/slack05.png)
![](/docs/images/slack06.png)

6. ByFactory의 Setting 메뉴에서 Slakc Webhook URL란에 생성한 url을 입력하고 연결을 해줍니다. 이후 신규 프로포절이 생성되면 연결된 슬랙채널에 알림이 옵니다.

![](/docs/images/slack07.png)