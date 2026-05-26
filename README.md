# snort와 iptables를 이용한 공격자 추적 자동화 시스템 구현

### snort로 탐지 후 iptable로 차단하는 python 코드를 제작

### 구성도

<img width="938" height="298" alt="image" src="https://github.com/user-attachments/assets/eaba9102-1983-4eab-adad-6a328a1453d4" />

##### Attacker : kali-linux-2025.2-vmware
##### Firewall : ubuntu-20.04.6-desktop
##### SERVER : ubuntu-20.04.6-live-server

##### 서버에 DVWA를 설치 후 low 난이도로 공격을 시도하였다.

### 실습한 공격 종류
##### SQL injection
##### TCP SYN Flooding
##### XSS
