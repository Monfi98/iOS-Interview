# TCP와 UDP에 대해 설명해주세요.
## TCP(Transmission Control Protocol)
- 정확한 데이터 전송을 위한 프로토콜
- 연결형(3-way handshaking, 4-way handshaking) 일 대 일 통신
- 흐름 제어, 혼잡 제어
- 신뢰성을 보장함(데이터가 정확하게 도착하지 않았다면 재전송 요청)
- SMTP(이메일), FTP(파일 전송)

## UDP(User Datagram Protocol)
- 빠른 데이터 전송을 위한 프로토콜
- 비연결형, 일 대 일, 일 대 다, 다 대 다 통신
- 빠르지만 패킷이 손실될 수 있음
- 실시간 비디오 스트리밍, 온라인 게임


## 면접용 답변
TCP와 UDP 모두 데이터 전송을 위한 프로토콜입니다. TCP는 흐름 제어 및 혼잡 제어로 높은 신뢰성을 보장하지만 UDP보다 속도가 느리고, UDP는 신뢰성이 낮지만 TCP보다 빠르다는 특징이 있습니다. TCP는 연결 지향 방식으로, 3-way handshaking과정을 통해 연결하고 4-way handshaking을 통해 해제합니다. 반면에 UDP는 비연결형이기 때문에 연결하고 해제하는 과정이 없고 흐름 제어, 혼잡 제어와 같은 기능도 처리하지 않기 때문에 신뢰성보다는 연속성이 중요한 서비스에서 사용합니다.

## 꼬리 질문
### 3 way handshaking, 4 way handshaking을 설명해주세요.

### 흐름 제어와 혼잡 제어에 대해서 설명해주세요.