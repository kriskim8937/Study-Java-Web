개발자와 관리자 입장에서 본 도커의 장점
http://www.mantech.co.kr/docker_container/

▣ 개발자와 관리자 관점에서 바라본 Docker의 장점 및 필요성

1. 개발자 관점에서 바라본 Docker의 장점
- 하나의 컨테이너는 물리 환경과 가상화 환경에서 모두 호환이 가능하므로 이식성이 매우 우수하다.
-  리눅스의 경우 다양한 배포판이 존재하는데, 개발과 운영환경의 서로 다른 리눅스 상에서도 애플리케이션 수정이 필요 없다.
-  컨테이너간은 완전 격리된 구조로 각 애플리케이션이 독립적으로 실행할 수 있어 버전 충돌이 없다.
-  개발 환경을 꾸미는데 매우 저렴한 비용과 단시간에 가능하므로 개발자가 인프라를 구성하는데 시간을 소모할 필요가 없다.

2. 관리자 관점에서 바라본 Docker의 장점

-  가상화처럼 격리된 가상서버에 별도의 OS를 구동하지 않기 때문에 오버헤드 없이 매우 경량이며, 성능이 우수하다.
-  일반적으로 CPU, 네트워크, 메모리와 디스크 I/O의 성능이 bare metal 대비 98% 이상 나온다.
-  Docker 컨테이너는 Host OS관점에서 하나의 파일로 관리가 되므로 다른 플랫폼으로의 마이그레이션과 백업 등의 관리가 매우 편리하다.
-  컨테이너를 이미지화하여 빠른 배포와 서비스 생성이 가능하며, 관리 툴과 연계하여 애플리케이션의 라이프싸이클의 자동화가 가능하다.
-  클라우드와 연계 시 무한의 확장성을 지닌 플랫폼 아키텍처 구성이 가능하다.
