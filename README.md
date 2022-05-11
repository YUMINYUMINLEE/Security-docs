## 황제펭귄의 "홈페이지 제작 및 TLS를 통한 보안채널 로그인" 졸업 프로젝트

### 2022년 1학기 [캡스톤 디자인]

#### 구성원

| 팀원  | 역할                            | 책임                                                |
|------|--------------------------------|-----------------------------------------------------|
| 정경재 | 팀 리더, 보안 팀장, 백엔드 부팀장     | 프로젝트 총 책임, 백엔드 개발, TLS 보안 로그인 개발           |
| 김도현 | 팀원                            | 백엔드 개발                                            |
| 김성호 | 프론트엔드 팀장                    | 프론트엔드 개발                                         |
| 이유민 | 백엔드 팀장, 팀 부 리더             | 프로젝트 총 책임 보조 ,백엔드 개발, TLS 보안 로그인 개발        |
| 오원식 | 팀원                            | 프론트엔드 개발                                         |

## 프로젝트 소개
상명대학교 2학년 2학기의 정보보호 강의와 3학년 2학기 암호학 강의을 통해 각종 보안 매커니즘들을 학습하고 이에 대해 간단한 Take to homework을 통해 직접 보안 메커니즘들을 실습해봤지만 이러한 실습들은 최근의 동향과 조금 거리가 있었기에 현재 웹에서 가장 많이 사용하고 기본인 보안인 Https 즉 TLS통신을 직접 구현해보고 이를 바탕으로 Password 로그인과 추가로 다양한 사용자 인증(ex) 인증서로그인, 블록체인 기반 로그인 등등)을 바탕으로 안전한 상명대학교 전용 은행 웹페이지 제작을 실습 목표로 진행하는 프로젝트입니다.

### 목적
TLS구현 실습을 통해 HTTPS로 동작하는 안전한 상명대학교 전용 은행 홈페이지 제작과 안전한 보안 로그인 기능 실습.

### 기능
공통기능: 계좌조회, 타 계좌로 이체, 거래내역 조회, 공지사항, 이벤트, 인증서발급, 보안기능(해외IP차단, 추가인증수단(질문을 통한 인증 등등), 카드발급.  
개인: 금융상품(Ex) 적금, 청약통장, 투자상품 등등), 등록금 납입, 대출.  
교직원: 연구비 관리를 위해 공통기능에서 거래내역조회, 남은 연구비 조회.  

## 산출물 종류

| 산출물                    | 산출물의 내용                                                                                                                                                                |
| ------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| 회의내용                  | 회의를 진행했던 날자에 간략한 회의 내용에 대한 요약정리                                                                                                                      |
| 프로젝트 진행일지         | 프로젝트를 진행하며 진행상황에 대한 산출물로 해당 일지는 "프로젝트 준비", "프로젝트 회의", "전달사항 배포", "프로젝트 개발일지",로 구성되어있습니다.                              |
| 프로젝트 저장소 사용 규칙 | 프로젝트를 진행하면서 사용하는 저장소의 사용 규칙이나 업로드 규칙을 명시해놓은 자료입니다. 모든 commit에 대한 규칙을 정의해 놨으며 이 규칙에 따라 옳바르게 commit을 진행할 것입니다. |
| 프로젝트 개발 자료  | 프로젝트를 진행하며 참고했던 개발자료나 개발에 대한 정보를 얻었던 곳에 대한 자료들을 업로드합니다.  이 산출물은 추후 재 설계나 문제점 파악 등 다양한 문제에서 원인을 쉽게 파악하고 수정하기 위해 개발진행시 참고했던 자료들에 대한 정보를 업로드합니다. 업로드한 자료의 정보는 내부의 README.md를 생성해 올려주시길 바랍니다. | 
| 프로젝트 개발 현황  | 프로젝트를 진행하면서 현재까지 개발한 현황에 대해 쉽게 공유하기 위해 문서화 해둔 산출물입니다. |
| 프로젝트 API 문서 | 프로젝트의 Front-End 와 Back-End 사이의 Api에 대해 정리한 산출물로써 추후 RestAPI를 적용할 때 사용할 것입니다.     |

## 산출물 관리

공통 산출물은 Git hub에 저장하고 관리한다.

Repository 주소: https://github.com/SMU-Graduation-Security-Project/Security-docs

| 산출물                | 파일 명                                   | 위치               | 비고                                         |
| --------------------|----------------------------------------- | ---------------   | ---------------------------------------------|
| 회의내용              | `2022_황제펭귄_회의내용-X.X.md `          | /회의내용          | X는 월.일                                    |
| 프로젝트 진행일지       | `2022_프로젝트 진행일지(O X.X).doc/pdf `   | / 프로젝트 일지    | O는 준비, 회의, 스터디, 배포, 개발, 정리 X는 월.일   |
| 프로젝트 저장소 규칙   | `2022_프로젝트 저장소 규칙.md `           | /저장소 규칙       |                                              |
| 프로젝트 개발 자료    | `파일원본이름 또는 간략한 내용`             | /프로젝트 개발자료 | 자료의 형식은 정해지지 않았습니다.             |
| 프로젝ㅌ 개발 현황      | `2022_프로젝트 개발현황(O X.X).doc/pdf `  | /프로젝트 개발 현황    | O는 정리, X는 월.일 |
| 프로젝트 API 문서     |     `RestAPI List.xlsx`                  | /프로젝트 API 문서 |                                              |


## 팀프로젝트 협업 도구
[![Notion](https://github.com/arad4228/2021_winter/blob/main/Security_Web_Source/Notion.png)](https://www.notion.so/2022-0f0c58dd61a54d2d981d36cbb33fe80f)
</br>

## 팀프로젝트 회의 링크
[![GatherTown](https://github.com/arad4228/2021_winter/blob/main/Security_Web_Source/Gather.png)](https://gather.town/invite?token=RzRSypa-RuM7iBzwl9fsMO_vLmk2QTck)
</br>
