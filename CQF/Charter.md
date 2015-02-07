# Clinical+Quality+Framework+Charter+and+Members   

## 1.挑战
鉴于CDS和eCQM质控指标紧密相关，拥有很多共同的需求，但是二者所采用的标准则是各异的，主要是表达患者数据和计算机化处理逻辑的方法是不同的      

| 类别 | 患者数据|处理逻辑|     
| ----------- | ----------- | ----------- |      
| CDS | VMR | CDS knowledge artifact实施指南 |    
| ECQM | quality reporting data architecture物理模型quality data model逻辑模型 | Health quality measure format HQMF 物理模型Quality data model逻辑模型 |


## 2.项目范围
* 定义、确定 整合一下几类CDS和eCQM的标准
    * A——metadata元数据：确定两个领域公用的一些元数据，统一这些元数据的表达方式
    * B——患者数据模型:能够同时满足CDS和eCQM的需求
    * C——逻辑表达语言：开发一种能够表达两类逻辑的语言
* 对已有的CDS和eCQM标准进行重构，形成统一的标准
* 尽可能的对产生的标准进行试点并及时作出调整
* 利用临床质控人员的参与 提升产生的标准的可用性和严密性
* 支持这些标准在HL7的投票和发布


## 3.核心价值

Much of the standards harmonization work is already underway in HL7 work groups. The Clinical Quality Framework Standards and Interoperability (S&I) initiative will promote wider visibility into the standards under development and provide additional implementation-based feedback, leading to more robust specifications.

CQF Value Statement Pic 20140410.jpg
CDS and eCQM are complementary and essential components of clinical quality improvement (CQI). Harmonizing the electronic standards used for these two domains and developing a common Clinical Quality Framework will have a number of important benefits, including the following:

    Reduced implementer burden with regard to time and cost.
    Increased re-use of eCQM artifacts in CDS and vice versa.
    Improved standards quality through the unification of community effort.



Community involvement in the harmonization of the eCQM and CDS standards gives participants the following:

    The ability to accelerate the standards development process.
    Early access to standards under development for internal prototyping, etc.



Furthermore, implementation-based feedback will enhance the quality of the standards that are developed. Ultimately, the work of the CQF initiative will facilitate the achievement of improved clinical quality and outcomes.
## 4. 预期目标

    Harmonized standards for representation of quality improvement (CDS and eMeasures) artifacts and for exchange of data related to quality improvement.
    Alignment with Meaningful Use and other related regulations.
    Unification of the existing CDS and eCQM standards communities.
    Broader visibility into the harmonized standards being developed in HL7.
    Incorporation of implementation-based feedback into CDS and eCQM standards development activities.

## 5. 预期输出 

    Project Charter
    Use cases and functional requirements
    List of relevant standards and stakeholders
    Harmonized standards for the domain
    CDS and eCQM standards refactored to use new harmonized standards
    Implementation feedback report
    Completion of pilots that demonstrate one or more use cases
    Report on lessons learned and experience gained during pilots

## 6. 相关标准和干系人 
Relevant Standards, Schemas, Formats, Terminologies, and Value Sets

###   数据标准 Data Model

– C-CDA (Consolidated Clinical Documentation Architecture)     
– CIMI (Clinical Information Modeling Initiative)      
– FHIM (Federal Health Information Model)     
– ebRIM/ebRS      
– HL7 Care Record     
– HL7 FHIR    
– HL7 HQMF      
– HL7 RIM     
– HL7 v2.5.1     
– QDM (Quality Data Model)     
– QRDA (Quality Reporting Documentation Architecture) I, II, III      
– vMR (Virtual Medical Record)      
 
###  安全标准  Security Layer

– TLS+SAML      
– TLS+OAuth2      
– S/MIME     

###  传输标准    Transport Layer

– MU2 ModSpec RTM     
– SOAP (IHE SOAP)     
– RESTful (IHE mHealth)     
– Direct     
– HTTP     
– SMTP     

###  知识表达标准 Knowledge Representation

– ArdenML     
– Arden Syntax     
– AHRQ eRecommendations Format     
– CDSC L3     
– CREF     
– HQMF (Health Quality Measure Format)     
– HL7 CDS Knowledge Artifact Specification      
– GELLO     
– GEM (Guideline Elements Model)     

###  术语和值集Terminologies and Value Sets

