# Resume
## 1. Outline
### 1.1. Profile
이름: 남 정호

  - 생년월일: 1988-03-11
  - 연락처: 010-3627-0016
  - Github: https://github.com/samchon

### 1.2. Educations
한성대학교, 2011-03 ~ 2014-08

  - 주전공: 정보시스템공학
  - 복수전공: 경영학
  - 학점: 4.16 / 4.50
    - 비고: 조기 졸업

### 1.3. Awards
저는 취미로 개인 프로젝트를 꾸준히 하고 있으며, 오픈소스 대회에도 근근히 참여 중입니다.

  - [Samchon Simulation](#322-samchon-simulation): 한성대 공학경진대회 2012 은상
  - [Samchon Framework](#311-samchon-framework): 공개소프트웨어개발자대회 2015 일반부 동상
  - [TSTL](#312-tstl): 공개소프트웨어개발자대회 2017 일반부 은상

### 1.4. Skills
저는 C++ 과 TypeScript 를 주력으로 하였으되, 굳이 언어나 프레임워크 등에 구애받지는 않습니다.

또한, 데이터 및 아키텍처 설계를 오래도록 해 와 능숙하며, 이를 표준화하고 데에 소질이 있습니다. 그리고 알고리즘을 연구하고 개발하는 데에도 소양이 있어, 최적화도 곧잘 해내고는 합니다. 마지막으로 문서화 및 개념 정리에 숙달하여, 이를 동료 개발자에게 전파하는 것에도 나름 일가견이 있다고 자부합니다.

Skill        | Experiences | Careers | Note
-------------|-------------|---------|-----------------------------------
C++          | 12 년       | 3 년    | 최신 STL 과 Template Meta Programming 에 능함
TypeScript   | 8 년        | 4 년    | 현 한국 랭킹 1 위 (git-awards 기준)
ActionScript | 20 년       | 2 년    | Flex Architecture 를 통해 고급 설계에 입문함
DB/SQL       | 20 년       | 5 년    | ERD 설계에 능함

### 1.5. Experiences
저는 11 살에 프로그래밍에 입문한 뒤, 22 년을 쉬지 않고 꾸준히 개발에 매진해 왔습니다. 그리고 상용 경력은 2014 년에 대학교를 졸업한 이래, 만 5 년 이상을 근무하였으며, 이로써 올해로 6 년차가 되었습니다.

더불어 그간 제가 개발했던 개인 및 상용 프로젝트들에 대한 상세 내역은, 아래 [3. My Projects](#3-my-projects) 및 [4. Commercial Projects](#4-commercial-projects) 단원에 정리해두었으니, 부디 참고해주시기 바랍니다.

  - 프로그래밍 경험: 22 년
  - 총 상용 경력 63 개월
    - 정규직: 50 개월
    - 계약직: 13 개월
  - 최종 급여
    - 정규직: 1 억 원 / 1 년
    - 계약직: 8,000 만 원 / 6 개월

Company                             | Entry Date | Leave Date | Form
------------------------------------|------------|------------|-------
[스마트케어웍스](#41-smartcareworks) | 2014-10    | 2015-02    | 계약직
[유니텍 해양연구소](#42-unitech)     | 2015-05    | 2015-07    | 계약직
[히즈윌 부설연구소](#43-hiswill)     | 2015-10    | 2015-11    | 계약직
[히즈윌 부설연구소](#43-hiswill)     | 2015-11    | 2017-01    | 정규직
[아이지넷](#44-aijinet)             | 2017-01    | 2019-12    | 정규직
[아이지넷](#44-aijinet)             | 2020-01    | 2020-07    | 계약직




## 2. Introduction
### 2.1. For a lifetime


### 2.2. Self Improvement
![Github Daily Contributions](assets/images/grass.png)

### 2.3. Standard


### 2.4. Documentations





## 3. My Projects
### 3.1. Open Source Projets
#### 3.1.1. Samchon Framework
ONN (Object Oriented Network) Framework for C++ & Flex.

  - Repository: https://github.com/samchon/framework
  - Guide Documents: https://github.com/samchon/framework/wiki
  - API Documents
    - C++: http://samchon.github.io/framework/api/cpp/
    - Flex: http://samchon.github.io/framework/api/v1.0/flex/
  - Note: 공개소프트웨어개발자대회 2015 동상 수상

`samchon-framework` 는, 과거 제가 알고리즘 및 최적화에 관련된 것은 C++ 로 만들고 프론트나 데모 어플리케이션 등은 Flex 로 만들던 시절에, C++ 과 Flex 의 원활한 연동을 위해 만들었던 네트워크 프레임워크입니다.

OON (Object Oriented Network) 와 Invoke 라는 특유의 패턴을 통하여, 복잡한 네트워크 시스템도 객체적인 접근을 통하여 쉽게 풀어나갈 수 있는 것이 특징입니다. 저의 개인 프로젝트인 [3.2.2. Samchon Simulation](#322-samchon-simulation) 과, 저의 첫 상용 프로젝트의 [4.1.1. OraQ (Selene TR-1)](#411-oraq-selene-tr-1) 이, 바로 이 `samchon-framework` 를 사용해 만들어졌습니다.

다만, `samchon-framework` 의 지원 언어에 TypeScript 를 추가하고 OON (Object Oriented Network) 에 대하여 더 심도있게 연구하는 와중에, RFC (Remote Function Call) 에 대한 실마리를 찾게 되었습니다. 때문에 2018 년 말, 오래도록 개발해오던 `samchon-framework` 를 중단하고, [3.1.3. TGrid](#313-tgrid) 를 만들게 됩니다.

#### 3.1.2. TSTL
TypeScript Standard Template Library.

  - Repository: https://github.com/samchon/tstl
  - API Documents: https://tstl.dev/api
  - Note: 공개소프트웨어개발자대회 2017 은상 수상

`tstl` 은 C++ STL (Standard Template Library, C++ 표준화 위원회가 매 3 년마다 발표하는 C++ 표준 인터페이스 규약) 의 인터페이스를, TypeScript 로 구현한 프로젝트입니다. 따라서 C++ 에서 제공되는 다양한 표준 라이브러리들을, TypeScript 에서 동일하게 제공하고 있습니다.

#### 3.1.3. TGrid
TypeScript Grid Computing Framework.

  - Repository: https://github.com/samchon/tgrid
  - Guide Documents: https://tgrid.com
  - API Documents: https://tgrid.com/api
  - Key Concept: RFC (Remote Function Call)

`tgrid` 는 [3.1.2. TSTL](#312-tstl) 의 thread 및 network 에 관한 extension module 이며 동시에, TypeScript 에서 RFC (Remote Function Call) 개념을 통해, Grid Computing 을 매우 쉽게 구현할 수 있도록 도와주는 프레임워크입니다.

이 Remote Function Call 은 원격 시스템의 함수를 마치 자신의 것인양 직접 호출할 수 있다라는 의미로써, 이를 활용하면 여러 대의 컴퓨터를 네트워크 통신으로 묶어 만드는 분산처리시스템의 프로그램 코드와, 한 대의 컴퓨터로 만드는 프로그램의 비지니스 로직 코드가 모두 동일 (similar) 합니다.

#### 3.1.4. Mutex Server
Critical sections in the network level.

  - Repository: https://github.com/samchon/mutex-server
  - API Documents: https://mutex.dev/api

`mutex-server` 는 C++ STL 에서 정의한 임계영역에 관련된 컴포넌트들을, 개별 컴퓨터가 아닌 네트워크 수준에서 사용할 수 있게 해 주는, `tstl` 의 critical section 에 관련된 extension module 입니다. 따라서 `mutex-server` 를 이용하면, 뮤텍스나 세마포어 등의 임계영역 관련 컴포넌트들을, 전 네트워크 영역에서 사용할 수 있습니다.

또한, `mutex-server` 는 급작스러운 네트워크 연결 해제에 대한 안전 장치가 마련되어있습니다. 따라서 `mutex-server` 에 접속된 특정 클라이언트가 돌연 접속 종료된다하더라도, 해당 클라이언트가 취득한 모든 lock 과 시도했던 acquire 등은 모두 자동으로 반환 및 취소되기에, `mutex-server` 는 안전합니다.

#### 3.1.5. Miscellaneous
저는 [3.1.2. TSTL](#312-tstl) 과 [3.1.3. TGrid](#313-tgrid) 및 [3.1.4. Mutex Server](#314-mutex-server), 그리고 [4.3.4. 3D Bin Packing](#434-3d-bin-packing) 이외에도 다수의 오픈소스 라이브러리들을 제작, 배포한 바 있습니다. 

이들 여타 라이브러리들은 주로 저 개인의 필요에 의해 제작하였으되, [ecol](https://github.com/samchon/ecol) 이나 [sxml](https://github.com/samchon/sxml) 처럼, 저도 모르는 새애 여러 사람에 의해 근근히 쓰이는 경우도 있었습니다.

  - tiny libaries
    - [cagen](https://github.com/samchon/cagen): 경우의 수 생성기
    - [ecol](https://github.com/samchon/ecol): Event Collections
    - [sxml](https://github.com/samchon/sxml): Simple XML library
  - plugins for others libraries
    - [typeorm-model](https://github.com/samchon/typeorm-model): TypeORM 에서 Laravel 스타일의 Model 을 구현
    - [gitbook-plugin-import](https://github.com/samchon/gitbook-plugin-import): Gitbook 에서 문서 간 import 태그 구현
    - [gitbook-plugin-hide-navigation-buttons](https://github.com/samchon/gitbook-plugin-hide-navigation-buttons): 불필요한 navigation 버튼 가리기
    - [gitbook-plugin-scroll-to-top](https://github.com/samchon/gitbook-plugin-scroll-to-top): 페이지 최상위로 이동 버튼 추가
    - [typedoc-plugin-exclude-references](https://github.com/samchon/typedoc-plugin-exclude-references): TypeDoc 에서 module 모드 사용시 reference 감추기

### 3.2. Private Projects
#### 3.2.1. Hansung Timetable
Hansung Timetable simulator.

  - Manual: [assets/manuals/hansung-timetable.pdf](assets/manuals/hansung-timetable.pdf)

#### 3.2.2. Samchon Simulation
Stock Simulation & Back Testing.

  - Manual: [assets/manuals/samchon-simulation.pdf](assets/manuals/samchon-simulation.pdf)
  - Demo Application: http://samchon.org/simulation

#### 3.2.3. Nam Tree
Complicate Dicision Tree.

  - Manual: [assets/manuals/nam-tree.pdf](assets/manuals/nam-tree.pdf)
  - Demo Aplication: http://samchon.org/simulation/index.php?window=BackTesting

#### 3.2.4. Miscellaneous




## 4. Commercial Projects
### 4.1. SmartCareWorks
#### 4.1.1. OraQ (Selene TR-1)
Cloud DICOM (PACS) Media Manager.

### 4.2. Unitech
#### 4.2.1. Torpedo Simulator Communication Module
Solving mis-designed hardward by SDN (Software Defined Network).

### 4.3. Hiswill
#### 4.3.1. TSP, Construction Scheduler
TSP (Traveling Salesman Problem) 솔루션.

#### 4.3.2. Project Management Strategy
Git 및 문서 관리전략 수립.

#### 4.3.3. Order Crawler
Order Crawler from the external partner company.

#### 4.3.4. 3D Bin Packing
3-dimensional spatial layout optimization.

  - Repository: https://github.com/betterwaysystems/packer
  - Demo Site: http://betterwaysystems.github.io/packer/demo

3D Bin Packing 은 본래 회사에서 목적한 바가 있어 만들었던 상용 프로젝트였습니다 (포장물 배치 최적화). 다만 회사의 어떠한 사정으로 인해 추진하던 계획이 돌연 취소됨에 따라, 회사 이름이라도 PR 하고자 오픈소스로 공개하게 되었던, 좀 특이한 사연을 가진 프로젝트입니다.

어쨋든 저는 이 프로젝트를 개발하면서, 동시에 3D Bin Packing 에 관련된 논문들을 탐독하면서, 공간 좌표 및 배치 최적화에 관한 나름의 노하우를 익히게 됩니다. 그리고 이 때 익혔던 공간 최적화에 관한 노하우는, 추후 히즈윌의 [4.3.5. Folding](#435-folding) 과 아이지넷의 [4.4.3. Insurance Engine](#443-insurance-engine) 을 만드는 데 매우 큰 도움이 되었습니다.

#### 4.3.5. Folding
Folding and Cutting Optimization.

인쇄 회사에서 책을 만들고자 할 때, 가령 A4 용지 크기의 책을 만든다 그러면, 실제 공정에서 각 페이지는 A4 보다 훨씬 큰 종이에 인쇄됩니다. 그리고 이를 접지 후 재단 및 제본하여 책으로 만들게 됩니다. 또한, 각 페이지에 들어가는 후처리 공정에 따라, 페이지의 배치나 사용하는 용지의 크기 등이 달라지게 됩니다.

그리고 책을 대량으로 제본하는 경우, 이러한 접지 및 재단의 종류 및 배치에 따라, 그 비용이 천차만별로 달라지게 됩니다. `folding` 은 이러한 접지 및 제본에 대한 최적 해답을 구해주는 프로젝트로써, 한 마디로 요약하면, 접지계의 [4.3.4. 3D Bin Packing](#434-3d-bin-packing) 이라 할 수 있겠습니다.

#### 4.3.6. Auto HL
Un-structured Factory Automation with Network.

#### 4.3.7. Distributed Button Finder
Image Recognizer with Distributed Processing System.

#### 4.3.8. Cropper
Polyline Separator with Button Finder.

#### 4.3.9. Kiosk Editor
Kiosk Editor with Critical Sections.

### 4.4. Aijinet
#### 4.4.1. Architecture Design
#### 4.4.2. API Server
#### 4.4.3. Iusurance Engine
#### 4.4.4. Private Engine for Hana Life
#### 4.4.5. TypeScript Migration