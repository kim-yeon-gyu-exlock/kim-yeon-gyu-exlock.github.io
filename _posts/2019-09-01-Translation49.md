---
layout: post
title: "트랜지스터에서 웹 브라우저까지: 지오핫 글 번역: 4편"
date: 2019-09-01 10:23:00 +0900
categories: [Plans]
---

I translated the content of [this markdown](https://github.com/geohot/fromthetransistor), if you think that there's any problem with this post, such as the licensing problems, contact me to code.yeon.gyu@gmail.com, so I can help you.

## 섹션 5: 운영체제: 우리에게 허락된 소프트웨어 -- 3 주

- MMU 만들기(Verilog, 1000) -- ARM9스타일로 TLB(변환 색인 버퍼, 가상메모리주소를 물리적 주소로 변환) 와 다른 재밌는것들을 설명합니다. Maybe also a memory controller, depending on how the FPGA is, then add the init code to your bootloader.
- 운영체제 만들기C, 2500) -- 유닉스 스타일, 사용자 영역 쓰레드만 개발합니다. (열기, 읽기, 쓰기, 닫기), (fork, execve, wait, sleep, exit), (mmap, munmap, mprotect) 등이 있겠죠. 당신이 사용하는 디버깅 인터페이스를 생각해보세요, printf의 범위부터 커널에 gdbremote stub하는것까지요. 서브챕터로 나눕니다.
- SD카드 다루기(Verilog, 150) -- 당신이 다룰 마지막 하드웨어입니다. 그리고 드라이버도요.
- FAT(C, 300) -- 제 생각에 가장 간단한 파일시스템 FAT이요.
- init, shell, download, cat, ls, rm(C, 250) -- 당신의 첫 유저영역 프로그램입니다.
