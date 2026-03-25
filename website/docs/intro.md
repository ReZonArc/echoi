---
sidebar_position: 1
slug: /
---

# Welcome to echoi Documentation

echoi is an AI-enhanced, customizable browser designed to streamline your digital experience with AI services.

## 🚀 Quick Start

- **Users**: Download echoi from [GitHub Releases](https://github.com/ReZonArc/echoi/releases)
- **Developers**: Check out the [Technical Architecture](./ARCHITECTURE.md)
- **Extension Developers**: See the [Extension Development Guide](./EXTENSION_DEVELOPMENT.md)

## 📖 Documentation Sections

### Technical Documentation
- **[Architecture Overview](./ARCHITECTURE.md)** - Complete system architecture with diagrams
- **[Extension Development](./EXTENSION_DEVELOPMENT.md)** - Build extensions for echoi
- **[Configuration System](./CONFIGURATION.md)** - Manage settings and configurations
- **[Development Guide](./DEVELOPMENT.md)** - Set up development environment

### Key Features

- **AI Support**: ChatGPT, Claude, Gemini, Grok, DeepSeek, GitHub Copilot, and more
- **Browser**: Customizable browsing with AI website integration
- **Extensions**: Chrome-like extension system for enhanced functionality
- **Prompts Management**: Robust prompt customization and management
- **Themes**: Multiple theme options including Light, Dark, System, and custom themes
- **Cache Mode**: Unique browsing experience without traditional tabs
- **Cookie Isolation**: Multiple accounts support for the same website

## 🎯 Getting Started

### For End Users
1. [Download echoi](https://github.com/ReZonArc/echoi/releases) for your platform
2. Install and launch the application
3. Configure your preferred AI services
4. Start exploring AI-enhanced browsing

### For Developers
1. Read the [Architecture Documentation](./ARCHITECTURE.md)
2. Set up your [Development Environment](./DEVELOPMENT.md)
3. Explore the [Extension System](./EXTENSION_DEVELOPMENT.md)
4. Check the [Configuration Guide](./CONFIGURATION.md)

## 🔧 System Requirements

- **Windows**: Windows 10 or later (x64)
- **macOS**: macOS 10.15 or later (Intel/Apple Silicon)
- **Linux**: Ubuntu 18.04+ or equivalent (x64)

## 🌐 Supported AI Services

### Popular AI Platforms
- [ChatGPT](https://chatgpt.com)
- [Claude](https://claude.ai)
- [Google Gemini](https://gemini.google.com)
- [Grok](https://grok.com)
- [GitHub Copilot](https://github.com/copilot)
- [HuggingChat](https://huggingface.co/chat)
- [Perplexity](https://www.perplexity.ai)

### Chinese AI Services
- 通义千问 (Qwen)
- 扣子 (Coze)
- 豆包 (Doubao)
- 智谱清言 (ChatGLM)
- DeepSeek

## 📊 Architecture Overview

```mermaid
graph TB
    subgraph "echoi Application"
        UI[User Interface]
        Browser[Browser Engine]
        Extensions[Extension System]
        Config[Configuration]
    end
    
    subgraph "AI Services"
        ChatGPT[ChatGPT]
        Claude[Claude]
        Gemini[Gemini]
        Others[Other AI Services]
    end
    
    UI --> Browser
    Browser --> Extensions
    Browser --> Config
    
    Browser --> ChatGPT
    Browser --> Claude
    Browser --> Gemini
    Browser --> Others
```

## 🤝 Contributing

We welcome contributions! Please see our:
- [Development Guide](./DEVELOPMENT.md) for setup instructions
- [GitHub Repository](https://github.com/ReZonArc/echoi) for issues and discussions
- [Extension Development](./EXTENSION_DEVELOPMENT.md) for creating extensions

## 📢 Community

- **GitHub**: [Star the project](https://github.com/ReZonArc/echoi)
- **Issues**: [Report bugs](https://github.com/ReZonArc/echoi/issues)
- **Discussions**: [Feature requests](https://github.com/ReZonArc/echoi/discussions)

## 📄 License

echoi is open-source software. Check the [repository](https://github.com/ReZonArc/echoi) for license details.