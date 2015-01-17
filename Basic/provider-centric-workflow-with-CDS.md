# 以医务人员的视角,从人员管理,病例管理(病例的寻找,患者的诊断,治疗计划的确定,治疗计划的实现,治疗结果的评估和监管)和病例评估(评审,上报,患者教育,随访)等分析可能应用临床决策支持技术的场景和会用到的临床决策支持的类型.

| 工作流 | 阶段 | 任务 | 活动 | 子活动 | | 参与角色  | Alerts/Reminders |   Order sets |  InfoButtons  | Data display  ||  Documentation templates    
| ------ | ----- | ----- | ----- | ------ | ------ | ----- | ----- | ----- | ------ | ------ |    
| 人员管理|  |  |  | || |  |  |  | | | |    
| 医师评审反馈报告|  | 评审报告 | 评审 |17.5-13(评审血压、身高、体重、教育程度、药物列表、检验结果、质控结果等的变化Review displayed changes in diastolic blood pressure, height, systolic blood pressure, weight, education provided, electronically formulary or preferred drug list, lab results electronically in human readable format, lab results incorporated as codified data, quality measure results) || 医师、护士、医师助理| x |  | x |x | |x |    
| |  | 跟踪 | 评审 | || 医师、护士、医师助理| x |  | x |x | |x |    
| |  | 分析和分级 | 执行 |18.1-5(根据病人意愿、病情和人口学信息、机构类型、医务人员角色进行分级通知Stratify notifications by patient preference, patients by condition, reports by demographic information, by provider type, by provider role) || 医师、护士、医师助理| x |  | x |x | |x |    
| |  | 上报 | 上报 |17.13(评审质控结果Review quality measure results) || 医师、护士、医师助理| x |  | x |x | |x |    
| |  | 警示 | 警示 |13.1(根据CDS规则的建议调整治疗方案Recommend care modifications based on clinical decision support rules || 医师、护士、医师助理| x |  |  |x | |x |    
| |  | 病人教育 | 建议 | || 医师、护士、医师助理| x |  | x |x | |x |    
| |  | 随访 | 通知 |9.1-2(告知病人随访和预防保健信息Notify patients for follow-up care and preventive care) || 医师、护士、医师助理|  |  |  | | |x |    
| |  | 联系病人 可能包含医嘱、让病人来就诊 | 执行 | || 医师、护士、医师助理|  |  |  | | |x |    
| 病例管理| 寻找病例 | 审核报告 确定候选人 | 审核 |17.13(审核质控结果Review quality measure results) || 医师、护士、医师助理|  | x |  | | | |    
| |  | 筛选 | 执行 | || 医师、护士、医师助理|  |  |  | | | |    
| |  | 注册 | 记录 |7.26(Document problem on problem list) || 医师、护士、医师助理|  |  |  | | |x |    
| | 评估 | 病人面谈 | 执行 | || 医师、护士、医师助理|  |  |  | | | |    
| |  | 确定需要 | 记录 |7.24(Document performance result) || 医师、护士、医师助理|  |  |  | | |x |    
| | Goal setting and service planning | 与病人一起做出决定 | 记录 |7.22(Document patient preference) || 医师、护士、医师助理|  |  |  | | |x |    
| |  | 专家咨询 | 传输 |19.5(Transmit clinical summary) || 医师、护士、医师助理|  |  |  | | | |    
| |  | 临床指南本地化和提醒 | 执行 |7.2(Document advanced directive), 7.3(Document alert provided to clients) || 医师、护士、医师助理|  |  |  | | |x |    
| |  | 医务人员培训 | 执行 | || 医师、护士、医师助理|  |  |  | | | |    
| | Care plan implementation | 患者教育 | 执行 | || 医师、护士、医师助理|  |  |  | | | |    
| |  | Patient activation/psychological support | 执行 | || 医师、护士、医师助理|  |  |  | | | |    
| |  | Guidelines available to patients | 通知 |9.1-2(Notify patients for follow-up care and preventive care) || 医师、护士、医师助理|  |  |  |x | |x |    
| |  | Implement the plans | 提醒 |15.1-2(Remind patients per patient preference for follow-up care and preventive care) || 医师、护士、医师助理| x |  |  |x | | |    
| | Monitoring and evaluation监管 评估 | Reviewing services delivered | 审查 |17.9(Review education provided) 17.13(Review quality measure results) || 医师、护士、医师助理|  |  |  |x | | |    
| |  | Feedback of performance data | 审查 |17.5-13(Review displayed changes in diastolic blood pressure, height, systolic blood pressure, weight, education provided, electronically formulary or preferred drug list, lab results electronically in human readable format, lab results incorporated as codified data, quality measure results) || 医师、护士、医师助理| x |  | x |x | |x |    