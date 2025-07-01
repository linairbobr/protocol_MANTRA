# MANTRA Protocol Suite
### Memory And Neural Token Recovery Architecture

**Author:** © Maksim Orlov (Russia)  
**Contact:** Lin-air@mail.ru | t.me/kurwa_bo  
**Date:** June 25, 2025  
**License:** All rights reserved. Use, copying or modification without written permission prohibited.

---

## 🎯 What is MANTRA?

MANTRA is a revolutionary protocol suite designed to solve the fundamental "AI dementia" problem - the tendency of language models to forget instructions, settings, and context as conversations progress. Created by a Russian electrician with zero IT background, this protocol emerged from pure engineering thinking and real-world frustration with AI memory limitations.

### The Problem
- AI models forget your custom instructions as context window fills
- Settings and preferences get lost mid-conversation  
- Users constantly repeat the same configuration requests
- Productivity drops as conversations become inconsistent

### The Solution
MANTRA creates a systematic "memory refresh" system that preserves all your customizations throughout the entire session, automatically maintaining context without user intervention.

---

## 🚀 Quick Start

1. **Choose your version** (see comparison below)
2. **Copy the protocol text** into your AI chat
3. **Add your custom rules**: `Add to mantra: [your rule]`
4. **Work normally** - MANTRA runs automatically in background

**That's it!** Your AI will now maintain perfect memory of all settings.

---

## 📦 Protocol Versions

### MANTRA UltraLight v1.0
**Best for:** Beginners, simple use cases, minimal overhead

**Features:**
* Basic memory preservation (1500 token intervals)
* Simple command set (Add/Remove/Show/Run)
* X+1 failure recovery
* File protection for large uploads
* Lightweight operation

**Use when:** You want simple, reliable memory without complexity

---

### MANTRA Base v1.3
**Best for:** Standard users who need reliability + some advanced features

**Features:**
* All UltraLight features
* Enhanced failure management system
* Multiple reset options
* Digital token control with warnings
* Modular architecture
* Document creation standards
* Comprehensive logging

**Use when:** You need robust memory with better error handling

---

### MANTRA Optima v1.0
**Best for:** Power users, complex workflows, maximum stability

**Features:**
* All Base features
* Multiple operation modes (Economical/Standard/Debug)
* Version control and rollback system
* Smart overload protection
* Advanced diagnostics
* Export/backup functionality
* Response numbering
* Status indicators

**Use when:** You need enterprise-grade reliability with full control

---

### MANTRA Core v1.4.3 (RAW)
**Best for:** Developers, AI researchers, maximum customization

**Features:**
* All Optima features
* Full machine-readable format
* CRC32 integrity checking
* Self-reattachment capabilities
* Advanced async checkpointing
* Complete version history
* Raw export functionality
* Professional debugging tools

**Use when:** You need maximum control and technical capabilities

---

## Which Version Should You Use?

| Use Case                          | Version     |
|----------------------------------|-------------|
| Quick tests                      | ULTRALIGHT  |
| Stable long sessions             | BASE        |
| Flexible multitasking + files   | OPTIMA      |
| Full session recovery & control | CORE        |

---

## 🎛️ Core Commands (Universal)

| Command | Function | Example |
|---------|----------|---------|
| `Add to mantra: [text]` | Add new rule | `Add to mantra: Always check links` |
| `Remove from mantra: [text]` | Remove specific rule | `Remove from mantra: Check links` |
| `Show mantra` | Display current rules | `Show mantra` |
| `Run` | Manual memory refresh | `Run` |

## Advanced Commands (Version-Specific)

**Optima & Core:**
* `Status` - Show system state
* `Mode [name]` - Switch operation modes
* `Export` - Full configuration backup
* `Rollback` - Return to previous version
* `Self-diagnosis` - Check system integrity

**Core Only:**
* `/emergency_refresh` - Critical failure recovery
* `/check_crc` - Verify data integrity
* `/atomic_reboot` - Complete system reset

---

## ⚙️ How It Works

## The Token Management System
* **Context Window:** ~4000 tokens typical limit
* **Refresh Trigger:** Every 1500 tokens used
* **Safety Margin:** Warnings at 500 tokens remaining
* **Emergency Mode:** At 80% context capacity

## The X+1 Rule (Failure Recovery)
When the system is busy with other tasks:
1. **Delay:** Memory refresh postponed to next available moment
2. **Maximum Wait:** 5 responses maximum
3. **Emergency:** Automatic critical recovery if still delayed
4. **Priority:** Memory refresh becomes top priority task

## Memory Preservation Flow
```
User Input → Token Count → Threshold Check → Auto-Refresh → Continue
     ↑                                            ↓
User Settings ←―――――――――――――――――― Memory Restored
```

---

## 💡 Usage Examples

### Basic Setup (Any Version)
```
[Activate MANTRA UltraLight]
Add to mantra: You are a Python expert
Add to mantra: Always explain code step-by-step  
Add to mantra: Use examples in every explanation
```

