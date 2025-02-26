# <img src="https://raw.githubusercontent.com/ordinarykaizen/PromptLab/main/assets/PromptLab (1).png" alt="PromptLab" width="30" height="30" style="vertical-align: middle;"> PromptLab

[![GitHub stars](https://img.shields.io/github/stars/ordinarykaizen/PromptLab?style=social)](https://github.com/ordinarykaizen/PromptLab/stargazers)
[![Discord](https://img.shields.io/discord/1234567890?label=Discord&logo=discord&logoColor=white&style=flat-square)](https://discord.com/invite/9YYEPceY)
[![Twitter Follow](https://img.shields.io/twitter/follow/trypromptlab?style=social)](https://x.com/trypromptlab)
[![License](https://img.shields.io/badge/license-MIT-blue.svg)](https://github.com/ordinarykaizen/PromptLab/blob/main/LICENSE)

## 🤖 Enable LLM Observability, Testing & Debugging

PromptLab is the easiest way to observe, test, and debug your LLM applications with precision.

## 🚀 Features

- **Real-time Prompt Debugging**: Analyze and optimize your prompts as you build
- **Comprehensive Analytics**: Track tokens, costs, latency, and response quality metrics
- **Automated Testing**: Create test suites to validate LLM outputs against expected behaviors
- **Version Control**: Track changes to prompts and model configurations over time
- **Comparative Evaluation**: Benchmark different models and prompt strategies side-by-side
- **Visual Insights**: Beautiful dashboards to visualize your LLM application performance

## 💡 Why PromptLab?

Building reliable LLM applications requires visibility into how your prompts and models perform. PromptLab gives you the tools needed to move from experimental prompts to production-ready, reliable AI systems.

## 🛠️ Quick Start

```bash
# Install PromptLab
npm install @promptlab/core

# Initialize your project
npx promptlab init

# Start monitoring your LLM application
import { PromptLab } from '@promptlab/core';
const promptlab = new PromptLab({
  apiKey: process.env.PROMPTLAB_API_KEY,
  project: 'my-awesome-project'
});

// Wrap your LLM calls
const result = await promptlab.track(
  () => openai.chat.completions.create({
    model: 'gpt-4',
    messages: [{ role: 'user', content: 'Hello world' }]
  })
);
```

## ⚡ Skip the Setup - Try Our Hosted Version

Skip the setup - try our hosted version for instant LLM debugging: [Try it now](https://www.trypromptlab.com/).

## 🌐 Links

- [Website](https://www.trypromptlab.com)
- [GitHub](https://github.com/ordinarykaizen/PromptLab)
- [Documentation](https://docs.trypromptlab.com)
- [Discord](https://discord.com/invite/9YYEPceY)
- [Twitter](https://x.com/trypromptlab)
- [LinkedIn](https://www.linkedin.com/company/trypromptlabs/)

## 👥 Team

- [Norm](https://x.com/ordinary_kaizen) - Founder
- [Akbar (Jon)](https://x.com/Akbar_Erkinov) - Co-founder

## 🗺️ Roadmap

| Timeline | Feature | Status |
|----------|---------|--------|
| Q1 2025 | Core Observability Pipeline | ✅ Complete |
| Q1 2025 | Multi-model Support (OpenAI, Anthropic, etc.) | ✅ Complete |
| Q2 2025 | Advanced Prompt Templates | 🚧 In Progress |
| Q2 2025 | Team Collaboration Features | 🚧 In Progress |
| Q3 2025 | CI/CD Integration | 📅 Planned |
| Q3 2025 | Custom Evaluation Metrics | 📅 Planned |
| Q4 2025 | Fine-tuning Workflow Management | 📅 Planned |
| Q4 2025 | Enterprise SSO & Advanced Security | 📅 Planned |

> See our [project board](https://github.com/ordinarykaizen/PromptLab/projects) for detailed development status

## 🤝 Contributing

We'd love to see what you create with PromptLab! Share your projects in our [Discord community](https://discord.com/invite/9YYEPceY).

## 📄 License

PromptLab is MIT licensed.

---

## 📄 License

PromptLab is MIT licensed.

---
