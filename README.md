<h1>📺 Network Product System</h1>

---

## 1. 개요
> NPS는 Network Production System의 약자로서 기존의 stand-alone 방식 NLE의 한계를 벗어 나 영상 인제스트, 영상 관리, 영상 편집등의 기능을 네트워크상에 하나의 시스템으로 구현하여 제작 프로세스 및 워크플로우를 개선하고 생산성을 향상시키기 위한 시스템이다.

2012년, 우리나라에서는 지상파 방송이 아날로그 TV 방송을 종료하고 디지털 방송의 새 시대를 맞이했습니다. 
이로 인해 방송 산업은 기존의 방식과는 완전히 다른 새로운 관점으로 인프라를 구축해야 했습니다. 
이를 위해 NPS(Network Production System)라는 시스템이 도입되었습니다.

NPS는 디지털 방송 환경에 맞춰 미디어 콘텐츠의 제작과 방송을 위한 네트워크 기반 시스템으로, 
방송 프로세스의 효율성을 높이고 품질을 향상시키기 위해 개발되었습니다. 
이 시스템은 고화질(HD) 및 초고화질(UHD) 콘텐츠 제작, 편집, 보관, 전송, 방송 등을 통합적으로 관리하며, 디지털 기술을 활용하여 방송 생산과정을 자동화하고 최적화합니다.
NPS를 통해 방송 산업은 기존의 아날로그 방송 방식에서 벗어나고, 디지털화된 환경에서 보다 안정적이고 효율적인 방송을 제공할 수 있게 되었습니다. 
이러한 변화는 시청자들에게 더욱 다양한 콘텐츠를 제공할 수 있는 기회를 열어주었고, 방송 산업의 경쟁력을 향상시켰습니다.

저는 이러한 디지털 방송 기술를 참고하여 NPS 토이 프로젝트를 제작하게 되었습니다.
이를 통해 저는 디지털 방송의 새로운 경험과 관점을 모색하고, 앞으로의 방송 기술 솔루션 개발에 기여하고자 합니다.

## 2. 프로젝트 서비스
> 클릭 시 해당 리포지토리 상세 내용을 보실 수 있습니다.

### [**미디어 자산 관리 시스템 ( media-asset-management )**](https://github.com/solarpark7346/media-asset-management) :
- 미디어의 수집부터 변환, 저장, 관리까지의 전체 워크플로우를 구현하는 시스템입니다.

### [**미디어 센터 ( media-center )**](https://github.com/solarpark7346/media-center) :
- 이 서비스는 영상 컨버팅을 위한 서비스로 FFmpeg'를 사용하여 다양한 형식과 포맷의 미디어를 변환하여 필요한 형태로 가공합니다.

### [**어도비 판넬 ( adobe-panel )**](https://github.com/solarpark7346/adobe-nps-panel) :
- 어도비 CEP(Common Extensibility Platform ) 프레임워크를 사용하여 개발된 웹 플러그인입니다.<br>
이를 통해 클라이언트는 어도비 소프트웨어 내에서 관리된 미디어 자산을 임포트하여 영상을 편집할 수 있습니다.

## 3. 프로젝트 기술 스택
### **>_ Client**

