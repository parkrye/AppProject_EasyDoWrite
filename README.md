# EasyDoWrite

인터넷 권한 없는 안드로이드 연재 소설 집필 앱. 원고(화 · 부 · 외전) · 설정 위키 · 아이디어 메모 · 글자 수 목표를 한 앱에서 관리하고, 데이터는 기기 밖으로 나가지 않음. EasyDo 시리즈.

## 다운로드

최신 버전 0.2.0 — [Releases 페이지](https://github.com/parkrye/AppProject_EasyDoWrite/releases)에서 `EasyDoWrite-<버전>.apk`를 받아 설치. Android 8.0 이상.

- 처음 설치 시 "출처를 알 수 없는 앱" 설치 허용 필요. Play 프로텍트가 검사 화면을 띄울 수 있음
- 업데이트는 새 APK를 같은 방식으로 덮어 설치. 원고 · 설정 유지
- 앱 안 `설정 → 앱 정보 → 새 버전 받기`로 Releases 페이지를 열 수 있음 (자동 업데이트 알림은 없음)
- 서명 인증서 SHA-256: `361872d81583c7f72c743d20ca6bb6e3c8705d442194282a421ba2499d3f08b6`
  (`apksigner verify --print-certs EasyDoWrite-<버전>.apk`로 확인. APK SHA-256은 각 Release 본문에 기재)
- 버그 · 제안은 [Issues](https://github.com/parkrye/AppProject_EasyDoWrite/issues)에

## 기능

| 영역 | 내용 |
|---|---|
| 작품 | 상태 · 소개 · 목표 글자 수(작품 · 화당 · 하루) · 날짜별 작성 기록 |
| 원고 | 부 · 외전 묶음, 화 유형(프롤로그 · 본편 · 에필로그 · 후기 · 공지), 묶음별 화수, 끌어서 정렬, 자동 저장, 이전 판 |
| 원고 주석 | 화 메모 · 구간 각주(본문과 분리 저장) |
| 위키 | 분류별 문서, `[[문서]]` 링크 · 역링크, 이미지, 메모 · 각주, 연표, 세계관 공유 |
| 아이디어 메모 | 태그 · 고정 · 작품 지정, 위키 문서 · 새 화로 옮기기 |
| 읽기 모드 | 연속 스크롤 · 쪽 넘김, 글꼴 · 크기 · 줄 간격 · 배경, 이어 읽기 |
| 기타 | 검색 · 원고 모두 바꾸기, 휴지통(30일), txt 내보내기 |
| 설정 | 글자 수에 공백 포함 / `데이터`(백업 만들기 · 백업에서 복원(zip, 복원 전 확인) · 휴지통) / `앱 정보` |
| 앱 정보 | 앱 이름 · 버전 · 개인정보 · 저작권 · 새 버전 받기 · 오픈소스 라이선스 |

## 개인정보

인터넷 권한 없음 · 광고 없음 · 수집 · 전송 없음.

- 계정 · 광고 · 사용 통계 · 오류 보고 없음
- 원고 · 위키 · 메모 · 이미지는 기기 안에만 저장. 앱 삭제 시 함께 삭제 (앱 안 백업으로 보관)
- 백업 파일 · txt는 사용자가 고른 위치에만 저장. 기기를 바꿀 때는 백업 파일을 옮겨 복원

## EasyDo 시리즈

| 앱 | 용도 | 플랫폼 |
|---|---|---|
| [EasyDoDraw](https://github.com/parkrye/MultiProject_EasyDoDraw) | 그림 · 애니메이션 | Android · Windows |
| [EasyDoWrite](https://github.com/parkrye/AppProject_EasyDoWrite) | 소설 · 글쓰기 | Android |
| [EasyDoRead](https://github.com/parkrye/AppProject_EasyDoRead) | 책 · 문서 읽기 | Android |
| [EasyDoShelve](https://github.com/parkrye/AppProject_EasyDoShelve) | 웹 소설 서재 | Android |
| [EasyDoPhoto](https://github.com/parkrye/AppProject_EasyDoPhoto) | 카메라 · 사진 편집 | Android |
| [EasyDoDiet](https://github.com/parkrye/AppProject_EasyDoDiet) | 식단 · 운동 기록 | Android |
| [EasyDoZip](https://github.com/parkrye/AppProject_EasyDoZip) | 파일 · 압축 관리 | Android |
| [EasyDoGame](https://github.com/parkrye/AppProject_EasyDoGame) | 미니 게임 모음 | Android |
| [EasyDoMix](https://github.com/parkrye/AppProject_EasyDoMix) | 영상 · 오디오 편집 | Android |
| [EasyDoRecord](https://github.com/parkrye/AppProject_EasyDoRecord) | 녹음 | Android |
| [EasyDoStudio](https://github.com/parkrye/DesktopProject_EasyDoStudio) | 화면 녹화 · 영상 편집 | Windows |

## 라이선스

MIT License · © parkrye. 포함된 서드파티 라이브러리 고지는 앱 안 `설정 → 앱 정보 → 오픈소스 라이선스`에서 확인.
