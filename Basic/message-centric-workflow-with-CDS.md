# 以系统交互的视角,从预约挂号,急诊信息流程,药房消息处理,术前准备,术中等分析可能应用临床决策支持技术的场景和会用到的临床决策支持的类型.



| 工作流 | 阶段 | 任务 | 活动 | 子活动 | | 参与角色  | Alerts/Reminders |   Order sets |  InfoButtons  | Data display  |  |Documentation templates|    
| ------ | ----- | ----- | ----- | ------ | ------ | ----- | ----- | ----- | ------ | ------ |    
| 以消息为中心|  |  |  | || |  |  |  | | | |    
| 病人预约申请|  | 核对病人是否符合要求 | 审核 |1.16 (获取病人人口学信息Access patient demographic data),17.3 (审核别人医保是否合格Review display of patients’ insurance eligibility) || 挂号人员| x |  |  | | | |    
| |  | 下达访前检验医嘱 | 医嘱 |10.4(下达检验医嘱order lab study) || 医师| x | x |  | | | |    
| |  | 预约 | 执行 | || 挂号人员|  |  |  | | | |    
| |  | 转诊到其他机构 | 医嘱 |10.10 (下达转诊申请医嘱Order provider referral) || 医师|  | x |  | | | |    
| |  | Refer to telephone consultation or secure messaging | 执行 | || 医师、护士|  |  |  | | | |    
| 急诊室信息流程|  | 告知急诊科ED病人即将到达 | 通知 | || EMS急诊护理人员|  |  |  | | | |    
| |  | 传输记录到救护车的run sheet | 创建 |7.1(记录每次encounter的病程记录Document a progress note on each encounter) || 护士|  |  |  | | | |    
| |  | 口头报告病例给ER |  | || EMS急诊护理人员|  |  |  | | | |    
| |  | 快速挂号、确认病人身份 | 创建 |7.8(Document encounter) || 护士|  |  |  | | |x |    
| |  | 书写报告 | 创建 |7.40(记录生命体征 vital signs); 7.41(记录体重weight) || EMS急诊护理人员|  |  |  | | | |    
| |  | 将报告传输给ER | 传输 |19.5(Transmit clinical summary) || EMS急诊护理人员|  |  |  | | | |    
| 药房消息处理| Intake | Take message | 执行 | || 挂号人员|  |  |  | | | |    
| |  | 核对Rx | 审核 |1.10-14(访问既往多次就诊的药物过敏史、既往多次就诊的病史、正在服用的药物列表、药嘱、非药物过敏史Access medication allergy history over multiple visit, history over multiple visits, active medication list and supplements, medication order, nonmedication allergy history over multiple visits), 10.10(下达转诊医嘱Order provider referral), 20.4-11( 更新药物过敏、药物列表、药嘱、非药物过敏，下达药嘱Update medication allergy, medication list, medication order,nonmedication allergy, order for medication),17.3-9(病人保险合格的展示、检验结果的接收、收缩压、舒张压的变化、提供的患者教育等Review display of patients’ insurance eligibility, received clinical lab test results for user interface, changes in diastolic blood pressure/height/systolic blood pressure/weight,education provided) || 护士、医师助理| x |  | x |x | | |    
| |  | 核对处方集 | 审核 |17.10(审核电子处方集或者药物列表Review electronically formulary or preferred drug list) || 护士、医师助理| x |  |  |x | | |    
| |  | Prior authorization Check | 审核 |19.10-13(向医保传输保险合格核对信息、向医保查询合格性Transmit insurance eligibility check to private/public payers, eligibility queries to private/public payers) || 医师| x |  |  |x | | |    
| | Routing to prescriber | 核对DDI | 审核 |3.2(实时药物-药物禁忌提醒Alert for drug-drug contraindications(real time)) || 护士、医师| x |  |  |x | | |    
| |  | 用药变更 | 创建 |10.1(下达药嘱Order(prescribe) medication), 10.5-7(下达常用药嘱和新药嘱Order medication as generic, new medication),20.6(更新药嘱列表Update medication list) || 医师| x | x | x |x | |x |    
| |  | 指导变更 | 记录 |7.1(Document a progress note for each encounter) || 护士|  |  |  |x | | |    
| |  | 获取预授权 | 接收 |12.8-9(从保险机构收到电子格式的保险合格核对信息Receive insurance eligibility check electronically from private payers/public payers) || 护士、医师助理|  |  |  | | |x |    
| | Routing back | 联系药房 | 通知 |19.6(传输电子处方Transmit electronic permissible medication order(prescription)) || |  |  |  | | |x |    
| |  | 联系病人 | 通知 |9.1-2(告知病人随访和预防保健相关信息Notify patients for follow-up care and preventive care) || 护士、医师助理、医师|  |  |  | | |x |    
| |  | 传输处方 | 传输 |19.18-24(Transmit to other provider diagnostic test results/immunizations/medication allergy list/medication list/problem list/procedures performed, transmit to patient summary record from other providers) || 医师、护士|  |  |  | | |x |    
| 与其他医师的相关消息|  | Msg. intake or outreach to other clinician | 传输 |19.18-24(Transmit to other provider diagnostic test results/immunizations/medication allergy list/medication list/problem list/procedures performed, transmit to patient summary record from other providers) || 医师、护士|  |  |  |x | |x |    
| |  | 商讨病例 | 执行 | || 医师、护士|  |  |  |x | |x |    
| |  | 达成一致 | 记录 |7.1(Document a progress note for each encounter) || 医师、护士|  |  |  |x | |x |    
| 术前阶段|  | 术前提醒病人相关信息 | 提醒 |9.1-2(告知病人随访和预防保健信息Notify patients for follow-up care and preventive care) || 医师、护士|  |  |  |x | |x |    
| |  | 联系护士团队 | 通知 |19.18-24(Transmit to other provider diagnostic test results/immunizations/medication allergy list/medication list/problem list/procedures performed, transmit to patient summary record from other providers || 医师、护士|  |  |  |x | |x |    
| |  | 联系麻醉师团队 | 通知 |19.18-24(Transmit to other provider diagnostic test results/immunizations/medication allergy list/medication list/problem list/procedures performed, transmit to patient summary record from other providers || 医师、护士|  |  |  |x | |x |    
| |  | 电话确认 | 通知 |19.18-24(Transmit to other provider diagnostic test results/immunizations/medication allergy list/medication list/problem list/procedures performed, transmit to patient summary record from other providers || 医师、护士|  |  |  |x | |x |    
| |  | 联系外科医生 | 通知 |19.18-24(Transmit to other provider diagnostic test results/immunizations/medication allergy list/medication list/problem list/procedures performed, transmit to patient summary record from other providers || 医师、护士|  |  |  |x | |x |    
| 手术安排| 预约手术 | 电话答复 | 执行 | || 护士、医师助理|  |  |  |x | |x |    
| |  | 核对时段 | 审核 | || 挂号人员|  |  |  |x | |x |    
| |  | 向pt确认 | 创建 |9.1-2(Notify patients for follow-up care and preventive care) || 挂号人员|  |  |  |x | |x |    
| |  | 提醒病人 | 提醒 |9.1-2(Notify patients for follow-up care and preventive care) || 挂号人员|  |  |  |x | |x |    
| | 安排手术人员 | Review historical patient visits | 审核 | || |  |  |  | | | |    
| |  | 核对人员是否空闲 | 审核 | || |  |  |  | | | |    
| |  | 分配时间 | 记录 | || |  |  |  | | | |    