<p align="center">
  <img src="./yoda.jpg" alt="Yoda">
</p>

# Figma MCP + Antigravity Demo

This project demonstrates the capabilities of using **Figma MCP**, **Antigravity**, and **Agent Configuration** (Skills and Rules) to convert a Figma design into a pixel-perfect landing page.

## Capabilities

### 🎨 Figma MCP
Integrates directly with Figma's Dev Mode using `figma-dev-mode-mcp-server` to:
- Fetch design context and properties.
- Map Figma nodes to code components.
- Generate pixel-perfect assets and CSS.

### 🤖 Antigravity
Leverages advanced agentic coding capabilities to:
- Plan and execute complex implementation tasks.
- Manage state and context across multiple steps.
- Autonomous verification and correction.

### ⚙️ Agent Configuration
Customized behavior through specialized Skills and Rules:

**Skills:**
- `database-schema-validator`: Ensures database integrity.
- `user-stories`: Generates Gherkin acceptance criteria for testing.

**Rules:**
- `database-access.md`: Protocols for database interactions (DBngin, PostgreSQL).
- `design-implementation.md`: Workflow for pixel-perfect design implementation.
- `tech-stack-guide.md`: Directives for Next.js, Drizzle ORM, and styling.

---

## Learn More

### Model Context Protocol (MCP)
- [MCP Documentation](https://modelcontextprotocol.io/) - Official MCP specification and guides
- [Figma MCP Server guide](https://help.figma.com/hc/en-us/articles/32132100833559-Guide-to-the-Figma-MCP-server) - Figma Dev Mode integration
- [MCP Servers Repository](https://github.com/modelcontextprotocol/servers) - Collection of official MCP servers

### Antigravity & Agent Configuration
- [Google Antigravity docs](https://antigravity.google/docs/get-started) - Advanced agentic coding AI
- [Agent Skills Documentation](https://agentskills.io/) - Open standart documentation for agent skills
- [Agent Skills Collection](https://github.com/VoltAgent/awesome-claude-skills) - Awesome collection of agent skills

---

## Original Demo Context

[Figma File](https://www.figma.com/design/Vz3PXmIf4wkkOmDU7vXfiK/SaaS-Landing-Page-Template---Landing-Page-Template-ready-to-export-to-HTML---Landing-page-for-SaaS--Community-?node-id=60-1115&p=f&m=dev)

### First Steps
Before running this demo, ensure you have:
1. **Figma Desktop App** - Antigravity works only with the desktop version of Figma (not the web version)
2. **Enable Dev Mode in Figma** - Open the Figma file and switch to Dev Mode (this is required for MCP to access design properties)
3. **Enable Figma MCP Connection** - Configure the Figma MCP server connection in Antigravity settings

### First Prompt
```
Review the design and make the implemenation plan for this landing page
i want it to be pixel perfect.

Features and reviews shold be loaded dynamically from the database using one API call

Write user stories first, so testers can easy validate the functionality
@https://www.figma.com/design/Vz3PXmIf4wkkOmDU7vXfiK/SaaS-Landing-Page-Template---Landing-Page-Template-ready-to-export-to-HTML---Landing-page-for-SaaS--Community-?node-id=47-686&m=dev
```