|                                                           React                                                           |                                                           TypeScript                                                           |                                                                              styled-components                                                                              | ... |
|:-------------------------------------------------------------------------------------------------------------------------:|:------------------------------------------------------------------------------------------------------------------------------:|:---------------------------------------------------------------------------------------------------------------------------------------------------------------------------:|:---:|
| ![react](https://github.com/solarpark7346/network-production-system/assets/61046271/34895f9a-343b-45c7-ba79-8a29ea0580f1) | ![typescript](https://github.com/solarpark7346/network-production-system/assets/61046271/0f1722b0-d7e2-493e-96bc-7bbf0567468b) | <img src="https://github.com/solarpark7346/network-production-system/assets/61046271/0630320e-d55a-400c-8093-669c7fa5c6e2" alt="styled-components" width="96" height="96"/> |     |


### **>_ Application**
> 세션 버전과 토큰 버전이 있습니다.

|                                                           java11                                                           |                                                           spring-boot                                                           |                                                           spring-security                                                           |                                                           mybatis                                                           |                                                           Gradle                                                           |                                                           JWT                                                           |                                                                              swagger                                                                              |
|:--------------------------------------------------------------------------------------------------------------------------:|:-------------------------------------------------------------------------------------------------------------------------------:|:-----------------------------------------------------------------------------------------------------------------------------------:|:---------------------------------------------------------------------------------------------------------------------------:|:--------------------------------------------------------------------------------------------------------------------------:|:-----------------------------------------------------------------------------------------------------------------------:|:-----------------------------------------------------------------------------------------------------------------------------------------------------------------:|
| ![java11](https://github.com/solarpark7346/network-production-system/assets/61046271/9cfdad43-bf72-4737-ada6-08a7ef17860a) | ![spring-boot](https://github.com/solarpark7346/network-production-system/assets/61046271/758706fb-bdc7-4ce2-b94c-686d7947f8b4) | ![spring-security](https://github.com/solarpark7346/network-production-system/assets/61046271/f9d96be2-67b4-4538-82b6-8e164dcca6ba) | ![mybatis](https://github.com/solarpark7346/network-production-system/assets/61046271/b9220db3-3882-48d0-a597-ac70e3eecd69) | ![gradle](https://github.com/solarpark7346/network-production-system/assets/61046271/0fbab405-fae7-4829-be3c-382e450d4b28) | ![jwt](https://github.com/solarpark7346/network-production-system/assets/61046271/6662e430-c0ec-4d48-a3e4-f5d8fb593692) | <img src="https://github.com/solarpark7346/network-production-system/assets/61046271/5f681cc8-315b-4edb-a5ca-a4b4e79ab18a" alt="swagger" width="96" height="96"/> |
 
### **>_ Database**

|                                                           mysql                                                           |   
|:-------------------------------------------------------------------------------------------------------------------------:|
| ![mysql](https://github.com/solarpark7346/network-production-system/assets/61046271/ffa6b374-8882-4dd2-9377-3b2a80eb7110) | 

### **>_ CI/CD**
|                                                          google cloud platform                                                       |                                                          docker                                                       |                                                          jenkins                                                       |
|:---------------------------------------------------------------------------------------------------------------------:|:----------------------------------------------------------------------------------------------------------------------:|:----------------------------------------------------------------------------------------------------------------------:|
| ![gcp](https://github.com/dogineer/network-production-system/assets/61046271/1434bdf5-a64f-443c-85da-93ad72a8a170) | ![docker](https://github.com/dogineer/network-production-system/assets/61046271/d08620f5-395f-4bc9-bcfb-26dc2959319a) | ![jenkins](https://github.com/dogineer/network-production-system/assets/61046271/63836b8b-51a4-4e6a-8138-595e2e1f0c29) |


## 4. 어플리케이션 상세 기술
> 다음은 프로젝트의 어플리케이션 상세 기술입니다.

1. RestApi: RESTful 아키텍처를 기반으로 한 API를 개발하여 클라이언트와의 통신을 처리합니다.
2. 세션 처리: 사용자 세션 관리를 위해 세션 처리 기능을 구현하였습니다.
3. 인사 관리: 인사 정보를 관리하기 위한 기능을 구현하였습니다.
4. 미디어 자산 관리: 미디어 자산의 업로드, 메타데이터 처리 등을 위한 기능을 구현하였습니다.
5. MSA (Microservices Architecture): MSA 아키텍처 패턴을 적용하여 각 기능을 독립적으로 개발하고 배포할 수 있도록 설계하였습니다.
6. 트랜스코딩: 다양한 형식과 포맷의 미디어 파일을 변환하는 기능을 구현하였습니다.
7. 실시간 트랜스코딩 확인: 웹 소켓을 활용하여 실시간으로 트랜스코딩 작업의 진행 상황을 확인할 수 있는 기능을 구현하였습니다.
8. 글로벌 예외 처리: 예외 상황을 전역적으로 처리하기 위한 글로벌 예외 처리 기능을 구현하였습니다.
9. 페이징: 대량의 데이터를 효율적으로 처리하기 위해 페이징 기능을 구현하였습니다.

## 5. ERD
<img width="1502" alt="image" src="https://github.com/solarpark7346/media-asset-management/assets/61046271/8d6d91e0-9c1a-4ab9-9236-ffd21b7ceb63">



