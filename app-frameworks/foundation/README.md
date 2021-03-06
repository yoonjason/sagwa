# Foundation

> 원문 출처  
> [https://developer.apple.com/documentation/foundation](https://developer.apple.com/documentation/foundation)

## 개요 <a id="overview"></a>

Foundation 프레임워크는 데이터 저장 및 지속성, 텍스트 처리, 날짜 및 시간 계산, 정렬 및 필터링, 네트워킹을 비롯한 애플리케이션과 프레임워크의 기본 기능 계층을 제공합니다. Foundation에서 정의한 클래스, 프로토콜 및 데이터 유형은 macOS, iOS, watchOS 및 tvOS SDK 전반에서 사용됩니다.

## 주제 <a id="topics"></a>

### 기초 <a id="fundamentals"></a>

* [숫자, 데이터와 기본값](numbers-data-and-basic-value.md)

  코코아 전체에서 사용되는 원시 값 및 기타 기본 타입을 사용하여 작업합니다.

* [문자열과 텍스트](strings-and-text.md)

  유니코드 문자의 문자열을 만들며 처리하고, 정규식을 사용하여 패턴을 찾고, 텍스트의 자연어 분석을 수행합니다.

* [컬렉션](collections.md)

  배열, 딕셔너리, 세트 및 특수 집합을 사용하여 체 또는 값 그룹을 저장하고 반복할 수 있습니다.

* [날짜와 시간](dates-and-times.md)

  날짜와 시간을 비교하고 달력 및 시간대 계산을 수행합니다.

* 단위와 측정

  로케일에 맞는 포맷과 연관 단위의 변환을 위해서 실제 치수를 숫자로 표현합니다.

* [데이터 포맷](data-formatting.md) 숫자와 날짜, 측정값과 기타 값을 로케일에 맞는 표현으로 변환합니다.
* 필터와 정렬

  predicates, expressions와 sort descriptors를 사용해서 컬렉션이나 다른 서비스의 요소들을 검사합니다.

### 앱 지원 <a id="app_support"></a>

* [작업 관리](task-management/)

  사용자와 시스템간 상호 작용과 앱 작업을 관리합니다.

* [리소스](resources/)

  앱에 번들되어 있는 Asset 과 기타 데이터에 액세스할 수 있습니다.

* [Notification](notification/)

  정보를 브로드캐스팅하고 받아보는 방법에 대한 디자인 패턴.

* 앱 확장 지원

  앱 확장과 호스팅 앱 간의 상호 작용을 관리합니다.

* 오류 및 예외

  API와의 상호 작용에서 문제 상황에 대응하고 더 나은 디버깅을 위해 애플리케이션을 미세 조정합니다.

* 스크립팅 지원

  사용자가 AppleScript 및 기타 자동화 기술로 프로그램을 제어하거나 앱 내에서 스크립트를 실행할 수 있도록 합니다.

### 파일 및 데이터 지속성 <a id="files_and_data_persistence"></a>

* [파일 시스템](file-system/)

  파일 시스템에서 파일 및 폴더를 생성, 읽기, 쓰기 및 검사합니다.

* 보관과 Serialization

  객체와 값을 속성 목록, JSON 및 기타 플랫 이진 표현으로 변환합니다.

* Preference

  앱을 구성하는 데 사용되는 도메인 범위의 정보를 영구적으로 저장합니다.

* Spotlight

  로컬 장치에서 파일 및 기타 항목을 검색하고 앱의 컨텐츠를 인덱싱합니다.

* iCloud

  사용자의 iCloud 장치 간에 자동으로 동기화되는 파일 및 키 값 데이터를 관리합니다.

### 네트워킹 <a id="networking"></a>

* [URL 로딩 시스템](url-loading-system/) URL과 상호 작용하고 표준 인터넷 프로토콜을 사용하여 서버와 통신합니다.
* Bonjour 로컬 네트워크 상에서 쉽게 발견할 수 있도록 서비스를 알리거나 다른 서비스를 찾습니다.

### 저레벨 유틸리티 <a id="low_level_utilities"></a>

* XPC

  보안 인터프로세스 통신을 관리합니다.

* [Object Runtime](object-runtime/)

  기본 Objective-C 기능, 코코아 디자인 패턴, 스위프트 통합에 대한 저수준 지원을 받을 수 있습니다.

* 프로세스와 스레드

  호스트 운영 체제 및 기타 프로세스와의 상호 작용을 관리하고 저수준의 동시성 기능을 구현합니다.

* 스트림, 소켓과 포트

  저수준 Unix 기능을 사용하여 파일, 프로세스 및 네트워크 간의 입력 및 출력을 관리합니다.

### 구조체 

* _struct_ NSOrderedCollectionDifferenceCalculationOptions

### 클래스

* _class_ ListFormatter `Beta`
* _class_ NSOrderedCollectionChange
* _class_ NSOrderedCollectionDifference
* _class_ RelativeDateTimeFormatter `Beta`
* _class_ NSSecureUnarchiveFromDataTransformer
* _class_ NSXPCCoder
* _class_ URLSessionWebSocketTask `Beta`
* _class_ UnitInformationStorage `Beta`

### 프로토콜

* _protocol_ ContiguousBytes
* _protocol_ DataProtocol
* _protocol_ MutableDataProtocol
* _protocol_ URLSessionWebSocketDelegate `Beta`

### 참조 <a id="reference"></a>

* 파운데이션 열거값
* 파운데이션 상수
* 파운데이션 데이터 타입 이 문서는 파운데이션 프레임워크에서 사용되는 데이터 타입과 상수를 설명합니다.

