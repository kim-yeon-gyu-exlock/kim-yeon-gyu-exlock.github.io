---
layout: post
title: "트랜지스터에서 웹 브라우저까지: 지오핫 글 번역: 5편"
date: 2019-09-02 15:56:00 +0900
categories: [Plans]
---

I translated the content of [this markdown](https://github.com/geohot/fromthetransistor), if you think that there's any problem with this post, such as the licensing problems, contact me to code.yeon.gyu@gmail.com, so I can help you.

#### 섹션 6: 브라우저: 온라인으로 갑시다 -- 1 주

- TCP 스택 제작(C, 500) -- 아마 커널에서 코딩될것입니다. 커널안의 이더넷 드라이버와 통합합니다. 네트워킹 시스템콜에 대한 지원을 커널에 추가합니다. (send, recv, bind, connect)
- telnetd, 멀티프로세서가 되는것의 힘(C, 50) -- 씨로 작성되어, 사용자는 텔넷을 통해 여러번 접속 할 수 있습니다. 진짜 그냥 bind shell이에요.
- 공간 절약 dyanamic linking(C, 300) -- 왜냐하면 우리는 dynamic linker가 어떻게 그저 사용자 영역 프로그램인지 설명 할 수 있기 때문입니다. 링커에 대한 수정이 필요해요.
- 웹에 대해 다룹시다(C, 500+) -- 멋있는 터미널과 ANSI를 사용한 좋은 텍스트 기반 웹브라우저를 만듭니다. 동적으로 연결되어있고 당신이 원하는 만큼 좋습니다.
