# 以患者的视角,从门诊,急诊,门诊手术,住院的一系列就医的流程中分析可能应用临床决策支持技术的场景和会用到的临床决策支持的类型.


| 工作流 | 阶段 | 任务 | 活动 | 子活动 |  | 参与角色   | Alerts/Reminders |   Order sets |  InfoButtons  | Data display  | |Documentation templates  |                
| ------ | ----- | ----- | ----- | ------ | ------ | ----- | ----- | ----- | ------ | ------ |     ------ |   
| 以病人为中心|  |  |  | || |  |  |  | | | |    
| 门诊| Intake and Nurse assessment | 挂号/登记 | 记录 |1.16 (访问患者人口学信息), 7.6 (记录出生日期), 7.9-12 (记录民族、性别、身高、成长曲线), 7.14 (记录医保类型), 7.25 (记录使用语言), 7.28 (记录种族), 7.34(记录吸烟状态),7.8(记录门诊情况encounter) || 挂号人员| x |  |  | | |x |    
| |  | 测量记录生命体征 | 记录 |7.40(记录生命体征 vital signs); 7.41(记录体重weight) || 医师助理、护士| x |  |  | | |x |    
| |  | 用药回顾 | 回顾 |1.10-12(访问药物过敏史、用药史、现用药列表mediation allergy history, medication history, active medication list ) || 医师助理、护士|  |  |  |x | | |    
| |  | Handoff/移交 | 通知 |2.2(临床摘要的接收确认acknowledge receipt of clinical summary), 19.5(临床摘要的传输transmit clinical summary), 12.13(接收来自其他机构的病人摘要记录receive patient summary allergy record from other providers) || 医师助理、护士、医师|  |  | x | | |x |    
| | 医师评估 | 表单回顾 | 回顾 |1.1-28 (访问医疗记录中的所有信息Access - all information in medical record)17.13 (回顾质控结果Review quality measure results || 医师|  |  |  |x | | |    
| |  | 询问病人 | 执行 | || 医师助理、护士、医师| x |  |  | | |x |    
| |  | 记录病史 | 记录/文档 |7.1(每次encounter 记录病程记录Document a progress note for each encounter) || |  |  |  | | |x |    
| |  | 诊断和制定治疗计划 | 执行 | || 医师|  |  | x | | |x |    
| |  | 回顾先前的检验结果 |  |17.1-2(回顾检验结果报告中所有信息review all information for a lab test report, clinical lab tests received with LOINC codes) || |  |  |  | | |x |    
| |  | 下达检验医嘱 | 医嘱 |10.4(下达检验医嘱order lab study) || 医师| x | x | x |x | |x |    
| |  | 处方 | 医嘱 |10.1(下达药嘱Order medication),10.5-7 (下达一般药嘱和新药嘱Order medication generic-, new), 19.6 (处方的传输transmit prescription) || 医师| x | x | x |x | |x |    
| |  | 转诊/转科 | 医嘱 |10.10 (下达转科/转诊医嘱Order provider referral) || 医师|  | x |  | | |x |    
| |  | 治疗 | 执行 | || 医师、护士|  |  |  | | | |    
| |  | 患者咨询 | 执行 | || 医师、护士| x |  |  | | |x |    
| | Check out/离开 | Give out instructions | 记录 |2.1(确认已接受患者教育Acknowledge education receipt || 医师助理、护士| x |  |  |x | |x |    
| |  | 安排下次预约  | Create |15.1-2 (提醒患者下次随访、预防保健Remind patient per patient preference for follow-up, preventive care) || 挂号人员|  |  |  | | | |    
| 急诊| 高危病人到达急诊室 | 通知救护车 | 通知 |12.13(收到来自其他机构的患者病历摘要Receive patient summary record from other providers), 2.2(确认接收Acknowledge receipt of clinical summary), 19.5(传输患者摘要信息Transmit clinical summary) || 护士|  |  |  | | |x |    
| |  | 测量、记录生命体征 | 记录 |7.40(记录生命体征 vital signs); 7.41(记录体重weight) || EMS医疗急救护理人员| x |  |  | | |x |    
| |  | Handoff | 记录 |7.1(记录每个encounter的病程记录) || 护士|  | x |  | | |x |    
| |  | 询问病人 | 执行 | || 护士、医师| x |  |  | | |x |    
| |  | 记录病史 | 记录/文档 |7.1(每次encounter 记录病程记录Document a progress note for each encounter) || 医师|  |  |  | | |x |    
| | 低危的urgent care /Safety net care 到达急诊室 |  |  | || |  |  |  | | | |    
| |  | 询问病人 | 执行 | || 护士、医师| x |  |  | | |x |    
| |  | 记录病史 | 记录/文档 |7.1(每次encounter 记录病程记录Document a progress note for each encounter) || 医师|  |  |  | | |x |    
| |  | 转诊/转科 | 医嘱 |10.10 (下达转科/转诊医嘱Order provider referral) || 医师|  | x |  | | |x |    
| |  | 传输文档 | 传送 |12.13(接收来自其他机构的病历摘要Receive patient summary record from other providers), 2.2(确认病历摘要的接收Acknowledge receipt of clinical summary), 19.5(传输病历摘要Transmit clinical summary) || 护士、医师助理|  |  |  | | | |    
| | 医师评估ED treatment (Clinician assessment | 转诊审查 | review |2.2临床摘要接收确认(Acknowledge receipt of clinical summary) || 护士、医师| x |  |  |x | |x |    
| |  | 下达检验医嘱 | 医嘱 |10.4(下达检验医嘱Order lab study), 10.2(影像检查diagnostic imaging procedure), 10.8(手术操作procedure), 12.2(接收检验结果Receive clinical lab test result), 17.2(接收LOINC编码的检验结果Review clinical lab tests received with LOINC codes),20.13(依据检验结果 更新病历信息Update patients record based on lab test result || 医师| x | x | x |x | |x |    
| |  | 诊断 | 记录/文档 |7.1(记录每个encounter的病程记录) || 医师|  |  |  | | | |    
| |  | 下达处方 | review 医嘱 |10.5-7(下达药嘱Order medication), 13.1(依据CDS规则的推荐疗法 建议调整治疗Recommend care modifications based on clinical decision support rules), 19.6 (传输电子处方/药嘱 Transmit electronic permissible medication order (prescription)) || 医师| x | x | x |x | |x |    
| | Patient disposition | Disposition patients | 执行 |9.1-2(告知病人随访和预防保健Notify patients for follow-up care and preventive care), 10.10(下达转诊医嘱Order provider referral) || 护士、医师助理|  | x |  | | |x |    
| 门诊手术| 术前阶段 | 登记 | 记录 |1.16 (访问患者人口学信息), 7.6 (记录出生日期), 7.9-12 (记录民族、性别、身高、成长曲线), 7.14 (记录医保类型), 7.25 (记录使用语言), 7.28 (记录种族), 7.34(记录吸烟状态), || 挂号人员|  |  |  | | |x |    
| |  | 测量、记录生命体征 | 记录 |7.40(记录生命体征 vital signs); 7.41(记录体重weight) || 护士、医师助理| x |  |  |x | |x |     
| |  | 病人与手术匹配 | 执行 | || 医师、医师助理、护士|  |  |  | | | |    
| |  | 护士术前检查/评估 | 医嘱、执行 | || 护士、医师助理| x |  |  |x | |x |    
| |  | 术前用药 | 医嘱 |10.5-7(下达药嘱Order medication), 13.1(基于CDS规则推荐的治疗方案调整Recommend care modications based on clinical decision support rules),17.9(回顾所提供的患者教育Review education provided) || 医师| x | x | x |x | |x |    
| |  | 转移至手术室 | 通知 | || 护士、医师助理|  |  |  | | | |    
| |  | 移交 | 通知 |2.2(确认临床摘要的接收Acknowledge receipt of clinical summary), 19.5(传输摘要信息Transmit clinical summary),12.13(接收其他机构的病人摘要记录receive patient summary allergy record from other providers) || 护士、医师助理|  | x |  | | |x |    
| | 手术室阶段 | 准备设备 | 执行 | || |  |  |  | | | |    
| |  | 确认病人 | 确认 | || |  |  |  | | | |    
| |  | 麻醉操作 | 执行 | || |  |  |  | | | |    
| |  | 手术操作 | 执行 | || |  |  |  | | | |    
| |  | 创建手术记录 | 创建 |7.1(为每次encounter记录病程记录Document a progress note for each encounter) || 医师| x |  | x |x | |x |    
| |  | 下达医嘱 | 医嘱 |10.1-10(下达所有类型的医嘱Order--all types) || 医师| x | x | x |x | |x |    
| |  | 移交 | 通知 |12.13(收到来自其他机构的患者病历摘要Receive patient summary record from other providers), 2.2(确认接收Acknowledge receipt of clinical summary), 19.5(传输患者摘要信息Transmit clinical summary) || 护士、医师助理|  | x |  | | |x |    
| | 术后阶段 | 转移到康复科室 | 通知 | || |  |  |  | | | |    
| |  | 术后检验 | 医嘱 |10.4(下达检验医嘱Order lab study), 10.8(下达医嘱套餐Order order set),10.9(下达手术医嘱Order procedure) || | x |  |  |x | | |    
| |  | 疼痛管理 | 执行 | || | x | x | x |x | |x |    
| |  | 出院 | 创建 |9.1-2(告知病人随访和预防保健Notify patients for follow-up care and preventive care), 10.10(下达转诊医嘱Order provider referral)2.1(确认接受教育Acknowledge education receipt || 医师助理、护士、医师|  |  |  | | | |    
| 住院病人住院|  |  |  | || |  |  |  | | | |    
| | 入院 | 测量、记录生命体征 | 记录 |7.40(记录生命体征 vital signs); 7.41(记录体重weight) || 护士、医师助理| x |  |  |x | |x |    
| |  | 病人转移 | 通知 | || |  |  |  | | | |    
| |  | 移交 | 通知 |12.13(收到来自其他机构的患者病历摘要Receive patient summary record from other providers), 2.2(确认接收Acknowledge receipt of clinical summary), 19.5(传输患者摘要信息Transmit clinical summary) || 医师助理、护士、医师|  | x |  | | |x |    
| | 检查 治疗 | 病史 体格检查 | 回顾 |1.1-28 (访问医疗记录中的所有信息Access - all information in medical record) || 医师| x |  |  |x | |x |    
| |  | 询问病人 | 执行 | || |  |  |  | | | |    
| |  | 记录病史 | 文档/记录 |7.1(为每次encounter记录病程记录Document a progress note for each encounter) || 医师助理、护士、医师|  |  |  |x | |x |    
| |  | 下达检验医嘱 | 医嘱 |10.4(下达检验医嘱Order lab study) || 医师|  |  |  | | | |    
| |  | 下达影像检查医嘱 | 医嘱 |10.2(下达诊断学影像检查医嘱Order diagnostic imaging procedure) || 医师| x |  |  |x | |x |    
| |  | 回顾先前的检验结果 | 回顾 |2.3(确认接收来自其他机构的诊断学检查结果Acknowledge receipt of diagnostic test results from other providers), 12.2(接收检验结果Receive clinical lab test result), 17.11-12(回顾人可读的电子格式的检验结果 其中包含了编码数据Review lab results electronically in human readable format, incorporated as codified data) || 医师、护士|  |  |  | | | |    
| |  | 诊断 | 执行 | || |  |  |  | | | |    
| |  | 下达处方 | 回顾、医嘱 |10.5-7(下达药嘱Order medication), 13.1(依据CDS规则的推荐疗法 建议调整治疗Recommend care modifications based on clinical decision support rules),  || 医师| x | x | x |x | |x |    
| |  | 治疗 | 执行 | || |  |  |  | | | |    
| |  | 给药 | 执行 | || |  |  |  | | | |    
| |  | 移交 | 通知 |12.13(收到来自其他机构的患者病历摘要Receive patient summary record from other providers), 2.2(确认接收Acknowledge receipt of clinical summary), 19.5(传输患者摘要信息Transmit clinical summary) || 医师助理、护士、医师|  | x |  | | |x |    
| | 转科 | 转到ICU 高护病房 | 通知 | || |  |  |  | | | |    
| |  | 移交 | 通知 |12.13(收到来自其他机构的患者病历摘要Receive patient summary record from other providers), 2.2(确认接收Acknowledge receipt of clinical summary), 19.5(传输患者摘要信息Transmit clinical summary) || 医师助理、护士、医师|  | x |  | | |x |    
| | 出院 | 出院指导 | 创建 |2.1(确认接受教育Acknowledge education receipt), 9.1-2(告知病人随访和预防性护理Notify patients for follow-up care and preventive care) || 医师助理、护士|  |  |  | | | |    
| |  | 转移病人 | 通知 | || |  |  |  | | | |    
| 住院病人手术| 术前阶段 | 登记 | 记录 |1.16 (访问患者人口学信息), 7.6 (记录出生日期), 7.9-12 (记录民族、性别、身高、成长曲线), 7.14 (记录医保类型), 7.25 (记录使用语言), 7.28 (记录种族), 7.34(记录吸烟状态), || 挂号人员|  |  |  | | |x |    
| |  | 测量、记录生命体征 | 记录 |7.40(记录生命体征 vital signs); 7.41(记录体重weight) || 护士、医师助理| x |  |  |x | |x |     
| |  | 病人与手术匹配 | 执行 | || 医师、医师助理、护士|  |  |  | | | |    
| |  | 护士术前检查/评估 | 医嘱、执行 | || 护士、医师助理| x |  |  |x | |x |    
| |  | 术前用药 | 医嘱 |10.5-7(下达药嘱Order medication), 13.1(基于CDS规则推荐的治疗方案调整Recommend care modications based on clinical decision support rules),17.9(回顾所提供的患者教育Review education provided) || 医师| x | x | x |x | |x |    
| |  | 转移至手术室 | 通知 | || 护士、医师助理|  |  |  | | | |    
| |  | 移交 | 通知 |2.2(确认临床摘要的接收Acknowledge receipt of clinical summary), 19.5(传输摘要信息Transmit clinical summary),12.13(接收其他机构的病人摘要记录receive patient summary allergy record from other providers) || 护士、医师助理|  | x |  | | |x |    
| | 手术室阶段 | 准备设备 | 执行 | || |  |  |  | | | |    
| |  | 确认病人 | 确认 | || |  |  |  | | | |    
| |  | 麻醉操作 | 执行 | || |  |  |  | | | |    
| |  | 手术操作 | 执行 | || |  |  |  | | | |    
| |  | 创建手术记录 | 创建 |7.1(为每次encounter记录病程记录Document a progress note for each encounter) || 医师| x |  | x |x | |x |    
| |  | 下达医嘱 | 医嘱 |10.1-10(下达所有类型的医嘱Order--all types) || 医师| x | x | x |x | |x |    
| |  | 移交 | 通知 |12.13(收到来自其他机构的患者病历摘要Receive patient summary record from other providers), 2.2(确认接收Acknowledge receipt of clinical summary), 19.5(传输患者摘要信息Transmit clinical summary) || 护士、医师助理|  | x |  | | |x |    
| | 术后阶段 | 转移到康复科室 | 通知 | || |  |  |  | | | |    
| |  | 术后检验 | 医嘱 |10.4(下达检验医嘱Order lab study), 10.8(下达医嘱套餐Order order set),10.9(下达手术医嘱Order procedure) || | x |  |  |x | | |    
| |  | 疼痛管理 | 执行 | || | x | x | x |x | |x |    
| |  | 出院 | 创建 |9.1-2(告知病人随访和预防保健Notify patients for follow-up care and preventive care), 10.10(下达转诊医嘱Order provider referral)2.1(确认接受教育Acknowledge education receipt || 医师助理、护士、医师|  |  |  | | | |  |      