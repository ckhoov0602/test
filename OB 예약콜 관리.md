# O/B예약콜 관리
O/B 예약콜 등록, 수정 및 삭제등 Campaign별 고객들에 대한 예약콜을 관리합니다.

## O/B 예약콜 관리 메인 화면
  * Campaign을 선택하여 예약콜 등록, 수정 및 삭제를 할 수 있습니다.
  * 예약콜명, 상세설명, 예약일시, 등록일, 등록자, 수정일, 수정자를 확인 할 수 있습니다.
  * `등록`, `수정` 및 `삭제` 버튼을 통해 예약콜을 등록, 수정 및 삭제 할 수 있습니다.
![OB예약콜 메인화면](https://user-images.githubusercontent.com/62526902/97529369-1ed5af80-19f3-11eb-9891-0e5ff4b766b8.PNG)

## O/B 예약콜 관리 등록
  * 메인 화면에 `등록` 클릭 시 예약콜을 등록 할 수 있는 팝업창이 나옵니다.
  * 등록 팝업창은 **예약콜**, **발송기간**, **발송대상**으로 나뉘어 있습니다.
  * 발송 대상은 오른쪽 상단에 `상세 검색` 클릭 시 검색 조건들이 나옵니다.
    * 상세 검색은 해당 Campaign별로 동적으로 생성이 됩니다.
  * 발송 대상 `검색` 클릭 시 발솔 대상 검색 조건에 맞는 고객 리스트가 나옵니다.
![OB예약콜 등록 상세 팝업창](https://user-images.githubusercontent.com/62526902/97530492-a02e4180-19f5-11eb-97ce-015bed3f0a32.PNG)
  * 각 필드에 내용을 입력합니다.(예약콜 / 발송 기간)
    * **예약콜 명** : 등록하려는 예약콜 명.
    * **상세 설명** : 해당 예약콜에 대한 설명.
    * **시작-종료 일자** : 예약콜을 진행하고자 하는 시작 및 종룍 기간.
    * **발송 시간** : 예약콜이 진행되는 시간.(시간: 00 ~ 23시 **1시간 단위**, 분: 00 ~ 50분 **10분단위**)
    * **요일 선택** : 예약콜이 진행되는 요일.(`주중`클릭시 **월,화,수,목,금** 선택 / `주말` 클릭 시 **토,일** 선택)
    * **시도 횟수** : 해당 회사 고객들의 예약콜 시도횟수를 선택.(0, 1, 2, 3이상 / **다중 선택 가능**)
    * **대상 상태** : 해당 회사 고객들의 상태를 선택 (미실행, 통화실패, 통화 성공/안내 실패, 통화 성공/ 안내 성공 / **다중 선택 가능**)
  * 상세 검색 조건 부분은 다를 수 있으므로 해당 필드명 조건에 맞춰서 검색하시면 됩니다. 
  * **주의 : 저장 전 발송 대상을 검색 후 저장하셔야 합니다.**
  
## O/B 예약콜 관리 수정
  * 메인 화면 리스트에서 `수정` 클릭시 해당 예약콜에 대한 수정 팝업창이 나옵니다.
  * 등록 시 입력 했던 예약콜 정보들이 나오며 수정하고자 하는 필드의 내용을 수정하시면 됩니다.
![OB예약콜 수정 상세 팝업창](https://user-images.githubusercontent.com/62526902/97533739-1afa5b00-19fc-11eb-8329-e54d7c995f51.png)

## O/B 예약콜 관리 삭제
  * 예약콜 리스트를 체크 하신 후 `삭제`클릭 시 체크된 예약콜 리스트가 삭제됩니다. (**다중 삭제 가능**)
![OB예약콜 삭제 관련 화면](https://user-images.githubusercontent.com/62526902/97534444-59dce080-19fd-11eb-9d83-6576507aec78.PNG)
  
