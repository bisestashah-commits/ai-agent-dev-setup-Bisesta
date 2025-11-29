Overview
This document lists all MCP (Model Context Protocol) servers configured for the AI Agent Developer bootcamp.

1. Rolldice Server
Package: @modelcontextprotocol/server-rolldice
Purpose: Demonstrates basic MCP server functionality through dice rolling operations.
Capabilities:

Roll dice with various configurations (e.g., 2d6, 1d20)
Random number generation
Simulates probabilistic outcomes

Use Cases:

Testing MCP server connectivity
Learning MCP protocol basics
Game development assistance


2. Bootcamp AI Agent Server
Package: @modelcontextprotocol/server-bootcamp
Purpose: Specialized server for AI Agent Developer bootcamp curriculum.
Capabilities:

Access to bootcamp resources
Course materials and documentation
Workshop-specific tools and utilities

Use Cases:

Accessing course content
Bootcamp-specific workflows
Learning path guidance


3. Calendar Booking Server
Package: @modelcontextprotocol/server-calendar
Purpose: Manages calendar operations and scheduling tasks.
Capabilities:

Create and manage calendar events
Schedule appointments
Check availability
Send calendar invitations

Use Cases:

Automated meeting scheduling
Time management workflows
Integration with scheduling systems


4. GitHub Server
Package: @modelcontextprotocol/server-github
Purpose: Enables direct interaction with GitHub repositories through Claude.
Capabilities:

Create, read, update repositories
Manage issues and pull requests
Search code across repositories
Create and modify files
Manage branches and commits

Use Cases:

Code repository management
Automated pull request workflows
Issue tracking and management
CI/CD integration

Authentication: Requires GitHub Personal Access Token with repo permissions.

Configuration Notes
All servers are configured to run via npx for easy installation and updates. The GitHub server requires environment variable configuration for authentication.
Troubleshooting

If a server fails to connect, restart Claude Desktop
Ensure Node.js is properly installed and in PATH
Check firewall settings if connection issues persist
Verify GitHub token has correct permissions
