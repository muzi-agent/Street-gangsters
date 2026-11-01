# 贡献指南

感谢你愿意为 Street-gangsters 做出贡献！本文说明如何提交一个 Pull Request（PR）。

## 开始之前

- 先查看 [Issues](https://github.com/muzi-agent/Street-gangsters/issues)，确认是否已有相同的问题或建议。
- 小改动可以直接提交 PR；较大的改动建议先开 Issue 讨论，确认方向后再动手。

## 提交 PR 的步骤

1. Fork 本仓库，然后把你的 fork 克隆到本地：

   ```bash
   git clone https://github.com/<你的用户名>/Street-gangsters.git
   cd Street-gangsters
   ```

2. 基于最新的 `main` 创建分支：

   ```bash
   git checkout main
   git pull origin main
   git checkout -b docs/your-change
   ```

3. 修改文件并提交：

   ```bash
   git add .
   git commit -m "docs: 说明你的改动"
   git push origin docs/your-change
   ```

4. 打开你的 fork 页面，点击 **Compare & pull request**。确认 base 仓库为 `muzi-agent/Street-gangsters`、base 分支为 `main`，填写 PR 标题和说明后提交。

5. 收到评审意见后，在同一个分支继续修改并推送，PR 会自动更新。

## PR 建议

- 标题简洁，并标注改动类型，例如 `docs:`、`fix:`、`feat:`。
- 在描述中说明改动内容、原因和验证方式；如果 PR 要关闭某个 Issue，可以写 `Closes #<Issue 编号>`。
- 每个 PR 尽量只做一件事，避免把无关改动混在一起。

## 提交前检查

- 确认改动的文件内容完整、格式正确。
- 本仓库目前没有自动化测试或 CI，请在提交前自行检查改动。
