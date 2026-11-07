# G5/G9 产品修改记录

- 产品编号：$(@{number=64; product_id=JLZ-EDU-SK-052; chinese_name=家庭学习任务设计; english_name=Home Learning Task Designer; repository_name=edu-home-learning-task-designer; repository_url=https://github.com/jinlize-tech/edu-home-learning-task-designer; product_type=Skill; category_code=05; category=05 家校服务中心; description=家庭学习任务设计。; target_users=System.Object[]; core_input=学生年级学科、近期目标、家庭可用时间、设备材料、家长能力和安全限制; main_output=家庭任务、时间安排、所需材料、家长指导、完成标准和反馈表; product_risk=任务过重、年龄不适配或要求家长代替学习; dedup_label=存在部分功能交叉; dedup_note=与分层作业区别：本产品跨课堂练习设计家庭学习活动，并包含家庭执行指导。; development_status=Planned / 待研发; license=Apache-2.0; spec_version=1.0.0; workbuddy_status=PLANNED_FOR_WORKBUDDY}.product_id)
- 产品名称：家庭学习任务设计
- 基线：EDUCATION_BASELINE_V1.0.0
- 基线提交：$BaselineCommit
- 原版本：1.0.0
- 新版本：1.0.1

## 本次修改

1. 强化产品专属执行流程、输入核对和输出验收规则。
2. 新增 scripts/validate_input.js，实际检查必填字段、冲突、未确认数据和敏感信息。
3. 新增正常、缺失、冲突、敏感信息和非法JSON场景输入。
4. 测试升级为 T1–T7 分层并保存逐项检查结果。
5. 安装包加入 Apache-2.0 LICENSE 和 THIRD_PARTY_NOTICES.md。
6. 安装包升级为 1.0.1，加入许可证、第三方声明和输入校验脚本，保留 1.0.0 ZIP。
7. 按本产品冻结规格补充专属处理规则、输入到成果的核对矩阵和去重边界。

## 产品专属增强

- 核心任务：家庭学习任务设计。
- 主要风险：任务过重、年龄不适配或要求家长代替学习
- 去重边界：与分层作业区别：本产品跨课堂练习设计家庭学习活动，并包含家庭执行指导。

- 先确认事实、涉及对象、沟通目的、渠道、时间要求和必须披露的信息。
- 给家长或学生的结论必须区分事实、观察、建议和待核实内容。
- 只披露与该家庭直接相关且确有必要的学生信息，避免交叉泄露。
- 投诉、退款、安全和健康事项设置人工升级条件，不替代正式处置。

## 运行边界

- 本地模型行为：NOT_RUNTIME_VERIFIED
- WorkBuddy平台验证：WORKBUDDY_VALIDATION_NOT_IN_SCOPE
- 本轮不执行上传、安装、审核或正式发布。
