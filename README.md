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
- [Figma MCP Server](https://github.com/modelcontextprotocol/servers/tree/main/src/figma) - Figma Dev Mode integration
- [MCP Servers Repository](https://github.com/modelcontextprotocol/servers) - Collection of official MCP servers

### Antigravity & Agent Configuration
- [Google DeepMind Antigravity](https://deepmind.google/technologies/gemini/antigravity/) - Advanced agentic coding AI
- [Agent Skills Documentation](./.agent/skills/) - Custom skills for specialized tasks
- [Agent Rules Documentation](./.agent/rules/) - Project-specific agent behavior rules

---

## Original Demo Context

[Figma File](https://www.figma.com/design/Vz3PXmIf4wkkOmDU7vXfiK/SaaS-Landing-Page-Template---Landing-Page-Template-ready-to-export-to-HTML---Landing-page-for-SaaS--Community-?node-id=60-1115&p=f&m=dev)

### First Prompt
```
Review the design and make the implemenation plan for this landing page
i want it to be pixel perfect.

Features and reviews shold be loaded dynamically from the database using one API call

Write user stories first, so testers can easy validate the functionality
@https://www.figma.com/design/Vz3PXmIf4wkkOmDU7vXfiK/SaaS-Landing-Page-Template---Landing-Page-Template-ready-to-export-to-HTML---Landing-page-for-SaaS--Community-?node-id=47-686&m=dev
```
