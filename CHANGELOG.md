# Changelog

## [1.0.5] - 2026-03-07

### 更新
- ✅ 补充 Git / GitHub CLI 安装检查步骤
- ✅ 补充 GitHub 鉴权、Git 身份配置、remote 配置说明
- ✅ 元数据补充 `gh` 依赖，避免技能声明与实际使用不一致

## [1.0.4] - 2026-03-07

### 更新
- ✅ 优化技能 description，明确覆盖“发布技能”“发到 ClawHub”“发布这个 skill”“写完就发布”“上线这个技能”等触发表达
- ✅ package.json 和 README.md 同步更新描述文案，减少触发歧义

## [1.0.3] - 2026-03-07

### 更新
- ✅ 新增硬规则：发布 `~/Skills` 下任意技能时，ClawHub 发布必须同步创建 GitHub Release
- ✅ 版本更新流程补充为：先 push + GitHub Release，再发布到 ClawHub

## [1.0.2] - 2026-03-05

### 更新
- ✅ 发布流程新增第 5 步：发布后必须同步 SKILL.md 到 agent 工作空间

## [1.0.1] - 2026-03-05

### 更新
- ✅ 新增"发布顺序"章节：明确 4 步发布流程顺序（版本号 → CHANGELOG → GitHub Release → ClawHub）

## [1.0.0] - 2026-02-27

### 新增
- 完整的 ClawHub 技能发布流程文档
- 常见问题与解决方案汇总
- 元数据规范说明
- 版本更新流程
- 安全注意事项
- 最佳实践建议

### 来源
基于发布 `dingtalk-ai-table` 技能的实际经验总结，包括：
- 学习 ClawHub 官方规范（skill-format.md, security.md）
- 修复元数据不一致问题（requires.env, requires.bins）
- 解决 CLI 超时和认证问题
- 成功发布 v0.3.3 版本
