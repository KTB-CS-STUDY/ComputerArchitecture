컴퓨터가 이해하는 어셈블리
cpu의 내부 - ALU, cu(?), register
메모리 - 가상메모리 구조, 이동구조
시스템 버스란?

레지, 캐시메모리, 메모리, 보조기억 - 피라미드구조


2장 질문 - 워드란, floating/fixed point의 차이, 2의보수, 아스키가 1바이트인데 표현가능한수가 128인 이유(parity bit), 명령어 사이클

3장 cpu 
- 레지스터 종류 : 프로그램 카운터, 명령어 레지스터(ALU로 이동 or 작동), 범용 레지스터, 플래그 레지스터(오버플로도 감지가능), 스택포인터, 
- 인터럽트: 인터럽트 서비스 루틴(=인터럽트 핸들러) + 인터럽트 백터, 파이프라이닝
- 파이프 라이닝 실패시 발생하는것들 -> data hazard, control hazard = resource hazard

4장 메모리 (발표)
메모리의 종류, 리틀-빅 엔디안, L캐쉬 - 캐쉬 적중률 -> 참조 지역성의 원리(locality of reference, principle of locatlity) 시각 지역성 : 최근 접근했다면 또 접근(변수), 공간 지역성 : 접근한곳의 근처로 또 접근함(배열) 
캐시메모리에 쓰는법 : 즉시, 지연

5장 보조기억, 입출력
RAID(Redundant Array of Independent Disks)