### Professional Workflow (Optima/Core)
```
[Activate MANTRA Optima]
Mode Debug
Add to mantra: Senior software architect role
Add to mantra: Follow SOLID principles
Add to mantra: Suggest refactoring opportunities
Status
```

### File Analysis (All Versions)
```
[Upload large file]
System: "Light mode. Full run after processing."
[File processed, memory automatically restored]
```

---

## 🔧 Technical Details

## Compatibility
* **Tested Models:** GPT-4, GPT-4o, Claude Sonnet
* **Context Windows:** 8K to 128K tokens adaptive
* **Languages:** English, Russian (easily adaptable)

## Architecture Philosophy
* **Stability > Functionality:** Core features never break
* **Fail-Safe Design:** Multiple recovery mechanisms
* **User-Friendly:** Works without technical knowledge
* **Modular:** Add only features you need

## Performance Impact
* **UltraLight:** Minimal (1-2% response time)
* **Base/Optima:** Low (3-5% response time)  
* **Core:** Moderate (5-10% with full diagnostics)

---

## 🚨 Troubleshooting

## Common Issues

**AI stopped following rules:**
* Try: `Run` (manual refresh)
* If failed: `Show mantra` (verify rules present)
* Emergency: Restart protocol

**Memory refresh not working:**
* Check if you're using priority tasks (file uploads, etc.)
* X+1 rule will trigger automatic recovery
* Use `Status` command (Optima+) for diagnostics

**Protocol seems corrupted:**
* Optima/Core: Use `Self-diagnosis`
* Core: Use `/check_crc` for integrity check
* Last resort: `Rollback` or restart

## Error Messages Explained

* `⚠️ Less than 500 tokens until run!` - Normal warning, refresh coming
* `❌ Emergency run required` - X+1 rule triggered
* `Critical failure detected` - Manual intervention needed
* `CRC mismatch` - Data corruption, automatic recovery initiated

---

## 🏆 Success Stories

> "Finally! An AI that remembers my coding style preferences throughout entire projects. Game changer for development work." - Anonymous Developer

> "I can have 200+ message conversations and the AI still remembers every setting from message 1. This is what AI should be." - Content Creator

> "Built by someone with no programming background but deep understanding of the actual problem. Brilliant solution." - AI Researcher

---

## 📚 Version Comparison Chart

| Feature | UltraLight | Base | Optima | Core |
|---------|------------|------|--------|------|
| Basic Memory | ✅ | ✅ | ✅ | ✅ |
| X+1 Recovery | ✅ | ✅ | ✅ | ✅ |
| File Protection | ✅ | ✅ | ✅ | ✅ |
| Advanced Logging | ❌ | ✅ | ✅ | ✅ |
| Multiple Modes | ❌ | ❌ | ✅ | ✅ |
| Version Control | ❌ | ❌ | ✅ | ✅ |
| Diagnostics | ❌ | Basic | Advanced | Professional |
| CRC Integrity | ❌ | ❌ | ❌ | ✅ |
| Self-Repair | ❌ | ❌ | Basic | Advanced |
| Complexity | Low | Medium | High | Expert |

---

## 🎓 The Story Behind MANTRA

Created by Maksim Orlov, a 37-year-old electrician from Russia with zero IT experience, MANTRA was born from pure frustration with AI "dementia." When his wife (an IT professional) constantly complained about ChatGPT forgetting settings, Maksim decided to solve it himself.

Starting with a simple question - "Can you repeat all settings to yourself in background mode?" - he developed this protocol suite through pure engineering thinking and relentless testing. What makes MANTRA special is its origin: built by someone who experiences AI the way normal users do, not developers.

### Evolution Timeline
- **Day 1:** Basic concept and first working prototype
- **Week 1:** X+1 rule development after step-counting failures  
- **Week 2:** Token-based system replacing step counting
- **Week 3:** Full protocol suite with multiple versions

The result: A protocol that actually works in real-world usage, created by someone who understands user frustration better than technical complexity.

---

## 📖 Protocol Philosophy

1. **"It Must Just Work"** - No technical knowledge required
2. **"Failure is Expected"** - Multiple recovery mechanisms built-in
3. **"One Size Doesn't Fit All"** - Multiple versions for different needs
4. **"User First"** - Designed by a user, for users

---

## 🤝 Contributing

While the protocol is copyrighted, feedback and suggestions are welcome:
- Email: Lin-air@mail.ru
- Telegram: @kurwa_bo

Share your success stories, report issues, or suggest improvements. The protocol continues to evolve based on real-world usage.

---

## 📁 Repository Structure

All versions of the protocol are available in this repository as .txt files inside `/base`, `/core`, `/optima`, and `/ultralight` folders.

## ⚖️ License

**License:** Attribution required. No commercial reuse without permission.

© 2025 Maksim Orlov. All rights reserved. This protocol suite is proprietary software. Any use, copying, modification, or distribution without written permission from the author is prohibited.

---

**Remember:** MANTRA doesn't just fix AI memory - it transforms how you work with AI. Choose your version, activate it, and experience AI that actually remembers.
