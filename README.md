# Get your MCP and Skills.md here: Agentic Development to the MAX

Full-day pre-conference workshop at Power Conference 2026, Prague, for intermediate and experienced Power BI and Fabric practitioners (level 200 to 300). It runs on December 2, 2026, from 9:00 to 17:00, at the Clarion Congress Hotel Prague. The day is for Power BI developers who have tried GitHub Copilot but do not yet have a structured workflow, Fabric developers and data engineers who want to see where MCP servers fit, and tech leads and architects who want hands-on evidence before recommending agentic tools. Teaching blocks and hands-on labs alternate through apps, semantic models, and reports.

## What you'll learn

- How agents, harnesses, skills, and tools fit together. You give the intent. The harness runs the agent. Skills teach the agent how you work. Tools, including MCP servers, do the work.
- How to build a report app in Power BI Desktop for Apps with GitHub Copilot.
- How to build an app in Rayfin Fabricator, and how to scaffold a Rayfin app in VS Code from a template.
- How to use MCP servers to explore a semantic model and shape it.
- How to shape a PBIP report with an agent. That covers the Desktop Bridge, Skills for Fabric, pages, visuals, and theme files.
- What you take home: a skills.md blueprint, prompt templates, and a decision map for when to use which tool.

## Agenda

| Time | Block |
| --- | --- |
| 9:00 to 9:15 | Arrival and setup check |
| 9:15 to 9:45 | Block 1. Intros and getting started with agents |
| 9:45 to 10:15 | Block 2. Power BI Desktop: build an app |
| 10:15 to 10:45 | Block 3. Lab 1: Desktop apps |
| 10:45 to 11:00 | Break |
| 11:00 to 11:30 | Block 4. Rayfin app building with Rayfin Fabricator |
| 11:30 to 12:00 | Block 5. Lab 2: install and build with Rayfin Fabricator |
| 12:00 to 12:45 | Lunch |
| 12:45 to 13:15 | Block 6. Building with Rayfin inside VS Code |
| 13:15 to 13:45 | Block 7. Lab 3: build from a Rayfin template |
| 13:45 to 14:15 | Block 8. Model development with MCP servers |
| 14:15 to 14:45 | Block 9. Lab 4: MCP servers to shape the model |
| 14:45 to 15:00 | Break |
| 15:00 to 15:30 | Block 10. Shaping PBIP with agents |
| 15:30 to 16:00 | Block 11. Lab 5: report pages, visuals and themes |
| 16:00 to 16:30 | Block 12. Wrap up and final thoughts |
| 16:30 to 17:00 | Block 13. Lab 6: open Q&A and final projects |

## Prerequisites

Bring a laptop with admin rights so you can install software. A personal laptop is recommended.

- Windows 11 for the Power BI Desktop for Apps lab. Mac users can still do the Rayfin Fabricator and VS Code labs.
- GitHub Copilot Pro or Pro+. Pro+ is the better fit for heavy agent use. You can downgrade after the workshop.
- VS Code (latest), with permission to install extensions.
- Power BI Desktop (latest, November 2026 release or later). Turn on Settings > Preview features > Power BI Desktop for Apps.
- Node.js 22.12 or later, and Git.
- [Rayfin Fabricator](https://spatney.github.io/rayfin-fabricator/). Rayfin Fabricator is a personal project by Sachin Patney, not an official Microsoft product.
- Access to a Fabric capacity workspace, with Build permission on the workshop semantic model.

Business and enterprise Copilot accounts need an admin to turn on the "MCP servers in Copilot" policy. Later labs also use the Power BI Authoring MCP Server extension for VS Code (`analysis-services.powerbi-modeling-mcp`), Azure CLI, and GitHub Copilot CLI.

## Labs

1. **Lab 1: Desktop apps.** Build and preview a report app on the workshop semantic model.
2. **Lab 2: Rayfin Fabricator.** Install Fabricator and build a small working app.
3. **Lab 3: Rayfin template.** Scaffold an app from the Rayfin template gallery and customize it with the agent in VS Code.
4. **Lab 4: MCP servers.** Connect the agent to a model and improve it through MCP.
5. **Lab 5: PBIP report.** Use the agent to reshape an existing PBIP report and verify it with the Desktop Bridge.
6. **Lab 6: Open Q&A.** Apply the day to your own project and get answers.

## Materials

This repo currently contains only this README. Coming soon: lab instructions, prompts, starter files, a starter skills.md blueprint, a prompt library, brand theme JSON, and a slide deck or command cheat sheet. The instructor will publish a sample semantic model to the workshop Fabric workspace. Finished copies of each lab will be available if you fall behind.

## Useful links

- [Rayfin Fabricator](https://spatney.github.io/rayfin-fabricator/)
- [awesome-rayfin templates](https://github.com/microsoft/awesome-rayfin)
- [Power BI Modeling MCP](https://github.com/microsoft/powerbi-modeling-mcp)
- [Skills for Fabric](https://github.com/microsoft/skills-for-fabric)
- [Fabric org app template](https://github.com/microsoft/fabric-org-app-template)

## Contact

Mike Carlo, PowerBI.tips (https://powerbi.tips)
