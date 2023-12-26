# NetworkSecurity

# 무선 보안 실습 코드

이 저장소는 무선 환경에서의 보안 실습을 위한 파이썬 코드를 포함하고 있습니다. 아래는 각각의 기능에 대한 간단한 설명과 사용법이 포함되어 있습니다.

## 1. 코드 스펙

- 작성 언어 : Python
- 테스트 환경 : Kali Linux, IPtime(N150UA2)
- 필수 사항 : 반드시 무선랜 카드가 반드시 monitor 모드를 지원해야 합니다.

## 2. 기능

**1) airodump**

무선 와이파이 정보 수집 명령어인 airodump 명령어를 파이썬 버전으로 작성하였습니다.

- [link](https://github.com/kimseongwoo61/NetworkSecurity/blob/main/airodump-main/airodump-main/README.md)

**2) Beacon Flooding Attack**

Wifi 공유기에 접속하기 위해 공유기들은 AP에게 주기적으로 Beacon Frame을 수신합니다.

위조된 Beacon Frame을 수신하여 가짜 와이파이를 생성하면서 동시에 다른 AP가 정상적으로 와이파이 접속하는 것을 방해할 수 있습니다.

- [link](https://github.com/kimseongwoo61/NetworkSecurity/tree/main/beacon-flood-main/beacon-flood-main)

**3) deauth attack**

와이파이에 접속 시도하면 연결 수락 후 본격적으로 통신을 진행하게 됩니다.

해당 공격 기법은 접속해제 통신을 수신하여 임의의 AP가 강제 접속 해제되도록 할 수 있습니다.

- [link](https://github.com/kimseongwoo61/NetworkSecurity/tree/main/deauth-attack-main/deauth-attack-main)

4**) signal strength check**

주변 와이파이 무선 신호 세기를 확인할 수 있도록 도와주는 코드입니다.

- [link](https://github.com/kimseongwoo61/NetworkSecurity/tree/main/signal-strength-main/signal-strength-main)

## 3. 주의 사항

- 본 코드를 무단으로 사용하거나 활용하여 발생하는 행위에 대해서는 일절 책임을 지지 않음을 밝힙니다.
- 해당 코드 시연은 반드시 통제된 환경(격리된 망 환경)에서 진행하시길 바랍니다.
