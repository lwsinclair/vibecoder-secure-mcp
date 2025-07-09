[![MseeP.ai Security Assessment Badge](https://mseep.net/pr/rvanheckers-vibecoder-secure-mcp-badge.png)](https://mseep.ai/app/rvanheckers-vibecoder-secure-mcp)

<!--
VIBECODER-SECURE MCP - Project README (Public Documentation)
Main project documentation for GitHub and external users

Dependencies:
- CLAUDE.md: Internal AI handover documentation (private)
- VIBECODER-MANUAL.md: Complete workflow guide (private)
- docs/: Generated API and security documentation

Purpose: Public-facing project overview, installation, and usage instructions
-->

# VIBECODER-SECURE MCP

**Secure document pipeline with integrity validation and audit capabilities for Vibecoder workflows**

[![Status](https://img.shields.io/badge/status-VIB--018%20Recovery%2090%25-yellow)]()
[![Version](https://img.shields.io/badge/version-1.0.0--recovery-orange)]()
[![License](https://img.shields.io/badge/license-MIT-blue)]()

## 🚨 **VIB-018 RECOVERY STATUS**

> **HTML Dashboard System Lost & 90% Recovered** - Critical UI components restored with exact original design

### ✅ **RECOVERED** (VIB-018 A/B/C):
- 🎨 **Dashboard**: Original purple/white theme with live data
- 🧪 **Test Report**: Comprehensive validation with 17 agents + 34 Makefile targets  
- 🗺️ **Visual Roadmap**: Interactive milestone tracking verified

### ⏳ **PENDING** (VIB-018D):
- **VIB-011**: Git-aware duplicate detection
- **VIB-012**: Intelligent file placement
- **VIB-013**: Dashboard UX improvements

## 🎯 Overview

VIBECODER-SECURE MCP is a comprehensive secure document pipeline designed specifically for Vibecoder workflows. It provides integrity validation, audit capabilities, automated healing, and cryptographic verification.

## 🚀 Quick Start

```bash
# Clone repository
git clone https://github.com/rvanheckers/vibecoder-secure-mcp.git
cd vibecoder-secure-mcp

# Install dependencies (recommended: use virtual environment)
pip install -r requirements.txt

# Initialize project
make init

# Generate documentation
make generate

# Validate integrity
make validate
```

## 🔧 Features

### **🎨 HTML Dashboard System** (VIB-018 Recovered)
- **📊 Real-time Dashboard**: Purple gradient theme with live project metrics
- **🧪 Test Report**: Comprehensive validation of 17 agents + 34 Makefile targets
- **🗺️ Visual Roadmap**: Interactive VIB milestone tracking and progress visualization

### **🔒 Core Security & Integrity**
- **🔐 Merkle Tree Validation**: SHA-256 cryptographic integrity checking
- **📝 Audit Trails**: Immutable, append-only operation logging
- **🛡️ GPG Signing**: Cryptographic document verification
- **🛠️ Auto-healing**: Detect and fix issues automatically  

### **📄 Documentation & Automation**
- **📋 AI Handover**: CLAUDE.md with complete context preservation
- **📚 Vibecoder Manual**: Complete workflow guide for AI agents
- **💾 Backup System**: Compressed snapshots with restore capability
- **🔄 Git Integration**: Pre-commit/post-merge hooks for automated workflows

## 📋 Makefile Commands

| Command | Description |
|---------|-------------|
| `make init` | Initialize new project |
| `make generate` | Generate documentation |
| `make validate` | Validate project integrity |
| `make heal` | Auto-heal detected issues |
| `make lock` | Update integrity lock file |
| `make sign` | Sign with GPG key |
| `make audit` | Generate audit report |
| `make backup` | Create backup snapshot |
| `make update-handover` | Update AI handover document |

## 🏗️ Architecture

**UNBREAKABLE SYSTEM**: 17 agents, 34 Makefile targets

```
├── main.py                 # FastAPI MCP hub orchestrator
├── src/agents/            # 17 UNBREAKABLE AGENTS
│   ├── generate_docs.py     # Documentation generation
│   ├── validate_docs.py     # Integrity validation
│   ├── auto_heal.py         # Auto-healing & recovery
│   ├── integrity.py         # Merkle tree hashing
│   ├── audit.py             # Audit logging
│   ├── backup.py            # Backup & restore
│   ├── smart_automation.py  # Context-aware automation
│   ├── enhanced_context.py  # AI context preservation
│   ├── monitoring.py        # Real-time monitoring
│   ├── duplicate_detection.py # Git-aware duplicate detection
│   ├── file_placement.py    # Intelligent file organization
│   ├── visual_roadmap.py    # Interactive roadmap generation
│   └── ... and 5 more agents
├── docs/                  # Generated documentation & HTML dashboards
├── .goldminer/           # Configuration, metrics & JSON logic
└── CLAUDE.md             # AI handover document (auto-updated)
```

## 🔐 Security Model

- **Merkle Tree Hashing**: SHA-256 based integrity verification
- **Append-only Audit Log**: Immutable operation history  
- **GPG Signing**: Cryptographic verification
- **Path Validation**: Secure project boundaries
- **Human Approval**: Required for destructive operations

## 🎯 Vibecoder Focus

This system is built specifically for **Vibecoder workflows** and includes:
- Milestone tracking and roadmap management
- AI handover documents for seamless transitions
- Vibecoder-specific compliance requirements
- Automated workflow integration

## 📚 Documentation

- 🎯 **[VIBECODER MANUAL](VIBECODER-MANUAL.md)** - **START HERE!** Complete Vibecoder workflow guide
- 📋 [AI Handover Document](CLAUDE.md) - Complete project state for AI agents  
- ⚡ [Quick Reference](docs/manual/quick-reference.md) - Emergency commands & checklist
- 📄 [API Documentation](docs/API.md) - FastAPI endpoint details
- 🔒 [Security Model](docs/SECURITY.md) - Security implementation details

## 🆘 Support

For Vibecoder-specific issues or feature requests, please open an issue with the `vibecoder` label.

## 📄 License

MIT License - see LICENSE file for details.

---

*Built with ❤️ for Vibecoder workflows*