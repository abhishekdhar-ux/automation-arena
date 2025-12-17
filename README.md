# 🎮 Automation Arena

**Master the art of choosing between Scripts, Workflows, and AI Agents**

A visual, interactive educational game that teaches IT professionals and developers when to use simple Scripts, structured Workflows, or intelligent AI Agents for automation tasks.

![License](https://img.shields.io/badge/license-MIT-blue.svg)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black)

## 🎯 What is this?

Automation Arena is a card-based learning game with 52 real-world IT scenarios. Players must classify each scenario as requiring:

- **Script** 💜 - Fixed, deterministic tasks with no ambiguity
- **Workflow** 💙 - Multi-step processes with conditional logic and human approvals
- **Agent** 💚 - Ambiguous goals requiring AI reasoning and context understanding

## ✨ Features

- 🎨 **Beautiful Visual Design** - Gradient backgrounds, smooth animations, and modern UI
- 🎴 **52 Real Scenarios** - Covering ITSM, DevOps, HR, Security, and more
- 📊 **Progress Tracking** - Circular progress indicator and live scoring
- 🧠 **Educational Feedback** - Learn the reasoning behind each answer
- 💻 **Technical Details** - Get implementation examples for each scenario
- 🎯 **Difficulty Levels** - Includes "borderline" trick questions
- 📱 **Responsive Design** - Works on desktop, tablet, and mobile

## 🚀 Play Now

### Online
Visit: `https://yourusername.github.io/automation-arena`

### Local
1. Download `index.html`
2. Open it in any modern web browser
3. Start playing!

No installation, no dependencies, no build process needed.

## 🎮 How to Play

1. Click **"Start Challenge"** to begin
2. Read each scenario carefully
3. Choose between **Script**, **Workflow**, or **Agent**
4. Get instant feedback with explanations
5. Complete all 52 scenarios to see your final score

### Decision Framework

**Choose Script when:**
- Single, well-defined task
- Fixed input/output
- No human intervention needed
- Deterministic logic

**Choose Workflow when:**
- Multiple sequential steps
- Conditional branching (if/then)
- Human approvals required
- Time-based triggers

**Choose Agent when:**
- Ambiguous or abstract goals
- Requires interpretation
- Context-dependent decisions
- Natural language understanding needed

## 🛠️ Technology Stack

- **Pure HTML5** - Single file, no frameworks
- **Tailwind CSS** (CDN) - Utility-first styling
- **Font Awesome** (CDN) - Icons
- **Vanilla JavaScript** - No libraries, no dependencies

## 📁 Project Structure

```
automation-arena/
├── index.html          # Main game file (all-in-one)
├── README.md           # This file
├── LICENSE             # MIT License
└── screenshots/        # Game screenshots (optional)
    ├── start-screen.png
    ├── gameplay.png
    └── feedback.png
```

## 🎓 Educational Use

This game is perfect for:

- **Training Programs** - IT automation workshops
- **Onboarding** - New developers learning automation patterns
- **Interviews** - Testing automation architecture knowledge
- **Self-Learning** - Understanding when to use different automation approaches

## 🤝 Contributing

Contributions are welcome! Here's how you can help:

1. **Add More Scenarios** - Submit new real-world examples
2. **Improve Explanations** - Enhance the educational content
3. **Bug Fixes** - Report or fix issues
4. **Translations** - Localize for other languages
5. **Visual Improvements** - Enhance animations and design

### How to Contribute

1. Fork this repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## 📝 Adding New Scenarios

To add new scenarios, edit the `deck` array in `index.html`:

```javascript
{
    id: 53,
    domain: "DOMAIN_NAME",
    text: "Your scenario description here.",
    type: "Script|Workflow|Agent",
    reasoning: "Why this is the correct answer.",
    tech: "Technical implementation example"
}
```

## 🐛 Bug Reports

Found a bug? Please open an issue with:
- Browser and version
- Description of the problem
- Steps to reproduce
- Expected vs actual behavior

## 📜 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🌟 Acknowledgments

- Inspired by real-world automation challenges
- Built with modern web standards
- Designed for educational purposes

## 📧 Contact

- GitHub Issues: [Report a bug or request a feature](https://github.com/yourusername/automation-arena/issues)
- Discussions: [Join the conversation](https://github.com/yourusername/automation-arena/discussions)

## 🎯 Roadmap

- [ ] Add difficulty levels (Beginner, Intermediate, Expert)
- [ ] Leaderboard with persistent storage
- [ ] Timer mode for speed challenges
- [ ] More scenario categories (Cloud, AI/ML, Data Engineering)
- [ ] Dark mode toggle
- [ ] Sound effects (optional)
- [ ] Multiplayer mode

---

**Made with ❤️ for the automation community**

⭐ Star this repo if you found it helpful!
