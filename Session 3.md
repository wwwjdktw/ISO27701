# ISO 27701 LA Session - 3 : PIMS requirements related to ISO/IEC 27002:2013
###### tags: `Tag(27701)`

In this session, we are going to discuss:
ISO/IEC 27002:2013
* Clause 6.0: PIMS-specific guidance related to ISO/IEC 27002
* Clause 6.1: General
* Clause 6.2: Information security policies
* Information Security & Privacy Policy Lifecycle
* Clause 6.3: Organization of information security
* Organization of Information Security
* Clause 6.4: Human resource security
* Employee Selection
* Training and Establishment of Trust
* Clause 6.5: Asset management
* Clause 6.6: Access control
* Access Administration and Control
* Access Control on System Basis
* Clause 6.7: Cryptography
* Clause 6.8: Physical and environmental security
* Device Protection
* Clause 6.9: Operations security
* Clause 6.10: Communications security
* Clause 6.11: System acquisition, development and maintenance
* Clause 6.12: Supplier relationships
* Clause 6.13: Information security incident management
* Clause 6.14: Information security aspects of business continuity management
* System Planning and Acceptance
* Business Continuity Management Context
* Rest Risk - Business Continuity Management
* Business Continuity Management Concrete
* Examples of Damage Progress
* Clause 6.15: Compliance.
## Clause 6.0: PI MS-specific guidance related to ISO/IEC 27002
* Clause 6.1: General
* Clause 6.2: Information security policies
	* Sub clause 6.2.1
* Clause 6.3: Organization of information security
	* Sub clause 6.3.1 to 6.3.2
* Clause 6.4: Human resource security
	* Sub clause 6.4.1 to 6.4.3
* Clause 6.5: Asset management
	* Sub clause 6.5.1 to 6.5.3
* Clause 6.6: Access control
	* Sub clause 6.6.1 to 6.6.4
* Clause 6.7: Cryptography
	* Sub clause 6.7.1
* Clause 6.8: Physical and environmental security
	* Sub clause 6.8.1 to 6.8.2
* Clause 6.9: Operations security
	* Sub clause 6.9.1 to 6.9.7
* Clause 6.10: Communications security
	* Sub clause 6.10.1 to 6.10.2
* Clause 6.11: Systems acquisition, development and maintenance
	* Sub clause 6.11.1 to 6.11.3
* Clause 6.12: Supplier relationships
	* Sub clause 6.12.1 to 6.12.2
* Clause 6.13: Information security incident management
	* Sub clause 6.13.1
* Clause 6.14: Information security aspects of business continuity management
	* Sub clause 6.14.1 to 6.14.2
* Clause 6.15: Compliance
	* Sub clause 6.15.1 to 6.15.2.
## Clause 6.0: PI MS-specific guidance related to ISO/I EC 27002 (continued...)
> 條款6.0 與ISOIEC 27002 相關的PIMS特定指南

* Clause 6,1: General
	* This clause provides some General guidance regarding application of ISO/IEC 27002 in PIMS
* Clause 6.2: Information Security_Policies
	* This clause specifies control, implementation guidance and other information regarding Implementation and maintenance of an information security and privacy policy.
* Clause 6,3: Organization of Information Security.
	* This clause specifies control, implementation guidance and other information regarding Establishment of a management framework to initiate and control implementation of information security and privacy within an organization
* Clause 6,4: Human Resource Security
	* This clause specifies control, implementation guidance and other information regarding measures to reduce risks of human error, theft, fraud or misuse of facilities
* Clause 6,5: Asset Management
	* This clause specifies control, implementation guidance and other information regarding asset management. Each asset should be identified, recorded and "ownership" apportioned
* Clause 6,6: Access Control
	* This clause specifies control, implementation guidance and other information regarding controls to prevent unauthorized access to computer networks and network services
* Clause 6.7: Cryptography
	* This clause specifies control, implementation guidance and other information to establish policy and key management for cryptographic controls.
* Clause 6.8: Physical and Environmental Security
	* This clause specifies control, implementation guidance and other information for Prevention of unauthorized access to offices, facilities, equipment, delivery areas etc. as well as prevention of interference to IT services and any damages to them.
* Clause 6.9: Operations Security
	* This clause specifies control, implementation guidance and other information To ensure correct and secure operation of computer and network facilities; protection from malwares, backup, logging and vulnerability management
* Clause 6.10: Communications security.
	* This clause specifies control, implementation guidance and other information to establish proper network security management and control for information transfer.
* Clause 6.11: System acquisition, development and maintenance
	* This clause specifies Security requirements of information systems, as well as control,implementation guidance and other information for security in development and support processes and protection of test data
* Clause 6.12: Supplier relationships
	* This clause specifies control, implementation guidance and other information to etablish information security in supplier relationships and service delivery management
* Clause 6.13: Information security incident management
	* This clause specifies control, implementation guidance and other information to investigate and assess information security events, report information security events as well as information security weaknesses and implement the lessons learned.
* Clause 6.14: Information security aspects of business continuity_ management
	* This clause specifies control, implementation guidance and other information to protect critical business processes from major failures and disasters.
* Clause 6.15: Compliance 
	* This clause specifies control, implementation guidance and other information for compliance with legal and contractual requirements in order to avoid breaches of statutory or contractual requirements and intellectual property rights and to ensure the PIMS is operational.
## Clause 6.1: General
> 條款6.1 總則

