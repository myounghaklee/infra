# DevOPs

사전 세팅
- 도매인 구매
- aws root, iam계정 생성
- docker hub 가입

Life before Virtualization
- 앱, 서비스를 실행하기 위해서 우리는 서버가 필요하다.
- 하나의 서비스는 하나의 서버를 원칙으로한다.(Isolation) 만약에 여러 서비스를 한 서버에서 동작하도록 한다면 모든 달걀을 한 바구니에 담는것과 같다. 
- 서버는 항상 `overporvisioned` 해야 한다. 
- 서버 자원은 항상 조금 사용하는것이 좋다. (UnderUtilized)
- Capital expenditure과 operational expenditure는 항상 큰 차이가 있어야 한다.

Types of Hipervisor
- Type 1
    - 가상화를 위한 Os없이 물리 서버 그대로 
    - runs as a base Os
    - Production
    -vmware esxi, Xen Hypervisor

- Type 2
    - runs a software
    - for Learn and Test
    - oracle virtualbox, vmware server

