#                             n n  cc      # 👋 Hi, I’m @DrBAE Ph.D.
- 이 문서의 원본 주소는 [여기(https://github.com/drbae)](https://github.com/drbae)입니다.

#### Ph.D. -  [`QuantumOptics`](https://ko.wikipedia.org/wiki/%EC%96%91%EC%9E%90%EA%B4%91%ED%95%99)
<!-- - [x] 2012년 전남대학교 물리학과에서 [`QuantumOptics`](https://ko.wikipedia.org/wiki/%EC%96%91%EC%9E%90%EA%B4%91%ED%95%99) 전공으로 박사학위를 취득하였다. -->
- [ ] In 2012, I obtained a Ph.D. in [`QuantumOptics`](https://en.wikipedia.org/wiki/Quantum_optics) with a major in Physics from Chonnam National University.

<!-- #### 2022~2024  제이디텍(주) `SW개발팀장`으로 근무 -->
#### 2022~2024 Worked as SW Development Team Leader at JD Tech Co., Ltd.
- [x] 모든 프로젝트에 사용되는 베이스 VS 솔루션 템플릿, 로그 라이브러리 등을 개발하였다.
- [ ] Developed base VS solution templates and log libraries used in all projects.
 
- [x] KETI(전자부품연구원)에 납품하는 LiDAR 평가시스템의 운용SW를 C#과 C++로 개발하였다.
 - `거리제어장비`는 회전2축 직선1축을 정밀제어하는 Motion Controll로 구현하였고
 - `각도제어장비`는 Yaw, Pitch, Roll의 정밀회전을 협동로봇(UR)을 이용하여 구현했다.
 - 각 SW의 C++용 라이브러리와 예제 프로그램을 개발 배포하였다. 

- [x] Koa Automotive(고아정공)에 납품하는 자동차용 Motor 생산 자동화 장비의 운용SW를 개발하였다.
 - `LeakTester`, `CoverAssembler` 장비는 C# WPF MVVM으로 구현하였다. 

- [x] 그 외 LG이노텍, Amkor, 삼성전자 등에 납품하는 자동화 장비의 SW를 보수, 개선 작업을 하였다.

#### 2021~2022  (주)비투팜 `스마트팜` 데이터 분석 SW 개발
- [x] 스마트팜 센서 데이터 관리 (Python/Flask/Dash) [`cams-server`](https://github.com/free302-b2f/cams-server)

#### 2008~2020까지 광통신 기업 연구소 근무
- [x] 광통신 관련 기업의 연구소에서 정밀 광학소자인 [`WDM칩`](https://ko.wikipedia.org/wiki/%ED%8C%8C%EC%9E%A5_%EB%B6%84%ED%95%A0_%EB%8B%A4%EC%A4%91)을 연구개발 하였다.
- [x] 관련 정부R&D과제 기획/관리 하였다.

- [x] WDM 칩의 성능검사장비를 개발하였다.
+ WDM 칩의 광학적 특성(투과스펙트럼)을 측정하여 파일로 저장한다.
+ 시스템은 `Mechanical Alignment Part`, `Optical Measurement Part`, `제어PC`로 구성된다.
+ `Mechanical Alignment Part`는 50nm 정밀도의 Motion 제어부와 기타 센서로 구성되며, 칩을 광원 및 계측기에 연결된 광섬유와 정렬한다.
+ `Optical Measurement Part`는 빛의 세기를 읽는 광파워미터와 가변파장의 레이저 광원(TLS)로 구성되며, 칩이 정렬된 상태에서 광투과율을 측정한다.
+ `제어PC`는 GPIB/DAQ/USB 등으로 각 장치들을 연결/제어하며 `측정제어SW`는 `C#`으로 개발하였다.

- [x] 장비 공유 서버를 제작하였다.
+ 고가의 TLS를 여러 시스템에 공유하기 위해 `TLS Server`를 개발하였다.
+ 서버와 클라이언트의 장치들은 전기적/광학적으로 연결되며 제어PC는 이더넷으로 연결된다.
+ 1개의 TLS를 2개의 클라이언트 시스템이 사용시 약간의 성능저하가 있지만, 이후 6개까지 클라이언트를 늘려도 추가 성능저하는 없었다.

- [x] 투과스펙트럼을 분석하기 위한 `wdm analyzing library`를 개발하여 데스크탑 앱과 웹서버에 사용하였다(C# & Python).
+ 라이브러리는 코드수정 없이 여러 분석알고리즘에 대응하도록 유연하게 설계하였고 수만개의 파일을 처리하는데 병렬처리 기법을 사용한다.

- [x] `데이터관리 Web서버`는 초기버전은 python과 Django기반으로 개발하였으며, 이후 `PostgreSQL` DB서버와 asp.net으로 재개발하였다.
+ 백엔드와 프런트엔드 모두에 C#이 사용가능한 [`Blazor`](https://docs.microsoft.com/en-us/aspnet/core/blazor/?view=aspnetcore-5.0) 기술을 활용하고,
+ 추후 추가되는 데이터모델을 기존코드 수정없이 런타임에 생성할 수 있도록 `OpCode Emission`기법으로 `Dynamic DB Context`를 개발하였다.

- [x] 그 외 광전변환장치(optical powermeter), 편광제어장치(polarization controller) 등 HW장비와 firmware를 개발하였다.

#### 다루는 언어와 툴:
- [x] 사용언어: C#, Python, C/C++, Java, Mathematica, Javascript, [`TeX`](https://ko.wikipedia.org/wiki/TeX)
- [x] TOOLs: Visual Studio, Notepad++, Git/Github, Mathematica, 3D Inventor, Altium Designer(전자회로설계), C2V Olympios(광도파로설계), Avr Studio

#### Getting in touch:
- [x] [:e-mail:](mailto:amadeus.bae@gmail.com) *amadeus.bae@gmail.com* [:phone: *010-9066-3569*](tel:010-9066-3569) [Slack](https://universesoft.slack.com/)

## :card_file_box: My Repositories
관리를 위해 되도록 앱(UI)과 라이브러리를 분리하였다.

#### 최근 관심분야/진행중 프로젝트 (C#/Python)
- [x] Spectrometer Measure & Analysis by Machine Learning [`ML`](https://github.com/free302/FiraAiSpecML) [`UI`](https://github.com/free302/FiraAiSpec)
 - 스펙트럼 분석을 통한 비채혈 혈당측정기 운용앱 및 ML 분석 라이브러리([`ML.NET`](https://docs.microsoft.com/ko-kr/dotnet/machine-learning/))
- [x] Coin Trading System [`UpbitTrader`](https://github.com/free302-BC/UpbitTrader)
 - Crypto-Currency 자동거래 시스템, 알고리즘 파리미터 컨트롤

#### Library Projects (C#)
- [x] TLS 공유를 위한 [`UniverseTcp`](https://github.com/free302/UniverseTcp)
 - TCP server/client library, TLS 제어 및 통신데이터 분석
- [x] 측정데이터 분석을 위한 [`UniverseWdm`](https://github.com/free302/UniverseWdm)
 - 공통 interface/자료형, 데이터 (투과스펙트럼) 분석 구현
- [x] Web application을 위한 [`WebData`](https://github.com/free302/WebData)
 - Generic model interface, dynamic db context interface & implimentation
- [x] 각종 유틸리티 클래스 모음 [`UniverseUtility`](https://github.com/free302/UniverseUtility)
 - Reflection을 이용한 설정파일관리, 설정파일내 문자열 조작&Casting 등 문자열 확장
 - 다중키 Dictionary/해쉬코드 등 자료구조, 압축, native/.net 로더 등
- [x] VS 프로젝트 버전을 자동으로 설정해주는 플러그인 [`BuildVersion`](https://github.com/free302/BuildVersion)
 - major.minor는 수동조작, 빌드 시각을 반영한 자동버전, 수동-자동 혼합 방식의 버전 관리 기능

#### Protection Tools (C#/C++)
- [x] 디컴파일 방지 native wrapping tool  [`CppWrap`](https://github.com/free302/CppWrap) (C++)
- [x] 복사 방지 툴 [`UniverseLicense`](https://github.com/free302/UniverseLicense)

#### 광특성 측정시스템 운용 관련 앱 및 웹서버
- [x] 데이터 분석/관리 Web Application [`WdmServer`](https://github.com/drbae/WdmServer) (ASP.NET Core)
- [x] 광특성 측정시스템의 서버 앱 [`TlsServer`](https://github.com/drbae/TlsServer)
- [x] 광특성 측정시스템의 클라이언트 앱 [`OdmsSw`](https://github.com/drbae/OdmsSw)
- [x] 광특성 측정시스템의 데이터분석 앱 [`WdmAnalyzer`](https://github.com/drbae/WdmAnalyzer)
- [x] WDM모듈 측정용 앱 [`Pigtail`](https://github.com/drbae/Pigtail)
- [x] `광특성 측정시스템`의 사양서 [`SpecSheet`](https://github.com/free302/SpecSheet) (Tex)

#### 기타 잡다한 것들
- [x] NavyField 게임 수병뽑기 자동화 툴 [`NFTool`](https://github.com/free302/NFTool)
- [x] 21대 총선 준연동제 국회의석수 계산기 [`Congress`](https://github.com/free302/Congress)
- [x] NTFS 파일의 alternate stream lib [`NtfsAltStream`](https://github.com/free302/NtfsAltStream)
- [x] 심전도 데이터에서 실시간 심박수 계산 및 시각화 앱 [`EcgDev`](https://github.com/free302/EcgDev)
- [ ] *금형제조업체의 금형관리 웹서버 (C# app을 activex로 변환)*
- [ ] *Android 용 연락처 관리, SMS 발송 앱 (Java)*
- [ ] *마우스 매크로를 위한 가상 마우스 드라이버 (C++)*


<!--
**drbae/drbae** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
