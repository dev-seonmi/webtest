# JSP 기반 홈페이지 (프로젝트 1차)
 
>## 프로젝트 기능
___
* 공지사항 목록/생성
 
>## 추가적으로 구현할 기능
___
* 로그인
 
>## Spring DI/AOP 사용
___ 
* Controller/Service/DAO

>## 결과 및 기능 소개
| **notice** | |
|-|-|
| **- 공지사항 목록 (new는 작성일로부터 3일간 표시)** | **- 공지사항 작성 (작성자, 목록, 비밀번호)** |
| ![image00003](https://github.com/dev-seonmi/webtest/assets/120024893/07c56a98-07bc-40e3-a939-026c382c144d) | ![image00004](https://github.com/dev-seonmi/webtest/assets/120024893/1b34081e-db95-40e0-a09a-d814d50555c8) |
| **- 공지사항 글 등록 실패** | **- 공지사항 글 등록 성공** |
| ![image00005](https://github.com/dev-seonmi/webtest/assets/120024893/837fd550-837f-4f23-8323-c56814a19d7b) | ![image00006](https://github.com/dev-seonmi/webtest/assets/120024893/2c299dca-9c40-4271-8495-c42da0454cbb) |
| **- 공지사항 글 작성 후** | **- 공지사항 글 보기 (공지사항 글 내용 + 댓글 표시)** |
| ![image00007](https://github.com/dev-seonmi/webtest/assets/120024893/6e612455-9515-46f9-a29a-c410b56e992f) | ![image00008](https://github.com/dev-seonmi/webtest/assets/120024893/4e19157f-0699-45b0-9f91-8a5c2023f188) ![image00009](https://github.com/dev-seonmi/webtest/assets/120024893/8cd1c684-ac33-4eb7-8578-0b3627a6bfe6) |
| **- 댓글 입력창에 빈칸이 있는 경우** | **- 댓글 byte 크기 초과한 경우 (내용 500, 작성자 30, 비밀번호 20)** |
| ![image00010](https://github.com/dev-seonmi/webtest/assets/120024893/6cb95c04-1861-4dee-8d7d-af784d6d393e) | ![image00011](https://github.com/dev-seonmi/webtest/assets/120024893/a6dafcb3-1c47-4796-9b50-39df30928312) |
| **- 공지사항 댓글 보기 (댓글 없는 경우)** | **- 공지사항 댓글 보기 (댓글 있는 경우, new는 작성일로부터 24시간만 표시)** |
| ![image00012](https://github.com/dev-seonmi/webtest/assets/120024893/abcc7407-0955-479e-89de-aa9aa5b708e1) | ![image00013](https://github.com/dev-seonmi/webtest/assets/120024893/bf08bc55-9ecf-45c8-b339-0b2c6ec095b2) |
| **- 공지사항 댓글 삭제 (비밀번호 확인 후 삭제)** |  |
| ![image00014](https://github.com/dev-seonmi/webtest/assets/120024893/dfcee129-9776-4c7a-bf3e-63a17cbefea9) | ![image00015](https://github.com/dev-seonmi/webtest/assets/120024893/82b7aed2-10ea-4309-8387-386a8bda458d) |
| **- 공지사항 수정** |  |
| ![image00016](https://github.com/dev-seonmi/webtest/assets/120024893/b7379fd4-047c-4035-aee0-e3d84e319110) |  |
| **- 수정 실패 (패스워드 오류)** | **- 수정 성공** |
| ![image00017](https://github.com/dev-seonmi/webtest/assets/120024893/4a39fa1f-b3f3-4e98-8555-14a1adcaf5ec) | ![image00018](https://github.com/dev-seonmi/webtest/assets/120024893/ab73e095-fc4b-4d3a-8114-45826e86c80c) ![image00019](https://github.com/dev-seonmi/webtest/assets/120024893/0de81ca5-1f74-400d-88f2-c8bbab1f983a)|
| **- 공지사항 삭제 (종속된 댓글도 함께 삭제)** |  |
| ![image00020](https://github.com/dev-seonmi/webtest/assets/120024893/62c15f2a-5ac0-4145-bf9f-0a94b5285e91) |  |
| **- notice database** | **- notice_reply database** |
| ![image00001](https://github.com/dev-seonmi/webtest/assets/120024893/acad8f4e-0424-4ba6-8015-56b8369e9bed) | ![image00002](https://github.com/dev-seonmi/webtest/assets/120024893/26c0d53b-07d0-4e07-bb05-53bf19ee3bc2) |

