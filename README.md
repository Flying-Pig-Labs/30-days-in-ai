# 🚀 30 Days in AI: Exploring Claude-Powered Tools

> A comprehensive exploration of 30+ cutting-edge AI tools recommended by Anthropic, all powered by Claude.

## 📚 Quick Links

- 🎥 **[Streaming Setup Guide](local-setup/README.md)** - Complete guide for streaming tool demonstrations

## The Prompt
I used a [claude-flow sparc](https://github.com/ruvnet/claude-code-flow) to set up this project. While I did lots of post-run editing, here's the one-shot prompt I used to get things set up:
```
You are my AI co-producer for a Twitch stream and YouTube series where my friend and I test drive tools from Anthropic’s “Claude for Business” partner showcase. Each episode is only 30 minutes long, so I need you to handle three roles:

1. **🧠 Research Lead**: For each tool in the README.md, dig deep and figure out:
 - What problem this tool actually solves (skip the marketing fluff)
 - Why it’s interesting or buzzy right now (zeitgeist/street chatter)
 - What makes it technically unique or cool

Use that research to pitch a specific sticky problem related to launching our consultancy, Flying Pig Labs, where we build generative AI applications (our "Overnight MVP" package). The problem should be real and solvable in a short window. Keep the use case grounded in what early-stage businesses or solo founders need:
 - Sales funnels
 - Content marketing
 - Event organization (meetups, webinars)
 - Software development
 - Legal/contract ops
 - SMB productivity + automation

---

2. **🎬 Project Manager**: Structure the 30-minute “test drive” to maximize learning + output. Each issue should:
 - Get an engaging title
 - Frame the problem we’re solving
 - Link to the tool
 - Outline the 30-minute breakdown (tight!)
 - Highlight relevant features to explore
 - Note any pre-reqs like “Fake dataset” or “Open a free account,” but bias hard toward just laptop + internet
 - Tag each issue with proof-of-concept and keep it scoped, exciting, and punchy.

---

3. **🧑‍💻 Technical Setup Helper**: Help us figure out how to record using basic webcams and MacBook Airs. We’ll either be co-located or remote. Recommend simple setups for:
 - Dual-screen share
 - Audio capture
 - Stream to Twitch + save to YouTube (or easier options for archiving)

---
Tone & Vibe Guidelines:
 - Speak with youthful language and energy but don’t overdo it
 - Use emojis sparingly but effectively
 - Avoid boring bullets - write with swagger
 - Be authoritative; do the research and back it up

Only spin up 5 tools at a time (parallel agents). Check your work when you're done.
```

## 🛠️ The Tools

Here are the 30+ AI-powered tools we're exploring. They cut across coding, productivity, content creation, and more:

| Tool / Company       | Category               | Special Sauce                                                                                 | Test Drive |
|----------------------|------------------------|-----------------------------------------------------------------------------------------------|------------|
| Augment Code         | Coding Tool            | Tailored for real-time code iteration and feedback loops in LLM-enhanced workflows.          | [#55](https://github.com/Flying-Pig-Labs/30-days-in-ai/issues/55) |
| Base44               | Coding Tool            | AI no-code platform with "Vibe Coding" - acquired by Wix for $80M.                         | [#31](https://github.com/Flying-Pig-Labs/30-days-in-ai/issues/31) |
| Bolt.new             | Coding Tool            | Extreme speed-to-prototype with built-in Claude integrations.                                | [#51](https://github.com/Flying-Pig-Labs/30-days-in-ai/issues/51) |
| Bubble               | Coding Tool            | Combines visual dev with Claude-driven logic—great for fast comprehension.                   | [#50](https://github.com/Flying-Pig-Labs/30-days-in-ai/issues/50) |
| Cursor (Anysphere)   | Coding Tool            | Best-in-class Claude-native dev environment with version-aware agents.                       | [#49](https://github.com/Flying-Pig-Labs/30-days-in-ai/issues/49) |
| Devin                | Coding Tool            | First real "AI software engineer" narrative tool—great for philosophical discussion.        | [#36](https://github.com/Flying-Pig-Labs/30-days-in-ai/issues/36) |
| Factory              | Coding Tool            | Built for running fully autonomous AI teams—dream case study material.                       | [#34](https://github.com/Flying-Pig-Labs/30-days-in-ai/issues/34) |
| Greptile             | Coding Tool            | Remarkably good at repo insight and summarization—bridges human+LLM understanding of systems.| [#35](https://github.com/Flying-Pig-Labs/30-days-in-ai/issues/35) |
| Lovable              | Coding Tool            | Lovable-first prompt UI makes it tangible for design thinkers and newcomers to AI.           | [#33](https://github.com/Flying-Pig-Labs/30-days-in-ai/issues/33) |
| Qodo                 | Coding Tool            | Includes full provenance chain for decisions—ideal for AI safety conversations.              | [#32](https://github.com/Flying-Pig-Labs/30-days-in-ai/issues/32) |
| Replit               | Coding Tool            | Fast, shareable, and collaborative—perfect for instant LLM code experiments.                 | [#56](https://github.com/Flying-Pig-Labs/30-days-in-ai/issues/56) |
| Zed                  | Coding Tool            | Minimalist IDE with Claude-in-the-loop—great for distraction-free dev.                      | [#37](https://github.com/Flying-Pig-Labs/30-days-in-ai/issues/37) |
| Zencoder             | Coding Tool            | Seamlessly turns audio/video into accessible learning formats.                               | [#39](https://github.com/Flying-Pig-Labs/30-days-in-ai/issues/39) |
| Clay                 | CRM/Data               | Combines relationship data and enrichment—perfect for civic + ecosystem mapping.             | [#38](https://github.com/Flying-Pig-Labs/30-days-in-ai/issues/38) |
| Databricks           | Data/Analytics         | Scales across entire ML lifecycle—teachable platform for practitioners.                      | [#57](https://github.com/Flying-Pig-Labs/30-days-in-ai/issues/57) |
| Day.ai               | Voice + Analytics      | Real-time analytics on voice inputs—great example of multimodal AI literacy.                 | [#42](https://github.com/Flying-Pig-Labs/30-days-in-ai/issues/42) |
| Dust                 | Productivity AI        | Shows how teams can operationalize Claude without code—agent creation made intuitive.        | [#53](https://github.com/Flying-Pig-Labs/30-days-in-ai/issues/53) |
| Gamma                | BI / Storytelling      | Stunning Claude-powered slide generation from just text input.                               | [#41](https://github.com/Flying-Pig-Labs/30-days-in-ai/issues/41) |
| Genspark             | Agents / Automation    | Highly modular agent creation—perfect for sandboxing civic or entrepreneurial bots.          | [#40](https://github.com/Flying-Pig-Labs/30-days-in-ai/issues/40) |
| Highlight AI         | Meeting AI             | Turns meetings into structured summaries—emphasizes AI as reflection tool.                   | [#43](https://github.com/Flying-Pig-Labs/30-days-in-ai/issues/43) |
| Interop.io           | Enterprise Integration | Unique focus on UI-level integration of disparate systems with AI overlays.                  | [#58](https://github.com/Flying-Pig-Labs/30-days-in-ai/issues/58) |
| Julius AI            | Data Analyst AI        | Feels like Excel + LLM—amazing bridge between classic BI and Claude.                         | [#45](https://github.com/Flying-Pig-Labs/30-days-in-ai/issues/45) |
| Captions             | Video Content          | Voice-to-video pipeline built on LLMs—ideal for expressive storytelling.                     | [#46](https://github.com/Flying-Pig-Labs/30-days-in-ai/issues/46) |
| InVideo              | Video Content          | Makes pro-quality video assets from prompts—low effort, high impact.                         | [#44](https://github.com/Flying-Pig-Labs/30-days-in-ai/issues/44) |
| Ginger Labs          | EdTech / Notes         | Claude integration with one of the most beloved classroom apps.                              | [#52](https://github.com/Flying-Pig-Labs/30-days-in-ai/issues/52) |
| StudyFetch           | Learning AI            | Built for note syncing, quiz generation, and spaced repetition—great for learning cycles.    | [#54](https://github.com/Flying-Pig-Labs/30-days-in-ai/issues/54) |
| Harvey               | Legal AI               | AI designed for law firms—real use case for professional AI co-pilots in regulated fields.   | [#47](https://github.com/Flying-Pig-Labs/30-days-in-ai/issues/47) |

## 🎬 About This Project

This repository serves as a comprehensive resource for exploring AI tools that leverage Claude's capabilities. Whether you're:

- 👨‍💻 A developer looking for AI-powered coding assistants
- 💼 A business professional seeking productivity tools
- 🎨 A content creator exploring AI-enhanced workflows
- 🎓 An educator interested in AI literacy

You'll find detailed test drives, demo scripts, and streaming guides to help you explore these tools effectively.

## 🚀 Getting Started

1. **Browse the Tools**: Review the table above to find tools that match your interests
2. **Try a Test Drive**: Click on the test drive links to access detailed challenge templates
3. **Watch Demos**: Check out our [streaming setup guide](local-setup/README.md) for live demonstrations
4. **Prepare Your Own Demos**: Use our [demo preparation guide](demo-preparation.md) for scripts and examples

## 📺 Streaming Schedule

Planning to stream all 30 tools? Our guides break it down into manageable blocks:

- **Coding Tools** (12 tools): ~60 minutes
- **Business & Productivity** (8 tools): ~40 minutes  
- **Content Creation** (6 tools): ~30 minutes
- **Specialized Tools** (4 tools): ~25 minutes

Total stream time: 2.5-3 hours including intro/outro

## 🤝 Contributing

Found a new Claude-powered tool? Have a great test drive idea? Contributions are welcome!

1. Fork this repository
2. Create a new branch for your contribution
3. Add your content following the existing patterns
4. Submit a pull request

## 📄 License

This project is open source and available under the MIT License.

---

*Built with ❤️ to showcase the amazing ecosystem of Claude-powered tools*
