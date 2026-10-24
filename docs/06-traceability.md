# 缺陷—测试用例追溯矩阵

18项主要问题均有至少一个本轮失败用例。25个失败用例不等于25项缺陷。建议观察、未执行提交和角色阻塞的边界详见测试报告。

| 缺陷 | 标题 | 关联失败用例 | 证据摘要 |
| --- | --- | --- | --- |
| [P1-01](03-defect-list.md#p1-01) | 手机端登录和后台布局挤压 | [TC-AUTH-002](04-test-cases.md#tc-auth-002)、[TC-DASH-002](04-test-cases.md#tc-dash-002) | [EV-01](05-evidence-index.md#ev-01) |
| [P1-02](03-defect-list.md#p1-02) | 今日商品销售排行使用近30天数据 | [TC-DASH-001](04-test-cases.md#tc-dash-001) | [EV-03](05-evidence-index.md#ev-03) |
| [P1-03](03-defect-list.md#p1-03) | 商品详情入口进入404 | [TC-PROD-002](04-test-cases.md#tc-prod-002) | [EV-05](05-evidence-index.md#ev-05) |
| [P1-04](03-defect-list.md#p1-04) | 角色功能权限不可读取或编辑 | [TC-RBAC-001](04-test-cases.md#tc-rbac-001) | [EV-18](05-evidence-index.md#ev-18) |
| [P1-05](03-defect-list.md#p1-05) | 过期状态被临期或缺货覆盖，收银加购无警示 | [TC-INV-001](04-test-cases.md#tc-inv-001)、[TC-INV-002](04-test-cases.md#tc-inv-002)、[TC-POS-015](04-test-cases.md#tc-pos-015) | [EV-11](05-evidence-index.md#ev-11)、[EV-23](05-evidence-index.md#ev-23) |
| [P1-06](03-defect-list.md#p1-06) | 称重补货建议数量和单位不准确 | [TC-BI-001](04-test-cases.md#tc-bi-001)、[TC-BI-002](04-test-cases.md#tc-bi-002) | [EV-17](05-evidence-index.md#ev-17) |
| [P1-07](03-defect-list.md#p1-07) | 称重商品首次加购直接默认1斤 | [TC-POS-003](04-test-cases.md#tc-pos-003) | [EV-23](05-evidence-index.md#ev-23) |
| [P1-08](03-defect-list.md#p1-08) | 采购测试账号叠加店长角色，与岗位清单不符 | [TC-RBAC-005](04-test-cases.md#tc-rbac-005) | [EV-20](05-evidence-index.md#ev-20)、[EV-06](05-evidence-index.md#ev-06) |
| [P2-01](03-defect-list.md#p2-01) | 库存告警徽标未明确统计范围 | [TC-INV-003](04-test-cases.md#tc-inv-003) | [EV-11](05-evidence-index.md#ev-11) |
| [P2-02](03-defect-list.md#p2-02) | 多行库存及同名补货建议缺少区分维度 | [TC-INV-004](04-test-cases.md#tc-inv-004)、[TC-BI-003](04-test-cases.md#tc-bi-003) | [EV-11](05-evidence-index.md#ev-11)、[EV-17](05-evidence-index.md#ev-17) |
| [P2-03](03-defect-list.md#p2-03) | 商品行流水入口未带入商品条件 | [TC-INV-005](04-test-cases.md#tc-inv-005) | [EV-12](05-evidence-index.md#ev-12) |
| [P2-04](03-defect-list.md#p2-04) | 促销状态与活动日期冲突 | [TC-PROMO-001](04-test-cases.md#tc-promo-001) | [EV-16](05-evidence-index.md#ev-16) |
| [P2-05](03-defect-list.md#p2-05) | 收银名称搜索与提示不一致 | [TC-POS-006](04-test-cases.md#tc-pos-006) | [EV-23](05-evidence-index.md#ev-23) |
| [P2-06](03-defect-list.md#p2-06) | F4会员识别未转移输入焦点 | [TC-POS-007](04-test-cases.md#tc-pos-007) | [EV-23](05-evidence-index.md#ev-23) |
| [P2-07](03-defect-list.md#p2-07) | 付款方式与数量控件缺少可访问语义 | [TC-POS-010](04-test-cases.md#tc-pos-010)、[TC-POS-011](04-test-cases.md#tc-pos-011) | [EV-23](05-evidence-index.md#ev-23) |
| [P2-08](03-defect-list.md#p2-08) | 库管员可见按钮与路由权限不同步 | [TC-RBAC-004](04-test-cases.md#tc-rbac-004)、[TC-RBAC-006](04-test-cases.md#tc-rbac-006) | [EV-19](05-evidence-index.md#ev-19) |
| [P2-09](03-defect-list.md#p2-09) | 历史报损缺少商品明细入口 | [TC-INV-008](04-test-cases.md#tc-inv-008) | [EV-14](05-evidence-index.md#ev-14) |
| [P2-10](03-defect-list.md#p2-10) | 称重报损缺少计量单位说明 | [TC-INV-009](04-test-cases.md#tc-inv-009) | [EV-14](05-evidence-index.md#ev-14) |

## 改进建议追溯

| 建议 | 标题 | 关联用例 | 证据 |
| --- | --- | --- | --- |
| [OBS-01](03-defect-list.md#obs-01) | 关联规则结果上限与查找 | [TC-UX-001](04-test-cases.md#tc-ux-001) | [EV-25](05-evidence-index.md#ev-25) |
| [OBS-02](03-defect-list.md#obs-02) | 技术文案混入业务页面 | [TC-UX-002](04-test-cases.md#tc-ux-002) | [EV-17](05-evidence-index.md#ev-17)、[EV-25](05-evidence-index.md#ev-25) |
| [OBS-03](03-defect-list.md#obs-03) | 登录标签与键盘语义 | [TC-AUTH-005](04-test-cases.md#tc-auth-005) | [EV-01](05-evidence-index.md#ev-01) |
| [OBS-04](03-defect-list.md#obs-04) | 预填凭据与记住设备 | [TC-UX-003](04-test-cases.md#tc-ux-003) | [EV-01](05-evidence-index.md#ev-01) |
| [OBS-05](03-defect-list.md#obs-05) | 收银历史、退款、补打入口待核实 | [TC-POS-019](04-test-cases.md#tc-pos-019) | [EV-22](05-evidence-index.md#ev-22)、[EV-24](05-evidence-index.md#ev-24) |
| [OBS-06](03-defect-list.md#obs-06) | 供应商对账缺少下钻 | [TC-UX-004](04-test-cases.md#tc-ux-004) | [EV-10](05-evidence-index.md#ev-10) |
| [OBS-07](03-defect-list.md#obs-07) | 权限与读取失败反馈 | [TC-UX-005](04-test-cases.md#tc-ux-005) | [EV-07](05-evidence-index.md#ev-07)、[EV-19](05-evidence-index.md#ev-19) |

## 未完成场景

| 用例 | 状态 | 原因/边界 |
| --- | --- | --- |
| [TC-AUTH-004](04-test-cases.md#tc-auth-004) | 未执行 | 未执行，避免锁定现有账号。 |
| [TC-AUTH-006](04-test-cases.md#tc-auth-006) | 部分执行 | 2026-10-24观察到登录页redirect中再次包含登录页；未完成本次验证码登录，未验证目标恢复，不列为新缺陷。 |
| [TC-PROD-004](04-test-cases.md#tc-prod-004) | 未执行 | 未保存调价；仅检查编辑表单。 |
| [TC-PUR-005](04-test-cases.md#tc-pur-005) | 未执行 | 未执行审核或驳回。 |
| [TC-PUR-006](04-test-cases.md#tc-pur-006) | 未执行 | 仅查看收货表单，未提交。 |
| [TC-PUR-007](04-test-cases.md#tc-pur-007) | 未执行 | 退货业务页尚未实际检查；后续导航因会话失效未到达业务页。 |
| [TC-SUP-003](04-test-cases.md#tc-sup-003) | 未执行 | 未登记任何付款。 |
| [TC-INV-007](04-test-cases.md#tc-inv-007) | 未执行 | 未新建或提交盘点。 |
| [TC-INV-011](04-test-cases.md#tc-inv-011) | 未执行 | 未提交报损，未验证扣减或超量服务端校验。 |
| [TC-INV-012](04-test-cases.md#tc-inv-012) | 未执行 | 本轮尚未实际检查调拨页与流转。 |
| [TC-MEM-003](04-test-cases.md#tc-mem-003) | 未执行 | 未充值，未执行资金或积分写入。 |
| [TC-MEM-004](04-test-cases.md#tc-mem-004) | 未执行 | 仅观察到入口，未验证其实际权限。 |
| [TC-PROMO-002](04-test-cases.md#tc-promo-002) | 未执行 | 未执行系统时间边界、优惠券使用或最终结算。 |
| [TC-BI-004](04-test-cases.md#tc-bi-004) | 未执行 | 未点击生成，以免创建业务记录。 |
| [TC-REP-003](04-test-cases.md#tc-rep-003) | 未执行 | 未执行导出及文件级数据隔离检查。 |
| [TC-RBAC-007](04-test-cases.md#tc-rbac-007) | 阻塞 | 现有采购测试账号同时有店长角色，无法代表纯采购员。 |
| [TC-RBAC-008](04-test-cases.md#tc-rbac-008) | 未执行 | 只检查到按钮，未点击审核；不能推断后端允许自审。 |
| [TC-POS-016](04-test-cases.md#tc-pos-016) | 未执行 | 未执行任何最终结算或真实支付。 |
| [TC-POS-017](04-test-cases.md#tc-pos-017) | 未执行 | 仅验证取单空状态，未创建挂单。 |
| [TC-POS-018](04-test-cases.md#tc-pos-018) | 未执行 | 未提交交班。 |
| [TC-POS-019](04-test-cases.md#tc-pos-019) | 部分执行 | 所查页面未见入口，未证明整站未实现这些功能。 |