1. The requirements of ISO/IEC 27002 mentioning "information security" should also be applied to the protection of privacy as potentially affected by the processing of PII.
>ISO/IEC 27002:2013中提及"信息安全"的指南應擴展到可能受PII處理潛在影響的隱私保護。
2. Places in ISO/IEC 27002 where the term "information security" is used in, we should use "information security and privacy" instead.
> 在實際使用中，在ISO/IEC 27002:2013中使用的"信息安全"的地方，等同於"信息
安全和隱私"
3. All control objectives and controls of ISO/IEC 27002:2013 should also be considered in the context of risks to privacy related to the processing of PII.
> 所有控制目標和控制者都應考慮到信息安全風險以及與「PII處理相關的隱私風險。」
## Clause 6.2: Information security policies
> 條款6.2信息安全策略
### Clause 6.2.1 Management for information security
> 信息安全管理指導
* This sub- clause specifies requirements To provide management direction and support for information security and privacy in accordance with business requirements and relevant laws and regulations. This sub clause has further two sub-clauses:
> 本小節規定了要求，以根據業務要求和相關法律法規為信息安全和隱私提供管理指導和支持。本小節還有另外兩個小節：
1. Clause 6.2.1.1: Policies for information security
> 條款6.2.1.1 信息安全策略
無論是製定單獨的隱私策略，還是通過增加信息安全策略，組織都應該制定一份聲明，
說明是否支持並致力於遵守適用的PII保護法律和或法規以及商定的合同條款(商定範圍包括組織之間及其合作夥伴，分包商及其合作夥伴適用的第三方如客戶，供應商等，且應明確分配它們之間的責任)。
針對 ISO/IEC 27002:2013 5.1.1 信息安全策略補充的其他信息是:
處理「PII的任何組織，無論是PII控制者還是PII處理者，都應在製定和維護信息安全
策略期間考慮適用的PII保護的法律和/或法規。
2. Clause 6.2.1.2: Review of the policies for information security
	* The organization should either develop a separate privacy policies, or augment the information security policies to cover privacy goals.
	* Prepare a statement regarding support for and commitment to achieving compliance with applicable PII protection legislation/ regulation and with the contractual terms.
	* Consider applicable Pll protection legislation and/or regulation during the development and maintenance of information security policies.
