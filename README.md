# BL4Mods — Liquid Effects

공개 알파 준비 중입니다. 아직 다운로드 가능한 정식 릴리즈가 없습니다.

배포 저장소: https://github.com/popcorn-kim93/BL4Mods-LiquidEffects
다운로드: https://github.com/popcorn-kim93/BL4Mods-LiquidEffects/releases
설치 방법: [INSTALL.ko.md](INSTALL.ko.md)

이 저장소는 배포 안내와 버전 정보를 관리합니다. 개발 원본은 별도 Perforce에서 관리하며
이 저장소에는 포함하지 않습니다. 실행용 Python 코드는 다운로드 패키지에 포함됩니다.

Releases에 Vortex 통합 설치용 ZIP 하나와 수동 설치용 Manual ZIP 하나를 제공합니다.
Nexus에도 동일한 파일과 체크섬을 사용합니다. Vortex 설치 검증은 아직 완료하지 않았습니다.
Vortex 1.14 이상과 BL4 확장이 필요합니다. Collections 설치는 현재 지원하지 않습니다.

현재는 Niagara CPU 시뮬레이션, 자체 C++ 충돌·이웃 계산, Niagara 메시 표시를 결합합니다.
PhysX/CUDA 및 Niagara FLIP 솔버를 사용하는 구현이 아닙니다.
피격 생성·지형 반응·표면 부착은 개발 환경에서 확인했지만,
회색 재질·고인 입자의 움직임·성능·폭발 및 블랙홀 연결은 개선 대상입니다.
0.17.1 수동 설치 패키지의 자동 시작과 피격 생성은 실제 게임 테스트로 확인했습니다.

필수 SDK: https://bl-sdk.github.io/oak2-mod-db/
공개 전 라이선스·의존성 고지 및 지원 버전 정보를 확정해야 합니다.
