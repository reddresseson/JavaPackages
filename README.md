# 프로젝트 개요 :computer:

프로그래밍 언어를 배우면서, 객체지향의 장점 중 하나로 다양한 라이브러리가 정의되어있어서 자잘한 코드는 굳이 직접 짜지 않아도 라이브러리에서 가져와서 사용할 수 있다고 배웠습니다.

그러나 막상 라이브러리를 참고하여 무언가를 사용하고자 할 때, 라이브러리가 온통 영어로 설명되어있어서 사용하기를 포기했던 경험이 한 두 번이 아닙니다.

이러한 경험을 떠올리면서, 누군가 이 페이지를 참고하여 자바 패키지를 자유자재로 사용할 수 있기를 바라며 자바 패키지 라이브러리를 번역하고자 합니다. 그뿐만 아니라 번역에 참여하는 저희도 자바를 공부하는 데 큰 도움을 얻을 수 있으리라 기대됩니다.


참조 : [API specification for the Java™ Platform](http://docs.oracle.com/javase/8/docs/api/)


***
# 패키지 설명 :pencil2:

| 패키지 이름 | 설명 |
| ------------- | ------------- |
| 박진희 | :small_red_triangle_down: |
| java.applet | 애플릿의 생성에 필요한 클래스와 애플릿이 애플릿 컨텍스트와 통신하기 위해서 사용하는 클래스를 제공합니다. |
| java.awt | 사용자 인터페이스를 작성하고 그래픽 및 이미지를 페인팅하기위한 모든 클래스를 포함합니다. |
| java.awt.color | 칼라 스페이스의 클래스를 제공합니다. |
| java.awt.datatransfer | 응용 프로그램간에 데이터를 전송하기위한 인터페이스와 클래스를 제공합니다. |
| java.awt.dnd | 드래그 앤 드롭은 많은 그래픽 사용자 인터페이스 시스템에서 발견되는 직접 조작 제스처로서 GUI의 표시 요소와 논리적으로 연관된 두 엔티티간에 정보를 전송하는 메커니즘을 제공합니다. |
| java.awt.event | AWT 컴퍼넌트에 의해 방아쇠되는 각종의 이벤트를 처리하기위한 인터페이스와 클래스를 제공합니다. |
| java.awt.font | 폰트에 관한 클래스 및 인터페이스를 제공합니다. |
| java.awt.geom | 2 차원 지오메트리에 관련한 객체에 대한 조작을 정의 및 실행하기위한 Java 2D 클래스를 제공합니다. |
| java.awt.im | 인풋 메소드 체제의 클래스 및 인터페이스를 제공합니다. |
| java.awt.im.spi | 임의의 Java 실행 환경으로 사용할 수있는 인풋 메소드의 개발을 가능하게하는 인터페이스를 제공합니다. |
| java.awt.image | 이미지의 작성 및 변경을위한 클래스를 제공합니다. |
| java.awt.image.renderable | 렌더링에 의존하지 않는 이미지를 생성하기위한 클래스 및 인터페이스를 제공합니다. |
| java.awt.print | 일반 인쇄 API 용 클래스 및 인터페이스를 제공합니다. |
| java.beans | Bean (JavaBeans ™ 아키텍처 기반의 구성 요소) 개발과 관련된 클래스가 들어 있습니다. |
| java.beans.beancontext | Bean의 문맥에 관련하는 클래스 및 인터페이스를 제공합니다. |
| java.io | 데이터 스트림, 직렬화 및 파일 시스템을 통한 시스템 입력 및 출력을 제공합니다. |
| java.lang | Java 프로그램 언어의 기본 설계 클래스를 제공합니다. |
| java.lang.annotation | Java 프로그램 언어의 주석 기능을 서포트합니다. |
| java.lang.instrument | Java 프로그래밍 언어 에이전트가 JVM에서 실행되는 프로그램을 계측 할 수있게 해주는 서비스를 제공합니다. |
| java.lang.invoke | java.lang.invoke 패키지에는, Java 코어 클래스 라이브러리 및 가상 머신이 직접 제공하는 동적 언어 지원이 포함되어 있습니다. |
| java.lang.management | Java 가상 머신 및 Java 런타임의 다른 구성 요소를 모니터링하고 관리하기위한 관리 인터페이스를 제공합니다. |
| java.lang.ref | 가비지 컬렉터와의 제한된 상호 작용을 지원하는 참조 객체 클래스를 제공합니다. |
| java.lang.reflect | 클래스 및 객체에 대한 반사 정보를 얻기위한 클래스 및 인터페이스를 제공합니다. |
| java.math | 임의 정밀도의 정수 연산 (BigInteger) 및 임의 정밀도의 10 진법 연산 (BigDecimal)을 실행하기위한 클래스를 제공합니다. |
| java.net | 네트워킹 응용 프로그램을 구현하기위한 클래스를 제공합니다. |
| java.nio | 데이터의 컨테이너 인 버퍼를 정의하고 다른 NIO 패키지의 개요를 제공합니다. |
| java.nio.channels | 파일 및 소켓과 같이 I / O 작업을 수행 할 수있는 엔터티에 대한 연결을 나타내는 채널을 정의합니다. 다중화 된 비 차단 I / O 작업을위한 선택기를 정의합니다. |
| java.nio.channels.spi | java.nio.channels 패키지의 서비스 프로 바이더 클래스. |
| java.nio.charset | 바이트와 유니 코드 문자 간 변환을위한 문자 세트, 디코더 및 인코더를 정의합니다. |
| java.nio.charset.spi | java.nio.charset 패키지의 서비스 프로 바이더 클래스. |
| java.nio.file | Java 가상 머신이 파일, 파일 속성 및 파일 시스템에 액세스 할 수 있도록 인터페이스 및 클래스를 정의합니다. |
| java.nio.file.attribute | 파일 및 파일 시스템 속성에 대한 액세스를 제공하는 인터페이스 및 클래스. |
| java.nio.file.spi | java.nio.file 패키지의 서비스 프로 바이더 클래스. |
| java.rmi |RMI 패키지를 제공합니다. |
| java.rmi.activation | RMI 객체 기동을 지원합니다. |
| java.rmi.dgc | RMI 분산 가베지 컬렉션 (DGC)의 클래스 및 인터페이스를 제공합니다. |
| java.rmi.registry | RMI 레지스트리의 클래스 및 2 개의 인터페이스를 제공합니다. |
| java.rmi.server | RMI의 서버 측을 서포트하는 클래스 및 인터페이스를 제공합니다. |
| java.security | 보안 프레임 워크의 클래스와 인터페이스를 제공합니다. |
| java.security.acl | 이 패키지의 클래스 및 인터페이스는, java.security 패키지의 클래스에 의해 옮겨 놓을 수있었습니다. |
| java.security.cert | 인증서, 인증서 해지 목록 (CRL) 및 인증서 경로를 구문 분석하고 관리하기위한 클래스와 인터페이스를 제공합니다. |
| java.security.interfaces | NIST의 FIPS-186에 정의 된대로 RSA Laboratory Technical Note PKCS # 1 및 DSA (Digital Signature Algorithm) 키에 정의 된 RSA (Rivest, Shamir 및 Adleman AsymmetricCipher 알고리즘) 키를 생성하기위한 인터페이스를 제공합니다. |
| java.security.spec | 키 사양 및 알고리즘 파라미터 사양의 클래스 및 인터페이스를 제공합니다. |
| java.sql | JavaTM 프로그램 언어를 사용해 데이터 소스 (일반적으로 관계형 데이타베이스)에 포함 된 데이터에 액세스 해 처리하는 API를 제공합니다. |
| java.text | 자연어에 관계없이 텍스트, 날짜, 숫자 및 메시지를 처리하기위한 클래스 및 인터페이스를 제공합니다. |
| java.text.spi | java.text 패키지 내의 클래스의 서비스 프로 바이더 클래스 |
| java.time | 날짜, 시간, 순간 및 기간에 대한 기본 API입니다. |
| java.time.chrono | 디폴트의 ISO 이외의 달력 시스템의 범용 API |
| java.time.format | 날짜와 시간을 인쇄하고 구문 분석하는 클래스를 제공합니다. | 
| java.time.temporal | 필드와 단위 및 날짜 시간 조정자를 사용하여 날짜와 시간에 액세스합니다. |
| java.time.zone | 시간대 및 규칙 지원.|
| 고유빈 | :small_red_triangle_down: |
| java.util | 컬렉션 프레임 워크, legacy collection classes, 이벤트 모델, 날짜 및 시간 기능, 국제화 및 기타 유틸리티 클래스를 포함한다. |
| java.util.concurrent | 유틸리티 클래스는 동시 프로그래밍에 유용하다.|
| java.util.concurrent.atomic | 단일 변수에서 잠금 없는  thread-safe programming을 지원하는 클래스의 작은 툴킷이다.|
| java.util.concurrent.locks | 내장 된 동기화 및 모니터와는 다른 조건으로 잠그고 기다리는 프레임 워크를 제공하는 인터페이스 및 클래스이다.|
| java.util.function | 함수 인터페이스는 람다 식과 메서드 참조에 대한 대상 유형을 제공한다.|
| java.util.jar | JAR (Java ARchive) 파일 형식 읽기 및 쓰기 클래스를 제공합니다. 이 형식은 표준 ZIP 파일 형식과 선택적 manifest file을 기반한다.|
| java.util.logging | JavaTM 2 플랫폼의 core logging 기능의 클래스 및 인터페이스를 제공한다.|
| java.util.prefs | 응용 프로그램에서 사용자 및 시스템 환경 설정 및 구성 데이터를 저장하고 검색 할 수 있다. |
| java.util.regex | 정규 표현식으로 지정된 패턴과 문자열을 일치시키는 클래스이다. |
| java.util.spi |  |
| java.util | 패키지의 서비스 공급자 클래스이다.|
| java.util.stream | 축소 변환과 같은 스트림 기능 스타일 작업을 지원하는 클래스이다.|
| java.util.zip | 표준 ZIP 및 GZIP 파일 형식 읽기 및 쓰기 클래스를 제공한다.|
| javax.accessibility | 사용자 인터페이스 구성 요소와 이러한 구성 요소에 대한 접근을 제공하는 보조 기술 간의 계약을 정의한다.|
| javax.activation |   |
| javax.activity | 비정렬화 중에 ORB 기계에 의한 활동 서비스 관련 예외가 포함된다.|
| javax.annotation |  |
| javax.annotation.processing | 주석 처리기를 선언하고 주석 처리기가 주석 처리 도구 환경과 통신 할 수 있게 해주는 기능을 한다.|
| javax.crypto | 암호화 조작을 위한 클래스 및 인터페이스를 제공한다.|
| javax.crypto.interfaces | RSA Laboratories의 PKCS # 3에 정의 된 Diffie-Hellman key를 위한 인터페이스를 제공한다.|
| javax.crypto.spec | key specifications 와 algorithm parameter specifications을 위한 클래스 및 인터페이스를 제공한다.|
| javax.imageio | Java Image 입출력 API의 주요 패키지이다.|
| javax.imageio.event | 이미지 읽기 및 쓰기 중 이벤트의 동기화 통지를 처리하는 Java 이미지 입출력 API 패키지이다.
| javax.imageio.metadata | 메타 데이타의 읽기 및 쓰기를 처리하는 Java Image 입출력 API 패키지이다.|
| javax.imageio.plugins.bmp | 내장 BMP 플러그 인에서 사용하는 공용 클래스가 들어있는 패키지이다.|
| javax.imageio.plugins.jpeg | 내장 된 JPEG 플러그인을 지원하는 클래스이다.|
| javax.imageio.spi | readers, Writers, 트랜스 코더, 스트림,  runtime registry를 위한 플러그 인 인터페이스를 포함한 Java 이미지 입출력 API 패키지이다.|
| javax.imageio.stream | 파일 및 스트림으로부터의 저레벨을 다루는 Java 이미지 입출력 API의 패키지이다.|
| javax.jws |  |
| javax.jws.soap |  |
| javax.lang.model | 자바 프로그래밍 언어를 모델링하는 데 사용되는 패키지의 클래스와 계층이다.|
| javax.lang.model.element | Java 프로그램 언어의 요소를 모델화하기 위해서 사용되는 인터페이스이다.| 
| javax.lang.model.type | Java 프로그래밍 언어 유형을 모델링하는 데 사용되는 인터페이스이다.|
| javax.lang.model.util | 프로그램 요소와 유형을 처리하는 데 도움이 되는 유틸리티이다.|
| javax.management | Java Management Extension의 핵심 클래스를 제공한다.|
| javax.management.loading | 진보된 동적로딩 클래스를 제공한다.|
| javax.management.modelmbean | ModelMBean 클래스의 정의를 제공한다.|
| javax.management.monitor | 모니터 클래스의 정의를 제공한다.|
| javax.management.openmbean | open data type 및 Open MBean 기술자 클래스를 제공한다.|
| javax.management.relation | 관계 서비스 정의를 제공한다.|
| javax.management.remote | JMX MBean 서버에 원격 접속하기위한 인터페이스이다.|
| javax.management.remote.rmi | RMI 연결기는 RMI를 사용하여 클라이언트 요청을 원격 MBean 서버로 전송하는 JMX 원격 API 용 커넥터이다.|
| javax.management.timer | Timer MBean의 정의를 제공한다.|
| javax.naming | naming services에 접근하기 위해 클래스 및 인터페이스를 제공한다.|
| javax.naming.directory | javax.naming 패키지를 확장하여 디렉토리 서비스 접근 기능을 제공한다.|
| javax.naming.event | 이름 지정 및 디렉토리 서비스에 접근 할 때 이벤트 알림을 지원한다.|
| javax.naming.ldap | LDAPv3 확장 작업 및 컨트롤을 지원한다.|
| javax.naming.spi |  |
| javax.net | 네트워킹 응용 프로그램을 위한 클래스를 제공한다.|
| javax.net.ssl | secure socket 패키지를 위한 클래스를 제공한다.|
| 김유리 | :small_red_triangle_down: |
| javax.print | Java Print Service API를 위한 기본 클래스와 인터페이스를 제공한다. |
| javax.print.attribute | Java Print Service에 해당하는 속성의 유형과, 속성 집합을 수집하는 방법을 설명하는 클래스와 인터페이스를 제공한다. |
| javax.print.attribute.standard | 이 패키지에는 특정 인쇄 속성에 대한 클래스가 포함되어 있다. |
| javax.print.event | 이 패키지에는 event 클래스와 listener 인터페이스가 포함되어 있다. |
| javax.rmi | 이 패키지에는 RMI-IIOP를 위한 사용자 API가 포함되어 있다. |
| javax.rmi.CORBA | 이 패키지에는 RMI-IIOP를 위한 이식성 API가 포함되어 있다. |
| javax.rmi.ssl | Secure Sockets Layer(SSL)또는 Transport Layer Security(TLS) 프로토콜을 통해 RMIClientSocketFactory 및 RMIServerSocketFactory의 구현을 제공합니다. |
| javax.script | scripting API는 Java Scripting Engines을 정의하는 인터페이스와 클래스로 구성되어있고, Java 애플리케이션에서 사용할 수 있는 프레임워크를 제공한다. |
| javax.security.auth | 이 패키지는 인증과 허가를 위한 프레임워크를 제공한다. |
| javax.security.auth.callback | 이 패키지는 정보를 검색하거나(예를 들면, 사용자 이름이나 패스워드 등의 인증 데이터) 정보를 표시하기 위해(예를 들면, 에러나 경고 메세지) 서비스가 애플리케이션과 상호 작용하는 데 필요한 클래스를 제공한다. |
| javax.security.auth.kerberos | 이 패키지는 Kerberos 네트워크 인증 프로토콜과 관련된 유틸리티 클래스를 포함한다. |
| javax.security.auth.login | 이 패키지는 플러그형 인증 프레임워크를 제공한다. |
| javax.security.auth.spi | 이 패키지는 플러그형 인증 모듈을 구현하는 데 사용할 인터페이스를 제공한다. |
| javax.security.auth.x500 | 이 패키지는 대상에 X500 Principal과 X500 Private Credentials를 저장하는 데 사용해야 하는 클래스를 포함한다. |
| javax.security.cert | public key 인증서에 대한 클래스를 제공한다. |
| javax.security.sasl | SASL을 지원하는 클래스와 인터페이스를 포함한다. |
| javax.sound.midi | 입출력, 순서화, MIDI(Musical Instrument Digital Interface)의 합성을 위한 인터페이스와 클래스를 제공한다. |
| 나은찬 | :small_red_triangle_down: |
| javax.xml |  |
| javax.xml.bind | 클라이언트 애플리케이션에 대한 런타임 바인딩 프레임워크를 제공합니다. |
| javax.xml.bind.annotation | Java프로그램 요소를 XML스키마 매핑에 사용자 정의하기 위한 주석을 정의합니다. |
| javax.xml.bind.annotation.adapters | XmlAdapter와 its sub-classes는 임의의 Java클래스를 JAXB와 함께 사용할 수 있도록 허용합니다. |
| javax.xml.bind.attachment | 이 패키지는 MIME-based 패키지 형식의 최적화된 바이너리 데이터를 해석하고 생성할 수 있는 MIME-based 패키지 프로세서를 통해 구현됩니다. |
| javax.xml.bind.helpers | JAXB 제공자 전용 사용:일부 기본 제공 인터페이스에 대해 부분적인 기본 구현을 제공합니다. |
| javax.xml.bind.util | 유용한 클라이언트 유틸리티 클래스. |
| javax.xml.crypto | XML암호화를 위한 공통 클래스. |
| javax.xml.crypto.dom | javax.xml.crypto 패키지를 위한 DOM-specific 클래스. |
| javax.xml.crypto.dsig | XML디지털 서명 생성 및 검증을 위한 클래스. |
| javax.xml.crypto.dsig.dom | javax.xml.crypto.dsig 패키지를 위한 DOM-specific 클래스. |
| javax.xml.crypto.dsig.keyinfo | 구문 분석 요소 및 구조를 구문 분석하고 처리하는 클래스. |
| javax.xml.crypto.dsig.spec | XML디지털 서명의 매개 변수 클래스. |
| javax.xml.datatype | 매핑 유형 매핑입니다. |
| javax.xml.namespace | XML네임 스페이스 처리. |
| javax.xml.parsers | XML문서를 처리할 수 있는 클래스를 제공합니다. |
| javax.xml.soap | SOAP메시지 생성 및 구축을 위한 API를 제공합니다. |
| javax.xml.stream |  |
| javax.xml.stream.events |  |
| javax.xml.stream.util |  |
| javax.xml.transform | 이 패키지는 변환 명령을 처리하기 위한 일반 API를 정의하고 소스에서 결과를 전환하는 데 사용됩니다. |
| javax.xml.transform.dom | 이 패키지는 DOM-specific 변환 API를 구현합니다. |
| javax.xml.transform.sax | 이 패키지는 SAX2-specific 변환 API를 구현합니다. |
| javax.xml.transform.stax | 멀티 테넌트(Multi-tenant)변환 API를 제공합니다. |
| javax.xml.transform.stream | 이 패키지는 스트림 및 URI-특정 변환 API를 구현합니다. |
| javax.xml.vaildation | 이 패키지는 XML문서 검증을 위한 API를 제공합니다. |
| javax.xml.ws | 이 패키지에는 핵심 JAX-WS API가 포함되어 있습니다. |
| javax.xml.ws.handler | 이 패키지는 메시지 핸들러를 위한 API를 정의합니다. |
| javax.xml.ws.handler.soap | 이 패키지는 SOAP메시지 핸들러를 위한 API를 정의합니다. |
| javax.xml.ws.http | 이 패키지는 HTTP바인딩과 관련된 API를 정의합니다. |
| javax.xml.ws.soap | 이 패키지는 SOAP바인딩과 관련된 API를 정의합니다. |
| javax.xml.ws.spi | 이 패키지는 JAX-WS에 대한 SPIs를 정의합니다. |
| javax.xml.ws.spi.http | 컨테이너에 있는 JAX-WS 웹 서비스의 휴대용 배포를 위해 사용되는 HTTPSPI를 제공합니다. |
| javax.xml.ws.wsaddressing | 이 패키지는 WS-Addressing와 관련된 API를 정의합니다. |
| javax.xml.xpath | 이 소포 XPath 식과 평가 환경에 대한 접근의 평가에 대한 대한 개체 모델 중립 API를 제공한다. |
| org.ietf.jgss | 이 패키지는 응용 프로그램 개발자가 통합 API를 사용하여 Kerberos와 같은 다양한 기본 보안 메커니즘에서 인증, 데이터 무결성 및 데이터 기밀성과 같은 보안 서비스를 사용할 수있게 해주는 프레임 워크를 제공합니다. |
| org.omg.CORBA | 프로그래머가 완전하게 기능하는 ORB (Object Request Broker)로서 사용할 수 있도록 (듯이) 구현 된 ORB 클래스를 포함한, OMG CORBA API와 JavaTM 프로그램 언어와의 매핑을 제공합니다. |
| org.omg.CORBA_2_3 | CORBA_2_3 패키지는 Java [tm] Standard Edition 6의 기존 CORBA 인터페이스에 대한 추가 사항을 정의합니다. 이러한 변경 사항은 OMG에서 정의한 CORBA API에 대한 최근 개정에서 발생했습니다. 새로운 메소드는 CORBA 패키지의 해당 인터페이스에서 파생 된 인터페이스에 추가되었습니다. 이는 이전 버전과의 호환성을 제공하고 JCK 테스트를 위반하지 않도록합니다. |
| org.omg.CORBA_2_3.portable | 값 유형의 입력 및 출력에 대한 메서드를 제공하며 org/omg/CORBA/portable 패키지에 대한 다른 업데이트를 포함합니다. |
| org.omg.CORBA.DynAnyPackage | DynAny 인터페이스에서 사용되는 예외를 제공합니다( InvalidValue, Invalid, InvalidSeq 및 TypeMismatch). |
| org.omg.CORBA.ORBPackage | ORB.resolve_initial_references 메소드에 의해 Throw되는 InvalidName 예외와 ORB 클래스의 Dynamic Any 작성 메소드에 의해 Throw되는 InconsistentTypeCode 예외를 제공합니다. |
| org.omg.CORBA.portable | 한 벤더에 의해 생성 된 코드가 다른 벤더의 ORB에서 실행될 수있게하는 이식성 레이어, 즉 ORB API 세트를 제공합니다. |
| org.omg.CORBA.TypeCodePackage | TypeCode 클래스의 메서드에 의해 Throw되는 사용자 정의 예외 BadKind 및 Bounds를 제공합니다. |
| org.omg.CosNaming | Java IDL의 네이밍 서비스를 제공합니다. |
| org.omg.CosNaming.NamingContextExtPackage | 이 패키지에는 org.omg.CosNaming.NamingContextExt로 사용되는 다음의 클래스가 포함되어 있습니다. |
| org.omg.CosNaming.NamingContextPackage | 이 패키지에는 org.omg.CosNaming 패키지의 Exception 클래스가 포함되어 있습니다. |
| org.omg.Dynamic | 이 패키지에는, OMG Portable Interceptor 스펙 (http://cgi.omg.org/cgi-bin/doc?ptc/2000-08-06, 섹션 21.9)로 지정된 Dynamic 모듈이 포함되어 있습니다. |
| org.omg.DynamicAny | 실행시에 any에 관련 지을 수 있었던 데이터 치의 traversal 및 데이터 치의 원시적 구성 요소의 추출을 가능하게하는 클래스와 인터페이스를 제공합니다. |
| org.omg.DynamicAny.DynAnyFactoryPackage | 이 패키지에는 OMG 공통 객체 요구 중개자 : Architecture and Specification (http://cgi.omg.org/cgi-bin/doc?formal/99-10)에 지정된 DynamicAny 모듈의 DynAnyFactory 인터페이스의 클래스와 예외가 포함되어 있습니다. 07, 섹션 9.2.2. |
| org.omg.DynamicAny.DynAnyPackage | 이 패키지에는, OMG로 지정된 DynamicAny 모듈의 DynAny 인터페이스로부터의 클래스와 예외가 포함되어 있습니다. Common Object Request Broker : Architecture and Specification, http://cgi.omg.org/cgi-bin/doc?formal/99-10- 07, 섹션 9.2. |
| org.omg.IOP | 이 패키지는 OMG 문서 공통 객체 요청 중개자 : 아키텍처 및 사양, http://cgi.omg.org/cgi-bin/doc?formal/99-10-07, 13.6 절에 지정된 IOP 모듈을 포함합니다. |
| org.omg.IOP.CodeFactoryPackage | 이 패키지에는, IOP :: CodeFactory 인터페이스로 지정된 예외가 포함됩니다 (Portable Interceptor 스펙의 일부로서). |
| org.omg.IOP.CodePackage | 이 패키지는, IOP :: Codec IDL 인터페이스 정의로부터 생성됩니다. |
| org.omg.Messaging | 이 패키지에는, OMG CORBA Messaging 사양, http://cgi.omg.org/cgi-bin/doc?formal/99-10-07로 지정되고있는 Messaging 모듈이 포함되어 있습니다. |
| org.omg.PortableInterceptor | ORB 서비스가 ORB의 정상적인 실행 플로우를 가로채는 ORB 훅을 등록하는 메커니즘을 제공합니다. |
| org.omg.PortableInterceptor.ORBInitInfoPackage | 이 패키지에는, OMG Portable Interceptor 스펙으로 지정된 PortableInterceptor 모듈의 ORBInitInfo 로컬 인터페이스 (http://cgi.omg.org/cgi-bin/doc?ptc/2000-08-06, 섹션 21.7.2.)의 예외 및 typedef가 포함되어 있습니다. |
| org.omg.PortableServer | 멀티 벤더 ORB간에 어플리케이션의 서버 측을 이식 가능하게하기위한 클래스와 인터페이스를 제공합니다. |
| org.omg.PortableServer.CurrentPackage | 메서드가 구현 된 개체의 ID에 액세스 할 수있는 메서드 구현을 제공합니다. |
| org.omg.PortableServer.POAManagerPackage | 관련 지을 수 있고있는 POA의 처리 상태를 캡슐화합니다. |
| org.omg.PortableServer.POAPackage | 프로그래머가 다른 ORB 제품간에 이식 가능한 객체 구현을 구성 할 수 있도록합니다. |
| org.omg.PortableServer.portable | 멀티 벤더 ORB간에 어플리케이션의 서버 측을 이식 가능하게하기위한 클래스와 인터페이스를 제공합니다. |
| org.omg.PortableServer.ServantLocatorPackage | 서번트를 검색하기위한 클래스 및 인터페이스를 제공합니다. |
| org.omg.SendingContext | 값 유형의 마샬링을 지원합니다. |
| org.omg.stub.java.rmi | java.rmi 패키지로 발생하는 리모트 타입의 RMI-IIOP Stub를 포함합니다. |
| org.w3c.dom | DOM (Document Object Model) 용 인터페이스를 제공합니다. |
| org.w3c.dom.bootstrap |  |
| org.w3c.dom.events |  |
| org.w3c.dom.ls |  |
| org.w3c.dom.views |  |
| org.xml.sax | 이 패키지는 핵심 SAX API를 제공합니다. |
| org.xml.sax.ext | 이 패키지에는 SAX 드라이버가 반드시 지원하지 않는 SAX2 기능에 대한 인터페이스가 포함되어 있습니다. |
| org.sml.sax.helpers | 이 패키지에는 SAX 기반 응용 프로그램의 부트 스트래핑을 비롯한 "도우미"클래스가 포함되어 있습니다. |