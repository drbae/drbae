## 👋 Hi, I’m @DrBAE Ph.D.
- 이 문서의 원본 주소는 [여기(https://github.com/drbae)](https://github.com/drbae)입니다.

#### Ph.D. -  [`QuantumOptics`](https://ko.wikipedia.org/wiki/%EC%96%91%EC%9E%90%EA%B4%91%ED%95%99)
<!-- - [x] 2012년 전남대학교 물리학과에서 [`QuantumOptics`](https://ko.wikipedia.org/wiki/%EC%96%91%EC%9E%90%EA%B4%91%ED%95%99) 전공으로 박사학위를 취득하였다. -->
- [ ] In 2012, I obtained a Ph.D. in [`QuantumOptics`](https://en.wikipedia.org/wiki/Quantum_optics) with a major in Physics from `Chonnam National University`.

<!-- #### 2022~2024  제이디텍(주) `SW개발팀장`으로 근무
- [x] 모든 프로젝트에 사용되는 베이스 VS 솔루션 템플릿, 로그 라이브러리 등을 개발하였다. 
- [x] KETI(전자부품연구원)에 납품하는 LiDAR 평가시스템의 운용SW를 C#과 C++로 개발하였다.
 - `거리제어장비`는 회전2축 직선1축을 정밀제어하는 Motion Controll로 구현하였고
 - `각도제어장비`는 Yaw, Pitch, Roll의 정밀회전을 협동로봇(UR)을 이용하여 구현했다.
 - 각 SW의 C++용 라이브러리와 예제 프로그램을 개발 배포하였다. -->

#### 2022~2024 Worked as SW Development Team Leader at JD Tech Co., Ltd.
- [x] Developed base VS solution templates and log libraries used in all projects.
- [x] Developed the operating software for the LiDAR evaluation system delivered to KETI (Korea Electronics Technology Institute) using C# and C++.
+ The `Distance Control Equipment` was implemented with Motion Control that precisely controls 2 rotational axes and 1 linear axis.
+ The `Angle Control Equipment` was implemented using a collaborative robot (UR) for precise rotation of Yaw, Pitch, and Roll.
+ Developed and distributed C++ libraries and example programs for each software.

<!-- - [x] Koa Automotive(고아정공)에 납품하는 자동차용 Motor 생산 자동화 장비의 운용SW를 개발하였다.
 - `LeakTester`, `CoverAssembler` 장비는 C# WPF MVVM으로 구현하였다. -->
- [x] Developed the operating software for automobile motor production automation equipment delivered to Koa Automotive.
- The LeakTester and CoverAssembler equipment were implemented with C# WPF MVVM

<!-- - [x] 그 외 LG이노텍, Amkor, 삼성전자 등에 납품하는 자동화 장비의 SW를 보수, 개선 작업을 하였다. -->
- [x] Additionally, I maintained and improved the software for automation equipment delivered to companies such as LG Innotek, Amkor, and Samsung Electronics.

<!-- #### 2021~2022  (주)비투팜 `스마트팜` 데이터 분석 SW 개발
- [x] 스마트팜 센서 데이터 관리 (Python/Flask/Dash) [`cams-server`](https://github.com/free302-b2f/cams-server) -->

#### 2021~2022 Developed Smart Farm Data Analysis SW at (주)비투팜
- [x] Smart farm sensor data management (Python/Flask/Dash) [`cams-server`](https://github.com/free302-b2f/cams-server)

#### 2008~2020 Worked at a research institute of an optical communication company
- [x] Researched and developed [`WDM`](https://en.wikipedia.org/wiki/Wavelength-division_multiplexing) chips, which are precision optical components, at a research institute of an optical communication company.
- [x] Planned and managed related government R&amp;D projects.

- [x] Developed `performance inspection equipment` for WDM chips.
+ Measures the optical characteristics (transmission spectrum) of WDM chips.
+ The system consists of a `Mechanical Alignment Part`, an `Optical Measurement Part`, and a `Control PC`.
+ The `Mechanical Alignment Part` consists of a Motion control unit with 50nm precision and other sensors, and aligns the chip with optical fibers connected to the light source and measuring instruments.
+ The `Optical Measurement Part` consists of an optical power meter that reads light intensity and a tunable laser source (TLS), and measures the light transmittance while the chip is aligned.
+ The `Control PC` connects and controls each device via GPIB/DAQ/USB, and the `Measurement Control SW` was developed in `C#`.

- [x] Built an equipment sharing server.
+ Developed a `TLS Server` to share expensive TLS equipment among multiple systems.
+ The devices of the server and clients are connected electrically and optically, and the control PCs are connected via Ethernet.
+ While there was a slight performance degradation when one TLS was used by two client systems, there was no further performance degradation even when the number of clients was increased to six.

- [x] Developed a `wdm analyzing library` to analyze transmission spectra, and it was used in desktop apps and web servers (C# & Python).
+ The library was flexibly designed to support various analysis algorithms without code modification, and it uses parallel processing techniques to handle tens of thousands of files.

[x] The `Data Management Web Server` was initially developed based on Python and Django, and was later redeveloped with a `PostgreSQL DB` server and `asp.net`.
+ It utilizes [`Blazor`](https://docs.microsoft.com/en-us/aspnet/core/blazor/?view=aspnetcore-5.0) technology, which allows C# to be used for both the backend and frontend.   
+ A `Dynamic DB Context` was developed using the `OpCode Emission` technique to enable the creation of subsequently added data models at runtime without modifying existing code.

[x] Additionally, I developed HW equipment such as `optical power meters` and `polarization controllers`, as well as firmware. 

<!-- #### 2008~2020까지 광통신 기업 연구소 근무
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

- [x] 그 외 광전변환장치(optical powermeter), 편광제어장치(polarization controller) 등 HW장비와 firmware를 개발하였다. -->

#### Languages and Tools
- [x] Languages: C#, Python, C/C++, Java, Mathematica, Javascript, [`TeX`](https://ko.wikipedia.org/wiki/TeX)
- [x] Tools: Visual Studio, Notepad++, Git/Github, Mathematica, 3D Inventor, Altium Designer(전자회로설계), C2V Olympios(광도파로설계), Avr Studio

#### Getting in touch:
- [x] [:e-mail:](mailto:amadeus.bae@gmail.com) *amadeus.bae@gmail.com* [WeChat]*free302* [Slack](https://universesoft.slack.com/)

## :card_file_box: My Repositories
<!-- 관리를 위해 되도록 앱(UI)과 라이브러리를 분리하였다. -->

#### 최근 관심분야/진행중 프로젝트 (C#/Python)
- [x] Spectrometer Measure & Analysis by Machine Learning [`ML`](https://github.com/free302/FiraAiSpecML) [`UI`](https://github.com/free302/FiraAiSpec)
 + Non-invasive blood glucose measurement app and ML analysis library using spectrum analysis.([`ML.NET`](https://docs.microsoft.com/ko-kr/dotnet/machine-learning/))
- [x] Crypto-Currency Trading System [`UpbitTrader`](https://github.com/free302-BC/UpbitTrader)

#### Library Projects (C#)
<!-- - [x] 각종 유틸리티 클래스 모음 [`UniverseUtility`](https://github.com/free302/UniverseUtility)
 - Reflection을 이용한 설정파일관리, 설정파일내 문자열 조작&Casting 등 문자열 확장
 - 다중키 Dictionary/해쉬코드 등 자료구조, 압축, native/.net 로더 등
- [x] VS 프로젝트 버전을 자동으로 설정해주는 플러그인 [`BuildVersion`](https://github.com/free302/BuildVersion)
 - major.minor는 수동조작, 빌드 시각을 반영한 자동버전, 수동-자동 혼합 방식의 버전 관리 기능 -->
- [x] Collection of various utility classes  [`UniverseUtility`](https://github.com/free302/UniverseUtility)
+Configuration file management using Reflection, string extension such as string manipulation & casting within configuration files
+Data structures such as multi-key Dictionary/hash code, compression, native/.net loader, etc.
- [x] Plugin to automatically set VS project version [`BuildVersion`](https://github.com/free302/BuildVersion)
+ Manual operation for major.minor, automatic versioning reflecting build time, version management with manual-automatic mixed method
- [x] Anti-decompilation tool [`CppWrap`](https://github.com/free302/CppWrap) (C++)
- [x] Anti-piracy tool [`UniverseLicense`](https://github.com/free302/UniverseLicense)

#### 광특성 측정시스템 운용 관련 앱 및 웹서버
- [x] 데이터 분석/관리 Web Application [`WdmServer`](https://github.com/drbae/WdmServer) (ASP.NET Core)
- [x] 광특성 측정시스템의 서버 앱 [`TlsServer`](https://github.com/drbae/TlsServer)
- [x] 광특성 측정시스템의 클라이언트 앱 [`OdmsSw`](https://github.com/drbae/OdmsSw)
- [x] 광특성 측정시스템의 데이터분석 앱 [`WdmAnalyzer`](https://github.com/drbae/WdmAnalyzer)
- [x] WDM모듈 측정용 앱 [`Pigtail`](https://github.com/drbae/Pigtail)
- [x] `광특성 측정시스템`의 사양서 [`SpecSheet`](https://github.com/free302/SpecSheet) (Tex)

#### Apps and Web Servers Related to `performance inspection equipment`
- [x] Data Analysis/Management Web Application [`WdmServer`](https://github.com/drbae/WdmServer) (ASP.NET Core)
- [x] TLS Server [`TlsServer`](https://github.com/drbae/TlsServer)
- [x] Operation App [`OdmsSw`](https://github.com/drbae/OdmsSw)
- [x] Data Analysis App [`WdmAnalyzer`](https://github.com/drbae/WdmAnalyzer)
- [x] `WDM Pigtail` inspection App [`Pigtail`](https://github.com/drbae/Pigtail)
- [x] Specification Sheet [`SpecSheet`](https://github.com/free302/SpecSheet) (Tex)

#### 기타 잡다한 것들
- [x] NavyField 게임 수병뽑기 자동화 툴 [`NFTool`](https://github.com/free302/NFTool)
- [x] 21대 총선 준연동제 국회의석수 계산기 [`Congress`](https://github.com/free302/Congress)
- [x] NTFS 파일의 alternate stream lib [`NtfsAltStream`](https://github.com/free302/NtfsAltStream)
- [x] 심전도 데이터에서 실시간 심박수 계산 및 시각화 앱 [`EcgDev`](https://github.com/free302/EcgDev)
- [ ] *금형제조업체의 금형관리 웹서버 (C# app을 activex로 변환)*
- [ ] *Android 용 연락처 관리, SMS 발송 앱 (Java)*
- [ ] *마우스 매크로를 위한 가상 마우스 드라이버 (C++)*

#### Other Miscellaneous Things
- [x] NavyField game helper [`NFTool`](https://github.com/free302/NFTool)
- [x] 21st National Assembly semi-linked proportional representation seat calculator [`Congress`](https://github.com/free302/Congress)
- [x] Library for `Alternate Stream` of NTFS files [`NtfsAltStream`](https://github.com/free302/NtfsAltStream)
- [x] Real-time heart rate calculation and visualization app from ECG data [`EcgDev`](https://github.com/free302/EcgDev)
- [ ] Mold management web server for a mold manufacturing company (converting C# app to ActiveX)
- [ ] Contact management and SMS sending app for Android (Java)
- [ ] Virtual mouse driver for mouse macros (C++)


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
