# infosecurity
1계층-물리계층(랜선) (HUB)=USBHUB
유선 네트워크: 이더넷 케이블(예: CAT5, CAT6), 광섬유 케이블 등이 포함됩니다.
무선 네트워크: Wi-Fi, 블루투스와 같은 무선 통신 기술이 포함됩니다.
하드웨어 장비: 네트워크 인터페이스 카드(NIC), 허브=USB허브, 스위치 등의 장비들이 물리 계층에서 작동합니다. 허브는 데이터를 물리적으로 전송하는 역할을 하지만, 데이터의 내용이나 경로를 결정하지는 않습니다.

이더넷 케이블 (Ethernet Cable)
광섬유 케이블 (Fiber Optic Cable): 빛 신호를 사용해 데이터를 매우 빠르고 먼 거리까지 전송할 수 있게 해주는 케이블입니다.
Wi-Fi: 무선으로 데이터를 전송하는 기술로, 라우터와 기기 간의 연결을 담당합니다.
Bluetooth: 근거리에서 데이터 전송을 지원하는 무선 기술입니다.
![스크린샷 2025-03-26 105417](https://github.com/user-attachments/assets/cb26b416-6c77-4922-a371-c76d08867471)

2계층-데이타 링크계층(집합계층학교라면 랜선의집합의 우송대주소='맥주소'라고한다,큰주소 MAC-(미디어 액세스 제어 주소)) SWITCH
하드웨어장비-SWITCH
데이터 링크 계층에서는 MAC 주소(미디어 액세스 제어 주소)를 사용합니다.
MAC 주소를 기반으로 데이터를 전송합니다. 
이를 통해 스위치는 데이터를 올바른 포트로 전달하여 네트워크 효율성을 높입니다.

프레임:
데이터 링크 계층은 데이터를 프레임이라는 단위로 묶어서 전송합니다. 프레임은 헤더와 트레일러를 포함하고 있으며, 그 안에 데이터를 전송할 장치의 MAC 주소를 포함합니다.

예를 들어, 출발지 MAC 주소와 목적지 MAC 주소가 포함되어, 데이터를 올바른 장치로 전달하는 데 사용됩니다.

이더넷: 가장 널리 사용되는 데이터 링크 프로토콜로, 이더넷 프레임을 사용하여 데이터를 전송합니다.

Wi-Fi: 무선 네트워크에서도 데이터 링크 계층은 MAC 주소를 사용하여 데이터를 전송하고, Wi-Fi 라우터는 MAC 주소를 통해 각 장치를 구분합니다.


3계층-network layer(ROUTER)
![스크린샷 2025-03-26 114858](https://github.com/user-attachments/assets/5a458573-a33f-4201-a240-d3a4014105e2)

![Uploading 스크린샷 2025-03-26 115109.png…]()



4계층- FTP(포트 20,21번) HTTP SMTP 라우팅프로토콜에대해


[01장_정보 보안의 세계.pptx](https://github.com/user-attachments/files/19356780/01._.pptx)
[02장_시스템 보안.pptx](https://github.com/user-attachments/files/19356784/02._.pptx)


![스크린샷 2025-03-20 101415](https://github.com/user-attachments/assets/9c9be6fa-0a85-4ca3-a70f-0785600d6f8e)
![스크린샷 2025-03-20 101659](https://github.com/user-attachments/assets/ebb39783-57a4-40e3-a79e-c2b63407db7d)
![스크린샷 2025-03-20 101717](https://github.com/user-attachments/assets/fa04fd36-f23c-4634-adad-924a33e16f08)

![스크린샷 2025-03-20 102007](https://github.com/user-attachments/assets/a7d61c60-d738-49ac-bec3-7cd9739b8b4f)


## 3장 시험많다

[03장_네트워크 보안.pptx](https://github.com/user-attachments/files/19356777/03._.pptx)


![스크린샷 2025-03-20 102524](https://github.com/user-attachments/assets/787afe65-6b2d-41bc-9dc4-82b0e3f37ab3)
![스크린샷 2025-03-20 102727](https://github.com/user-attachments/assets/d456d6a0-fd81-4d11-8e1a-efe5aa6a7bed)

MAC주소(랜카드주소)
![스크린샷 2025-03-20 103304](https://github.com/user-attachments/assets/8553d7b3-5420-4289-a838-019181f939c7)

![스크린샷 2025-03-20 104512](https://github.com/user-attachments/assets/36f6dd5e-8d13-4e99-b864-eb009f6ddf8b)
![스크린샷 2025-03-20 104611](https://github.com/user-attachments/assets/093ab03b-4f4f-4819-8f21-ddea25fefa7b)
![스크린샷 2025-03-20 104657](https://github.com/user-attachments/assets/8046b6c7-b2e6-4fa1-b82d-44031db4f0bd)
![스크린샷 2025-03-20 104743](https://github.com/user-attachments/assets/bb2537af-4e91-4338-bea8-ea1c5586301a)

2계층 맥주소=물리적주소(랜선)와 ip주소
1계층-물리적연결->랜선 UTP/FTP/STP

## ..
![스크린샷 2025-03-20 105128](https://github.com/user-attachments/assets/ab81f17a-cee1-4ecb-a020-6837e7c01ad1)
##맥주소및ip cmd명령어 ipconfig /all

### 네트워크 IP 검색 ->명령어 nslookup ~
IP 검색 방법(cmd 창에서)
 - nslookup naver.com
 - nslookup wsu.ac.kr (DNS 서버에 등록된 주소임)

(학교서버 및 naver.com 경로 파악 : tracert)
tracert naver.com(naver.com 까지 가는 경로를 볼 수 있음)
Tracert wsu.ac.kr

해당 서버의 상태 혹인 : ping
 - ping(Packet Internet Grouper)
 - ping  
    - 현재 사용중인 네트워크 상태 체크
    - 위험 노출 및 트래픽 관리차원에서 대부분 차단 
![image](https://github.com/user-attachments/assets/02d42536-5023-4a87-8d4d-b5834b684dc5)
![스크린샷 2025-03-20 110632](https://github.com/user-attachments/assets/4f44f5c3-ac43-4883-a8ad-b3641219d8c6)
### ->

##실습
![스크린샷 2025-03-20 112154](https://github.com/user-attachments/assets/eeb13d75-a590-413a-8b4a-221cf63105c1)
![스크린샷 2025-03-20 112214](https://github.com/user-attachments/assets/6b338999-9827-4de1-b9db-10028c4a04b8)

![스크린샷 2025-03-20 112400](https://github.com/user-attachments/assets/9d6ec10d-fedc-4d4d-b8bc-557e7da244e6)



##
23/
53/ 
110/
138
숙지필요
세븐레이버
![스크린샷 2025-03-20 112606](https://github.com/user-attachments/assets/fad5a1a8-5460-4ee6-979c-8ab0c0f89091)


나의 정보(네트워크계층과 전송계층정보)
![스크린샷 2025-03-20 112606](https://github.com/user-attachments/assets/0225fd98-4d39-42dd-a141-324e11e9ec6d)

![스크린샷 2025-03-20 113035](https://github.com/user-attachments/assets/c3255cf8-52d7-4c75-9315-d0ee7f1e6fb0)

## ->netstat -an or netstat -a



## 3
![스크린샷 2025-03-20 113449](https://github.com/user-attachments/assets/643acb80-b155-4073-8c18-34f992ee3adc)
![스크린샷 2025-03-20 113743](https://github.com/user-attachments/assets/22db0714-6b40-4c7f-897e-64b93e7a800d)
![스크린샷 2025-03-20 114015](https://github.com/user-attachments/assets/5076665c-7664-4462-ab28-e6574aaef2de)
3way
## 중요 7계층과 계층주소찾아가는거
![스크린샷 2025-03-20 114526](https://github.com/user-attachments/assets/73435ace-817b-434e-9557-160f4b90a971)
[Uploading 03장_네트워크 보안.pptx…]()
