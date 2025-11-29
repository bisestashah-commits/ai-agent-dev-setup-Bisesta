# AI Agent Developer Setup - [Your Name]

**Cohort:** [Your Cohort Name]  
**Week:** 1 - Development Environment Setup  
**Date:** [Submission Date]

---

## 🎯 Overview

This repository demonstrates a complete AI Agent Developer environment setup with all required MCP (Model Context Protocol) servers configured and operational. This serves as the foundation for the 10-week AI Agent Developer bootcamp.

---

## ✅ Development Environment Checklist

### 1. Node.js Installation
**Status:** ✅ Installed  
**Version:** v24.11.1



### 2. Git Installation
**Status:** ✅ Installed  
**Version:** 2.52.0

```bash
git --version
# Output: git version [your-version]
```

---

### 3. VS Code Insiders with GitHub Copilot
**Status:** ✅ Configured

**Configuration:**
- GitHub Copilot extension enabled
- Recommended extensions installed
- Workspace configured for AI-assisted development

---

### 4. Claude Desktop with MCP Servers
**Status:** ✅ All 4 servers connected


**Connected Servers:**
1. ✅ Rolldice
2. ✅ Bootcamp AI Agent
3. ✅ Calendar Booking
4. ✅ GitHub

---

## 🔧 MCP Servers Explanation

### 1. **Rolldice Server**
A foundational MCP server that demonstrates basic protocol functionality through dice rolling mechanics. This server helps verify MCP connectivity and provides a simple interface for understanding how MCP servers communicate with Claude.

**Key Functionality:** Random number generation, dice rolling operations, probabilistic simulations.

---

### 2. **Bootcamp AI Agent Server**
A specialized server designed specifically for this bootcamp curriculum. It provides access to course materials, resources, and bootcamp-specific tools that enhance the learning experience throughout the 10-week program.

**Key Functionality:** Course content access, learning path guidance, workshop-specific utilities.

---

### 3. **Calendar Booking Server**
Enables calendar management and scheduling capabilities directly through Claude. This server transforms Claude into a scheduling assistant that can create events, check availability, and manage time-based workflows.

**Key Functionality:** Event creation, availability checking, appointment scheduling, calendar integration.

---

### 4. **GitHub Server**
The most powerful MCP server in this setup - it provides full GitHub integration allowing Claude to interact with repositories, manage code, create issues, and handle pull requests. This is essential for AI-assisted development workflows.

**Key Functionality:** Repository management, code search, issue tracking, pull request automation, branch management.

**Authentication:** Configured with Personal Access Token for secure API access.

---

## 🐛 Troubleshooting Notes

### Issue 1: [Describe any issue you faced]
**Problem:** [What went wrong]  
**Solution:** [How you fixed it]  
**Learned:** [Key takeaway]

### Issue 2: [Another issue if applicable]
**Problem:** [What went wrong]  
**Solution:** [How you fixed it]  
**Learned:** [Key takeaway]

---

## 📁 Repository Structure

```
ai-agent-dev-setup-[your-name]/
├── mcp-configs/
│   ├── claude-desktop-config.json
│   ├── mcp-servers-list.md
│   └── connection-test.md
├── screenshots/
│   ├── node-version.png
│   ├── git-version.png
│   ├── vscode-insiders.png
│   └── claude-mcp-servers.png
├── README.md
├── reflection.md
└── VERIFICATION.md
```

---

## 🚀 Quick Start

To replicate this setup:

1. Install Node.js from https://nodejs.org/
2. Install Git from https://git-scm.com/
3. Install VS Code Insiders from https://code.visualstudio.com/insiders/
4. Install Claude Desktop from https://claude.ai/download
5. Copy `mcp-configs/claude-desktop-config.json` to your Claude config directory
6. Restart Claude Desktop
7. Verify all servers are connected

---

## 📚 Resources

- [MCP Documentation](https://modelcontextprotocol.io/)
- [Claude Desktop Documentation](https://claude.ai/docs)
- [GitHub Personal Access Tokens](https://github.com/settings/tokens)
- [Bootcamp Resources](./mcp-configs/mcp-servers-list.md)

---

## 📫 Contact

**Name:** Bisesta Shah
**GitHub:** https://github.com/bisestashah-commits
**Email:** bisestshah@gmail.com

---

## 📄 License

This project is part of the AI Agent Developer Bootcamp curriculum.