– IHE Sharing Value Sets      
– SNOMED CT, LOINC, ICD, CPT, RxNorm, NDC, etc.      
– Value Sets Used in eCQMs       

###  其他相关标准  Other Relevant Standards

– HL7 Decision Support Service (DSS) Specifications      
– HL7 Context Aware Information Retrieval (InfoButton)       
– HL7 Model Interchange Format     
– IHE Care Management Profile    
– IHE Retrieve Clinical Knowledge Profile (Profile for InfoButton)     
– IHE RFD (Retrieve Clinical Format for Data Capture)     
– IHE RPE (Request for Procedure Execution)     
– IHE Request for Clinical Guidance Profile (an implementation of HL7 DSS)      

###   相关的干系人Relevant Stakeholders              


*  Content and Guideline Creators (such as but not limited to):

– Academic and Community Provider Organizations     
– Content Publishers     
– HIT Vendors      
– Medical Research Organizations      
– Medical Societies     
– Patients (PGHD – Patient Generated Health Data)     
– Pharmaceutical and Medical Device Companies     
– Public Health Agencies and other Government Agencies (CDC, NIH, NLM, FDA, etc.)      
– Standard Terminology Suppliers        

*   Content Integrators (such as but not limited to):

– Clinical Decision Support Consortium    
– Content Publishers who offer CDS services     
– Content Implementers (i.e. consulting firms)    
– HIT Vendors    
– HIEs     
– HISPs (Health Information Service Providers)     
– OpenCDS     
– Providers implementing clinical content in an HIT system     
– Registries (e.g., professional association registries)        


*  Content Users (such as but not limited to):    

– Case Managers     
– Compliance, regulatory, and legal entities     
– Home Health Agencies    
– Patients     
– Payers and their agents involved in revenue cycle     
– Practitioners     
– Provider Organizations (including VA and DoD)     
– Public Health Agencies    
– Pharmacies and MTM Services     
– Social Security Administration (SSA)     

*   Standards and Schema Development Agencies (such as but not limited to):

– ASTM (American Society for Testing and Materials)     
– CDSC (Clinical Decision Support Consortium)    
– GLIDES (GuideLines Into DEcision Support)    
– HITSP (Health Information Technology Standards Panel)    
– HL7 (Health Level Seven International)     
– IHE (Integrating the Healthcare Enterprise)     
– NQF (National Quality Forum)     
– OMG (Object Management Group)     

*  Quality Measurement Entities (such as but not limited to):

– AHRQ USHIK (Agency for Healthcare Research and Quality United States Health Information Knowledgebase)     
– AMA-convened Physician Consortium for Performance Improvement® (PCPI®)     
– ANA (American Nursing Association) NDNQI (Nursing Database Nursing Quality Indicators)     
– BTE (Bridges to Excellence)     
– CDC (Centers for Disease Control and Prevention)     
– CMS Hospital Inpatient Quality Reporting System     
– CMS Hospital Outpatient Quality Reporting System    
– CMS/PQRS (Center for Medicare and Medicaid Services, Physician Quality Reporting System)      
– NCQA (National Committee for Quality Assurance)      
– NQF (National Quality Forum)      
– OFMQ (Oklahoma Foundation for Medical Quality)      
– QOPI (Quality Oncology Practice Initiative)     
– The Joint Commission      

## 7. 潜在风险
1.Given the aggressive timeline, a schedule delay in one item may have significant downstream scope and schedule impact.       

    Mitigation/Response: Prioritize activities and leverage community expertise.


2.Additional review and implementation-based feedback may introduce delays into the development of harmonized standards.     

    Mitigation/Response: Review and implementation feedback are critical to the quality of standards; the benefits outweigh the risk.


3.Implementation and piloting of non-final standards may result in “throwaway” work.     

    Mitigation/Response: Implementation feedback is critical to the quality of standards; the benefits outweigh the risk.


4.Vendors’ focus on Meaningful Use activities may impact their ability to participate in pilots.     

    Mitigation/Response: Focus on items already in EHR certification criteria (at least proposed), actively engage with vendors, and make tools and resources (e.g., an open-source environment) available to them to make participation easier and beneficial.




Additional risks and mitigations may be identified during discovery phase.

## 8. 时间点           


![](material/CQF_HL_TimelineGraphic20140410.jpg)

## 9. 参考资料
1. [原始网站](http://wiki.siframework.org/Clinical+Quality+Framework+Charter+and+Members)
