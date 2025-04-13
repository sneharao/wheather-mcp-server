
<h3 align="center">MCP Weather Server</h3>

<div align="center">

[![Status](https://img.shields.io/badge/status-active-success.svg)]()
[![GitHub Issues](https://img.shields.io/github/issues/kylelobo/The-Documentation-Compendium.svg)](https://github.com/sneharao/wheather-mcp-server/issues)
[![GitHub Pull Requests](https://img.shields.io/github/issues-pr/kylelobo/The-Documentation-Compendium.svg)](https://github.com/sneharao/wheather-mcp-server/pulls)
[![License](https://img.shields.io/badge/license-MIT-blue.svg)](/LICENSE)

</div>

---

<p align="center"> This project is to use MCP server protocol of Anthropic to retrieve wheather alerts or details about the wheather using Claude Desktop app
    <br> 
</p>

## 📝 Table of Contents

- [About](#about)
- [Getting Started & Usage](#getting_started)
- [Built Using](#built_using)
- [References](#references)

## 🧐 About <a name = "about"></a>

Write about 1-2 paragraphs describing the purpose of your project.

## 🏁 Getting Started <a name = "getting_started"></a>

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. See [deployment](#deployment) for notes on how to deploy the project on a live system.

1. Do a "npm i"
2. Build the project using "npm build"
3. Run the MCP server using node build/index.js
4. Modify CLAUDE_DESKTOP_CONFIG.json (found in Library/Application Support/Claude)
   If not available make a new one and paste below code.
   // {
   // "mcpServers": {
   // "weather": {
   // "command": "node",
   // "args": [
   // "/Users/spidugu/Downloads/my-projectspace/wheather/build/index.js"
   // ]
   // }
   // }
   // }
5. Restart claude desktop
   THE HAMMER ICON WOULD SHOW THE INSTALLED MCP, CHECK THE LOGS IF THERE IS ISSUE

### Prerequisites

What things you need to install the software and how to install them.

Claude Desktop (https://claude.ai/download)
Node version 20 and above (https://nodejs.org/en/download)

### Usage
<img width="758" alt="Screenshot 2025-04-13 at 07 39 51" src="https://github.com/user-attachments/assets/cf9c2b49-3911-42d0-a33e-7adaa1a49b04" />


## ⛏️ Built Using <a name = "built_using"></a>

- [NodeJs](https://nodejs.org/en/) - Server Environment

## ✍️ References <a name = "references"></a>

https://modelcontextprotocol.io/quickstart/server
