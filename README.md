# github-actions-practice

开源软件设计实验 03 —— GitHub Actions 实践

一个简单的 Python 计算器模块，配合 pytest 单元测试，
通过 GitHub Actions 在每次 push 时自动运行测试。

## 运行测试

```bash
pip install -r requirements.txt
pytest -v
```

## CI

工作流配置见 `.github/workflows/ci.yml`，触发条件为 push 和 pull_request。
