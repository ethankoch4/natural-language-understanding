---

copyright:
  years: 2015, 2017
lastupdated: "2018-03-16"

---

{:shortdesc: .shortdesc}
{:new_window: target="_blank"}
{:tip: .tip}
{:pre: .pre}
{:codeblock: .codeblock}
{:screen: .screen}
{:javascript: .ph data-hd-programlang='javascript'}
{:java: .ph data-hd-programlang='java'}
{:python: .ph data-hd-programlang='python'}
{:swift: .ph data-hd-programlang='swift'}

# 관계 유형(버전 1)

다음 표에서는 _버전 1_ 관계 유형 시스템에서 리턴한 관계 유형을 나열합니다. {{site.data.keyword.nlushort}}에서 사용하는 관계 유형 시스템은 사용하는 언어에 따라 다릅니다. 자세한 내용은 [관계 유형](relations.html) 페이지를 참조하십시오.
{: shortdesc}

| 관계            | 설명                                                                                                                                                                                                                   |
|-----------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| affectedBy      | 명확한 방향성이 있고 엔티티에 영향을 미치는 이벤트와 엔티티 사이에 존재합니다.                                                                                                                                                                       |
| affiliatedWith  | 제휴를 맺었거나 유사하게 연결된 두 엔티티 사이에 존재합니다.                                                                                                                                                                                 |
| ageOf           | 수명을 엔티티와 관련시킵니다.                                                                                                                                                                                                   |
| agentOf         | 텍스트에 따라 엔티티가 가장 능동적인 역할을 수행하는 이벤트와 엔티티 사이에 존재합니다. 배경 지식이 없어도 됩니다.                                                                                                                                                  |
| authorOf        | 개인과 해당 개인이 생성한 TitleWork 사이에 존재합니다.                                                                                                                                                                              |
| awardedBy       | 상 또는 학위와 상을 수여하거나 학위를 부여한 개인 또는 조직 사이에 존재합니다.                                                                                                                                                                      |
| awardedTo       | 상 또는 학위와 상을 받거나 학위를 받은 개인 또는 조직 사이에 존재합니다.                                                                                                                                                                         |
| basedIn         | 조직과 해당 조직이 주로, 유일하게 또는 고유하게 위치하는 장소 사이에 존재합니다.                                                                                                                                                                     |
| before          | 두 시간 또는 이벤트 사이의 임시 관계 "before"를 나타냅니다. 텍스트에서 관계를 명확하게 지정하는 경우에만 표시합니다.                                                                                                                                             |
| bornAt          | 개인이나 동물과 해당 개인 또는 동물이 태어난 장소 사이에 존재합니다.                                                                                                                                                                            |
| bornOn          | 개인이나 동물과 해당 개인 또는 동물이 태어난 날짜 또는 시간 사이에 존재합니다.                                                                                                                                                                      |
| capitalOf       | 수도와 해당 국가, 주 또는 구/군/시 사이에 존재합니다. 세계 정세에 관한 지식을 기반으로 하지 않고 텍스트에서 명시적으로 관계를 나타내는 경우에만 표시합니다.                                                                                                                         |
| citizenOf       | 개인과 해당 개인이 시민으로 속해 있는 GeopoliticalEntity 사이에 존재합니다.                                                                                                                                                                  |
| clientOf        | 한 엔티티가 다른 엔티티의 직접적인 비즈니스 클라이언트인 경우(즉, 특정 서비스나 제품에 대해 비용 지급) 두 엔티티 사이에 존재합니다.                                                                                                                                       |
| colleague       | 동일한 조직에 속한 두 사람 사이에 존재합니다.                                                                                                                                                                                         |
| competitor      | 경제적 경쟁에 참여하고 있는 두 개의 GeopoliticalEntities 또는 조직 사이에 존재합니다.                                                                                                                                                         |
| contactOf       | 연락처 정보를 엔티티와 관련시킵니다.                                                                                                                                                                                               |
| diedAt          | 개인이나 동물과 해당 개인 또는 동물이 죽은 장소 사이에 존재합니다.                                                                                                                                                                             |
| diedOf          | 개인이나 동물과 해당 개인 또는 동물이 죽은 이유 사이에 존재합니다.                                                                                                                                                                             |
| diedOn          | 개인이나 동물과 해당 개인 또는 동물이 죽은 날짜 또는 시간 사이에 존재합니다.                                                                                                                                                                       |
| dissolvedOn     | 조직과 같은 엔티티와 해당 엔티티가 해체된 날짜 또는 시간 사이에 존재합니다.                                                                                                                                                                        |
| educatedAt      | 개인과 해당 개인이 교육을 받고 있거나 받은 조직 사이에 존재합니다.                                                                                                                                                                               |
| employedBy      | 한 엔티티가 다른 엔티티에게 특정 작업 또는 서비스에 대해 비용을 지불할 때 두 엔티티 사이에 존재합니다. 이때 금전적 보상이 있어야 합니다. 대부분의 경우 이 관계를 표시하려면 세계 정세에 관한 지식이 필요합니다.                                                                                           |
| foundedOn       | 조직과 같은 엔티티와 해당 엔티티가 설립된 날짜 또는 시간 사이에 존재합니다.                                                                                                                                                                        |
| founderOf       | 개인 또는 GeopoliticalEntity와 해당 개인 또는 해당 조직에서 설립한 조직과 같은 엔티티 사이에 존재합니다.                                                                                                                                                 |
| hasDisease      | 개인 또는 동물이 병에 걸렸음을 표시합니다.                                                                                                                                                                                           |
| hasMoney        | 개인과 같은 엔티티가 금전을 갖고 있음을 표시합니다.                                                                                                                                                                                      |
| instrumentOf    | 무기와 같은 엔티티와 해당 엔티티가 사용되는 이벤트 사이에 존재합니다.                                                                                                                                                                            |
| locatedAt       | 엔티티와 실제 위치 사이에 존재합니다.                                                                                                                                                                                              |
| managerOf       | 개인과 해당 개인이 업무상 관리하는 개인 또는 조직과 같은 다른 엔티티 사이에 존재합니다.                                                                                                                                                                   |
| measureOf       | 엔티티의 높이 또는 중량과 같은 특정 수치를 표시합니다.                                                                                                                                                                                    |
| memberOf        | 개인, 조직 또는 GeopoliticalEntity와 같은 엔티티와 해당 엔티티가 속한 다른 엔티티 사이에 존재합니다.                                                                                                                                                 |
| near            | 물리적으로 서로 가까이 있는 두 엔티티 사이에 존재합니다.                                                                                                                                                                                   |
| overlaps        | 두 시간 또는 이벤트가 임시로 겹침을 나타냅니다. 텍스트에서 관계를 명확하게 지정하는 경우에만 표시합니다.                                                                                                                                                        |
| ownerOf         | 개인, 조직 또는 GeopoliticalEntity와 같은 엔티티와 해당 엔티티가 영구적이나 임시로 소유하는 엔티티 사이에 존재합니다.                                                                                                                                        |
| parentOf        | 개인 또는 동물과 해당 개인 또는 동물의 자식 또는 의붓자식 사이에 존재합니다.                                                                                                                                                                       |
| participantIn   | 개인, 동물, 조직 또는 GeopoliticalEntity와 같은 참가자와 해당 참가자가 참여하고 있거나 참여한 이벤트 사이에 존재합니다.                                                                                                                                      |
| partner         | 경제적 협력에 참여하고 있는 두 개의 GeopoliticalEntities 또는 조직 사이에 존재합니다.                                                                                                                                                         |
| partOf          | 유형이 같거나 유형이 연관되어 있으며 두 번째 엔티티가 첫 번째 엔티티를 포함하는 상대적으로 소규모이고 대규모인 엔티티 사이에 존재합니다. 엔티티가 이벤트이면 두 번째 엔티티 기간 내에 첫 번째가 발생해야 합니다.                                                                                            |
| partOfMany      | 유형이 같거나 유형이 연관되어 있으며 상대적으로 소규모와 대규모인 엔티티 사이에 존재합니다. 이때 두 번째 엔티티는 복수로 구성되어야 하며, 하나 이상의 엔티티로 구성될 수 있는 첫 번째 엔티티를 포함합니다.                                                                             |
| playsRoleOf     | 개인과 해당 개인이 공연에서 수행하는 특정 역할 사이에 존재합니다.                                                                                                                                                                            |
| populationOf    | 기수와 해당 숫자가 전체 모집단을 나타내는 조직 또는 국가와 같은 엔티티 사이에 존재합니다.                                                                                                                                                                |
| productOf       | 제품 또는 TitleWork와 해당 제품 또는 TitleWork를 생산한 조직 사이에 존재합니다.                                                                                                                                                             |
| quantityOf      | 두 번째 엔티티의 수량 또는 양인 기수를 표시합니다.                                                                                                                                                                                      |
| rateOf          | 비율과 해당 비율이 발생 빈도를 나타내는 이벤트 사이에 존재합니다.                                                                                                                                                                              |
| relative        | 더 구체적인 관계가 적합하지 않은 경우 개인이나 동물과 해당 개인이나 동물이 관련된 다른 개인 또는 동물 사이에 존재합니다.                                                                                                                                                |
| residesIn       | 살아 있는 엔티티와 해당 엔티티가 영구적으로 거주하는 위치 사이에 존재합니다.                                                                                                                                                                        |
| shareholdersOf  | 개인, 조직 또는 GeopoliticalEntity와 첫 번째 엔티티가 주주인 조직 사이에 존재합니다.                                                                                                                                                          |
| siblingOf       | 개인 또는 동물과 해당 개인 또는 동물의 형제자매 또는 의붓형제자매 사이에 존재합니다.                                                                                                                                                                   |
| spokespersonFor | 개인과 해당 개인이 대표하는 엔티티 사이에 존재합니다. 세계 정세에 관한 지식을 기반으로 하지 않고 텍스트에서 명시적으로 관계를 나타내는 경우에만 표시합니다.                                                                                                                             |
| spouseOf        | 공식적인 배우자인 두 사람 사이에 존재합니다.                                                                                                                                                                                          |
| subsidiaryOf    | 첫 번째 조직이 두 번째 조직의 자회사인 경우 두 조직 사이에 존재합니다. 즉, 두 번째 엔티티의 제어를 받기는 하지만 첫 번째 엔티티에 상당한 정도의 자치권이 있습니다.                                                                                                                    |
| timeOf          | 이벤트가 발생한 날짜, 시간 또는 기간을 나타냅니다. 즉, TitleWork가 공개, 수행 또는 브로드캐스팅되었거나 법률이 처음 입안되거나 작성, 통과 또는 폐지된 날짜, 시간 또는 기간입니다.                                                                                                       |

