# Advent of Agents Copilot Agent 🎄

Advent of Agents is a **Proof of Concept Agent** built in Copilot Studio Lite designed to provide users with an advent calendar of Copilot agent ideas to build each day during December.

It acts like a daily inspiration guide, helping users explore and learn about building different types of Copilot agents throughout the advent season.

In its current iteration it helps you explore:
- **Daily agent ideas** - A new agent concept revealed each day of advent
- **Step-by-step guidance** - Instructions on how to build each suggested agent
- **Use case inspiration** - Real-world scenarios where each agent would be valuable
- **Skill building** - Progressive complexity to build your agent-building skills

Future iterations will bring:
- **Customizable calendars** - Create your own advent themes
- **Community challenges** - Collaborative agent building activities
- **Template library** - Starter templates for each day's agent

**Note - Whilst this is a Copilot Studio Lite agent, it can equally be built in Copilot Studio and rolled out across your Organization.**

This repository contains **setup documentation and instructions** for building the agent in your own Copilot environment.  

No code is included.

---

## 🌐 Knowledge Sources

By default, **Advent of Agents is web grounded** only, allowing it to be used by all Copilot users for free including Copilot Chat (unlicensed users).

The agent provides a curated list of 25 agent ideas (one for each day of advent from December 1st to December 25th), each with:
- Agent concept and purpose
- Key features to implement
- Suggested knowledge sources
- Difficulty level

⚠️ **Important Note:**  
The advent calendar content is maintained as part of this agent's instructions. For production use, customers are encouraged to **customize the advent calendar** with agent ideas relevant to their organization.

---

## 📖 Documentation

- [Agent Instructions](Instructions.md) – Copy & paste these directly into your Copilot Studio agent

---

## 🚀 Getting Started

1. Create a new agent in Copilot Studio Lite (Agent Builder).
2. Click the '**Configure**' tab and fill out the details as follows (feel free to adjust the Name/Description for your organisation):

- **Name**: Advent of Agents
- **Description**: An advent calendar agent that reveals a new Copilot agent idea each day of December, helping you learn and build different types of agents throughout the holiday season.

3. Copy the [Agent Instructions](Instructions.md) and paste these into your agent.
4. Configure the following 'Suggested prompts' (feel free to adjust to your needs):

| Title | Message |
|----------|----------|
| Today's Agent 🎁 | What agent should I build today? |
| Calendar Overview 📅 | Show me the full advent calendar of agents |
| Get Started 🚀 | I'm new to building agents, where should I start? |

5. Check the agent is working by selecting one of the suggested prompts or ask a question in the builder chat pane.
6. Click '**Create**'.
7. View and use the agent in Copilot.
8. (Optional) - Share your agent with your team/colleagues or deploy as an organization wide agent (see below).
9. (Optional) - Customize the advent calendar with your own agent ideas (see below).

---

## 🏗️ Deploying Organization Wide

Should you wish to deploy the agent across your entire organization you have a few options:

- Build the agent in Copilot Studio Lite, download the manifest zip file (click the ellipsis) and submit to an admin for approval in the Microsoft Admin Center (MAC).
- Build the agent in Copilot Studio instead and use the out of the box share functionality to submit the agent for approval.

## 🎨 Customizing the Calendar

You can customize the advent calendar by updating the agent instructions:

1. Open the [Agent Instructions](Instructions.md)
2. Modify the **Advent Calendar** section to include your own agent ideas
3. Adjust difficulty levels and descriptions to match your organization's needs
4. Update the agent in Copilot Studio with your customized instructions

## 🤝 Contributing

Contributions are welcome!  

If you'd like to improve the documentation, suggest new agent ideas for the advent calendar, or share setup experiences, please open an issue or PR.

---

## Support

This solution is open-source and community provided with no active community providing support for it. This solution is maintained by both Microsoft employees and community contributors and is not a Microsoft provided solution so there is no SLA or direct support for this from Microsoft. Please report any issues by raising an issue.

## 📜 License

This project is licensed under the [MIT License](LICENSE).
