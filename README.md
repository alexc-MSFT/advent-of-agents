# Advent of Agents Copilot Agent 🎄

'Advent of Agents' is an built in Microsoft 365 Copilot Agent Builder designed to provide users with an advent calendar of Copilot agent ideas to build each day during December.

It acts like a daily inspiration guide, helping users explore and learn about building different types of Copilot agents throughout the festive season, with the ultimate aim of upskilling users and increasing the adoption of agents within your organization.

In it's current iteration it provides:
- **Daily agent ideas** - A new agent idea to build every day in the run up to Christmas
- **Step-by-step guidance** - Instructions on how to build each suggested agent along with suggested knowledge sources, functionality and more
- **Use case inspiration** - Real-world business scenarios where each agent would be valuable

This repository contains **setup documentation and instructions** for building the agent in your own Copilot environment.  
---

## 🌐 Knowledge Sources

By default, **Advent of Agents is web grounded** only, allowing it to be used by all Copilot users for free including Copilot Chat (unlicensed users).

The agent provides a curated list of 25 agent ideas that can be built by users in Agent Builder (one for each day from December 1st to December 25th), each with:
- Agent idea, description and purpose 
- Key features to implement
- Suggested knowledge sources e.g. Teams/Outlook/SharePoint etc.
- Suggested functionality e.g. Document/Image generation

⚠️ **Important Note:**  
The advent calendar content is maintained as part of this agent's instructions. For production use, customers are encouraged to **customize the advent calendar instructions** with agent ideas relevant to their organization.

The included advent calendar ideas are for Agent Builder only and do not cover Copilot Studio Custom Agents or Pro Code Agents.

---

## 📖 Documentation

- [Agent Instructions](Instructions.md) – Copy & paste these directly into your agent

---

## 🚀 Getting Started

1. Create a new agent in Agent Builder (Copilot Studio Lite).
2. Click the '**Configure**' tab and fill out the details as follows (feel free to adjust the Name/Description for your organisation):

- **Name**: Advent of Agents
- **Description**: Unwrap 24 days of Copilot creativity! Each door reveals a festive agent idea to spark innovation and sharpen your skills. From knowledge grounding to document and image generation, it’s the perfect blend of holiday cheer and practical Copilot know‑how.
- **Icon**: Upload the provided icon file and choose an accent color if desired.

3. Copy the [Agent Instructions](Instructions.md) and paste these into your agent.
4. Configure the following 'Suggested prompts' (feel free to adjust to your needs):

| Title | Message |
|----------|----------|
| Today's Agent Idea 🎁 | Open todays advent calendar idea |
| Specific day 📅 | Show me the idea for Day 1 |
| Idea for date 📅 | Show me the idea for {Date} |
| Suggest idea 💡 | Suggest a festive agent idea |

5. Add the following website as a knowledge source - https://learn.microsoft.com/en-us/microsoft-365-copilot.
6. Disable 'Search all websites', 'Only use specified sources', 'Reference people in organization'.
7. Check the agent is working by selecting one of the suggested prompts or ask a question in the Agent preview chat pane.
8. Click '**Create**'.
9. View and use the agent in Copilot.
10. (Optional) - Share your agent with your team/colleagues or deploy as an organization wide agent (see below).
11. (Optional) - Customize the advent calendar with your own agent ideas (see below).

---

## 🏗️ Deploying Organization Wide

Should you wish to deploy the agent across your entire organization you have a few options:

- Build the agent in Agent Builder, download the manifest zip file (click the ellipsis) and submit to an admin for approval in the Microsoft Admin Center (MAC).
- Build the agent in Copilot Studio Full as a Declarative Agent instead and use the out of the box share functionality to submit the agent for approval.

## 🎨 Customizing the Calendar

You can customize the advent calendar by updating the agent instructions:

1. Open the [Agent Instructions](Instructions.md)
2. Modify the **Advent Calendar Ideas Table** section to include your own agent ideas
3. Adjust agent ideas and descriptions to match your organization's needs
4. Update the agent in Agent Builder with your customized instructions

## 🤝 Contributing

Contributions are welcome!  

If you'd like to improve the documentation, suggest new agent ideas for the advent calendar, or share setup experiences, please open an issue or submit a PR.

---

## Support

This solution is open-source and community provided with no active community providing support for it. This solution is maintained by both Microsoft employees and community contributors and is not a Microsoft provided solution so there is no SLA or direct support for this from Microsoft. Please report any issues by raising an issue.

## 📜 License

This project is licensed under the [MIT License](LICENSE).
