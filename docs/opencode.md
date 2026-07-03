[English](./opencode.md) | [简体中文](./opencode.zh-CN.md) · [← Back](../README.md)

# Integrate with OpenCode

OpenCode is an open-source AI coding assistant available in terminal, web, and other forms.

#### 1. Install OpenCode Terminal

```bash
npm i -g opencode-ai
```

> Alternatively, use `curl -fsSL https://opencode.ai/install | bash`, `brew install anomalyco/tap/opencode`, etc. See the [download page](https://opencode.ai/download) for all options.

To avoid compatibility issues, ensure the version is >= v1.14.24.

#### 2. Run and Configure

- Execute the `opencode` command<br/>
- Type `/connect` in the input box, then enter `deepseek` and select the provider<br/>
- Enter your [DeepSeek API Key](https://platform.deepseek.com/api_keys)<br/>
- Select the DeepSeek-V4-Pro model
