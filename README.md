# 中国市场规模估算 Skill

为中国及跨境业务快速或完整估算外部市场的 TAM、SAM、SOM，统一市场边界、付费主体、年份、币种、公式、来源与敏感性。

## 适合处理

- 新产品、新地区或新客群的市场进入判断
- 商业计划、融资与投资材料中的市场规模论证
- 自上而下、自下而上和价值池等多路径交叉验证
- 证据不足时的假设情景、“不估”判断与补证计划

本 Skill 不用于内部工具 ROI、竞品功能对比、销售目标倒推，也不会把 TAM 当作收入承诺。

## 使用

在 Codex 中直接调用：

```text
$discover-market-sizing-cn 估算这个外部市场机会，并明确公式、来源、敏感性和不能推出的结论。
```

安装到个人 Skill 目录的一种方式：

```bash
git clone https://github.com/fengxinbo558/discover-market-sizing-cn.git ~/.codex/skills/discover-market-sizing-cn
```

若目标目录已经存在，请先自行检查，不要直接覆盖。

## 内容

- `SKILL.md`：主入口、模式、证据等级与估算规则
- `agents/openai.yaml`：中性中文 UI 元数据
- `references/TEMPLATE.md`：完整输出模板
- `references/EXAMPLE.md`：有边界的估算示例
- `evals/`：触发与行为样例

## 验证与来源

本仓库版本已通过结构、安全、链接和隔离安装检查。来源和修改边界见 `UPSTREAM.md`，适用许可证原文见 `LICENSE.upstream`；这些文件属于法律与诚实溯源记录，不应删除。
