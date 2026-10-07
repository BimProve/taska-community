# Taska Community

**Taska** is BIM Collaboration Infrastructure by [BIMPROVE](https://bim-prove.com) that lives right where the model is: inside Autodesk Revit, inside Autodesk Navisworks, or as a standalone desktop app.

This repository is the public home of Taska. Here you find everything meant for users and integrators.

**Current version: 2.4.0**

📖 **[User Manual](https://bim-prove.notion.site/User-Manual-3e27ad7d1f0780b19479f805a72974f3)**: the complete guide to the interface and the workflows.

---

## What is Taska?

Coordination issues such as clashes, RFIs, punch-list items and design notes usually end up scattered across spreadsheets, emails and chats. Taska replaces them with **one shared list of issues per project**. The whole team creates, discusses and resolves them in the same place, without leaving the model.

### Key features

Each issue carries its status, priority, assignee and deadlines, along with marked-up 3D viewpoints, comments and attachments. Changes reach the whole team in real time. Projects come with a dashboard, role-based permissions and an activity history, and issues move in and out through BCF. AI assistants such as Claude and Codex can work with Taska too, through the [MCP server](#ai-assistants-mcp). The [User Manual](https://bim-prove.notion.site/User-Manual-3e27ad7d1f0780b19479f805a72974f3) covers every feature in detail.

### Where Taska runs

| Application | Versions | How it looks |
| --- | --- | --- |
| Autodesk Revit | 2022 to 2027 | Dockable panel inside Revit |
| Autodesk Navisworks Manage / Simulate | 2025 to 2027 | Dockable panel inside Navisworks |
| Taska Desktop | Windows 10 / 11 (x64) | Standalone app, no Autodesk software required |

All three work with the same projects and issues, so a coordinator in Navisworks and a designer in Revit see the same list in real time.

### AI assistants (MCP)

The **Taska MCP Server** connects AI assistants that support the [Model Context Protocol](https://modelcontextprotocol.io), such as Claude and Codex, to Taska. You can ask the assistant in plain language to find, create or update issues, add comments and attachments, or capture and open 3D views. It can also give you a quick overview of a project and prepare reports, for example what is overdue, what is due this week, or how the work is spread across the team. It works through the Taska app running on your computer, with the same projects and permissions you have. Its installer registers the server in Claude Desktop, Claude Code and Codex automatically. Deleting data always requires your confirmation.

---

## What you will find here

| Content | Purpose |
| --- | --- |
| `README.md` | This overview |
| Update manifest | The release information that Taska checks to tell you a new version is available |
| Release notes | What changed in each version |
| Public API documentation | For teams who want to connect their own scripts and tools to Taska |
| MCP Server documentation | Tools available to AI assistants, and how to connect a client |

Items are added to this repository as they are published.

---

## Getting help

1. Check the **[User Manual](https://bim-prove.notion.site/User-Manual-3e27ad7d1f0780b19479f805a72974f3)**.
2. If something goes wrong, send us the most recent log file (`taska-YYYY-MM-DD.log`):

| Application | Log folder |
| --- | --- |
| Revit | `%AppData%\Bimprove\Taska\logs\Revit` |
| Navisworks | `%AppData%\Bimprove\Taska\logs\Navisworks` |
| Desktop | `%AppData%\Bimprove\Taska\logs\Desktop` |

Paste the path into the File Explorer address bar and press Enter to open the folder.

---

## About BIMPROVE

BIMPROVE is a BIM service company focused on development and automation for the AEC industry.

- **Website:** [bim-prove.com](https://bim-prove.com)
- **LinkedIn:** [BIMPROVE](https://www.linkedin.com/company/bimprove/home/)
