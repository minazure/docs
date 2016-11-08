---

copyright:
  years: 2016
lastupdated: "2016-10-13"

---
{:new_window: target="_blank"}
{:shortdesc: .shortdesc}
{:screen:.screen}
{:codeblock:.codeblock}

# UI 스타터를 사용하여 프로젝트 작성
{: #projects_ui}

마지막 업데이트 날짜: 2016년 10월 13일
{: .last-updated}

{{site.data.keyword.Bluemix}} 모바일 대시보드에서 UI 스타터를 사용하여 {{site.data.keyword.Bluemix_notm}} 환경에 프로젝트를 작성할 수 있습니다. 이 프로시저는 코드 스타터를 사용하는 프로젝트에 적용되지 않습니다. 코드 스타터 관련 지시사항은 [코드 스타터를 사용하여 프로젝트 작성](projects_code.html)을 참조하십시오.
{:shortdesc}

UI 스타터를 사용하여 프로젝트를 작성하려면 다음 단계를 완료하십시오. 

1. {{site.data.keyword.Bluemix_notm}}에서 새 모바일 대시보드 프로젝트를 작성하십시오. 

 모바일 카탈로그를 선택한 후 *시작하기* 탭으로 시작하십시오. 사용할 수 있는 선택된 스타터에 대한 설명과 사용자에게 필요한 지원 수준에 따라 프로젝트를 작성하는 여러 방법에 대한 설명이 제공됩니다. 최소한의 도움으로 시작하려면 **프로젝트 작성**을 선택하십시오. 

 프로젝트가 이미 있는 경우에는 *시작하기* 탭에 있는 동안 *프로젝트* 탭을 선택할 수 있습니다. {{site.data.keyword.Bluemix_notm}} 모바일 대시보드 **프로젝트** 보기에서 작업할 프로젝트를 선택할 수 있으며 프로젝트에 대한 *조치*를 사용하여 프로젝트를 삭제하거나, 프로젝트에 사용할 코드를 다운로드하거나, 새 프로젝트를 작성할 수 있습니다. UI 스타터에서 프로젝트를 시작한 경우 *조치* 메뉴를 사용하여 직접 UI 빌더에서 프로젝트를 열 수도 있습니다.  

	1. {{site.data.keyword.Bluemix_notm}} 콘솔에서 {{site.data.keyword.Bluemix_notm}} 로고 옆의 세 개의 선이 있는 메뉴를 펼친 후 **모바일**을 선택하십시오.  
	
	2. **프로젝트 작성**을 선택하십시오.  

	  또는 **프로젝트** 탭을 선택하여 사용자 모바일 환경에 이미 있는 프로젝트를 보고 **프로젝트 작성**을 클릭하여 새 프로젝트를 작성할 수 있습니다.  

	3. 작성하려는 앱의 유형과 가장 일치하는 스타터를 선택한 후 **프로젝트 작성**을 선택하십시오. **UI 스타터**와 **코드 스타터**가 있습니다. 스타터와 스타터 사용 방법에 대한 자세한 정보는 [스타터](starters.html)를 참조하십시오.  
	
	4. 프로젝트의 이름을 입력하고 **작성**을 선택하십시오. 
	
2. **프로젝트 개요** 화면에서 선택사항을 결정하십시오. **프로젝트 개요** 화면에는 프로젝트와 프로젝트에 추가할 수 있는 선택적 기능(예: Push Notifications)에 대한 정보가 표시됩니다.   

	1. 선택사항: 나열된 기능 중 하나를 프로젝트에 추가하려면 **추가**를 선택하십시오. 서비스의 **서비스 이름**을 편집하고 **작성**을 클릭하십시오. 
	
	2. 선택사항: 프로젝트에 추가하려는 추가 기능에 대해 *a* 단계를 반복하십시오.  

3. UI 빌더를 사용하여 사용자 인터페이스를 디자인하십시오. 

   참고: 코드 스타터에는 사용자 정의할 수 있는 사용자 인터페이스가 없으므로 *디자인* 탭을 사용할 수 없습니다. 

    1. 탐색 메뉴에서 **UI 빌더**를 선택하여 앱의 디자인을 사용자 정의하십시오. <!--Most of the design screens have sections that begin with a navigation on the left of the screen, and the sections more specific as it moves to the right side preview of your app. Note: Not all design screens in the starters have the same sections.--> 
	
	2. **화면** 탭에서 앱 레이아웃을 사용자 정의하십시오. 
	
	3. **화면 작성**을 선택하여 새 화면을 추가하십시오. 앱에서 참조하기 쉽도록 새 화면의 이름을 지정하십시오. 다음 유형의 화면 중에서 선택할 수 있습니다.  
	    * 메뉴
		* 목록
		* 맵
		* 사용자 정의 
		* 차트
		
	4. 인터페이스의 **레이아웃** 섹션에서 *메뉴* 텍스트 상자를 선택하고 **표시할 데이터** 필드의 컨텐츠를 바꿔 앱의 메뉴 제목을 변경할 수 있습니다. 시뮬레이션된 디바이스 섹션에서 업데이트를 보십시오. 
	
		필요에 따라 각 항목을 선택하고 정보를 업데이트하여 디자인 항목을 업데이트하십시오. 이들 항목은 트리 형식으로 표시됩니다. 항목을 새 위치로 끌어와 메뉴 항목의 순서 또는 위치를 변경할 수 있습니다. 모든 하위 항목도 상위와 함께 이동합니다. **표시할 데이터** 필드에 표시되는 트리 항목의 텍스트 정보는 데이터 소스 스프레드시트의 컨텐츠를 참조합니다. *해당 항목을 **데이터** 보기에서 식별된 데이터 소스의 컨텐츠로 겹쳐쓰므로 **디자인** 보기에서 해당 항목을 변경하지 마십시오. * 
		
		트리에서 *양식*으로 식별되는 항목은 독립적이며 인라인으로 수정될 수 있습니다. 이 항목은 데이터 소스의 정보를 참조하지 않습니다. 
	
	5. 탐색에서 **데이터**를 선택하여 앱에서 사용 중인 데이터를 표시하십시오. 템플리트에 기본 정보가 있지만 **새로 작성**을 선택하여 데이터의 소스를 변경할 수 있습니다. 둘 이상의 데이터 소스를 참조할 수 있으므로 사용하는 각 소스의 이름을 제공하십시오. 다음 데이터 소스 옵션 중에서 선택할 수 있습니다. 
		* 클라우드
		* 로컬
		* Cloudant
		* Google 스프레드시트
		* Excel Online
		* Google 드라이브
	
	또한 단추를 사용하고 테이블에서 컨텐츠를 선택하여 테이블에 있는 컨텐츠를 가져오거나, 내보내거나, 수정할 수 있습니다(컨텐츠가 로컬인 경우). 
	     
		 주의사항: 기본 데이터의 구조와 일치하지 않는 데이터를 가져오는 경우 *스키마 대체* 슬라이더를 켜십시오. 해당 예는 스타터에서 제공되는 데이터보다 열 수가 적은 .csv 파일입니다. 
		 
	6. 탐색에서 **사용자 액세스**를 선택하여 프로젝트의 액세스 요구사항을 수정하십시오. 스위치를 사용하여 사용자 액세스 켜기와 끄기를 토글할 수 있습니다. 사용자 액세스가 켜진 경우 비활성 사용자 제한시간과 앱에 액세스할 수 있는 사용자의 신임 정보를 설정할 수 있습니다. 
	
	7. 탐색 메뉴에서 **설정**을 선택하여 프로젝트의 전체 정보와 색상을 수정하십시오. 이 화면에서, 프로젝트에 추가한 기능에 필요한 경우 Google API 키를 입력할 수 있습니다. 또한 이 화면에서 Apple Store 또는 Google Play 스토어에 등록된 고유 번들 ID를 추가할 수 있습니다. 
	
		프로젝트에 IBM MobileFirst Foundation SDK를 추가하려면 스위치를 토글하여 켜십시오. 
		
	8. *설정* 화면에서 프로젝트에 IBM MobileFirst Platform Foundation을 추가하도록 스위치를 토글한 경우 탐색에 **Foundation** 선택사항이 표시됩니다. **Foundation**을 선택하고 IBM MobileFirst Platform Foundation에 특정한 필수 정보를 완료하십시오. 
	
	9. 탐색 메뉴에서 **공개**를 선택해서 모바일 앱을 작성할 최종 정보를 입력하십시오. iOS용 번들 ID와 Android용 애플리케이션 ID를 입력할 수 있습니다. 
	
	iOS 앱을 작성할 경우 번들 ID, 배포 인증서를 *.p12* 파일로 얻고 Apple 프로비저닝 포털에서 프로비저닝 프로파일을 *.mobileprovision* 파일로 얻어야 합니다. 이 세 항목을 Apple Store에 앱을 게시할 때 사용할 컴퓨터에서 동시에 작성해야 합니다. 배포 인증서와 프로비저닝 프로파일은 번들 ID를 기반으로 해야 합니다.  	

4.  *프로젝트 개요* 화면으로 돌아가 앱의 코드를 검색하고 앱을 사용해 보십시오. iOS 또는 Android 운영 체제에서 코드를 직접 다운로드하거나 Android 운영 체제의 경우 QR 코드를 스캔하여 코드를 다운로드할 수 있습니다.  