> 條款6.2.1.2 信息安全策略的評審
> 適用 ISO/IEC 27002:2013,5.12中規定的控制，實施指南和其他信息。
> 組織應該制定單獨的隱私策略，或者擴展信息安全策略以涵蓋隱私目標。
準備一份聲明，以支持和承諾遵守適用的PII保護法律/法規和合同條款。
在製定和維護信息安全策略時，請考慮適用的Pll保護法規和/或法規
* What is Information Security & Privacy Policy?
1. It is Commitment of managment to information security & privacy
2. It is top-level document containing information security & privacy principles
3. It is an opinion leading within the organization
4. It is used to frame goals of information security & privacy.
> 什麼是信息安全和隱私政策？
1.是對信息安全和隱私的管理承諾
2.它是包含信息安全和隱私原則的頂級文檔
3.這是組織內部的領導意見
4.用於製定信息安全和隱私的目標。
## Information Security & Privacy Lifecycle
![](https://i.imgur.com/ev95GBK.png)
## Clause 6.3: Organization of information security
* Clause 6.3.1: Internal organization
	* To establish a management framework to initiate and control the implementation and operation of information security and privacy within the organization.
> 條款6.3.1 信息安全組織
> 建立管理框架以啟動和控制組織內信息安全和隱私的實施和操作。
> 在處理PI方面組織宜指定一個聯絡點，供客戶使用。當組織是「PII控制者時，組織在處理PII方面給PII主體指定聯絡點(參見7.3.2)。組織宜指定一名或多名負責制定，實施，維護和監督組織範圍的治理和隱私流程(program)的人員，以確保遵守有關處理PII的所有適用法律和法規。在適當時,負責人宜:
一獨立並直接向組織的適當管理層報告,以確保有效管理隱私風險;
一參與管理與處理「有關的所有問題;
一是數據保護法律,監管和實踐方面的專家;
一作為監管機構的聯絡點;
一告知高層管理層和組織內員工在處理PII方面的義務
一就組織進行的隱私影響評估提供建議。
注:某些司法管轄區會定義何時需要這樣的職位,以及他們的職位和角色,這樣的人被
稱為數據保護官。該職位可由內部工作人員或外包人員履行。
* Clause 6.3.1.1: Information security roles and responsibilities
* Clause 6.3.1.2: Segregation of duties
* Clause 6.3.1.3: Contact with authorities
* Clause 6.3.1.4: Contact with special interest groups
> 條款6.3.1.1 信息安全角色與職責，適用 ISO/IEC 27002:2013，6.1.1中規定的控制，實施指南和其他信息。
> 條款6.3.1.2 職責分離，適用 ISO/IEC 27002:2013，6.1.2中規定的控制，實施指南和其他信息。
> 條款6.3.1.3 與職能機構的聯繫，適用 ISO/IEC 27002:2013，6.1.3中規定的控制，實施指南和其他信息。
> 條款6.3.1.4 與特殊利益集團聯繫，適用 ISO/IEC 27002:2013，6.1.4中規定的控制，實施指南和其他信息。
* Clause 6.3.1.5: Information security in project management
	* The organization should Designate a point of contact for the customer regarding the processing of PII. When the organization is a PII controller, designate a point of contact for PII principals
	* Appoint one or more persons responsible for developing, implementing, maintaining and monitoring an organization-wide governance and privacy program
	* The responsible person, also called data protection officer, should:
	* be independent and report directly to the top management of the organization to ensure effective management of privacy risks;
	* be involved in the management of all issues relating to the processing of PII;
	* be expert in data protection legislation, regulation and practice;
	* act as a contact point for supervisory authorities;
	* inform top/senior level management and employees of the organization of their obligations with respect to the processing of PII;
	* provide advice in respect of privacy Impact assessments conducted by the organization.
> 條款6.3.1.5項目管理中的信息安全，適用 ISO/IEC 27002:2013，6.1.5中規定的控制，實施指南和其他信息。
> 1.一組織應為客戶指定有關PII處理的聯繫點。當組織是PII負責人時，請指定PII負責人的聯繫點
2.任命一個或多個負責制定，實施，維護和監視組織範圍內的治理和隱私計劃的人員
負責人，
3.也稱為數據保護官，應：
4.具有獨立性，並直接向組織的最高管理層報告，以確保有效管理隱私風險；
5.參與與PII處理有關的所有問題的管理；
6.成為數據保護立法，法規和實踐方面的專家；
7.擔任監管部門的聯絡點；
8.告知組織的最高/高層管理人員和僱員他們在處理個人身份信息方面的義務；
9.提供有關組織進行的隱私影響評估的建議。
* Clause 6.3.2: Mobile devices and teleworking
	* To ensure the security of teleworking and use of mobile devices. This sub clause has further two sub-clauses : 
> 條款6.3.2：移動設備和遠程辦公，適用 ISO/IEC 27002:2013，6.2.1中規定的控制，實施指南和其他信息以及以下補充指南。
確保遠程辦公和使用移動設備的安全性。本小節還有另外兩個小節：
* Clause 6.3.2.1: Mobile device policy
> 條款6.3.2.1 移動設備策略
* Clause 6.3.2.2: Teleworking
> 條款6.3.2.2 遠程辦公
> 用 ISO/IEC 27002:2013，6.2.2中規定的控制，實施指南和其他信息以及以下補充指南。
* The organization should ensure that the use of mobile devices does not lead to a compromise of Pll.
> ISO/IEC 27002:2013，6.2.1的移動設備策略的補充實施指南是:
組織宜確保移動設備的使用不會導致PII的危害。
## Organization of Information Security
![](https://i.imgur.com/RUO0X69.png)
## Clause 6.4: Human resource security
> 條款6.4 人力資源安全
* Clause 6.4.1: Prior to employment
	* This sub clause requires the organization To ensure that employees and contractors understand their responsibilities and are suitable for the roles for which they are considered.
> 條款6.4.1 任用前
> 本子條款要求組織確保僱員和承包商理解他們的責任並適合他們所考慮的角色。
* Clause 6.4.1.1: Screening
> 條款6.4.1.1 審查，適用 ISO/IEC 27002:2013，6.4.1.1中規定的控制，實施指南和其他信息。
* Clause 6.4.1.2: Terms and conditions of employment.
> 條款6.4.1.2 任用條款和條件，適用 ISO/IEC 27002:2013，6.4.1.2中規定的控制，實施指南和其他信息。
## Employee Selection
![](https://i.imgur.com/cCm0XED.png)
* Clause 6.4.2: During employment
	* This sub clause requires the organization To ensure that employees and contractors are aware of and fulfill their information security responsibilities.
> 條款6.4.2任用中
> 本子條款要求組織確保僱員和承包商了解並履行其信息安全責任。
* Clause 6.4.2.1: Management responsibilities
> 條款6.4.2.1管理責任
> 適用 ISO/IEC 27002:2013，7.2.1中規定的控制，實施指南和其他信息。
* Clause 6.4.2.2: Information security awareness, education and training
> 條款6.4.2.2 信息安全意識、教育和培訓
> 適宜採取措施，包括對事故報告的認識，以確保相關工作人員了解對組織可能造成的後
果(例如法律後果，業務損失和品牌或聲譽受損)，對工作人員的後果(例如紀律處分的後
果)以及對違反隱私或安全規則和流程(尤其是那些涉及PII處理的規則和流程)的PII主
體的後果(例如物理，物質和情感的後果)。
注:這些措施可包括對有權訪問PII的人員進行適當的定期培訓。
* Clause 6.4.2.3: Disciplinary process
	* Appropriate periodic training should be provided to personnel having access to Pll, in order to ensure that they are aware of the possible consequences of breaching privacy or security rules and procedures
> 應該為有權使用PII的人員提供適當的定期培訓，以確保他們知道違反隱私或安全規則和程序的可能後果。適用 ISO/IEC 27002:2013，7.2.3中規定的控制，實施指南和其他信息。
* Clause 6.4.3: Termination and change of employment
	* This sub clause says to protect the organization's interests as part of the process of changing or terminating employment.
> 條款6.4.3 任用終止和變更，本小節說，在變更或終止僱用過程中，要保護組織的利益。
* Clause 6.4.3.1: Termination or change of employment responsibilities
> 條款6.4.3.1：終止或變更工作職責。適用 ISO/IEC 27002:2013，7.3.1中規定的控制，實施指南和其他信息。
## Training and Establishment of Trust
* To ensure Information security and privacy awareness among employees, the organization should provide Induction Training before joining the duties and Regular Training during the employment.
> 培訓和建立信任
> 為確保員工之間的信息安全和隱私意識，組織應在上崗前提供上崗培訓，並在工作期間進行定期培訓。
* Such training should cover:
	1. Security & privacy policy;
	2. Job dependent rules;
	3. State-of-the-art security measures, and;
	4. New threats.
> 此類培訓應涵蓋：
1.安全與隱私政策；
2.工作相關規則；
3.最先進的安全措施；以及
4.新的威脅。
## Clause 6.5: Asset management
> 條款6.5 資產管理
* Clause 6.5.1: Responsibility for assets
	* This sub clause says to identify organizational assets and define appropriate protection responsibilities.
> 條款 6.5.1 資產責任，本小節規定了識別組織資產並定義適當的保護責任。
* Clause 6.5.1.1: Inventory of assets
> 條款6.5.1.1 資產清單。適用 ISO/IEC 27002:2013，8.1.1中規定的控制，實施指南和其他信息。
* Clause 6.5.1.2: Ownership of assets
> 條款6.5.1.2 資產的所屬關係。適用 ISO/IEC 27002:2013，8.1.2中規定的控制，實施指南和其他信息。
* Clause 6.5.1.3: Acceptable use of assets
> 條款6.5.1.3 資產的可接受使用。適用 ISO/IEC 27002:2013，8.1.3中規定的控制，實施指南和其他信息。
* Clause 6.5.1.4: Return of assets
> 條款6.5.1.4 資產規還。適用 ISO/IEC 27002:2013，8.1.4中規定的控制，實施指南和其他信息。
* Clause 6.5.2: Information classification
	* This sub clause requires the organization to ensure that information receives an appropriate level of protection in accordance with its importance to the organization.
> 條款 6.5.2 信息分類，本條款要求組織確保信息對組織的重要性得到適當的保護。
* Clause 6.5.2.1: Classification of information
> 條款 6.5.2.1 信息分類。適用 ISO/IEC 27002:2013，8.2.1中規定的控制，實施指南和其他信息
組織的信息分類系統宜明確將PII視為其實施方案的一部分。在整個分類系統中考慮
PII對於理解組織什麼處理PII(例如種類，特殊類別)，以及存儲此類PII的位置以及它可
以在哪些系統內流通是不可或缺的。
* Clause 6.5.2.2: Labeling of information
> 條款6.5.2.2 信息標記
> 適用 ISO/IEC 27002:2013，8.2.2中規定的控制，實施指南和其他信息以及以下附加補充。ISO/IEC 27002:2013，8.2.2，信息的標記的補充實施指南是:
組織宜確保其控制下的人員了解PII的定義以及如何識別PII信息。
* Clause 6.5.2.3: Handling of assets
	* The organization's information classification system should explicitly consider PII as part of the scheme it implements.
	* Ensure that people under its control are made aware of the definition of PII and how to recognize information that is PII.
> 條款6.5.2.3 資產處理
> 適用 ISO/IEC 27002:2013，8.2.3中規定的控制，實施指南和其他信息
一組織的信息分類系統應明確將PII視為其實施方案的一部分。
一確保受其控制的人員了解PII的定義以及如何識別PII信息。
* Clause 6.5.3: Media handling
	* To prevent unauthorized disclosure, modification, removal or destruction of information stored on media.
> 條款 6.5.3 介質處理
> 為了防止未經授權地披露，修改，刪除或破壞存儲在媒體上的信息。
* Clause 6.5.3.1: Management of removable media
> 條款6.5.3.1 可移動介質的管理
> 適用 ISO/IEC 27002:2013,831中規定的控制,實施指南和其他信息以及以下補充指南
ISO/EC 27002:2013，8.3.1移動介質的管理的補充實施指南是:
組織應記錄用於存儲「PII的移動介質和或設備的任何使用情況。在可行的情況下，組織
宜在存儲PII時，對可移動物理介質和或設備使用加密方法。未加密的介質僅宜在不可避免
的情況下使用，並且在使用未加密的介質和或設備的情況，組織宜實施相應規程或補償控
制(例如防篡改包裝)以降低PI的風險。
ISO/EC 27002:2013，8.3.1，移動介質管理的其他信息是:
被帶出組織的物理範圍之外的移動介質容易丟失，損壞，被不當訪問。加密移動介質可
為PII增加一定程度的保護，從而降低移動介質在安全性和隱私方面受到侵害的風險。
* Clause 6.5.3.2: Disposal of media
> 條款6.5.3.2 介質的處置
> 適用 ISO/IEC 27002:2013，8.3.2中規定的控制，實施指南和其他信息以及以下補充指南。ISO/IEC 27002:2013，8.3.2，介質的處置的補充實施指南是:
在處置存儲PII的移動介質的情況下，安全處理規程應包括在存檔文件中，並實施以確
保先前存儲的PII信息不能被訪問。
* Clause 6.5.3.3: Physical media transfer
> 條款6.5.3.3 物理介質的轉移
> 適用 ISO/IEC 27002:2013，8.3.3中規定的控制，實施指南和其他信息以及以下補充指南。ISO/IEC 27002:2013，8.3.3物理介質的轉移的補充實施指南是:
如果使用物理介質進行信息傳輸，則宜建立一個系統來記錄包含「PII的傳入和傳出物理
介質的信息，包括物理介質的類型，授權的發件人收件人，日期和時間以及物理介質的數
量。在可能的情況下，宜實施其他措施(如加密)，以確保數據只能在目的地而非傳輸途中
被訪問。組織宜在物理介質離開所在場所之前對包含PII的物理介質實施授權的規程，並確保除授權人員之外的任何人都無法訪問PII。
注:確保離開組織場所的物理介質上的PII安全的一種可能的措施是加密PII使其不可訪
問,並且將解密的能力限定在被授權人員身上。
* ISO/IEC 27701 additionally specifies that:
	1. The organization should document any use of removable media and/or devices for the storage of PII.
	2. Wherever feasible, the organization should use removable physical media and/or devices that permit encryption when storing PII.
	3. Unencrypted media should only be used where unavoidable.
	4. If unencrypted media and/or devices are used, the organization should implement procedures and controls to mitigate risks to the PII.
	5. Where removable media on which PII is stored is disposed of, establish and implement documented procedure for secure disposal in order to ensure that previously stored PII could not be accessed by anyone.
	6. If physical media is used for information transfer, establish a system to record incoming and outgoing physical media containing PII.
	7. Implement additional measures such as encryption to ensure that the data can not be accessed in transit.
	8. Before physical media containing PII leaves premises, ensure the PII is not accessible to anyone other than authorized personnel.
> ISO / IEC 27701另外規定：
1.組織應記錄可移動媒體和/或設備用於存儲PII的任何使用。
2.在可行的情況下，組織應使用可移動的物理介質和/或允許在存儲PII時進行加密的設備。
3.僅在不可避免的情況下才應使用未加密的媒體。
4.如果使用未加密的媒體和/或設備，組織應實施程序和控制措施以減輕PII的風險。
5.在處置了存儲PII的可移動介質的地方，建立並實施有記錄的安全處置程序，以確保任何人都無法訪問以前存儲的PII。
6.如果使用物理媒體進行信息傳輸，請建立一個系統來記錄包含PII的傳入和傳出物理媒體。
7.實施其他措施，例如加密，以確保在傳輸過程中無法訪問數據。
8.在包含PII的物理媒體離開場所之前，請確保除授權人員外，其他任何人都無法訪問PII。
## Clause 6.6: Access control
> 條款6.6 訪問控制
* Clause 6.6.1: Business requirements of access control
	* To limit access to information and information processing facilities.
> > 第6.6.1條：訪問控制的業務要求
限制訪問信息和信息處理設施。
* Clause 6.6.1.1: Access control policy
> 第6.6.1.1條：訪問控制策略
* Clause 6.6.1.2: Access to networks and network services
> 第6.6.1.2條：訪問網絡和網絡服務
* Clause 6.6.2: User access management
	* To ensure authorized user access and to prevent unauthorized access to systems and services.
> 條款 6.6.2 用戶訪問管理
> 確保授權用戶訪問並防止未經授權訪問系統和服務。
* Clause 6.6.2.1: User registration and de-registration
> 條款6.6.2.1 用戶註冊和註銷
> 適用 ISOIEC27002:2013，9.2.1中規定的控制，實施指南和其他信息以及以下補充指南:
ISO/IEC 27002:2013，9.2.1，用戶註冊和註銷的補充實施指南是:
管理或操作處理PII的系統和服務的用戶，其註冊和註銷流程宜解決用戶對其的訪問控制
受到危害的情況，例如密碼或其他用戶註冊數據的損壞或危害(例如，無意洩露的情況)。
對於處理PII的系統和服務，組織不宜向用戶重新發布任何已失效或已過期的用戶ID。
在組織將PII處理作為服務提供的情況下，客戶可以負責一些或所有方面的用戶ID管
理。此類情況宜包括在文件化信息中。
注:某些司法管轄區對與處理PII的系統相關的未使用的身份驗證憑據的檢查頻率提出了特
定要求。在這些司法管轄區運營的組織應考慮到這些要求。
* Clause 6.6.2.2: User access provisioning
> 條款6.6.2.2用戶訪問權限設置
> 適用 ISO/IEC 27002:2013，9.2.2中規定的控制，實施指南和其他信息以及以下補充指南。
ISO/IEC 27002:2013的9.2.2，用戶訪問配置的補充實施指南是:
組織宜保持為已授權訪問信息系統(其中包含PII)創建的用戶信息的記錄準確，且保
持最新。該記錄包括關於該用戶的一系列數據，包括用戶PII，以及用於實現提供授權訪問
的所識別的技術控制。
通過設置用戶訪問的唯一ID，實施適當配置以使得系統能夠識別訪問PII的用戶、以
及用戶所做的添加、刪除或更改。這樣的配置在保護了組織的同時也保護了用戶，系統可以
識別用戶已處理、未處理的內容。
在組織將「PII處理作為服務提供的情況下，客戶可以承擔訪問管理的部分或全部職責。
在適當的情況下，組織宜向客戶提供執行訪問管理的方法，例如通過提供管理權限來管理或
終止訪問。此類情況宜包括在文件化信息中。
* Clause 6.6.2.3: Management of privileged access rights
> 條款6.6.2.3 特定訪問權管理
> 適用 ISO/IEC 27002:2013，9.3.3中規定的控制，實施指南和其他信息
* Clause 6.6.2.4: Management of secret authentication information of users
> 條款6.6.2.4 用戶的秘密鑑別信息管理
> 適用 ISO/IEC 27002:2013，9.2.4中規定的控制，實施指南和其他信息
* Clause 6.6.2.5: Review of user access rights
> 條款6.6.2.5 用戶訪問權的評審
> 適用 ISO/IEC 27002:2013，9.2.5中規定的控制，實施指南和其他信息
* Clause 6.6.2.6: Removal or adjustment of access rights.
> 條款6.6.2.6 訪問權的移除或調整
> 適用 ISO/IEC 27002:2013，9.2.6中規定的控制，實施指南和其他信息
* Some additional requirements regarding user access management as per ISO/IEC 27701 are:
	1. Registration and de-registration procedures for users who administer/ operate systems and services that process Pll should address the situations such as the corruption or compromise of passwords or other user registration data.
	2. Any de-activated or expired user IDs should not be reissued to users of systems and services that process Pll.
	3. Organizations should comply with any specific requirements of local jurisdictions.
	4. The organization should maintain an accurate, up-to-date record of the user profiles created for users who have been authorized access to the information system and the Pll contained therein.
	5. In the case where the organization is providing PlI processing as a service, the customer can be responsible for some or all aspects of user ID management and/or access management.Such cases should be included in the documented information.
> 根據ISO / IEC 27701，有關用戶訪問管理的一些其他要求是：
1.管理/操作系統處理PII的用戶的註冊和註銷程序應解決諸如密碼或其他用戶註冊數據損壞或洩露的情況。
2.不應將任何停用或過期的用戶ID重新發布給處理Pll的系統和服務的用戶。
3.組織應遵守當地司法管轄區的任何特定要求。
4.組織應維護準確，最新的用戶檔案記錄，這些檔案是為已被授權訪問信息系統及其包含的PII的用戶創建的。
5.如果組織將PlI處理作為服務提供，則客戶可以負責用戶ID管理和/或訪問管理的某些或全部方面。這種情況應包括在書面信息中。
* Clause 6.6.3: User responsibilities
	* To make users accountable for safeguarding their authentication information.
> 條款6.6.3用戶責任
> 使用戶負責維護其身份驗證信息。
* Clause 6.6.3.1: Use of secret authentication information
> 條款6.6.3.1 機密認證信息的使用
> 適用 ISO/IEC 27002:2013，9.3.1中規定的控制，實施指南和其他信息
* Clause 6.6.4: System and application access control
	* To prevent unauthorized access to systems and applications.
> 條款6.6.4 信息訪問限制
> 防止未經授權訪問系統和應用程序。
* Clause 6.6.4.1: Information access restriction
> 條款6.6.4.1 信息訪問限制
> 適用 ISO/IEC 27002:2013，9.4.1中規定的控制，實施指南和其他信息
* Clause 6.6.4.2: Secure log-on procedures
> 條款6.6.4.2 安全登入程序
> 適用 ISO/IEC 27002:2013，9.4.2中規定的控制，實施指南和其他信息以及以下補充指南。
ISO/IEC 27002:2013，9.4.2，安全登錄程序的補充實施指南是:
如果客戶要求，組織宜具備為客戶控制下的任何帳戶提供安全登錄程序的能力。
* Clause 6.6.4.3: Password management system
> 條款6.6.4.3 密碼管理系統
> ISO/IEC 27002:2013，9.4.3中規定的控制，實施指南和其他信息
* Clause 6.6.4.4: Use of privileged utility programs
> 條款6.6.4.4 特權實用程序的使用
> ISO/IEC 27002:2013，9.4.4中規定的控制，實施指南和其他信息
* Clause 6.6.4.5: Access control to program source code
	* For Secure log-on procedures, ISO/ EC 27002:2013 additionally specifies that if required by the customer, the organization should provide the capability for secure log-on procedures for any user accounts under the customer's control.
> 條款6.6.4.5 程序源代碼的訪問控制
> 對於安全登錄程序，ISO / EC 27002：2013額外規定，如果客戶要求，組織應提供在客戶控制下的任何用戶帳戶的安全登錄程序的功能。
* Password Management: Key Points
	* Awareness: Keep passwords secret.
	* Change initial passwords
	* Clear regulations of password quality (length, character set, history, lock outs, change,...)
	* No storage of passwords, keep password hashes secure
	* Awareness: Do not write down passwords
	* Motto: Do not compromise security with comfort !
> 密碼管理：關鍵點
意識：將密碼保密。
更改初始密碼
明確的密碼質量規定（長度，字符集，歷史記錄，鎖定，更改等）
不存儲密碼，保持密碼哈希安全
意識：請勿寫下密碼
座右銘：不要以舒適感破壞安全性！
* Access Control: Key Points
	* Regular check for unused accounts
	* Regular check for redundant right structures
	* Check access protocols for illegal (attempts of) access
	* Immediate deletion or lock if employee situation changes
	* Report on suspicion of misuse
	* Limit (time) accounts in sensitive areas.
> 訪問控制：關鍵點
定期檢查未使用的帳戶
定期檢查多餘的權利結構
檢查訪問協議是否存在非法（嘗試）訪問
如果員工情況發生變化，立即刪除或鎖定
關於懷疑濫用的報告
在敏感區域的限制（時間）帳戶。
## Access Administration and Control
![](https://i.imgur.com/4wO7xMU.png)
## Access Control on System Basis
![](https://i.imgur.com/v1oE9Gd.png)
## Clause 6.7:Cryptography
* Clause 6.7.1: Cryptographic controls
	* To ensure proper and effective use of cryptography to protect the confidentiality,authenticity and / or integrity of information.
> 條款6.7.1：密碼控制
確保正確有效地使用加密技術，以保護信息的機密性，真實性和/或完整性。
* Clause 6.7.1.1: Policy on the use of cryptographic controls
> 條款6.7.1.1 密碼控制的使用策略
> 適用 ISO/IEC 27002:2013，10.1.1中規定的控制，實施指南和其他信息以及以下補充指南，ISO/IEC 27002:2013，10.1.1，密碼控制的使用策略的補充實施指南是:
某些司法管轄區可能要求使用加密技術來保護特定類型的PII，例如健康數據，居民登
記號碼，護照號碼和駕駛執照號碼。組織宜向客戶提供有關其使用什麼樣的加密技術來保護其處理的I的信息。組織還宜向客戶提供相應的功能信息，以幫助客戶應用自己的加密技術保護自身的PII信息。
南。
* Clause 6.7.1.2: Key management
> 條款6.7.1.2 密鑰管理
> 適用 ISO/IEC 27002:2013，10.1.2中規定的控制，實施指南和其他信息
* Regarding policy on the use of controls, ISO/lEC 27002:2013 additionally specifies that the organization should provide information to the customer regarding :
	1. The circumstances in which cryptography is used to protect the PII it processed.
	2. Any capabilities it provides that can assist the customer in applying their own cryptographic protection.
> 關於控件使用的政策，ISO / IEC 27002：2013另外指定組織應向客戶提供有關以下方面的信息：
1.使用密碼術保護它處理的PII的情況。
2.它提供的任何可以幫助客戶應用自己的加密保護的功能。
## Clause 6.8: Physical and environmental security
> 條款6.8 物理與環境安全
* Clause 6.8.1: Secure areas
	* To prevent unauthorized physical access, damage and interference to the organization's information and information processing facilities.
> 條款6.8.1 安全區域
> 防止未經授權的物理訪問，損壞和干擾組織的信息和信息處理設施。
* Clause 6.8.1.1: Physical security perimeter
* Clause 6.8.1.2: Physical entry controls
* Clause 6.8.1.3: Securing office, room and facilities
* Clause 6.8.1.4: Protecting against external and environmental threats
* Clause 6.8.1.5: Working in secure areas
* Clause 6.8.1.6: Delivery and loading areas.
> 條款 6.8.1.1物理安全邊界
適用 ISO/IEC 27002:2013，11.1.1中規定的控制,實施指南和其他信息。
條款 6.8.1.2物理入口控制
適用 ISO/IEC 27002:2013，11.1.2中規定的控制,實施指南和其他信息。
條款 6.8.1.3辦公室,房間和設施的安全保護
適用 ISO/IEC 27002:2013，11.1.3中規定的控制,實施指南和其他信息。
條款 6.8.1.4外部和環境威脅的安全防護
適用 ISO/IEC 27002:2013，11.1.4中規定的控制,實施指南和其他信息。
條款 6.8.1.5在安全區域工作
適用 ISO/IEC 27002:2013，11.1.5中規定的控制,實施指南和其他信息。
條款 6.8.1.6 交接區
適用 ISO/IEC 27002:2013，11.1.6中規定的控制,實施指南和其他信息。
* Clause 6.8.2: Equipment
	* To prevent loss, damage, theft or compromise of assets and interruption to the organization's operations.
> 條款6.8.2 設備
> 防止資產的丟失，損壞，被盜或損害以及組織運作中斷。
* Clause 6.8.2.1: Equipment siting and protection
* Clause 6.8.2.2: Supporting utilities
* Clause 6.8.2.3: Cabling security
* Clause 6.8.2.4: Equipment maintenance
* Clause 6.8.2.5: Removal of assets
* Clause 6.8.2.6: Security of equipment and assets off-premises
* Clause 6.8.2.7: Security disposal or re-use of equipment
* Clause 6.8.2.8: Unattended user equipment
* Clause 6.8.2.9: Clear desk and clear screen policy
* Additional requirements as per ISO/IEC 27701:2019
> 條款6.8.2.1 設備安置和保護
適用 ISO/IEC 27002:2013，11.2.1中規定的控制，實施指南和其他信息。
條款 6.8.2.2 支持性設施
適用 ISO/IEC 27002:2013，11.2.2中規定的控制，實施指南和其他信息。
條款 6.8.2.3 布線安全
適用 ISO/IEC 27002:2013，11.2.3中規定的控制，實施指南和其他信息。
條款 6.8.2.4 設備維護
適用 ISO/IEC 27002:2013，11.2.4中規定的控制，實施指南和其他信息。
條款 6.8.2.5 資產的移動
適用 ISO/IEC 27002:2013，11.2.5中規定的控制，實施指南和其他信息。
條款 6.8.2.6 組織場所外的設備與資產安全
適用 ISO/IEC 27002:2013，11.2.6中規定的控制，實施指南和其他信息。
* Sub-clause 6.8.2.7
	1. If storage space is re-assigned, ensure that any PII previously residing on that storage space is not accessible.
	2. The risk that another user can access the PII should be avoided by specific technical measures.
	3. For secure disposal or re-use, equipment containing storage media that can possibly contain PII should be treated as though it does contain PII.
> 條款 6.8.2.7 設備的安全處置或再利用
> 適用 ISO/IEC 27002:2013，11.2.7，實施指南和其他信息。
> 1.如果重新分配了存儲空間，請確保以前位於該存儲空間上的任何PII均不可訪問。
2.應通過特定的技術措施避免其他用戶可以訪問PII的風險。
3.為了安全處置或重複使用，應將包含可能包含PII的存儲介質的設備視為確實包含PII。
* Sub-clause 6.8.2.8:
> 條款 6.8.2.8 無人值守的用戶設備
> 適用 ISO/IEC 27002:2013，11.2.8，實施指南和其他信息。
* Sub-clause 6.8.2.9:
> 條款6.8.2.9 清理桌面與屏幕策略
> 適用 ISO/IEC 27002:2013，11.2.7，實施指南和其他信息。
* Restrict the creation of hardcopy material, including PII， to the minimum needed to fulfill the identified processing purpose.
> 將硬拷貝材料（包括PII）的創建限制在滿足已確定的處理目的所需的最低限度。
## Device Protection
![](https://i.imgur.com/Tx1VsPC.png)
## Clause 6.9:Operations security
> 條款6.9 運行安全
* Clause 6.9.1: Operational procedures and responsibilities
	* To ensure correct and secure operations of information processing facilities.
> 條款6.9.1 運行規程和責任
> 確保信息處理設施的正確和安全運行。
* Clause 6.9.1.1: Documented operating procedures
* Clause 6.9.1.2: Change management
* Clause 6.9.1.3: Capacity management
* Clause 6.9.1.4: Separation of development, testing and operational environments
> 條款 6.9.1.1文件化的操作規程
適用 ISO/IEC 27002:2013，12.1.1中規定的控制，實施指南和其他信息。
條款 6.9.1.2 變更管理
適用 ISO/IEC 27002:2013，12.1.2中規定的控制，實施指南和其他信息。
條款 6.9.1.3 容量管理
適用 ISO/IEC 27002:2013，12.1.3中規定的控制，實施指南和其他信息。
條款 6.9.1.4開發,測試和運行環境的分離
適用 ISO/IEC 27002:2013，12.1.4中規定的控制，實施指南和其他信息。
* Clause 6.9.2: Protection from malware
	* To ensure that information and information processing facilities are protected against malware.
	* The requirements of this sub- clause are specified under single sub-clause: 6.9.2.1 Controls against malware
> 條款6.9.2：防範惡意軟件
確保保護信息和信息處理設施免受惡意軟件的侵害。
本小節的要求在單個小節中指定：
* Clause 6.9.2.1
> 條款6.9.2.1惡意軟件的控制
適用 ISO/IEC 27002:2013，12.2.1中規定的控制，實施指南和其他信息。
* Malware Protection:Key Points
	1. Use only approved and licensed software
	2. Installation and regular update of virus scanners
	3. Regular audits of critical systems for non-approved files or software
	4. Clear procedures in case of virus attacks
	5. Establish early warning procedures (CERT)
	6. Contingency plans in case of virus incidents.
> 惡意軟件防護：要點
1.僅使用批准和許可的軟件
2.病毒掃描程序的安裝和定期更新
3.定期審核關鍵系統中未經批准的文件或軟件
4.清除程序以防病毒攻擊
5.建立預警程序（CERT）
6.發生病毒事件時的應急計劃。
* Clause 6.9.3: Backup
	* The requirements of this sub- clause are specified under single sub-clause: 6.9.3.1 Information backup
> 條款6.9.3 備份
> 本小節的要求在單個小節中規定：6.9.3.1信息備份
* Information Backup:Key Points
	1. Storage in secure, remote area
	2. Sufficient physical protection
	3. Regular test of backup media
	4. Regular test of restore procedures
	5. Replace backup media according to manufacturer guidelines
	6. Consistent protocols (uninterrupted)
	7. User PC regulation.
> 信息備份：重點
1.存放在安全的偏遠地區
2.足夠的身體保護
3.定期測試備份媒體
4.定期測試還原程序
5.根據製造商準則更換備份媒體
6.一致的協議（不間斷）
7.用戶PC法規。
> 6.9.3.1 信息備份
適用 ISO/IEC 27002:2013，12.3.1中規定的控制，實施指南和其他信息以及以下補充指南。ISO/IEC 27002:2013，12.3.1信息備份的補充實施指南是:
組織宜制定策略，以滿足PII的備份，恢復和恢復要求(可以是整體信息備份策略的一
部分)，進而滿足刪除備份數據中包含的PII信息的要求(例如合同和/或法律要求)。
在這方面，PII的具體職責可能取決於客戶。組織宜確保已通知客戶有關備份的服務限
制。如果組織明確向客戶提供備份和還原服務，組織宜向他們提供有關其備份和恢復PII功
能的明確信息。某些司法管轄區對PII的備份頻率，備份的審查頻率，測試和恢復頻率或者相應的恢復規程提出了具體要求。在這些司法管轄區運營的組織宜證明符合這些要求。
可能存在需要恢復PII的情況，可能是由於系統故障，攻擊或災難。當PII恢復時(通
常來自備份介質)，需要建立確保PII恢復到可以確保PII完整性的狀態，和識別PII不
準確和或不完整的狀態以及解決這些問題的流程(可能涉及PII主體)。
組織宜有PII恢復工作的流程和日誌。至少，PII恢復的日誌宜包含:
一負責恢復的人的姓名;
一已恢復的PII的說明。
一些司法管轄區規定了PII恢復工作日誌的內容。組織宜能夠記錄恢復日誌的適當內容以符合轄區特定要求。此類審議的結論宜包括在文檔化信息中。
在本標準中記述的關於分包商處理PII信息的控制(請參閱6.53.3,6.12.1.2)中，規定了使用分包商來存儲PII處理的複製或備份的要求。本標準中的控制(6.10.2.1)也包含了與備份和恢復相關的物理介質傳輸的情況。
* Clause 6.9.4: Logging and monitoring
	* To record events and generate evidence. The requirements of this sub-clause are specified under four further sub-clauses:
> 條款 6.9.4 日誌和監視
* Clause 6.9.4.1: Event logging
> 條款6.9.4.1 事態日誌
> 適用 ISO/IEC 27002:2013，12.4.1中規定的控制，實施指南和其他信息以及以下補充指:ISO/IEC 27002:2013，12.4.1事態日誌的補充實施指南是:
宜建立一個流程並使用連續的，手動或自動化的監控和警報流程來審查事件日誌。手動
審查宜以明確的、文檔化規定的周期實施，以識別違規行為並提出補救措施。
在可能的情況下，事件日誌應記錄對的訪問，包括由誰，何時，訪問哪個PII主體
的PII，以及由於事件而進行的任何更改(添加，修改或刪除)。
如果多個服務提供者參與提供服務，則在實施本指南時可能會有不同或共享角色。宜明
確定義這些角色並將其包含在文檔化信息中，並宜就供應者實施的任何日誌訪問達成協議。
PII處理者的實施指南:
組織宜定義關於客戶是否，何時以及如何確保日誌信息可用的標準。這些標準宜提供給
客戶。如果組織允許其客戶訪問組織控制的日誌記錄，組織宜實施適當的控制以確保客戶只能
訪問與該客戶的活動相關的記錄，不能訪問與其他客戶的活動相關的任何日誌記錄，並且不
能以任何方式修改日誌。
* Clause 6.9.4.2: Protection of log information
> 條款6.9.4.2 日誌信息的保護
> 適用 ISO/IEC 27002:2013，12.4.2中規定的控制，實施指南和其他信息以及以下補充指ISO/IEC 27002:2013，12.4.2，日誌信息的保護的補充實施指南是:
記錄的日誌信息例如安全，監視和操作診斷可以包含PII。宜採取措施如控制訪問(參
見ISO/IEC 27002:2013，9.2.3)，以確保記錄的信息僅按預期使用。
宜建立一個規程，最好是自動規程，以確保按照保留計劃刪除或去標誌記錄信息(參見
7.4.7)
* Clause 6.9.4.3: Administrator and operator logs
> 條款6.9.4.3 管理員和操作員日誌
> 適用 ISO/IEC 27002:2013，12.4.3中規定的控制，實施指南和其他信息
* Clause 6.9.4.4: Clock synchronization
> 條款6.9.4 時鐘同步
> 適用 ISO/IEC 27002:2013，12.4.4中規定的控制，實施指南和其他信息
* Clause 6.9.5: Control of operational software
	* To ensure the integrity of operational systems.
	* The requirements of this sub-clause are specified under single sub-clause 6.9.5.1 Installation of software on operational systems.
> 條款6.9.5 運行軟件的控制
> 確保操作系統的完整性。本小節的要求在單個小節6.9.5.1中指定，在操作系統上安裝軟件。
* Clause 6.9.6: Technical vulnerability management
	* To prevent exploitation of technical vulnerabilities. The requirements of this sub-clause are specified under two further sub-clauses:
> 條款 6.9.6 技術脆弱性管理
> 適用 ISO/IEC 27002:2013，12.5.1中規定的控制，實施指南和其他信息
> 防止利用技術漏洞。本條款的要求在另外兩個條款中規定：
* Clause 6.9.6.1: Management of technical vulnerabilities
> 條款6.9.6.1 技術脆弱性的管理
> 適用 ISO/IEC 27002:2013，12.6.1中規定的控制，實施指南和其他信息
* Clause 6.9.6.2: Restrictions on software installation
> 條款6.9.6.2 軟件安裝限制
> 適用 ISO/IEC 27002:2013，12.6.2中規定的控制，實施指南和其他信息
* Clause 6.9.7: Information systems audit considerations
	* To minimize the impact of audit activities on operational systems.
	* The requirements of this sub-clause are specified under single sub-clause 6.9.7.1 Information systems audit controls.
> 條款6.9.7 信息系統審計的考慮
> 盡量減少審核活動對操作系統的影響。
> 本條款的要求在單個條款6.9.7.1信息系統審核控制中指定。
* Clause 6.10: Communications security
> 條款6.10 通訊安全
* Clause 6.10.1: Network security management
	* To ensure the protection of information in networks and its supporting information processing facilities.
> 條款6.10.1 網路安全管理
> 適用 ISO/IEC 27002:2013，13.1.1中規定的控制，實施指南和其他信息
> 確保保護網絡及其支持的信息處理設施中的信息。
* Clause 6. 10. 1. 1: Network controls
> 條款6.10.1.1 網路控制
* Clause 6. 10. 1.2: Security of network services
> 條款6.10.1.2 網路服務的安全
* Clause 6. 10. 1.3: Segregation in networks
* Network Management: Key Points
	1. Separation of network and host operations
	2. Detailed regulations for remote administration
	3. Detailed regulations for data transmission via external networks
	4. Coordination of activity (internal, external partners).
* Clause 6.10.2: Information transfer
	* To maintain the security of information transferred within an organization and with any external entity.
* Clause 6.10.2. 1: Information transfer policies and procedures
* Clause 6.10.2.2: Agreements on information transfer
* Clause 6.10.2.3: Electronic messaging
* Clause 6.10.2.4: Confidentiality or non-disclosure agreements.