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
| ![image00003](https://github.com/dev-seonmi/webtest/assets/120024893/a6f74c46-33f1-4362-b5e3-77d61e84f2c4) | ![image00004](https://github.com/dev-seonmi/webtest/assets/120024893/dfa73399-fe5b-438f-a792-b91b09b650f6) |
| **- 공지사항 글 등록 실패** | **- 공지사항 글 등록 성공** |
| ![image00005](https://github.com/dev-seonmi/webtest/assets/120024893/66bb455e-0db6-47c9-ac4c-a88f01daa833) | ![image00006](https://github.com/dev-seonmi/webtest/assets/120024893/9c2258ca-1c42-4786-ac40-0913f4b5ca0b) |
| **- 공지사항 글 작성 후** | **- 공지사항 글 보기 (공지사항 글 내용 + 댓글 표시)** |
| ![image00007](https://github.com/dev-seonmi/webtest/assets/120024893/cfe2b0b9-7d5b-4a02-bbb4-c503643aac65) | ![image00008](https://github.com/dev-seonmi/webtest/assets/120024893/4aedf4f9-9858-4bdb-a5c9-2510118e7fdc)![image00009](https://github.com/dev-seonmi/webtest/assets/120024893/23f2ce6b-8bf7-42b8-b5fb-fd2a5348603e) |
| **- 댓글 입력창에 빈칸이 있는 경우** | **- 댓글 byte 크기 초과한 경우 (내용 500, 작성자 30, 비밀번호 20)** |
| ![image00010](https://github.com/dev-seonmi/webtest/assets/120024893/19a67a72-3d74-4b3c-81b3-4b6a75cb4182) | ![image00011](https://github.com/dev-seonmi/webtest/assets/120024893/e2b192df-fd68-486c-b920-46b3848c81b9) |
| **- 공지사항 댓글 보기 (댓글 없는 경우)** | **- 공지사항 댓글 보기 (댓글 있는 경우, new는 작성일로부터 24시간만 표시)** |
| ![image00012](https://github.com/dev-seonmi/webtest/assets/120024893/45cf14e4-7ba5-4ffb-8162-62bb44ace6b0) | ![image00013](https://github.com/dev-seonmi/webtest/assets/120024893/95b1222a-1ecf-400d-b9ca-7383d896a64e) |
| **- 공지사항 댓글 삭제 (비밀번호 확인 후 삭제)** |  |
| ![image00014](https://github.com/dev-seonmi/webtest/assets/120024893/49bd6f9c-f313-4f30-922c-79f77eda0479) | ![image00015](https://github.com/dev-seonmi/webtest/assets/120024893/e81fec8d-ed75-40f4-bb57-109c0bc5a1d3) |
| **- 공지사항 수정** |  |
| ![image00016](https://github.com/dev-seonmi/webtest/assets/120024893/cc1e673d-1f80-4077-80ee-22ebd84e2474) |
| **- 수정 실패 (패스워드 오류)** | **- 수정 성공** |
| ![image00017](https://github.com/dev-seonmi/webtest/assets/120024893/073d7e12-20a2-475b-adc5-41e2d1038425) | ![image00018](https://github.com/dev-seonmi/webtest/assets/120024893/f2f49650-e093-430c-ac18-8a5b424cd3db)![image00019](https://github.com/dev-seonmi/webtest/assets/120024893/0c76f6e4-1ebf-46fb-8826-a465913dedef) |
| **- 공지사항 삭제 (종속된 댓글도 함께 삭제)** |  |
| ![image00020](https://github.com/dev-seonmi/webtest/assets/120024893/8b5546c2-c170-4dd8-bf30-d4a855b782c3) |  |
| **- notice database** | **- notice_reply database** |
| ![image00001](https://github.com/dev-seonmi/webtest/assets/120024893/475980be-3826-47e5-bcc4-d72b61d6caf6) | ![image00002](https://github.com/dev-seonmi/webtest/assets/120024893/6130f664-b4b2-4a18-8d83-0970f027b483) |