## 관계에 고유한 엔티티 유형

_버전 1_ 관계 유형 시스템에 관련된 엔티티 유형은 기본 엔티티 유형 시스템에 관련된 엔티티 유형과 다릅니다. 기본 엔티티 감지 모델을 대체하도록 `entities` 기능의 `model` 매개변수에서 다음 관계 엔티티 모델 중 하나를 지정할 수 있습니다.

|모델 ID |설명       |
|--------|-----------|
|ar-news|아랍어 뉴스 |
|en-news|영어 뉴스   |
|es-news|스페인어 뉴스|

다음 엔티티는 `relations` 모델로 식별할 수 있습니다.

|엔티티 유형|
|---|
|Age |
|Anatomy |
|Animal |
|Award |
|Cardinal |
|Crime |
|Date |
|Degree |
|Duration |
|EmailAddress |
|Event |
|EventBusiness |
|EventCommunication |
|EventCustody |
|EventDemonstration |
|EventEducation |
|EventElection |
|EventGathering |
|EventLegal |
|EventLegislation |
|EventMeeting |
|EventPerformance |
|EventPersonnel |
|EventViolence |
|Facility |
|Food |
|GeographicFeature|
|GeopoliticalEntity |
|HealthCondition |
|Law |
|Location |
|Money |
|Measure |
|NaturalEvent |
|Organization |
|Ordinal |
|Percent |
|Person |
|Phone |
|Plant |
|Product |
|SportingEvent |
|Substance |
|Ticker |
|Time |
|TitleWork |
|Vehicle |
|Weapon |
|Weather |
|Web |

