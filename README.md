# Testocracy - Democracy of Testing

**Homebrew tap for tools that democratize testing and QA automation.**

> *Bringing Product Managers closer to QA. Automate testing without coding.*

## Installation

```bash
brew tap mheryerznkanyan/testocracy
brew install ios-test-automator
```

## What is Testocracy?

**Testocracy** is about democratizing quality assurance. Our tools empower Product Managers, designers, and non-technical team members to create and run automated tests using natural language - no coding required.

### The Vision

- 🤝 **Bridge PM ↔ QA** - Product Managers write tests in plain English
- ⚡ **Automate QA work** - AI generates test code automatically
- 💪 **Empower everyone** - Testing shouldn't require coding skills
- 🎯 **Shift-left testing** - Catch issues earlier in the development cycle

## Featured Tool: iOS Test Automator

AI-powered iOS test automation with RAG-enhanced test generation.

**What it does:**
- Describe tests in natural language
- Automatically generates Swift XCUITest code
- Finds UI elements using RAG (Retrieval-Augmented Generation)
- Executes tests on iOS Simulator
- Records video of test execution
- Beautiful web interface - no terminal needed

### Quick Start

After installation:

```bash
# Initialize configuration
ios-test-automator init

# Add your Anthropic API key
ios-test-automator config

# Index your iOS app (one-time setup)
ios-test-automator rag ingest --app-dir /path/to/your/app

# Start the backend
ios-test-automator server

# Launch the UI (in new terminal)
ios-test-automator ui
```

Then open http://localhost:8501 in your browser and start creating tests!

### Example

**You type (in plain English):**
```
Test login with email test@example.com and password password123,
verify the home screen appears with "Welcome" text
```

**The tool:**
1. 🔍 Finds the right UI elements in your app
2. ✨ Generates Swift test code automatically
3. ▶️ Runs the test on iOS Simulator
4. 📹 Records video of execution
5. ✅ Shows you the results

No Swift knowledge needed. No XCTest experience required.

## Philosophy: Democracy of Testing

**Traditional QA:**
- Only QA engineers write tests
- PMs write specs, wait for QA to test
- Slow feedback loops
- Manual testing bottlenecks

**Testocracy:**
- Anyone can create automated tests
- PMs validate features instantly
- Fast feedback loops
- Automated from the start

## Future Tools

Testocracy will expand to include:
- Android test automation
- Web/API testing tools
- Visual regression testing
- Accessibility testing
- Performance testing

All with the same philosophy: **Make testing accessible to everyone.**

## Available Formulae

| Formula | Description |
|---------|-------------|
| `ios-test-automator` | AI-powered iOS test automation |

## Documentation

- [iOS Test Automator User Guide](https://github.com/mheryerznkanyan/iOS-test-automator/blob/main/USER_GUIDE.md)
- [Quick Reference](https://github.com/mheryerznkanyan/iOS-test-automator/blob/main/QUICK_REFERENCE.md)
- [GitHub Repository](https://github.com/mheryerznkanyan/iOS-test-automator)

## Support

- Report issues: https://github.com/mheryerznkanyan/iOS-test-automator/issues
- Feature requests: https://github.com/mheryerznkanyan/homebrew-testocracy/discussions

## Contributing

Have a tool that democratizes testing? Want to add it to Testocracy?

Open a discussion or PR! We welcome tools that:
- Make testing accessible to non-technical users
- Use AI to automate QA work
- Bridge the gap between product and quality
- Shift testing left in the development cycle

## License

MIT

---

**Testocracy** - *Testing for everyone, by everyone.* 🎯
