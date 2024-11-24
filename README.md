
# 🌟 Dev Template

![License: MIT](https://img.shields.io/badge/license-MIT-blue.svg)
![Issues](https://img.shields.io/github/issues/cbq1024/dev-template)
![Build Status](https://img.shields.io/github/actions/workflow/status/cbq1024/dev-template/release-drafter.yaml?label=CI%2FCD)

## 📖 项目概述

**Dev Template** 是一个现代开发的综合启动模板，包括：
- 🖥️ 完全配置的开发容器（DevContainer）。
- 🚀 预配置的 CI/CD 工作流。
- 📦 用于自动依赖更新的 Dependabot 集成。
- 📝 结构化的错误报告和功能请求模板。

---

## ✨ 功能亮点

- **DevContainer 支持**: 预配置支持 Visual Studio Code 的远程容器开发。
- **CI/CD 集成**: 使用 GitHub Actions 的自动构建和发布流程。
- **可定制的 Issue 模板**: 提供用于错误、功能和增强的模板。
- **跨语言代码检查**: 前端使用 ESLint 和 TypeScript，后端支持 Maven 或 Gradle。
- **依赖管理**: 启用 Dependabot 的自动依赖更新。

---

## 🛠️ 设置指南

### 前端配置

1. 确保安装 **Yarn**:
   ```bash
   npm install --global yarn
   ```
2. 克隆代码库:
   ```bash
   git clone https://github.com/cbq1024/dev-template.git
   cd dev-template
   ```
3. 安装依赖:
   ```bash
   yarn install
   ```
4. 启动开发服务器:
   ```bash
   yarn run docs:dev
   ```

### 后端配置 (Maven)

1. 确保安装 **Maven**。
2. 编译项目:
   ```bash
   mvn compile
   ```
3. 运行应用程序:
   ```bash
   mvn spring-boot:run
   ```

### 后端配置 (Gradle)

1. 安装 **Gradle**。
2. 构建项目:
   ```bash
   ./gradlew build
   ```
3. 启动服务器:
   ```bash
   ./gradlew run
   ```

---

## 🚀 使用示例

### 在开发容器中运行

1. 在 **Visual Studio Code** 中打开代码库。
2. 安装推荐的扩展:
   - Dev Containers
3. 打开命令面板 (Ctrl+Shift+P) 并选择 `Dev Containers: Reopen in Container`。

### 调试前端
```bash
yarn run start
```
访问应用程序: `http://localhost:3000`。

### 调试后端
```bash
mvn spring-boot:run
```
访问 API: `http://localhost:8080`。

---

## 📂 项目结构

```plaintext
.devcontainer/          # DevContainer 配置
.github/                # GitHub Actions 工作流和 Issue 模板
src/                    # 应用程序源代码
docs/                   # 文档文件
```

---

## 📝 贡献指南

欢迎贡献代码！请查阅 [CONTRIBUTING.md](CONTRIBUTING.md) 文件了解详细信息。

---

## 🔒 安全策略

如有安全问题，请参考我们的 [SECURITY.md](SECURITY.md) 文件。

---

## 📄 开源协议

本项目基于 MIT 许可协议，详情请参考 [LICENSE](LICENSE) 文件。
