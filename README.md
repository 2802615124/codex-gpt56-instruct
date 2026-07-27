# Codex GPT-5.6 Instruction & Evaluation Pack

> 面向 Codex CLI 指令配置的版本化提示词、部署脚本与回归评测资料。

## 功能概览

- 提供 `v5` 与 `v35` 两套指令包及其明文、压缩归档和校验信息。
- 使用 `codex-instruct.py` 完成安装、切换、恢复和目标目录指定。
- 保存提示词测试集、模型输出、评测记录、图表和历史报告。
- 中英文 README 同步维护，便于复现和对比不同版本的结果。

## 使用入口

```bash
python3 codex-instruct.py --help
```

主要资料：

| 路径 | 内容 |
| --- | --- |
| `gpt-5.6-sol-unrestricted-v5.md` | 推荐版本的明文指令。 |
| `gpt-5.6-sol-unrestricted-v35.zip` | 特殊场景优化版本归档。 |
| `scripts/` | 测试、对比和资料同步脚本。 |
| `tests/` | 测试样本、输出与通过状态。 |
| `reports/` | 历史评测和候选版本看板。 |
| `docs/` | 图表和评测文档。 |

## 分支说明

| 分支 | 用途 |
| --- | --- |
| `main` | 当前指令包、部署脚本、评测数据和文档。 |

## 许可证

MIT，详见 `LICENSE`。
