# 第三方来源与许可声明

本仓库中的代码由 **倪若冰** 编写，采用 AGPL-3.0 许可（与上游一致，详见 [LICENSE](LICENSE)）。

## 运行时依赖

| 项目 | 地址 | 许可 | 与本仓库的关系 |
|---|---|---|---|
| SillyTavern | https://github.com/SillyTavern/SillyTavern | AGPL-3.0 | 宿主程序。本仓库通过其扩展接口加载，**不包含、未修改**其源码 |
| TavernAI 1.2.8 | https://github.com/TavernAI/TavernAI | MIT | SillyTavern 的上游 |

## 本仓库明确不含

- SillyTavern 或其依赖的任何源代码
- 任何模型权重（含 GPT-SoVITS 训练产物）
- 任何 API 密钥、接口地址、账号凭据
- 任何角色卡的剧情文本（仅保留字段结构说明）
- 任何真实用户的对话记录

## 关于「AGPL 与本仓库边界」

SillyTavern 采用 AGPL-3.0。本仓库的做法是：

1. **不 fork、不 patch** 上游源码——所有功能通过 ST 提供的扩展 / 正则 / 主题接口实现；
2. 仓库内代码均为独立编写的实现，可单独阅读与部署；
3. 为避免许可争议，本仓库自身同样以 AGPL-3.0 发布——即便将来被认定为衍生作品，也满足上游许可要求。

如果你要基于本项目二次开发，请同时遵守 SillyTavern 的 AGPL-3.0 条款。
