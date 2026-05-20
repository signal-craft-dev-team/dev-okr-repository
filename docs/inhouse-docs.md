# 인하우스 툴 사용 설명
- 버전 : 1.0
- 작성일 : 2026년 5월 20일
- 작성자 : 정현후
---

> 이 문서는 시그널크래프트 내부 인원이 데이터에 접근하기 위해 사용할 웹앱에 대한 사용 설명서입니다.<br>
> 추후 지속적으로 업데이트가 될 예정이며, 필요한 기능이나 수정할 기능의 경우 OKR 관리 툴에 작성부탁드립니다.<br>

[OKR 프로젝트 관리 페이지](https://github.com/orgs/signal-craft-dev-team/projects/2)

## 데이터 다운로드 방법

1. 웹앱에 접속합니다.<br>
웹앱 주소 : https://inhouse-tool-frontend-55721952249.us-central1.run.app

2. 왼쪽 사이드바에서 "데이터 다운로드" 를 선택합니다.

3. 페이지 호출시 아래 그림처럼 "고객사" 목록이 보여집니다.
<picture>
    <source media="(prefers-color-scheme: dark)" srcset="./images/1_customer.png">
    <img src="./images/1_customer.png" alt="고객사">
</picture>
<br><br>
4. 고객사를 선택하면 고객사에 설치된 "서버" 목록이 보여집니다.
<picture>
    <source media="(prefers-color-scheme: dark)" srcset="./images/2_server.png">
    <img src="./images/2_server.png" alt="서버">
</picture>
<br><br>
5. 서버를 선택하면 수집한 날짜와 데이터 양이 보여지는 "날짜" 달력이 보여집니다.
<picture>
    <source media="(prefers-color-scheme: dark)" srcset="./images/3_calander.png">
    <img src="./images/3_calander.png" alt="날짜">
</picture>
<br><br>
6. "날짜" 달력이 보여진 이후, 원하는 "날짜"를 선택하면 하단에 다운로드 형식을 선택할 수 있는 창이 보여집니다.
<picture>
    <source media="(prefers-color-scheme: dark)" srcset="./images/4_select.png">
    <img src="./images/4_select.png" alt="다운로드선택">
</picture>
<br><br>
7. "다운로드" 시에는 하루치의 전체 데이터, 혹은 특정 센서에서만 수집된 데이터를 선택해서 다운로드 받을수 있습니다.<br>
"ZIP 다운로드" 버튼을 누르면 오디오 데이터에 대한 편집(센서별로 자르기)이 백엔드 서버에서 진행됩니다.<br>
잠시 후 기다리면 자동으로 압축파일이 로컬 컴퓨터로 다운로드됩니다.<br>
<picture>
    <source media="(prefers-color-scheme: dark)" srcset="./images/5_download.png">
    <img src="./images/5_download.png" alt="다운로드과정">
</picture>
<br><br>

## 주의사항
- 작성일 기준 현재 PoC 단계에서의 데이터 스펙은 다음과 같습니다.
> [!IMPORTANT]
> 샘플레이트 : 32kHz<br>
> 비트뎁스 : 16bit<br>
> 센서1개당 오디오 길이 : 10초<br>
> 수집 간격 : 20초에 1번(1분에 총 3개의 오디오 파일을 수집)<br>

- 용량이 클 경우 다운로드 속도는 느릴수 있습니다. 페이지에서 벗어나지 말고 켜둔 상태를 유지해주시길 바랍니다.

